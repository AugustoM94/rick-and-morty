<template>
  <header class="bg-white">
  <div class="container">
     <HeaderApp />
  </div>
  <HeaderDownApp/>
</header>
   <div class="container">
        <AppMainUp />
   </div>
   <div class="bg-main-down">
    <AppMainDown/>
   </div>
<footer>
    <AppFooterUp/>
    <AppFooterDown/>
</footer>
</template>

<script>
import HeaderApp from "./components/HeaderApp.vue";
import AppMainUp from "./components/AppMainUp.vue";
import AppMainDown from "./components/AppMainDown.vue";
import AppFooterUp from "./components/AppFooterUp.vue";
import AppFooterDown from "./components/AppFooterDown.vue";
import HeaderDownApp from "./components/HeaderDownApp.vue";




  export default {
    components: {
      HeaderApp,
      AppMainUp,
      AppMainDown,
      AppFooterUp,
      AppFooterDown,
      HeaderDownApp
    }
  }
</script>

<style lang="css">

</style>