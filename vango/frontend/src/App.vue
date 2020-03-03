<template>
  <div id="app">
    <p class="hi-world">greeting </p>
  </div>
</template>

<script>
export default {
  data() {
    greeting: "Look at the vue."
  }
}
</script>

<style>
  body {
    font-family: -apple-system, 'Open Sans', sans-serif;
  }
  .hi-world {
    display: flex;
    background-color: darkslateblue;
    color: white;
    border-radius: 5px;
    padding: 10px;
  }
</style>
