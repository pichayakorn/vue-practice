<template>
  <div>
    <h1>V-Model</h1>
    <input v-model="message" />
    <h3>{{ message }}</h3>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "",
    };
  },
};
</script>