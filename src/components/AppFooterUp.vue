<template>
 <div class="bg-img">
    <div class="container">
      <div class="row">
         <div class="col-6 d-flex justify-content-space-around mt-5" >
            <div>
                <ul>
                <h5>dc comics</h5>
                <li><a href="#">Characters</a></li>
                <li><a href="#">comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
            </ul>

             <ul>
                <h5>Shop</h5>
                <li><a href="#">Shop dc</a></li>
                <li><a href="#">Shop Dc Collectibles</a></li>
            </ul>
        </div>

      <div class="d-flex">
           <ul >
                <h5>dc</h5>
                <li><a href="#">Term of Use</a></li>
                <li><a href="#">Privacy policy(New)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscriptions</a></li>
                <li><a href="#">Talent Workshop</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
         </ul>
      </div>
      <div class="d-flex">
          <ul>
                <h5 >Sites</h5>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
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