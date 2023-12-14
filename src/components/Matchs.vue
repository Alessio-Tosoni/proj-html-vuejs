<script>
    export default {
    name: "Matchs",
    }
</script>

<template>
    <div class="container ">
        <h2 class="c-wht fs-46 txt-cen">Upcoming Matchs</h2>
        <!-- partita 1 -->
        <div class="partita my-20">
            <div class="SingleMatch flex jc-cen ai-cen">
                <div class="squadra-casa flex jc-cen ai-cen mr-20">
                    <h2>Schalke Club</h2 >
                    <img src="\assets\club-3.png" alt="">
                </div>
                <div class="fs-52">VS</div>
                <div class="squadra-trasferta flex jc-cen ai-cen  ml-20">
                    <img src="\assets\club-4.png" alt="">
                    <h2>Inter Club</h2>
                </div>
            </div>
            <div class="info flex jc-cen ai-cen">
                <div class="flex jc-cen ai-cen">
                    <i class="fa-regular fa-calendar-days fa-sm"></i>
                    <p class="ml-12 fw-7">October 20,2022 17:00 pm</p>
                </div>
                <div class="flex jc-cen ai-cen ml-20">
                    <i class="fa-solid fa-circle-plus"></i>
                    <p class="ml-12 fw-7">Expert Stadium</p>
                </div>
            </div>
        </div>

        <!-- partita 2 -->
        <div class="partita my-20">
            <div class="SingleMatch flex jc-cen ai-cen">
                <div class="squadra-casa flex jc-cen ai-cen mr-20">
                    <h2>Atletico Club</h2 >
                    <img src="\assets\club-9.png" alt="">
                </div>
                <div class="fs-52">VS</div>
                <div class="squadra-trasferta flex jc-cen ai-cen  ml-20">
                    <img src="\assets\club-6.png" alt="">
                    <h2>Shalke Club</h2>
                </div>
            </div>
            <div class="info flex jc-cen ai-cen">
                <div class="flex jc-cen ai-cen">
                    <i class="fa-regular fa-calendar-days fa-sm"></i>
                    <p class="ml-12 fw-7">September 18,2022 21:00 pm</p>
                </div>
                <div class="flex jc-cen ai-cen ml-20">
                    <i class="fa-solid fa-circle-plus"></i>
                    <p class="ml-12 fw-7">Expert Stadium</p>
                </div>
            </div>
        </div>

        <!-- partita 3 -->
        <div class="partita my-20">
            <div class="SingleMatch flex jc-cen ai-cen">
                <div class="squadra-casa flex jc-cen ai-cen mr-20">
                    <h2>United Fs Club</h2 >
                    <img src="\assets\club-2.png" alt="">
                </div>
                <div class="fs-52">VS</div>
                <div class="squadra-trasferta flex jc-cen ai-cen  ml-20">
                    <img src="\assets\club-8.png" alt="">
                    <h2>Bayern Club</h2>
                </div>
            </div>
            <div class="info flex jc-cen ai-cen">
                <div class="flex jc-cen ai-cen">
                    <i class="fa-regular fa-calendar-days fa-sm"></i>
                    <p class="ml-12 fw-7">August 3,2022 19:00 pm</p>
                </div>
                <div class="flex jc-cen ai-cen ml-20">
                    <i class="fa-solid fa-circle-plus"></i>
                    <p class="ml-12 fw-7">Expert Stadium</p>
                </div>
            </div>
        </div>

        <!-- partita 4 -->
        <div class="partita my-20">
            <div class="SingleMatch flex jc-cen ai-cen">
                <div class="squadra-casa flex jc-cen ai-cen mr-20">
                    <h2>Arsenal Club</h2 >
                    <img src="\assets\club-7.png" alt="">
                </div>
                <div class="fs-52">VS</div>
                <div class="squadra-trasferta flex jc-cen ai-cen  ml-20">
                    <img src="\assets\club-9.png" alt="">
                    <h2>Atletico Club</h2>
                </div>
            </div>
            <div class="info flex jc-cen ai-cen">
                <div class="flex jc-cen ai-cen">
                    <i class="fa-regular fa-calendar-days fa-sm"></i>
                    <p class="ml-12 fw-7">july 8,2022 12:00 pm</p>
                </div>
                <div class="flex jc-cen ai-cen ml-20">
                    <i class="fa-solid fa-circle-plus"></i>
                    <p class="ml-12 fw-7">Expert Stadium</p>
                </div>
            </div>
        </div>

        <!-- partita 5 -->
        <div class="partita my-20">
            <div class="SingleMatch flex jc-cen ai-cen">
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
                    <p class="ml-12 fw-7">June 12,2022 09:00 am </p>
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

<style  scoped>

.container{
    background-image: url('/assets/saha.jpg');
    min-height: 800px;
    background: cover;
    background-size: cover;
    background-repeat: no-repeat;
}

.SingleMatch{
    color: white;
    background-color: rgba(0,0,0,.2);
    width: 80%;
    margin: auto;
}
.info{
    color: white;
    background-color: rgba(0,0,0,.4);
    width: 80%;
    margin: auto;
    padding:5px 0
}

    
</style>