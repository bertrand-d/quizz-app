<template>
  <header class="header">
    <div class="header-title">
      <img src='/images/icon-accessibility.svg' />
      <span>Accessibilité</span>
    </div>
    <div class="header-toggle">
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

<style lang="scss">

.header {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 50px;
}

</style>
