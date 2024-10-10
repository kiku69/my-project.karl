<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container">
    <div class="box big">Box 1</div>
    <div class="box">Box 2</div>
    <div class="box">Box 3</div>
    <div class="box big">Box 4</div>
    <div class="box">Box 5</div>
    <div class="box">Box 6</div>
  </div>
</template>

<script>
export default {
  name: 'BoxLayout'
}
</script>

<style>
.container {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.box {
  background-color: lightblue;
  border: 1px solid #007BFF;
  padding: 20px;
  text-align: center;
  flex: 1 1 30%; /* Default size for small boxes */
}

.big {
  flex: 1 1 45%; /* Bigger size for larger boxes */
}
</style>

