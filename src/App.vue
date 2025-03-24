<script setup>
import NavBar from './components/NavBar.vue';
import Square from './components/Square.vue';
import Circle from './components/Circle.vue';
import ActionBtn from './components/ActionBtn.vue';
import DifficultyBtn from './components/DifficultyBtn.vue';
</script>

<template>
  <NavBar />
  <div id="container">
    <h3>Category/Date</h3>
    <section id="grid">
      <Square v-for="num in 16"/>
    </section>
    <section id="attemptSection">
      <h4>Mistakes/Tries left:</h4>
      <Circle v-for="num in 5"/>
    </section>
    <section id="actionSection">
      <ActionBtn title="Shuffle" btnStyle="default"/>
      <ActionBtn title="Deselect All" btnStyle="default"/>
      <ActionBtn title="Submit" btnStyle="submit"/>
    </section>
    <section id="difficultySection">
      <DifficultyBtn title="Easy"/>
      <DifficultyBtn title="Daily"/>
      <DifficultyBtn title="Hard"/>
    </section>
  </div>
</template>

<script>
</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

#container {
  width: 624px;
  margin: 0 auto;
}

#grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  justify-items: center;
  gap: 0.5rem;
}

#attemptSection, 
#actionSection, 
#difficultySection {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}

</style>
