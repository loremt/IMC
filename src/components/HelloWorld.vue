<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
   <h1>Indice de masa corporal == {{ 100 * (peso / (altura*altura))}}</h1>
    <input type="text" v-model="peso">
    <input type="text" v-model="altura"> 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    altura:Number,
    peso:Number
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
