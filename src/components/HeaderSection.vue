<template>
  <header class="header">
    <div>
      <img src='/images/icon-accessibility.svg' />
      <span>Accessibilité</span>
    </div>
    <div>
      <img src='/images/icon-sun-dark.svg' />
      <img src='/images/icon-moon-dark.svg' />
    </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderSection'
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}</style>
