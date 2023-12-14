<script>
    export default {
        name: "PlayerCard",
        props: ["players"]
       
      
        
    }
</script>

<template>
<div class="card c-wht fs-14">
    <img  :src= "players.pic" alt="">
    <p>{{ players.Number }}</p>
    <p>{{ players.Name }}</p>
    <p>{{ players.Position }}</p>
</div>

</template>
<style scoped>
    .card{
        width: calc(100% / 4);
        margin: 12px auto;
    }
    img{
        width: 60%;
        height: 70%;
        }
</style>