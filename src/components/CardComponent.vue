<template>
    <div class="col-12 col-md-3">
        <img :src="images" alt="name" class="rounded-circle ">
        <h2>{{ name }}</h2>
        <h4 class="text-secondary">{{status }}</h4>
        <h4 class="text-secondary">{{ species }}</h4>
    </div>
</template>

<script>
    export default {
        name:'CardComponent',
        props:{
            name: String,
            status: String,
            species: String,
            images: String

        }
    }
</script>

<style lang="scss" scoped>

</style>