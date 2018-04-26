<template lang="pug">
  main.container-fluid.p-0.m-0.flex-column
    v-navbar
    section
      v-infobar
</template>

<script>
import NavBar from 'src/components/NavBar/NavBar.vue'
import InfoBar from 'src/components/InfoBar/InfoBar.vue'
 export default{
   components: {
     'v-navbar': NavBar,
     'v-infobar': InfoBar
   },
   data: () => ({
     ballance: (1304.01).toString().replace('.', ','),
     isActive: false
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
  section
    height: auto
    margin: 0px 135px
</style>
