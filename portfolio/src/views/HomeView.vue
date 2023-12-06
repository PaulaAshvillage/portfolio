<template>
  <div class="home-container">
    <h1>Welcome to my portfolio <span id="dot">.</span></h1>
    <div class="link-container">
      <router-link id="project-shape" class="shaped-link" to="/projects"
        >projects
      </router-link>
      <router-link id="about-shape" class="shaped-link" to="/about"
        >about
      </router-link>
    </div>
  </div>
</template>
<style scoped>
.home-container {
  display: flex;
  margin-top: 20%;
  align-items: center;
}
h1 {
  font-size: 78px;
}
#dot {
  color: var(--color-purple);
}
.link-container {
  margin-right: 10%;
  display: flex;
  gap: 2rem;
  flex-direction: column;
}

#project-shape {
  color: var(--color-beige);
  font-weight: 600;
  font-size: 1.2rem;
  background-color: var(--color-orange);
  height: 180px;
  width: 180px;
  border-radius: 180px 0 0 0;
  display: flex;
  align-items: flex-end;
  justify-content: end;
}

#about-shape {
  color: var(--color-beige);
  font-weight: 600;
  font-size: 1.2rem;
  background-color: var(--color-purple);
  height: 180px;
  width: 180px;
  border-radius: 0 180px 0 0;
  display: flex;
  align-items: flex-end;
  justify-content: start;
}
</style>
<script></script>
