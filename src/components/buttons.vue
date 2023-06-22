<script setup>
defineProps({
  msg: {
    title: String,
    background: String,
    text_color: String,
    outline: String,
    width: String,
    height: String,
    required: true
  }
})

import { computed } from 'vue';

const getStyleObject = computed(() => {
  return {
    background: msg.background ? 'background' : ''
  };
});
</script>

<template>
    <button class="btn" :style="{ backgroundColor: msg.background, color:msg.text_color, border: msg.outline, width: msg.width, height: msg.height}"> {{ msg.title }}</button> 

</template>

<style  scoped>
template{
    display: inline-block;
}
.btn{
    width: 81px;
    height: 36px;
    

    font-family: 'Noto Sans JP';
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 20px;
    text-align: center;
    margin-bottom: 35px;
    border-radius: 6px;
    background-color: white;

}
.btn:hover{
    /* background-color: rgba(41, 98, 255, 0.1); */
    /* filter: grayscale(1px); */
    opacity: 0.5;
    cursor: pointer;
}
</style>
