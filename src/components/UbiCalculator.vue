<template>
  <div class="ubicalculator">
    <h1>{{ msg }}</h1>
    <p>
      A simple calculator to estimate the impact a Universal Basic Income (UBI) would have on your after tax income
    </p>
  </div>
</template>

<script>
export default {
  name: 'UbiCalculator',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
