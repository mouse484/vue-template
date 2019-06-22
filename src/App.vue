<template>
  <div id="app">
    <componentA/>
  </div>
</template>

<script>
import componentA from "./components/componentA.vue";

export default {
  name: "app",
  components: {
    componentA
  }
};
</script>

