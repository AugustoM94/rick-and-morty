<template>
 <div class="bg-img">
    <div class="container">
      <div class="row">
        <div class="col-6 d-flex justify-content-space-around mt-4">
            <div v-for="category in data.menuItems" class="d-flex" >
              <ul>
                <h5>{{ category.title }}</h5>
                <li v-for="link in category.links" :key="link"><a href="#">{{ link }}</a></li>
              </ul>
          </div>
        </div>
        <div class="col-6 position">
          <img src="/vue-dc-comics-1/img/dc-logo-bg.png" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      data: {
        menuItems: [
          {
            title: 'dc comics',
            links: ['Characters', 'Comics', 'Movies', 'TV', 'Games', 'Videos', 'News']
          },
          {
            title: 'Shop',
            links: ['Shop dc', 'Shop Dc Collectibles']
          },
          {
            title: 'dc',
            links: ['Term of Use', 'Privacy policy(New)', 'Ad Choices', 'Advertising', 'Jobs', 'Subscriptions', 'Talent Workshop', 'CPSC Certificates', 'Ratings', 'Shop Help', 'Contact Us']
          },
          {
            title: 'Sites',
            links: ['DC', 'MAD Magazine', 'DC Kids', 'DC Universe', 'DC Power Visa']
          }
        ]
      }
    };
      }
        
    }
</script>

<style lang="css" scoped>
.bg-img {
  background-image: url(./vue-dc-comics-1/img/footer-bg.jpg);
}
h5 {
    color: white;
    text-transform: uppercase;
    font-size: 0.9rem;
}

a{
    text-decoration: none;
    color: grey;
    font-size: 0.7rem;
}
li{
  line-height: 15px;

}
img {
    width: 400px;
}
.position{
    position: relative;
    bottom:50px;
}
</style>