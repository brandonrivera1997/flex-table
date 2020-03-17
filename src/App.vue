<template>
  <div class="app">
    <div class="rivera">
      <MyTable class="my-table"/>
       <b-button class="my-button">Default</b-button>
    </div>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue';
import MyTable from './components/MyTable.vue';

export default {
  name: 'App',
  components: {
    MyTable
  }
}
</script>

<style>

.app {
  margin: 1rem;
  display: flex;
  border: 2px solid lime;
  /*height: 40rem;*/
}

.my-table {
  flex-grow: 0;
  border: 2px solid red;
}

.rivera {
  display: flex;
  border: 3px solid black;
  height: 40rem;
  flex-direction: column;
}

.my-button {
  /*margin-top: 1rem;*/
  align-self: center;
  /*flex-grow: 1;*/
}

</style>
