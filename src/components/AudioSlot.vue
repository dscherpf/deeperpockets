<template>
  <div> {{ slotName }} </div>
</template>

<style lang="scss" scoped>
@use "@/scss/components/AudioSlot.scss" 
</style>


<script>
export default {
  props: [
    'slotName'
  ]
}
</script>