<template>
  <div class="home-container">
    <h1>Welcome to my portfolio <span id="dot">.</span></h1>
    <div class="link-container">
      <router-link class="shaped-link" to="/projects">projects</router-link>
      <router-link class="shaped-link" to="/about">about</router-link>
    </div>
  </div>
</template>
<style scoped>
.home-container {
  display: flex;
}
h1 {
  font-size: 96px;
}
#dot {
  color: var(--color-purple);
}
.link-container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.shaped-link {
  padding-block: 2rem;
  padding-inline: 2rem;
  background-color: blue;
}
</style>
<script></script>
