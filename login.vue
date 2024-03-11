<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import IconEcosystem from "@/components/icons/IconEcosystem.vue";
</script>

<template>
  <h2 style="text-align: center; margin-bottom: 3rem"> 垠域网络 </h2>
  <img style="display: block; height: 8rem; margin: 1rem auto" src="./assets/icon/logo.svg"/>
  <div style="display: flex; justify-content: center; align-items: center">
    <img style="height: 1.5rem;  margin: 0.5rem;" src="./assets/icon/i-user.svg"/>
    <input style="height: 2rem;" type="text" name="fname">
  </div>
  <div style="display: flex; justify-content: center; align-items: center">
    <img style="height: 1.5rem;  margin: 0.5rem;" src="./assets/icon/i-lock.svg"/>
    <input style="height: 2rem;" type="password" name="lname">
  </div>
  <div style="text-align: center">
    <button style="width: 4rem; margin: 1rem 1rem;"> 登录 </button>
    <button style="width: 4rem; margin: 1rem 1rem;"> 登出 </button>
  </div>
</template>

<style scoped>

 .wrapper {
    display: flex;
    justify-content: space-evenly;
    align-items: center;

    //flex-wrap: wrap;
  }
</style>
