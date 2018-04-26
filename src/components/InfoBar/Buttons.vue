<template lang="pug">
div.btn-group(role="group")
  button.btn.btn-light.px-16(
    type="button",
    :class="{ 'btn-active': isActive }",
    @click="isActive = !isActive"
    ) All
  button.btn.btn-light.px-16(type="button") Withdrawal
  button.btn.btn-light.px-16(type="button") Additions
</template>

<script>
 export default{
   data: () => ({
     isActive: false
   })
 }
</script>

<style lang="sass" scoped>
  .btn
    background-color: #f9f9f9 !important
    font-family: "Roboto", sans-serif !important
    font-weight: 400 !important
    font-size: 16px !important
    line-height: 24px !important
  .btn-active
    background-color: #57b6ff !important
    border-color: #57b6ff !important
    color: #fff !important
</style>
