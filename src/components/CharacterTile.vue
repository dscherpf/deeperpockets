<script setup>
import AudioSlot from './AudioSlot.vue';
import ProgressPip from './ProgressPip.vue';
</script>

<template>
  <div class="characterContainer">
    <section class="radio">
      <span class="material-symbols-rounded">radio_button_unchecked</span>
    </section>
    <section class="audioSlots">
      <AudioSlot slot-name="Q"/>
      <AudioSlot slot-name="W"/>
      <AudioSlot slot-name="E"/>
      <AudioSlot slot-name="R"/>
    </section>
    <section class="pips">
      <ProgressPip />
      <ProgressPip />
      <ProgressPip />
      <ProgressPip />
      <ProgressPip />
    </section>
  </div>
</template>

<style lang="scss" scoped>
@use "@/scss/components/CharacterTile.scss";
</style>