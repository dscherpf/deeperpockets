<script setup>
  import TitleBar from './TitleBar.vue';
  import CharacterTile from './CharacterTile.vue';
  import AudioTile from './AudioTile.vue';
</script>

<template>
  <div class="container">
    <TitleBar />
    <section class="game">
      <div class="characterTiles">
        <CharacterTile />
        <CharacterTile />
        <CharacterTile />
        <CharacterTile />
      </div>
      <div class="audioTiles">
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
        <AudioTile />
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
@use "@/scss/components/DeeperPocketsGame.scss"
</style>
