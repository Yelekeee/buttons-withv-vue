<script setup>
defineProps({
  desc: {
    title: String,
    text: Boolean,
    required: true
  }
})
</script>

<template>
    <p class="description" :style="{ color: desc.text ? '#333333;' : '#828282' }">{{ desc.title }}</p>
    
    
</template>

<style scoped>
template{
  display: flex;
}
.description{
  width: 220px;
  height: 12px;

  font-family: 'Ubuntu Mono';
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 12px;
  margin-bottom: 10px;
  /* identical to box height */

  text-align: start;
}
</style>
