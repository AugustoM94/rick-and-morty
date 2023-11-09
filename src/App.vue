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
<footer>
  <div>
    <AppFooterUp/>
  </div>
</footer>
</template>

<script>
import HeaderApp from "./components/HeaderApp.vue";
import AppMainUp from "./components/AppMainUp.vue";
import AppMainDown from "./components/AppMainDown.vue";
import AppFooterUp from "./components/AppFooterUp.vue";



  export default {
    components: {
      HeaderApp,
      AppMainUp,
      AppMainDown,
      AppFooterUp,
    }
  }
</script>

<style lang="css">

</style>