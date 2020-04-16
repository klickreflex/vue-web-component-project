<template>
  <div class="box">
    <h1>My Vue Web Component</h1>
    <div>{{ msg }}</div>
  </div>
</template>
<script>
  export default {
    props: ['msg']
  }
</script>

<style scoped>
    .box {
        border: 3px dotted rebeccapurple;
        padding: 16px;
    }

    h1 {
        color: lightgreen;
        font-weight: bold;
        font-size: 58px;
    }

    div {
        font-family: monospace;
        font-size: 18px;
    }
</style>