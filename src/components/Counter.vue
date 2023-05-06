<script>
export default {
  data() {
    return {
      value: 10,
    };
  },
};
</script>

<template>
  <div class="container">
    <va-counter v-model="value" messages="A simple counter" />
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  align-items: center;
  text-align: center;
  justify-content: center;
  height: 100%;
  margin: 20px;
}
</style>
