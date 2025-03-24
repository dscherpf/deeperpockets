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

<style scoped>
div {
  display: flex;
  border-radius: 27px;
  border: 1px solid #000000;
  height: fit-content;
  width: fit-content;
  align-items: center;
  justify-content: center;
  margin: 0 0.5rem;
}

div:hover {
  cursor: pointer;
}

p {
  font-size: 16px;
  font-weight: 700;
  margin: 0;
  padding: 0.5rem 1rem;
}

.submit {
  background-color: #000000;
  color: #ffffff;
}
</style>
