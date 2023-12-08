<template>
  <div class="body-background-container">
    <img class="body-background" src='/images/pattern-background-desktop-light.svg' />
  </div>
  <HeaderSection />
  <router-view></router-view>
</template>

<script>
import HeaderSection from './components/HeaderSection.vue'

export default {
  name: 'App',
  components: {
    HeaderSection
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
  background-color: #F4F6FA;
}


.body-background-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw;
  z-index: -1;
  overflow: hidden;
  max-height: 100vh;
}

.body-background {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

#app {
  @import url('https://fonts.googleapis.com/css2?family=Manrope:wght@400;700&family=Rubik:ital,wght@0,400;0,500;1,300;1,400&display=swap');
  font-family: Rubik, Helvetica, Arial, sans-serif;
  font-weight: 300;
  color: #2c3e50;
  margin-top: 60px;
}

.max-container {
  max-width: 1200px;
}

h1 {
  margin: 0;
  font-size: 4em;
  font-weight: 300;
}

p {
  margin: 0;
}

.html {
  background-color: #FFF1E9;
}

.css {
  background-color: #E0FDEF;
}

.js {
  background-color: #EBF0FF;
}

.accessibility {
  background-color: #F6E7FF;
}
</style>