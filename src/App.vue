<template>
  <div id="app" class="container">
    <img src="./assets/logo.png" class="logo">
    <Login></Login>
    <hr/>
    <todo-list></todo-list>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import TodoList from './components/TodoList'
import Login from './components/Login'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TodoList,
    Login
  }
}
</script>

<style>

* {
  box-sizing: border-box;
}

.container  {
  max-width: 600px;
  margin: 0 auto;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

.logo {
display: block;
  margin: 20px auto;
  height: 75px;
}

</style>
