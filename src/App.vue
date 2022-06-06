<template>
  <m-header></m-header>
  <Tab></Tab>
  <router-view></router-view>
</template>

<script>
import MHeader from "@/components/header/header";
import Tab from "@/components/tab/tab";
export default {
  components: { MHeader, Tab },
};
</script>
