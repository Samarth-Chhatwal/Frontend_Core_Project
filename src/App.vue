<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Flafal"/> -->
    <!-- <try/> -->
    <try data='Samarth'/>
    <try-2/><br>
    <user/>
    <!-- <Check/>
    <Counter />
    <Text /> -->
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
// import Check from './components/Check.vue'
// import Counter from './components/Counter.vue'
import Try from './components/Try.vue'
import Try2 from './components/Try2.vue'
import User from './components/User.vue'
export default {
  name: 'App',
  components: {
    
    Try,Try2,User
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
