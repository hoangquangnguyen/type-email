<template>
  <!-- navigation -->
  <header class="flex h-[900px] flex-col bg-black">
    <div
      class="mx-[140px] flex flex-row items-center justify-between pt-[48px]"
    >
      <p class="text-gradient text-3xl">Type Email</p>
      <div
        class="flex flex-row gap-9 text-center text-base font-normal text-white"
      >
        <p>Home</p>
        <p>Pricing</p>
        <p>Resources</p>
        <p>Support</p>
      </div>
      <Button
        class="mr-0 rounded-md bg-gray-700 py-[9px] px-[25px] text-center text-white hover:bg-gray-600"
        >Login</Button
      >
    </div>

    <div
      class="left-1/2 mx-auto mt-[80px] flex max-w-[830px] flex-col items-center"
    >
      <h1
        class="text-gradient text-center text-[52px] font-semibold leading-[62px]"
      >
        Online shoppers into loyal, lifetime customers with email & sms
        marketing
      </h1>
      <div
        class="mt-[54px] flex flex-row items-center justify-between text-lg font-normal text-white"
      >
        <button
          class="rounded-[10px] bg-green-600 px-[30px] py-[18px] hover:bg-green-500"
        >
          Get Started
        </button>
        <button class="ml-7 flex flex-row items-center">
          <p>How it work</p>
          <img src="@/assets/video-button.png" alt="" class="ml-4" />
        </button>
      </div>
    </div>
  </header>
  <div class="relative mx-8 flex h-[300px] items-center justify-around">
    <img
      src="@/assets/dasboard.png"
      alt=""
      class="absolute top-0 -translate-y-1/2"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HeaderComponent",
  components: {},
});
</script>
