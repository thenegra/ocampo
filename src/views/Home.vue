<template>
  <div class="home">
    <h1>Home</h1>
    <ListaTrabajos></ListaTrabajos>
  </div>
</template>

<script>
// @ is an alias to /src

import ListaTrabajos from '../components/ListaTrabajos.vue'
export default {
  name: 'Home',
  components: {
    //HelloWorld
    ListaTrabajos
  }
}
</script>
