<template>
  <div id="app">
    <img src="./assets/logo.png">
    <MyComponent msg="This is a prop edit in app.vue."/>
   <e1 />
     <e2 />
   <!--- <HelloWorld /> --> 
    <!--<router-view/>-->
  </div> 

</template>


<script>
import MyComponent from './components/MyComponent'
import HelloWorld from './components/HelloWorld'
import e1 from './components/e1'
import e2 from './components/e2'
export default {
   
  name: 'App',
  components: {
    MyComponent,
    HelloWorld,
    e1,
    e2
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Kanit|Prompt');
#app {
  font-family: 'Kanit', sans-serif;
  
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
<!--font-family: 'Avenir', Helvetica, Arial, sans-serif;-->