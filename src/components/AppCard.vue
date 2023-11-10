<template>
    
        <div class="col-12 col-md-3 col-lg-2">
            <div class="card-container p-2 h-100 ">
            <div class="card h-100 " style="width: 13rem;">
                  <img :src="image" class="card-img-top" :alt="series">
                <div class="card-body">
                    <h5 class="card-title px-1 ">{{ series }}</h5>
                    <p class="card-text">{{ type }}</p>
                    <small class="px-1">{{ price }}</small>
                 </div>
             </div>
        </div>
</div>
</template>

<script>
export default {
  name: 'AppCard',
  props: {
    image: String,
    price: String,
    series: String,
    type: String 
  }
}
</script>


<style lang="css" scoped>


</style>