<template>
    <div class="relative w-full">
      <div class="w-full h-1 bg-gray-200 bg-opacity-30">
        <div
          class="h-1 bg-teal-400"
          :style="{ width: `${percentage}%` }"
        ></div>
      </div>
      <div
        class="absolute -mt-6 text-teal-400 font-bold text-sm"
        :style="{ left: `${percentage}%`, transform: `translateX(-${percentage}%)` }"
      >
        {{ percentage }}%
      </div>
    </div>
  </template>

  <script>
  export default {
    props: {
      percentage: {
        type: Number,
        required: true,
        default: 0
      }
    }
  };
  </script>

  <style scoped>
  </style>
