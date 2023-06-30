<template>
<h1>Check out our products⬇️</h1>
    <div v-if="products" class="flex-container">
        <Card v-for="product of products" :product="product" :key="product.id" />
    </div>
    <div v-else>Loading..</div>
    
</template>

<script>
import Card from '@/components/Card.vue'

export default {
    components: { Card },

    computed: {
        products() {
            return this.$store.state.products
            
        }
    },

    mounted() {
        this.$store.dispatch("getProducts")
        console.log(this.products)
    }
}
</script>

<style scoped>
.flex-container{
    display: flex;
    flex-direction:row;
    flex-wrap: wrap;
    justify-content: space-between;
    margin: auto;
    margin-inline: 20px;
}
    
</style>