<template>
    <div>
        <h2>This is the required info {{infor}}</h2>
        <input type="text" v-model="infor">
        <button @click="doit">click me</button>
    </div>
</template>

<script>
export default {
    data : function(){
        return{
            infor : ""
        }
    },
    methods:{
        doit(){
            this.infor = "f4q34r32";
        }
    }
}
</script>

<style scoped>
    div{
        border: 2px solid red;
        margin: 3rem;
        padding: 2rem;
        text-align: center;
    }
</style>