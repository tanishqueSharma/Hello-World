<template>
<div>
  <h1>{{msg}}</h1>
  <SignUp />
  </div>
</template>

<script>
import SignUp from './components/SignUp.vue'
export default {
  name: 'App',
  components:{
    SignUp
  },
  
  data(){
    return{
      msg:'Hello World!'
    }
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
