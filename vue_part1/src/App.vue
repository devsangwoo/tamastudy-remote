<template>
  <div id="app">
    <Todo />
  </div>
</template>

<script>
import Todo from './components/Todo';
export default {
  name: 'App',
  components: {
    Todo,
  },
};
</script>

<style lang="scss">
@import './styles/main.scss';
</style>
