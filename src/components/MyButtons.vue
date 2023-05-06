<template>
  <div class="buttonContainer">
    <va-button color="info" gradient class="mr-6 mb-2"> Information </va-button>
    <va-button color="danger" gradient class="mr-6 mb-2">
      Close the application
    </va-button>
    <va-button color="warning" gradient class="mr-6 mb-2">
      Are you sure?
    </va-button>
  </div>
</template>

<style scoped>
.buttonContainer {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100%;
  margin: 20px;
}
</style>
