<template></template>
<script setup lang="ts">
import { onMounted } from "vue";
import TypeIt from "typeit";

onMounted(() => {
  new TypeIt(".tagline", {
    strings: [
      "嵌入式开发涵盖硬件接口设计、驱动编写、RTOS 开发和应用实现，广泛用于消费电子、工业控制、汽车电子等领域。",
    ],
    speed: 200,
  }).go();
});
</script>
