<template>
  <div class="container">
    <img class="image" src="../static/scene.svg" alt="Intro-svg">
    <img class="image_tab" src="../static/scene_tab.svg" alt="Intro-svg">
    <aboutMe />
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import AboutMe from "~/components/AboutMe.vue";

export default {
  components: {
    Logo,
    AboutMe
  }
};
</script>

<style scoped>
.container {
  background-color: #3498db;
  margin: 0 auto;
  padding: 0;
  transform: translateY(45px);
  min-height: auto;
  max-width: 100vw;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.image{
  width: 100vw;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #25385e;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

@media only screen and (min-width: 1000px) {
  .image_tab {
    display: none;
  }
}
@media only screen and (max-width: 999px) {
  .image {
    display: none;
  }
}
</style>
