<template>
  <header class="max-container header ">
    <div class="header-title">
      <div class="header-img-container accessibility">
        <img src='/images/icon-accessibility.svg' />
      </div>
      <span>Accessibility</span>
    </div>
    <div class="header-toggle">
      <img src='/images/icon-sun-dark.svg' />
      <label class="switch">
        <input type="checkbox">
        <span class="slider round"></span>
      </label>
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
  justify-content: space-between;
  align-items: center;
  margin: 0 auto 50px auto;

  &-title,
  &-toggle {
    display: flex;
    align-items: center;
  }

  &-title {
    gap: 25px;
    font-size: 1.5em;
    font-weight: 500;
  }

  &-img-container {
    padding: 10px;
    border-radius: 5px;
  }

  &-toggle {
    gap: 15px;
  }

  /* The switch - the box around the slider */
  .switch {
    position: relative;
    display: inline-block;
    width: 50px;
    height: 30px;
  }

  /* Hide default HTML checkbox */
  .switch input {
    opacity: 0;
    width: 0;
    height: 0;
  }

  /* The slider */
  .slider {
    position: absolute;
    cursor: pointer;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #A729F5;
    -webkit-transition: .4s;
    transition: .4s;
  }

  .slider:before {
    position: absolute;
    content: "";
    height: 20px;
    width: 20px;
    left: 5.5px;
    bottom: 5.5px;
    background-color: white;
    -webkit-transition: .4s;
    transition: .4s;
  }

  input:checked+.slider {
    background-color: #A729F5;
  }

  input:checked+.slider:before {
    transform: translateX(18px);
  }

  /* Rounded sliders */
  .slider.round {
    border-radius: 34px;
  }

  .slider.round:before {
    border-radius: 50%;
  }
}
</style>
