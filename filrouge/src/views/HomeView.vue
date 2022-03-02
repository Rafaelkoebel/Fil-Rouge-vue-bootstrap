<template>
<div id="rouge">
  <TheHeader />

  <TheMain />
  <div>    
        <div>
           <TheProduit v-for="(produit,index) in produits" :key="index" :titre="produit.titre" :image="produit.image" /> 
        </div>
  </div>

  <TheFooter />
</div>
</template>

<script>
// @ is an alias to /src
import TheHeader from '@/components/TheHeader.vue'
import TheMain from '@/components/TheMain.vue'
import TheFooter from '@/components/TheFooter.vue'
import TheProduit from '@/components/TheProduit.vue'
import axios from 'axios'

export default {
  name: 'HomeView',
  components: {
    TheHeader,
    TheMain,
    TheFooter,
    TheProduit
  },
  data(){
        return {
            produits:[],
            errors: []
        }
  },
  created() {
    axios.get(`http://localhost:8088/produits.json`)
    .then(response => {
      this.produits = response.data.produits
    })
    .catch(e => {
      this.errors.push(e)
    })
  }
}
</script>

<style scoped>

#rouge{
        background-image: url(../assets/rouge.jpg);
    }
</style>
