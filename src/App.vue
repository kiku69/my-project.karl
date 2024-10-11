<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>


<template>
  <div class="container">
    <div class="row">
      <div class="box box-1">
        <h6>Resilience</h6>
      </div>
      <div class="box box-2">
        <h6>Growth</h6>
      </div>
      <div class="box box-3">
        <h3>Engagement</h3> 
      </div>
    </div>
    <div class="row">
      <div class="box box-4">
        <h3>Visioning </h3>
      </div>
      <div class="box box-5">
        <h6>Goal Orientation</h6>
      </div>
      <div class="box box-6">
        <h6>Self heliief</h6>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.row {
  display: flex;
  gap: 8px;
}

.box-1 {
  background-color: #e63e3e;
  width: 100px;
  height: 100px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  border-radius: 5px;
}

.box-2 {
  background-color: #1fab89;
  width: 100px;
  height: 100px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  border-radius: 5px;
}

.box-3 {
  background-color: #d17219;
  width: 210px;
  height: 210px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  border-radius: 5px;
}

.box-4 {
  background-color: #a168f1;
  width: 210px;
  height: 210px;
  margin-top: -110px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  border-radius: 5px;
}

.box-5 {
  background-color: #1c7eff;
  width: 100px;
  height: 100px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  border-radius: 5px;
}

.box-6 {
  background-color: #a200ff;
  width: 100px;
  height: 100px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  border-radius: 5px;
}
</style>
