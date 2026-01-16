<template>
  <div class="okra">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Okra',
      message: 'I like Okra'
    }
  }
};
</script>

<style>
  .okra {
      border: dashed black 1px;
      display: inline-block;
      margin: 10px;
      padding: 10px;
      background-color: lightgreen;
      alignment: center;
    }
</style>