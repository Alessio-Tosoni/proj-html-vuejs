<script>
export default {
    name: "PageFooter",
}
</script>

<template>
    <div class="container">
        <div class=" flex jc-sb ai-cen mt-16">
            <div class="col-sx flex clmn ai-fs c-wht w30 ">
                <img class="w15 my-20" src="\assets\logo-footer-football.png" alt="">
                <div class="position flex jc-cen ai-bas ">
                    <i class="fa-solid fa-location-dot fa-xl " style="color: #ffffff;"></i>
                    <p class="ml-12 fs-20">New Jersey, USA</p>
                </div>
                <div class="phone-number flex jc-cen ai-bas">
                    <i class="fa-solid fa-phone-volume fa-xl" style="color: #ffffff;"></i>
                    <p class="ml-12 fs-20">+1(234) 567 89 10</p>
                </div>
                <div class="email flex jc-cen ai-bas">
                    <i class="fa-regular fa-envelope fa-xl"></i>
                    <p class="ml-12 fs-20">example@example.com</p>
                </div>
                <div class="socials flex jc-sb ai-bas mb-20">
                    <div class="bor-wht p-12 "><i class="fa-brands fa-facebook-f fa-xl " style="color: #ffffff;"></i></div>
                    <div class="bor-wht p-12 mo-12"><i class="fa-brands fa-instagram fa-xl "></i></div>
                    <div class="bor-wht p-12"><i class="fa-brands fa-twitter fa-xl" style="color: #ffffff;"></i></div>
                </div>
            </div>
            <div class="col-cen flex clmn ai-fs c-wht w30">
                <h5>Join Our Newsletter</h5>
                <p>Subscribe to be informed about important developments in our club and football world.</p>
                <input class="w80 bor-30 fs-14 p-12" type="text" placeholder="Your Email Address">
                <div class="w80 bg-wht bor-30 mt-16 p-12 c-blk txt-cen">Subscribe</div>
            </div>
            <div class="col-dx flex  ai-fs c-wht w30">
                <div class="col-a flex clmn ai-fs c-wht w50">
                    <div>
                        <h5>Education</h5>
                    </div>
                    <span class="fs-14 mt-8"> - FIXTURES & RESULTS</span>
                    <span class="fs-14 mt-8"> - LEAGUE TABLE</span>
                    <span class="fs-14 mt-8"> - PLAYERS</span>
                    <span class="fs-14 mt-8"> - GALLERY</span>




                </div>
                <div class="col-b flex clmn ai-fs c-wht w50 ">
                    <h5>Quick Links</h5>
                    <span class="fs-14 mt-8"> - HOME</span>
                    <span class="fs-14 mt-8"> - BLOG</span>
                    <span class="fs-14 mt-8"> - GALLERY</span>
                    <span class="fs-14 mt-8"> - CONTACT</span>

                </div>
            </div>
        </div>
        <p class="txt-cen fs-14 c-wht"><i class="fa-regular fa-copyright" style="color: #ffffff;"></i>2022 Football Club - All Rights Reserved</p>
    </div>
</template>

<style lang="scss">
@use '../Styles/general.scss'
</style>

<style lang="scss" scoped>
@use '../Styles/parziali/_variabili.scss' as *;

.container {
    background: $blacktheme;
}
</style>