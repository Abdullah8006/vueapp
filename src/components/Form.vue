<template>
  <div class="form">
    <input type="text" name="Username" value="">
  </div>
</template>

<script>
import axios from 'axios';

export default {
  name: 'form',
  data: function () {
    return {
      msg: 'Form component'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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

table {
  text-align: left;
}
</style>
