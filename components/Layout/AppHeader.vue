<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <a slot="brand" class="navbar-brand mr-lg-5" href="/">
                <img src="logo.png">
            </a>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="/">
                        <img src="logo.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a :href="appLink" target="_blank"
                       class="btn btn-neutral btn-icon">
                        <span class="btn-inner--icon">
                        <i class="fa fa-cloud-download mr-2"></i>
                        </span>
                        <span class="nav-link-inner--text">Download</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from '@/components/BaseNav'
import BaseDropdown from '@/components/BaseDropdown'
import CloseButton from '@/components/CloseButton'

export default {
  data() {
    return {
      appLink: 'https://play.google.com/store/apps/details?id=id.spgdt.app'
    }
  },
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
}
</script>
<style>
</style>
