<template>
  <div id="app">
    <div class="flex-row">
      <LiquidSvg :data="50" :width="300" theme="blue" />
      <LiquidSvg :data="50" :width="300" theme="green" />
      <LiquidSvg :data="50" :width="300" theme="yellow" />
    </div>
  </div>
</template>

<script>
// 本地
// import LiquidSvg from "./package/LiquidSvg/index.vue";
// npm
import { LiquidSvg } from "vue2-liquid-svg";
import "vue2-liquid-svg/liquid-svg.css";
export default {
  name: "App",
  components: { LiquidSvg },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.flex-row {
  width: 90%;
  margin: 0 auto;
  display: flex;
  align-content: center;
  justify-content: space-between;
}
</style>
