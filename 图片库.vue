<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import IconEcosystem from "@/components/icons/IconEcosystem.vue";
var list = [1,2,3,4,5,6,7,8,9,10]
</script>

<template>
  <div style="display: flex; flex-wrap: wrap">
    <div v-for="i in list" style="border: solid red 1px; margin: 0.5rem 0.25rem 0.5rem; background-color: #eee">
      <img style="height: 10rem; width: 10rem" src="http://vip.51haosuan.cn/static/image/hp.png"/>
      <p style="color: coral; font-size: 2rem">双插盒</p>
      <p style="color: coral">可选锁舌</p>
      <p style="color: blueviolet">{{i}}</p>
    </div>
  </div>
  <div style="background-color: #2c3e50; height: 0.2rem; margin: 1rem"></div>

</template>

<style scoped>


</style>
