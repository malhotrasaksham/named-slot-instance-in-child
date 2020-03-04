<template>
  <div id="app">
    <HelloWorld>
      <template #primary>
        <div class="content">Hello Vue!</div>
      </template>
    </HelloWorld>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
}
</style>
