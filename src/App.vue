<template>
  <HeaderComponent/>
  <main class="container">

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
      getCharacters(){
        axios.get(store.apiUrl+store.endPoint.character).then((response) =>{
          store.characterList = response.data.results;
        }).catch((error)=>{
          console.log(error);
        }).finally(()=>{
          this.loading= false;
        })
      }
    },
    created(){
      this.getCharacters();
    }
  }
</script>

<style lang="scss" scoped>

</style>