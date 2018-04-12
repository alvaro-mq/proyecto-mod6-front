<template>
  <div class="hello">
    <v-alert type="success" :value="true">
      This is a success alert.
    </v-alert>
     <v-badge left>
      <span slot="badge">6</span>
      <v-icon large color="grey lighten-1">shopping_cart</v-icon>
    </v-badge>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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
</style>
