<template>
  <main-layout>
    <div class="deco">
      <p>Welcome home</p>
      <p>this is a brand new day</p>
    </div>
  </main-layout>
</template>

<script>
import MainLayout from "../layouts/Main.vue";

export default {
  components: {
    MainLayout
  }
};
</script>
<style scoped>
.deco {
  font-family: 'Courier New', Courier, monospace;
  font-size: 4em;
  color: blue;
  text-align: center;
}
</style>