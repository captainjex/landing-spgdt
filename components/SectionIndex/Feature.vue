<template>
  <section class="section section section-shaped my-0 overflow-hidden">
      <div class="shape shape-style-1 bg-gradient-warning shape-skew">
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
      </div>
      <div class="container pb-0">
          <div class="row row-grid align-items-center">
              <div class="col-md-6 order-lg-2 ml-lg-auto">
                  <div class="position-relative pl-md-5">
                      <img src="img/ill/ill-2.svg" class="img-center img-fluid">
                  </div>
              </div>
              <div class="col-lg-6 order-lg-1">
                  <card v-for="i in 5" :key="i" shadow class="shadow-lg--hover mt-5">
                      <div class="d-flex px-3">
                          <div>
                              <icon name="ni ni-satisfied" gradient="success" color="white" shadow
                                    rounded></icon>
                          </div>
                          <div class="pl-4">
                              <h5 class="title text-success">24 Jam</h5>
                              <p>Tim PSC 119 selalu siaga 24 jam dengan peralatan, fasilitas dan armada yang selalu optimal</p>
                          </div>
                      </div>
                  </card>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      features: []
    }
  }
}
</script>
