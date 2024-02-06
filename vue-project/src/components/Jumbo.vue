<script>
import AppTitle from './AppTitle.vue';


export default {
  components:{
    AppTitle,
    
  }
  }

</script>


<template>
    
  <div class="centro">
  <AppTitle/>
    <h2>Sito incredibile</h2>
</div>

</template>



<style scoped>
    .centro{
        background-color: grey;
        width: 100%;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        gap: 20px;
        align-items: center;
        justify-content: center;
        height: 350px;

    }
    
    
</style>