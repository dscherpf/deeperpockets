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

<style scoped>
div {
  display: flex;
  background-color: #e5e4e2;
  border-radius: 4px;
  height: fit-content;
  width: fit-content;
  align-items: center;
  justify-content: center;
  margin: 1rem 0.5rem;
}

div:hover {
  cursor: pointer;
}

p {
  font-size: 16px;
  margin: 0;
  padding: 0.5rem 1rem;
}
</style>