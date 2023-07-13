<script>
export default {
    name: "MainComponent",
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <main>
        <div class="container">
            content goes here
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

main {
    background-color: black;
}
.container {
    padding: 40px;
    background-color: black;
    max-width: 1200px;
    margin: auto;
}
</style>