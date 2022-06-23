<template>
  <div class="flex h-[300px] flex-row items-center justify-around bg-[#E2F471]">
    <div class="flex flex-col items-center gap-[22px]">
      <h3 class="text-[44px] font-semibold leading-[55px]">1,700+</h3>
      <p class="text-[18px] font-normal leading-[28px]">
        Companies using Sendlance
      </p>
    </div>
    <div class="flex flex-col items-center gap-[22px]">
      <h3 class="text-[44px] font-semibold leading-[55px]">40 million+</h3>
      <p class="text-[18px] font-normal leading-[28px]">Emails sent daily</p>
    </div>
    <div class="flex flex-col items-center gap-[22px]">
      <h3 class="text-[44px] font-semibold leading-[55px]">20.000+</h3>
      <p class="text-[18px] font-normal leading-[28px]">Users on sendlance</p>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "CountDown",
});
</script>
