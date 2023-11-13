<template>
    <div class="row" >
        <CardComponent
        v-for="character in store.characterList"
         :character='character.name'
         :status="character.status"
         :species="character.species"
         :images="character.image"
        />
    </div>
</template>

<script>
import CardComponent from './CardComponent.vue'
import { store } from '../data/store'
    export default {
        name: 'CharacterListComponent',
        components:{
            CardComponent,
        },
        data(){
            return{
                 store

            }
        }
    }
</script>

<style lang="scss" scoped>

</style>