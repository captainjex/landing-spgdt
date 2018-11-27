<template>
    <div>
        <hero></hero>
        <basic-elements></basic-elements>
        <inputs></inputs>
        <custom-controls></custom-controls>
        <navigation></navigation>
        <javascript-components></javascript-components>
        <icons></icons>
        <examples></examples>
        <download-section></download-section>
        <carousel></carousel>
    </div>
</template>
<script>
import Hero from '@/components/SectionIndex/Hero'
import BasicElements from '@/components/SectionIndex/BasicElements'
import Inputs from '@/components/SectionIndex/Inputs'
import CustomControls from '@/components/SectionIndex/CustomControls'
import Navigation from '@/components/SectionIndex/Navigation'
import JavascriptComponents from '@/components/SectionIndex/JavascriptComponents'
import Carousel from '@/components/SectionIndex/Carousel'
import Icons from '@/components/SectionIndex/Icons'
import Examples from '@/components/SectionIndex/Examples'
import DownloadSection from '@/components/SectionIndex/DownloadSection'

export default {
  components: {
    Hero,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    Icons,
    Examples,
    DownloadSection
  }
}
</script>
