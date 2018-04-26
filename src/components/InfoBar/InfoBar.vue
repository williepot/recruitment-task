<template lang="pug">
div.d-flex.justify-content-between.info-bar
  div.d-flex
    h6.align-self-center.p-0.m-0.mr-4 Your wallet's ballance is
    h6.align-self-center.p-0.m-0.ballance {{ ballance }}
  v-buttons
</template>

<script>
import Buttons from './Buttons.vue'
 export default{
   components: {
     'v-buttons': Buttons
   },
   data: () => ({
     ballance: (1304.01).toString().replace('.', ','),
   })
 }
</script>

  <style lang="sass" scoped>
    .info-bar
      height: 40px
      width: 100%
    .ballance
      font-weight: 900
      color: #3692d8
  </style>
