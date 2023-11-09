<template>
  <header class="bg-white">
  <div class="container">
     <HeaderApp />
  </div>
</header>
   <div class="container">
        <AppMainUp />
   </div>
</template>

<script>
import HeaderApp from "./components/HeaderApp.vue";
import AppMainUp from "./components/AppMainUp.vue";

  export default {
    components: {
      HeaderApp,
      AppMainUp,
    }
  }
</script>

<style lang="css" scoped>

</style>