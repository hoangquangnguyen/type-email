<template>
  <div class="m-auto flex flex-col items-center">
    <div class="mt-[140px] flex flex-col items-center">
      <h2
        class="max-w-[630px] text-center text-[50px] font-semibold leading-[63px]"
      >
        More than just drips and newsletters
      </h2>
      <p
        class="mt-[18px] max-w-[480px] text-center text-[18px] font-normal leading-[23px]"
      >
        awareness through email became a must-have, and our ESP wasn't cutting
      </p>
    </div>

    <div
      class="ml-[130px] mt-[95px] flex flex-row items-center justify-between gap-x-[100px]"
    >
      <div class="relative z-10 flex-1">
        <img src="@/assets/featuresboard.png" alt="" class="relative z-10" />
        <div
          class="absolute -top-[10%] -left-[70%] z-0 h-[120%] w-full bg-[#EFE7D7CC]"
        ></div>
      </div>
      <div class="flex flex-1 flex-col items-start gap-y-3">
        <h4 class="max-w-[380px] text-[40px] font-semibold leading-[50px]">
          Create raving fans that keep buying over and over you get the point.
        </h4>
        <p class="max-w-[510px] text-[18px] font-normal leading-[28px]">
          Unlock customer insights to grow your business faster. Store all your
          customer data collected from storefront to marketing channels in one
          central hub far easy use in every strategy.
        </p>
        <p>
          Our open rate has tripled and our click rate on links is up at least
          15%.
        </p>
        <button class="rounded-xl bg-[#00BD82] px-14 py-4 text-white">
          Learn More
        </button>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "FeaturesComponent",
});
</script>
