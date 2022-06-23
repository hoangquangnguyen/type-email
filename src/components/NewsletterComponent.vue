<template>
  <div class="flex flex-col items-center">
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
      <div class="flex-1">
        <h4 class="max-w-[380px] text-[40px] font-semibold leading-[50px]">
          Drive 30-40% of your revenue with email marekiting
        </h4>
        <p class="max-w-[510px] text-[18px] font-normal leading-[28px]">
          Unlock customer insights to grow your business faster. Store all your
          customer data collected from storefront to marketing channels in one
          central hub far easy use in every strategy.
        </p>
        <div class="mt-9 flex flex-row items-start gap-x-5">
          <div>
            <div class="w-fit rounded-full bg-[#00BD82] p-2">
              <img src="@/assets/home-automation.png" alt="" />
            </div>
            <h4 class="mt-5 text-xl font-semibold leading-6">
              Marketing Automation
            </h4>
            <p class="mt-2">
              From open rates to conversion performance, get access to tons of
              data.
            </p>
            <a
              href="/"
              class="mt-7 font-medium underline decoration-[#00BD82] underline-offset-4"
              >Read More</a
            >
          </div>
          <div>
            <div class="w-fit rounded-full bg-[#00BD82] p-2">
              <img src="@/assets/logo-python.png" alt="" />
            </div>
            <h4 class="mt-5 text-xl font-semibold leading-6">Experiments</h4>
            <p class="mt-2">
              From sign up to sale track your contacts every move.
            </p>
            <a
              href="/"
              class="mt-7 font-medium underline decoration-[#00BD82] underline-offset-4"
              >Read More</a
            >
          </div>
        </div>
      </div>

      <div class="relative z-10 flex-1">
        <img src="@/assets/HiShownpic.png" alt="" class="relative z-10" />
        <div
          class="absolute -top-[10%] left-[30%] z-0 h-[120%] w-full bg-[#EFE7D7CC]"
        ></div>
      </div>
    </div>
  </div>
  <div class="h-[100px]"></div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "NewsletterComponent",
  components: {},
});
</script>
