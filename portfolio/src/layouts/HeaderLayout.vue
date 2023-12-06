<template>
  <nav>
    <router-link id="home-link" to="/">paula.</router-link>

    <router-link class="site-links" to="/projects">projects</router-link>
    <router-link class="site-links" to="/about">about</router-link>
    <router-link class="site-links" to="contact">contact</router-link>
  </nav>
</template>
<style scoped>
nav {
  padding-top: 1rem;

  display: flex;
  justify-content: flex-end;
  gap: 2rem;
  font-size: 1.2rem;
}
.site-links:hover {
  text-decoration: underline;
  text-decoration-color: var(--color-purple);
}

#home-link {
  font-weight: 100;
  margin-right: auto;
}
</style>
