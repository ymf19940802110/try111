<template>
    <div id="app" @click="sayHello">app</div>
</template>

<script>
    export default {
        name: "test",
        method:{
            sayHello(){
                alert("你好呀")
            }
        }
    }
</script>

<style scoped>
    #app{
        background-color: #42b983;
    }
</style>