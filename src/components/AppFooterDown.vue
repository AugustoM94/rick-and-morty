<template>
    <div class="bg-footer-down mb-5 position">
        <div class="container  justify-content-space-around ">
       <div class="row">
         <div class="col-6 d-flex align-items-center">
              <button class="mt-2" type="button">Sign-up Now!</button>
         </div>
         <div class="col-6 d-flex justify-content-end">
            <h5 class="mt-1">Follow Us</h5>
                <ul class=" d-flex justify-content-space-around"> 
                    <li class="px-2"><a href="#"><img src="/vue-dc-comics-1/img/footer-facebook.png" alt="Logo Facebook"></a></li>
                    <li class="px-2"><a href="#"><img src="/vue-dc-comics-1/img/footer-twitter.png" alt="Logo Twitter"></a></li>
                    <li class="px-2"><a href="#"></a><img src="/vue-dc-comics-1/img/footer-youtube.png" alt="Logo YouTube"></li>
                    <li class="px-2"><a href="#"></a><img src="/vue-dc-comics-1/img/footer-pinterest.png" alt="Logo Pinterest"></li>
                    <li class="px-2"><a href="#"><img src="/vue-dc-comics-1/img/footer-periscope.png" alt="Logo Periscope"></a></li>
                </ul>
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
button {
    border: 1px solid #0282f9;
    background-color: transparent;
    color: white;
    padding: 8px;
    text-transform: uppercase;
    
}

li {
    list-style: none;
}
a {
    text-decoration: none;
}
h5 {
    color: #0282f9;
}
.bg-footer-down {
    background-color: #303030;
}
.position{
    position: relative;
    padding-bottom: 10px;
    
}
</style>