<template>
  <div class="overflow-x-hidden bg-[#FDF9F1]">
    <Header />
    <CountDown />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Header from "../components/Header.vue";
import CountDown from "@/components/CountDown.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    Header,
    CountDown,
  },
});
</script>
