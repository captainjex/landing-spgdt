<template>
    <div>
        <examples></examples>
        <visi-misi></visi-misi>
        <feature-section></feature-section>
        <call-to-action></call-to-action>
    </div>
</template>
<script>
import Examples from '@/components/SectionIndex/Examples'
import VisiMisi from '@/components/SectionIndex/VisiMisi'
import FeatureSection from '@/components/SectionIndex/Feature'
import CallToAction from '@/components/SectionIndex/CallToAction'

export default {
  components: {
    Examples,
    VisiMisi,
    FeatureSection,
    CallToAction
  }
}
</script>
