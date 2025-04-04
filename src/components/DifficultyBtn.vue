<template>
  <div >
    <p>{{ title }}</p>
  </div>
</template>

<script>
export default {
  props:["title"]
}
</script>

<style lang="scss" scoped>
  @use "@/scss/components/difficultyBtn.scss" as *;
</style>