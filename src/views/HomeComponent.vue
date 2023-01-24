<script lang="ts">
export default {
  props: [],
};
</script>
<script setup lang="ts">
const intros = [""];
</script>
<template>
  <div class="mockup-code text-sm lg:text-base w-8/12 flex flex-col gap-1">
    <pre
      data-prefix="$"
      class="text-base lg:text-lg bg-warning text-warning-content font-semibold"
    ><code>MyFormTemplate</code></pre>
    <pre data-prefix=">"><code>Welcome to my little form!</code></pre>
    <pre data-prefix=">" class="text-info"><code>Introduction</code></pre>
  </div>
</template>
<style scoped></style>
