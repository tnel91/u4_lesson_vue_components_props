<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <MyComponent msg="This is my component!"/>
    <SecondComponent msg="Second Component"/>
    <ThirdComponent msg1='Third Component' msg2='paragraph'/>
  </div>
</template>

<script>
import MyComponent from './components/MyComponent.vue';
import SecondComponent from './components/SecondComponent.vue';
import ThirdComponent from './components/ThirdComponent.vue';
export default {
  name: 'App',
  components: {
    MyComponent,
    SecondComponent,
    ThirdComponent
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
