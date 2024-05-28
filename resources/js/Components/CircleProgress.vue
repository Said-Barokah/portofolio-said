<template>
    <div class="flex items-start justify-start">
        <svg class="w-28 h-28" viewBox="0 0 36 36">
            <path class="text-[#373b40] stroke-current" d="M18 2.0845
           a 15.9155 15.9155 0 0 1 0 31.831
           a 15.9155 15.9155 0 0 1 0 -31.831" fill="none"
            stroke-width="1.5" />
            <path class="text-teal-400 stroke-current" :d="pathDescription" fill="none" stroke-width="1.5"
                :stroke-dasharray="dashArray" stroke-linecap="round" />
            <text x="18" y="20.35" class="fill-current text-[#68e0cf]" text-anchor="middle">{{ percentage }}%</text>
        </svg>
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
  },
  computed: {
    dashArray() {
      const circumference = 2 * Math.PI * 15.9155;
      const offset = ((100 - this.percentage) / 100) * circumference;
      return `${circumference - offset} ${offset}`;
    },
    pathDescription() {
      return `M18 2.0845
              a 15.9155 15.9155 0 0 1 0 31.831
              a 15.9155 15.9155 0 0 1 0 -31.831`;
    }
  }
};
</script>
