<template>
    <main class="homepage max-container">
        <div class="homepage-left">
            <h1 class="main-title">Welcome to the
                <span class="bold">Frontend Quiz!</span>
            </h1>
            <p class="italic">Pick a subject to get started.</p>
        </div>
        <div class="homepage-right">
            <div class="card-choice">HTML</div>
            <div class="card-choice">CSS</div>
            <div class="card-choice">Javascript</div>
            <div class="card-choice">Accessibility</div>
        </div>
    </main>
</template>
  
<script>
export default {
    name: 'HomePage'
}
</script>
  
<style lang="scss">
.bold {
    font-weight: 500;
}

.italic {
    font-style: italic;
}

.homepage {
    display: flex;
    margin: 0 auto;
    justify-content: center;
}


</style>
  