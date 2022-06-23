<template>
  <div class="overflow-x-hidden bg-[#FDF9F1]">
    <HeaderComponent />
    <CountdownComponent />
    <NewsletterComponent />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HeaderComponent from "../components/HeaderComponent.vue";
import NewsletterComponent from "../components/NewsletterComponent.vue";
import CountdownComponent from "../components/CountdownComponent.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    HeaderComponent,
    CountdownComponent,
    NewsletterComponent,
  },
});
</script>
