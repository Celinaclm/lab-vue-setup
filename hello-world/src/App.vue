<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Hola mundo!" />
    <h1>To-Do List</h1>
    <ul>
       <li>
        <to-do-item label="My ToDo Item"></to-do-item>
      </li>
    </ul>
  </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue';
import ToDoItem from './components/ToDoItem.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    ToDoItem,
  },
};
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2C3E50;
  margin-top: 60px;
}
h1 {
  color:royalblue;
}
</style>
