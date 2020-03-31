<template>
<body>
  <div class="container-fluid">
    <img class="image" src="../static/scene.svg" alt="Intro-svg">
  </div>
</body>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

<style scoped>
body {
  background-color: #3498db;
}
.image{
  width: 100vw;
}

.container-fluid {
  margin: 0 auto;
  padding: 0;
  transform: translateY(45px);
  min-height: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
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

</style>
