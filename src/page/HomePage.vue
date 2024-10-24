<script setup>
import AboutComponent from '@/components/AboutComponent.vue'
import DifferentComponent from "@/components/DifferentComponent.vue";
import CeramicsComponent from "@/components/CeramicsComponent.vue";
import PopularComponent from "@/components/PopularComponent.vue";
import JoinComponent from "@/components/JoinComponent.vue";
import HistoryComponent from "@/components/HistoryComponent.vue";
import FooteComponent from "@/components/FooteComponent.vue";
</script>

<template>
  <div class="container">
  <AboutComponent></AboutComponent>
    <DifferentComponent></DifferentComponent>
    <CeramicsComponent></CeramicsComponent>
   <PopularComponent></PopularComponent>
  </div>
<JoinComponent></JoinComponent>
  <div class="container">
  <HistoryComponent></HistoryComponent>
  </div>
  <FooteComponent></FooteComponent>
</template>

<style scoped>

</style>