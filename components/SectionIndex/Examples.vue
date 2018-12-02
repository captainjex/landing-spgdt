<template>
    <section class="section section-lg section-shaped overflow-hidden my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="container shape-container py-5 pb-5">
            <div class="row row-grid justify-content-between align-items-center">
                <div class="col-lg-6">
                    <h3 class="display-3 text-white">SPGDT
                        <small><span style="font-size: 18pt">Sistem Penganggulangan Gawat Darurat Terpadu</span></small>
                        <br>
                        <span class="text-white">We Care Your Safety</span>
                    </h3>
                    <br>
                    <!-- <p class="lead text-white">The Design System comes with four pre-built pages to help you get started
                        faster. You can change the text and images and you're good to go. More importantly, looking at
                        them will give you a picture of what you can built with this powerful Bootstrap 4 Design
                        System.</p> -->
                    <div class="btn-wrapper">
                        <a :href="appLink" target="_blank" data-toggle="tooltip" data-original-title="Bootstrap 4 - Most popular front-end component library">
                            <img v-lazy="'https://user-images.githubusercontent.com/21119252/49340896-6c670780-f678-11e8-8612-965322a2f262.png'" class="img-fluid">
                        </a>
                    </div>
                </div>
                <div class="col-lg-5 mb-lg-auto">
                    <div class="transform-perspective-right">
                        <img v-lazy="'https://user-images.githubusercontent.com/21119252/49342200-c1ac1480-f68a-11e8-86d2-f45ecbbef927.png'" class="img-fluid">

                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
  data() {
    return {
      appLink: 'https://play.google.com/store/apps/details?id=id.spgdt.app'
    }
  }
}
</script>
<style>
</style>
