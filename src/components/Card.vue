<template>
  <router-link :to="{ name: 'product', params: { id: product} }" class="card">
    <img :src="product.Image" :alt="product.name" />
    <!-- <h3>
      {{ product.name }} -->
    <!-- </h3> -->
    <p> {{ product.desc }}</p>
    <p> R {{ product.price }}</p>
    <button @click="add">Add to cart</button>
  </router-link>
</template>
<script>
export default {
  props: ["product"],
};
</script>
<style scoped>
  .card{
    width: 400px;
    height: 80%;
    margin-block: 70px;
    margin-bottom: 150px;
  }

  img{
    width: 100%;
    height: 80%;
  }

  button{
    width: 100px;
    height: 40px;
    margin-bottom: 20px;
    background-color: blueviolet;
    border-radius: 8px;
    align-self: center;
    
  }
</style>
