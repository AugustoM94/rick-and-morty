<template >
 <header class="bg-white p-3 mt-4">
    <div class=" row d-flex justify-content-between align-items-center ">
        <div class="col-4">
            <img src="/public/vue-dc-comics-1/img/dc-logo.png" alt="logo-dc">
        </div>
        <div class="col-8">
            <ul class="d-flex ">
                <li class="px-3" v-for="(link, index) in links" :key="index"><a href="#">{{ link.text }}</a></li>
            </ul>
        </div>
    </div>
</header>

</template>

<script>
    export default {
        data(){
            return {
                 links: [
                      {
                        text: "Characters"
                      },
                      {
                        text: "Comics"
                      },
                      {
                        text: "Movies"
                      },
                      {
                        text: "TV"
                      },
                      {
                        text: "Collectibles"
                      },
                      {
                        text: "Videos"
                      },
                      {
                        text: "Fans"
                      },
                      {
                        text: "News"
                      },
                      {
                        text: "Shop"
                      },
                 ]
            }
        }
    }
</script>

<style lang="css" scoped>
li {
    list-style: none;
}

a {
    text-decoration: none;
    color: black;
    font-weight: 400;
    text-transform: uppercase;
    font-size: .8rem;
}

img {
    width: 70px;
}
</style>