<template>
    <nav class="topnav">
        <logo>XB Hoody store</logo>
    <router-link class="active" to="/">Home</router-link>
    <router-link class="active" to="/about">About</router-link>
    <router-link class="active" to="/products">Products</router-link>
    <router-link class="active" to="/admin">Admin</router-link>
    <router-link class="active" to="/form">Sign in📩</router-link>


    </nav>
</template>

<script>
export default {
    
}
</script>
<style scoped>

.topnav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 160px;
    background-color: rgb(222, 98, 222)
}

routerlink {
     float: left;
     color:cadetblue;
     text-align: center;
     padding: 14px 16px;
     text-decoration: none;
     font-size: 20px;

}
.active:hover{
    background-color:blueviolet;
}

logo{
    font-size: 40px;
}
    
</style>
