<script>
export default {
  data() {
    return {
      options: ["one", "two", "three"],
      selectedOption: "one",
    };
  },
};
</script>

<template>
  <div class="container">
    <va-radio
      v-model="selectedOption"
      :option="options[0]"
      color="warning"
      label="warning"
    />
    <va-radio
      v-model="selectedOption"
      :option="options[1]"
      color="danger"
      label="danger"
    />
    <va-radio
      v-model="selectedOption"
      :option="options[2]"
      color="info"
      label="info"
    />
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
