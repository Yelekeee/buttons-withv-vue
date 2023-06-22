
<script setup>
import buttons from '../components/buttons.vue'
import texts from '../components/texts.vue'


</script>

<template>
    <div class="main">
        <h1 class="header">Buttons</h1>
        <div class="content1">
            <div class="content-card1">
            <texts class="texting" :desc= "{title: '<Button />', text: true}" />
            <buttons  class="content-card1-btn1" :msg="{ title: 'Default', background: '#E0E0E0' }" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '&:hover, &:focus', text: false}" />
            <buttons :msg="{ title: 'Default', background:'#AEAEAE'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button variant=”outline />', text: true}" />
            <buttons :msg="{ title: 'Default', text_color: '#3D5AFE', outline: '2px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '&:hover, &:focus', text: false}" />      
            <buttons :msg="{ title: 'Default', background:'rgba(41, 98, 255, 0.1)', text_color: '#3D5AFE', outline: '2px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button variant=”text” />', text: true}" />
            <buttons class="content-card1-btn5" :msg="{ title: 'Default', text_color: '#3D5AFE', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '&:hover, &:focus', text: false}" />
            <buttons :msg="{ title: 'Default', background:'rgba(41, 98, 255, 0.1)', text_color: '#3D5AFE', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button disableShadow />', text: true}" />
            <buttons :msg="{ title: 'Default', background:'#3D5AFE', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1"></div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button disabled />', text: true}" />
            <buttons :msg="{ title: 'Disabled', background:'#E0E0E0', text_color: '#9E9E9E', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button variant=”text” disabled />', text: true}" />
            <buttons :msg="{ title: 'Disabled', background:'white', text_color: '#9E9E9E', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button startIcon=”local_grocery_store” />', text: true}" />
            <div class="part">
            <buttons :msg="{ title: '& Default', background:'#2962FF', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button endIcon=”local_grocery_store” />', text: true}" />
            <div class="part">
            <buttons :msg="{ title: 'Default &', background:'#2962FF', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>
            </div>
           

        </div>

        <div class="content2">
            <div class="content-card1">
            <texts class="texting" :desc= "{title: '<Button size=”sm” />', text: true}" />
            <buttons  class="content-card1-btn1" :msg="{ title: 'Default', background: '#2962FF', text_color: '#FFFFFF', outline: '2px solid rgba(61, 90, 254, 1)', width: '76px', height: '31px'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button size=”md” />', text: true}" />
            <buttons :msg="{ title: 'Default', background:'#2962FF', text_color: '#FFFFFF', outline: '2px solid rgba(61, 90, 254, 1)', width: '81px', height: '36px'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button size=”lg” />', text: true}" />
            <buttons :msg="{ title: 'Default', background:'#2962FF', text_color: '#FFFFFF', outline: '2px solid rgba(61, 90, 254, 1)',  width: '86px', height: '41px'}" />
            </div>

            <div class="content-card1">
            </div>
            
            <div class="content-card1">
            <texts class="texting" :desc= "{title: '<Button color=”default” />', text: true}" />
            <buttons :msg="{ title: 'Default', background: '#E0E0E0', text_color: '#3F3F3F', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button color=”primary” />', text: true}" />
            <buttons :msg="{ title: 'Default', background:'#2962FF', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button color=”secondary” />', text: true}" />
            <buttons :msg="{ title: 'Default', background:'#455A64', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '<Button color=”danger” />', text: true}" />
            <buttons :msg="{ title: 'Default', background:'#D32F2F', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc= "{title: '<Button color=”default” />', text: true}" />
            <buttons :msg="{ title: 'Default', background: '#E0E0E0', text_color: '#3F3F3F', outline: '0px solid rgba(61, 90, 254, 1)'}" class="custom-button" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '', text: true}" />
            <buttons :msg="{ title: 'Default', background:'#2962FF', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '', text: true}" />
            <buttons :msg="{ title: 'Default', background:'#455A64', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>

            <div class="content-card1">
            <texts class="texting" :desc="{title: '', text: true}" />
            <buttons :msg="{hover: 'red', title: 'Default', background:'#D32F2F', text_color: '#FFFFFF', outline: '0px solid rgba(61, 90, 254, 1)'}" />
            </div>


            </div>
        </div>
     <!-- <button class="proba">click me</button> -->
  </template>
  
  
  <style>

.img{
    width: 20px;
    height: 20px;
}

.custom-button:hover {
  /* Hover styles */
  background-color: #FF5252;
  /* Change the color to your desired hover color */
}
.part{
    display: flex;
}
.proba{
    justify-content: center;
    width: 100px;
    height: 25px;
    border-radius: 10px; 
    size: 'sm';
    border: 0px solid white;
}
.main{
    width: 100%;
    height: 100%;
    margin-top: 10%; 
}
.header{

    width: 93px;
    height: 36px;
    left: 320px;
    top: 53px;

    margin-top: 15px;
    margin-bottom: 15px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 36px;
    /* identical to box height */
    /* Gray 2 */
    color: #4F4F4F;

  }
  .content1{
    display: grid;
    grid-template-columns: repeat(2, 0.2fr);

  }

  .content2{
    display: grid;
    grid-template-columns: repeat(4, 0.2fr);

  }

 
  /* @media (min-width: 1024px) {
    .main {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  } */
  </style>
  