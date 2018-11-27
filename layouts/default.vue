<template>
  <div>
    <app-header></app-header>
    <main>
      <fade-transition
        :duration="250"
        origin="center"
        mode="out-in">
        <router-view/>
      </fade-transition>
    </main>
    <app-footer></app-footer>
  </div>
</template>
<script>
import { FadeTransition } from 'vue2-transitions'
import AppHeader from '@/components/Layout/AppHeader'
import AppFooter from '@/components/Layout/AppFooter'

export default {
  components: {
    FadeTransition,
    AppHeader,
    AppFooter
  }
}
</script>
