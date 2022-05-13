<template>
  <div>
    <h1>Home</h1>
    <card class="center"></card>
    <card class="center">2nd Card</card>
    <card class="center"
      ><card style="width: 200px; margin: 0 auto 0 auto">3rd Card</card></card
    >
  </div>
</template>

<script>
import card from "./card";

export default {
  components: {
    card,
  },
};
</script>

<style>
.center {
  margin-left: auto;
  margin-right: auto;
}
</style>