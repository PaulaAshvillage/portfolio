<template>
  <Header-layout />
</template>
<script>
import HeaderLayout from "@/layouts/HeaderLayout.vue";

export default {
  components: {
    HeaderLayout,
  },
};
</script>
<style>
@import url("./assets/reset.css");
@import url("./assets/base.css");
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600&display=swap");
#app {
  font-family: "Poppins", Helvetica, sans-serif;
}
</style>
