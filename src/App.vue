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




  export default {
    components: {
      HeaderApp,
      AppMainUp,
      AppMainDown,
      AppFooterUp,
      AppFooterDown
    }
  }
</script>

<style lang="css">

</style>