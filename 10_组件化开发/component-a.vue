<template>
        <h2>{{title}}</h2>
        <h2>component-b</h2>
        <button @click="btnClick">btn</button>
</template>
<script>
export default{
    data(){
        return{
        title:'titleaaaa'
        }
    },
    methods: {
        btnClick(){
            alert("hi~");
        }
    }

}
</script>
<style scoped>
</style>