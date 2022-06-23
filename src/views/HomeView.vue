<template>
  <div class="overflow-x-hidden bg-[#FDF9F1]">
    <Header />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Header from "../components/Header.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    Header,
  },
});
</script>
