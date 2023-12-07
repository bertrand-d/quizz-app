<template>
  <HeaderSection />
  <HomePage />
</template>

<script>
import HeaderSection from './components/HeaderSection.vue'
import HomePage from './pages/HomePage.vue'

export default {
  name: 'App',
  components: {
    HeaderSection,
    HomePage
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
  background-color: #F4F6FA;
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
