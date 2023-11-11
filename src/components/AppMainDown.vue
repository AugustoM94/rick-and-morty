<template>
    <div class=" container py-5">
               <ul class="d-flex justify-content-around align-items-centers">
                    <li v-for="(item, index) in card" :key="index">
                        <img :src="item.img" alt="logo-{{ item.text }}">
                        <span class="px-1">{{ item.text }}</span>
                    </li>
               </ul>
    </div>
</template>

<script>
    export default {
        data(){
            return {
                card: [
                  {
                    img: '/vue-dc-comics-1/img/buy-comics-digital-comics.png',
                    text:"Digital comics",

                  },
                  {
                    img: '/vue-dc-comics-1/img/buy-comics-merchandise.png',
                    text:'Dc Merchandise',

                  },
                  {
                    img: '/vue-dc-comics-1/img/buy-comics-subscriptions.png',
                    text:'Subscription',

                  },
                  {
                    img: '/vue-dc-comics-1/img/buy-comics-shop-locator.png',
                    text:'Comic shop locator',

                  },
                  {
                    img: '/vue-dc-comics-1/img/buy-dc-power-visa.svg',
                    text:'Dc power visa',

                  }
                ]
            }
        }
    }
</script>

<style lang="css" scoped>
img {
    width: 50px;
    height: 50px;
}
li {
    list-style: none;
}
span {
    color: white;
    text-transform: uppercase;
    font-size: 0.7rem;
}

</style>