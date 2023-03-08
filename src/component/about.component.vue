<template>
    <div class="about">
        <h1>About</h1>
        <p>
            This is a project done with <a href="https://vuejs.org/" target="_blank">Vue.js</a> and
             that fetches my repositories from
            Github and displays them on the page.
        </p>
    </div>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style lang="scss" scoped>
.about {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 90vh;

    h1 {
        font-size: 3rem;
        margin-bottom: 1rem;
    }

    p {
        font-size: 1.5rem;
        margin-bottom: 1rem;
        color: #2E3840;
    }

    a {
        color: #E9A178;
        text-decoration: none;
    }
}
</style>