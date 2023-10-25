<script setup lang="ts">

</script>

<template>
<div class="content">



<div class="data-form">
  <span class="circle circle--yellow-top"></span>
  <span class="circle circle--yellow-middle"></span>
  <span class="circle circle--blue-right"></span>
  <span class="circle circle--pink-left"></span>
  <span class="circle circle--pink-bottom"></span>
</div>
  
  <dvi class="link">
    <ul class="link--sign-in">
      <li><nuxt-link to="index1">First</nuxt-link></li>
    </ul>
  </dvi>














</div>
</template>

<style scoped>
.content{
  width: 1440px;
  height: 7937px;
}

.circle--yellow-top{
  position: absolute;
  border-radius: 50%;
  width: 400px;
  height: 400px;
  color: #FFDC60;
  margin-right: 1850px;
  margin-bottom: 922px;
}

.circle--yellow-middle{
  position: absolute;
  border-radius: 50%;
  width: 128px;
  height: 128px;
  color: #FFDC60;
}

.circle--blue-right{
  position: absolute;
  border-radius: 50%;
  width: 1220px;
  height: 1220px;
  color: #5956E9;
}

.circle--pink-left{
  position: absolute;
  border-radius: 50%;
  width: 48px;
  height: 48px;
  color: #FAB8C4;
}

.circle--pink-bottom{
  position: absolute;
  border-radius: 50%;
  width: 180px;
  height: 180px;
  color: #FAB8C4;
}

.data-form{
  border-radius: 40px;
  background: #fff;

  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;

  padding: 30px 0 60px;

  width: 50%;
  margin:60px auto 25px;

  position: relative;
}







</style>