<template>
  <div :class="btnStyle">
    <p>{{ title }}</p>
  </div>
</template>

<script>
export default {
  props: ["title", "btnStyle"]
}
</script>

<style lang="scss" scoped>
  @use "@/scss/components/actionBtn.scss" as *;
</style>
