<template>
<h2>Sign in Below</h2>
    <form>
        <div class="container">
            <label>Username</label>
            <input type="text" placeholder="enter your username" v-model="form.username">
    
            <label>Email</label>
            <input type="email" placeholder="enter your email" v-model="form.email">|
    
            <label>Cell No</label>
            <input type="number" placeholder="enter your cell no" v-model="form.cellno">
    
    
            <label>Password</label>
            <input type="password" placeholder="enter your password" v-model="form.password">
            <button @click="submit" type="button">Sign in</button>

        </div>
    </form>
</template>

<script>
export default {
    name: "Form",
    data() {
        return {
          form: {
                username: '',
                email: '',
                cellno: '',
                password: '',
            }
        }
    },
    methods: {
        submit()
        {
            console.warn(this.form)
        }
    }
    
}
</script>

<style scoped>
form{
margin:auto;
padding: 40px;
    
}
.container{
    display: flex;
    flex-direction: column;
    width: 30%;
    min-height: 20vh;
    background-color:ghostwhite;
    box-shadow: 6px 6px 6px 6px;
    align-items: center;
    border-radius: 8px;

}

input{
    border: none;
    border-bottom: 2px solid;
    margin-top: 20px;
    
}

button{
    margin-top: 20px;
    width: 80px;
    border-radius: 6px;
    margin-bottom: 20px;

}

button:hover{
    background-color: blueviolet;
}



    
   

    
   

    
</style>