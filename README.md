# liquid-svg

liquid-svg 是一个水球进度百分比，支持三种主题色，蓝色、绿色、黄色；默认黄色。

## 效果

![demo](https://i.postimg.cc/TP90m1HF/demo.gif)

### 如何使用?

```bash
npm i vue2-liquid-svg
```

## 版本

vue3 版本，请使用 [liqiud-svg](https://www.npmjs.com/package/liquid-svg) 包

### 示例

```vue
<template>
  <LiquidSvg :data="50" />
  <LiquidSvg :data="10" :width="100" theme="blue" />
  <LiquidSvg :data="50" :width="300" theme="green" />
  <LiquidSvg :data="90" :width="300" theme="yellow" />
</template>

<script>
import { LiquidSvg } from "vue2-liquid-svg";
import "vue2-liquid-svg/liquid-svg.css";
</script>
```

### 参数

| 属性  | 描述                           |  类型  | 默认值 | 必填 |
| ----- | ------------------------------ | :----: | :----: | ---- |
| data  | 百分比                         | Number |   0    | 否   |
| width | 水球宽高                       | Number |  100   | 否   |
| theme | 主题色可选 blue、green、yellow | String |  blue  | 否   |
