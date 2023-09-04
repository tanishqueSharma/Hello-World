<template>
<!-- <div>
  <h1>{{msg}}</h1>
  <SignUp />
  <LoginPage />
  </div> -->
  <h1>{{msg}}</h1>
  <router-link to="/home">HomePage</router-link><br>
<router-link to="/login">LoginPage</router-link><br>
<router-link to="/sign-up">SignUp</router-link>
  <router-view></router-view>
</template>

<script>
//import LoginPage from './components/LoginPage.vue'
//import SignUp from './components/SignUp.vue'
export default {
  name: 'App',
  // components:{
  //   SignUp,
  //   LoginPage
  // },
  
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
