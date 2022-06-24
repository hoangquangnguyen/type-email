<template>
  <div class="overflow-x-hidden bg-[#FDF9F1]">
    <HeaderComponent />
    <CountdownComponent />
    <NewsletterComponent />
    <FeaturesComponent />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HeaderComponent from "../components/HeaderComponent.vue";
import NewsletterComponent from "../components/NewsletterComponent.vue";
import CountdownComponent from "../components/CountdownComponent.vue";
import FeaturesComponent from "@/components/FeaturesComponent.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    HeaderComponent,
    CountdownComponent,
    NewsletterComponent,
    FeaturesComponent,
  },
});
</script>
