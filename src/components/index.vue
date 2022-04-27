<template>
    <!-- <h1>This is first user define component </h1>
    <h2>Email : {{email}}</h2>
    <h2>Mobile No : {{mobile}}</h2>
    <h2>First Name : {{getName("Raviraj")}}</h2>
    <h2>Last Name : {{getName("Kher")}}</h2>
    <h2>All Data: {{getData().email}}</h2>
    <br>
    <br> -->
    <br>
    <input type="text" placeholder="Enter email" v-model="email">
    <br>
    <br>
    <input type="password" placeholder="Enter Password" v-model="password">
    <br><br>
    <button v-on:click="getData()" type="button">Get Value</button>
</template>
<script>
export default {
    name: 'IndexPage',

    data(){
        return {
            // email: 'raviraj@gmail.com',
            // mobile: 1234567891, 
            email: null,
            password: null,
         }
    },
    methods:{
        // getName(name)
        // {
        //     return name
        // },
        getData(){
            // return {
            //     name: 'Raviraj',
            //     email: this.email
            // }
            console.warn("Values: ", this.email, this.password)
        }
    }
}
</script>