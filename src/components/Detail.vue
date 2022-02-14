<template>
  <v-container>
      <h1>Product Detail Page</h1>
      <h2>ID = {{ productid }}</h2>
      
  </v-container>
</template>

<script>

export default {
    data(){
        return{
            productid: this.$route.params.id,
            rate: this.$route.params.Name,
        };
        
    },
    

    

};
</script>

<style>

</style>