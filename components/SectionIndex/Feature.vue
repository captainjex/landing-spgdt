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
              <div class="col-lg-12">
                    <div class="row row-grid justify-content-center">
                        <div v-for="(feature, index) in features" :key="index" class="col-lg-4 my-3">
                            <card class="border-0 text-center" hover shadow body-classes="py-5">
                                <icon :name="feature.icon" :type="feature.color" rounded class="mb-4">
                                </icon>
                                <h6 :class="`text-${feature.color} text-uppercase`">{{ feature.title }}</h6>
                                <p class="description mt-3">{{ feature.description }}</p>
                            </card>
                        </div>
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
      features: [
        {
          icon: 'ni ni-check-bold',
          color: 'primary',
          title: '24 Jam',
          description:
            'Tim PSC 119 selalu siaga 24 jam dengan peralatan, fasilitas dan armada yang selalu optimal'
        },
        {
          icon: 'ni ni-check-bold',
          color: 'default',
          title: 'Gratis',
          description:
            'Dapatkan Layanan pre-hospital penanganan darurat tanpa batasan gender, suku, ras, agama, usia dan tanpa biaya.'
        },
        {
          icon: 'ni ni-check-bold',
          color: 'info',
          title: 'Resmi',
          description:
            'Kami bermitra dengan pemerintah setempat untuk menghadirkan layanan SPGDT terbaik untuk masyarakat'
        },
        {
          icon: 'ni ni-check-bold',
          color: 'success',
          title: 'Cepat Tanggap',
          description:
            'Lebih dari 300 kejadian darurat telah dilaporkan dan diproses kurang dari 10 menit  secara profesional.'
        },
        {
          icon: 'ni ni-check-bold',
          color: 'warning',
          title: 'Profesional',
          description:
            'Didukung oleh paramedik profesional dan stakeholder terkait, termasuk rumah sakit, puskesmas, kepolisian serta Pemadam Kebakaran'
        }
      ]
    }
  }
}
</script>
