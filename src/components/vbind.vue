<template>
  <div>
    <h1>V-Bind</h1>
    <button
      v-bind:class="{ green: check, red: !check }"
      v-on:click="check = !check"
    />
    <p v-if="check">This is TRUE</p>
    <p v-else>This is FALSE</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      check: true,
    };
  },
};
</script>

<style>
.green {
  background-color: green;
  width: 100px;
  height: 100px;
}
.red {
  background-color: red;
  width: 100px;
  height: 100px;
}
</style>