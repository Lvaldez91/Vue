<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <Testcomponent></Testcomponent>
  </div>
</template>

<script>
import Testcomponent from './Testcomponent.vue'
export default {
  name: 'HelloWorld',
  components: {
    Testcomponent
  },
  props: {
    msg: String
  },
  data() {
    return {
      texto: 'Hola Mundo es mi primer programa en VUE',
    }
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
