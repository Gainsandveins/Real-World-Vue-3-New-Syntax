<script setup>
// defineProps({
//   msg: {
//     type: String,
//     required: true
//   }
// })
import { Ref } from 'vue';
const event = ref({
  
})
</script>

<template>
  <div class="event-card">
  </div>
</template>

<style scoped>
.event-card{
  padding: 20px;
  width: 250px;
  cursor: pointer;
  border: 1px solid black;
  margin-bottom: 18px;
}
.event-card:hover{
  transform: scale(1.01);
  box-shadow: 1 3px 12px 0 rgba(0, 0, 0, 0.2);
}
</style>
