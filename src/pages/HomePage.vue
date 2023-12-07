<template>
    <main class="homepage max-container">
        <div class="homepage-left">
            <h1 class="main-title">Welcome to the
                <span class="bold">Frontend Quiz!</span>
            </h1>
            <p class="italic">Pick a subject to get started.</p>
        </div>
        <div class="homepage-right">
            <div class="card-choice">
                <div class="image-container html">
                    <img src='/images/icon-html.svg' />
                </div>
                HTML
            </div>
            <div class="card-choice">
                <div class="image-container css">
                    <img src='/images/icon-css.svg' />
                </div>
                CSS
            </div>
            <div class="card-choice">
                <div class="image-container js">
                    <img src='/images/icon-js.svg' />
                </div>
                Javascript
            </div>
            <div class="card-choice">
                <div class="image-container accessibility">
                    <img src='/images/icon-accessibility.svg' />
                </div>
                Accessibility
            </div>
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
    gap: 150px;
    margin: 0 auto;
    justify-content: center;

    &-left {
        display: flex;
        flex-direction: column;
        gap: 50px;
        margin-left: auto;
        width: 25%;
    }

    &-right {
        display: flex;
        flex-direction: column;
        gap: 20px;
    }
}

.card-choice {
    display: flex;
    background: #fff;
    box-shadow: 0px 15px 45px rgba(143, 160, 193, 0.1);
    align-items: center;
    gap: 30px;
    font-weight: 500;
    font-size: 1.5em;
    padding: 20px;
    border-radius: 25px;
    width: 550px;
    cursor: pointer;
    transition: all ease-in-out 0.2s;

    &:hover {
        box-shadow: 0px 15px 45px rgba(143, 160, 193, 0.3);
    }

    .image-container {
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 10px;
        border-radius: 10px;
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
}
</style>
  