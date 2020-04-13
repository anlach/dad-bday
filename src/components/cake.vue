<template>
  <div class="cake">
    <h2>Snuff out the candles!</h2>
    <div id="container">
    </div>
  </div>
</template>

<script>
export default {
  name: 'cake',
  props: {
    msg: String
  }
}
</script>

<style >
#container {
  width: 300px;
  height: 300px;
  text-align: center;
  background: rgba(36, 22, 9, 0.959);
}
</style>
