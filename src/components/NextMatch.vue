<script>
    export default {
    name: "NextMatch",
    }
</script>

<template>
   <div class="matchsection">
    <div class="container">
        <div class="squadre flex jc-cen ai-cen">
            <div class="squadra-casa flex jc-cen ai-cen mr-20">
                <h2>Istanbul Sports</h2 >
                <img src="\assets\club-1.png" alt="">
            </div>
            <div class="fs-52">VS</div>
            <div class="squadra-trasferta flex jc-cen ai-cen  ml-20">
                <img src="\assets\club-2.png" alt="">
                <h2>United Fs Club</h2>
            </div>
        </div>
        <div class="info flex jc-cen ai-cen">
            <div class="flex jc-cen ai-cen">
                <i class="fa-regular fa-calendar-days fa-sm"></i>
                <p class="ml-12 fw-7">May 21,2022 18.05 pm</p>
            </div>
            <div class="flex jc-cen ai-cen ml-20">
                <i class="fa-solid fa-circle-plus"></i>
                <p class="ml-12 fw-7">Expert Stadium</p>
            </div>
        </div>
    </div>
   </div>
</template>

<style lang="scss">
@use '../Styles/general.scss'
</style>

<style lang="scss" scoped>
@use '../Styles/parziali/_variabili.scss' as *;

    
</style>