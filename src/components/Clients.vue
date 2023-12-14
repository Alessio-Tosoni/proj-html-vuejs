<script>
    export default {
    name: "Clients",
    }
</script>

<template>
   <div class="container  flex jc-sa ai-cen">
        <div class=" w30">
            <img class="bor-wht bor-12 con my-8 " src="\assets\client2.png" alt="">
        </div>
        <div class=" w30">
            <img class="bor-wht bor-12 con my-8" src="\assets\client3.png" alt="">
        </div>
        <div class=" w30">
            <img class="bor-wht bor-12 con my-8" src="\assets\client4.png" alt="">
        </div>
        <div class=" w30">
            <img class="bor-wht bor-12  con my-8" src="\assets\client7.png" alt="">
        </div>
        <div class=" w30">
            <img class="bor-wht bor-12 con my-8" src="\assets\client9.png" alt="">
        </div>
        <div class=" w30">
            <img class="bor-wht bor-12 con my-8" src="\assets\client10.png" alt="">
        </div>
   </div>
   
</template>

<style lang="scss">
@use '../Styles/general.scss'
</style>

<style lang="scss" scoped>
@use '../Styles/parziali/_variabili.scss' as *;
    .container{
        background-color: $blacktheme;
        min-width: 1300px;
        img{
            object-fit: contain;
        }
    }
    
</style>