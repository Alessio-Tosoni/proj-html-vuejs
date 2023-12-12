<script>
    export default {
    name: "AppHeader",
    }
</script>

<template>
   <div class="myHeader">
    <div class="container ">
        <div class="loghiHeader">
            <img src="\assets\sponsor1.png" alt="">
            <img src="\assets\sponsor2.png" alt="">
            <img src="\assets\logo-football.png" alt="">
            <i class="fa-brands fa-facebook-f fa-2xl mo-12" style="color: #f0f2f4;"></i>
            <i class="fa-brands fa-instagram fa-2xl mo-12" style="color: #ffffff;"></i>
            <i class="fa-brands fa-twitter fa-2xl mo-12" style="color: #ffffff;"></i>
        </div>
        <div class="voci flex jc-sb ai-cen py-24">
            <a>HOME</a>
            <a>FIXTURES & RESULTS</a>
            <a>LEAGUE TABLES</a>
            <a>PLAYERS</a>
            <a>GALLERY</a>
            <a>BLOG</a>
            <a>CONTACT</a>
        </div>
    </div>
   </div>
</template>

<style lang="scss">
@use '../Styles/general.scss'
</style>

<style lang="scss" scoped>
@use '../Styles/parziali/_variabili.scss' as *;
    .myHeader{
        background: $blacktheme ;
        width:100%;
        height:220px;
        color: $whitetheme;
        opacity: 80%;
        .container{
            width: 70%;
            margin: auto;
        }
        .loghiHeader{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        a:hover{border-bottom: 2px solid $whitetheme;}
    }       
</style>