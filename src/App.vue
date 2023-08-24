<template>
  <div class="container app__container">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ChatBot msg="ChatBot"/>
  </div>

</template>

<script>
import HelloWorld from './components/HelloWord.vue'
import ChatBot from './components/ChatBot.vue'



export default {
  name: 'App',
  components: {
    HelloWorld, ChatBot
  }
}
</script>

<style>
#app {

  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
.app__container {
  display: flex;
  justify-content: space-around;
  min-height: 100vh


}
</style>
