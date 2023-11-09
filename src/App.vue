<template>
  <header class="bg-white">
  <div class="container">
     <HeaderApp />
  </div>
</header>
   <div class="container">
        <AppMainUp />
   </div>
   <div class="bg-main-down">
    <AppMainDown/>
   </div>
</template>

<script>
import HeaderApp from "./components/HeaderApp.vue";
import AppMainUp from "./components/AppMainUp.vue";
import AppMainDown from "./components/AppMainDown.vue";


  export default {
    components: {
      HeaderApp,
      AppMainUp,
      AppMainDown,
    }
  }
</script>

<style lang="css">

</style>