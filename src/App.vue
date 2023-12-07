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
}

#app {
  @import url('https://fonts.googleapis.com/css2?family=Manrope:wght@400;700&family=Rubik:ital,wght@0,400;0,500;1,300;1,400&display=swap');
  font-family: Rubik, Helvetica, Arial, sans-serif;
  font-weight: 300;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.max-container {
  max-width: 1400px;
}

h1 {
  margin: 0;
  font-size: 2.5em;
  font-weight: 300;
}

p {
  margin: 0;
}
</style>
