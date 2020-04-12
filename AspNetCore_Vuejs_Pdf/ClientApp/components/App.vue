<template>
    <div>
        <h1>Welcome to Hands on Vue.js with Asp.Net Core</h1>
        <p>The time is: {{time}}</p>
    </div>
</<template>

<script>
export default {
    name: 'app',
    data(){
        return{
            time: new Date().toString()
        }
    }
}
</script>

<style>

</style>
