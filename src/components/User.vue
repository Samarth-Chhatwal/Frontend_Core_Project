<template>
    <div>
        <input type="text" v-model="cred.Username" name='Username' placeholder="Enter Username"/> <br><br>
        <input type="password" v-model="cred.Password" name='Password' placeholder="Enter Password"/><br><br>
        <button v-on:click="Login">Login</button>
    </div>
</template>
<script>
export default {
    name:'User',
    methods:{
        Login()
        {
            console.log("cred",this.cred.Username,this.cred.Password)
        }
    },
    data()
        {
            return{cred:{
                Username:null,
                Password:null,
            }}
        }
}
</script>