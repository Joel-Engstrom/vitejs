<script setup>
import MyButtons from "./components/MyButtons.vue";
import Counter from "./components/Counter.vue";
import RadioButtons from "./components/RadioButtons.vue";
import Title from "./components/Title.vue";
</script>

<template>
  <div class="container">
    <Title />
    <MyButtons />
    <va-chip shadow> chip with shadow </va-chip>
    <Counter />
    <RadioButtons />
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  justify-content: center;
  height: 100vh;
  width: 100vw;
  margin: 0;
  padding: 0;
  background-color: #181123;
}

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
</style>
