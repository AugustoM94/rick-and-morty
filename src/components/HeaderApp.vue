<template>
    <div>
        <div>
            <img src="/public/vue-dc-comics-1/img/dc-logo.png" alt="logo-dc">

        </div>
         <div>
            <ul>
                <li><a href="#"></a></li>
            </ul>
         </div>
    </div>
</template>

<script>
    export default {
        name: HeaderApp,
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

</style>