<template>
    <header class=" container text-center ">
        <h1 class=" display-1 fw-semibold  ">Rick and Morty</h1>
    </header>

</template>

<script>
import { store } from '../data/store'

    export default {
    name: "HeaderComponent",

    data() {
        return {
            store
        };
    },
}

</script>

<style lang="scss" scoped>

</style>
