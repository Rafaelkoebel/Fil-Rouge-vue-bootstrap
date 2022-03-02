<template>
    <div id="bloc" class="d-flex align-items-center flex-column">
        <h1>{{titre}}</h1>
        <img :src="require(`@/assets/${image}`)" width="600" class="img-fluid" alt="..." >
    </div>
</template>
<script>
export default {
    name: 'TheProduit',
    props: {
        titre:{
        type:String, 
        default:""},
      
        image:{
        type:String, 
        default:""}
    }
}
</script>
<style scoped>
h1{
        text-align: center;
        color: white;
        margin-top: 22px;
        -webkit-text-stroke: 0.1px black;


    }
img{
        border: solid 2px black;
        margin: auto;
    }

</style>
