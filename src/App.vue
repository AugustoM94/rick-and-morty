<template>
  <HeaderComponent/>
  <main class="container">
    <div class="d-flex justify-content-center align-items-center container">
        <h2 class="display-1 fw-bold">Loading...</h2>
    </div>
    <CharacterListComponent />

  </main>
</template>

<script>

import HeaderComponent from './components/HeaderComponent.vue';
import axios from 'axios';
import { store } from './data/store';
import CharacterListComponent from './components/CharacterListComponent.vue';
  export default {
    name: 'App',
    components:{
      HeaderComponent,
      CharacterListComponent
    },
    data(){
      return{ 
        store,
        loading:true
      }
    },
    methods:{
      getCharacters() {
      const url = store.apiUrl + store.endPoint.character
      axios.get(url).then((response) => {
        store.characterList = response.data.results
      }).catch((error) => {
        console.log(error)
      }).finally(() => {
        this.loading = false
      })
    },
  },
    created(){
      this.getCharacters();
    }
  }
</script>

<style lang="scss" scoped>

</style>