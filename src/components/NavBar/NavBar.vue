<template lang="pug">
    nav.top-nav.navbar.d-flex.justify-content-between
      a.navbar-brand.d-flex.p-0
        img.logo.align-self-center(src="~assets/logo-only.svg", alt="Logo: InventiStudio recruitment task")
        img.brand.align-self-center(src="~assets/brand.svg", alt="Brand: InventiStudio recruitment task")
      p.align-self-center Sign out
</template>

<script>
import InfoBar from 'src/components/InfoBar/InfoBar.vue'
 export default{
   data: () => ({

   })
 }
</script>

<style lang="sass" scoped>
  .top-nav
    margin: 43px 185px 70px 85px
    height: 50px
    a
      width: auto
      .logo
        height: 50px
        margin-right: 30px
      .brand
        height: 20px
</style>
