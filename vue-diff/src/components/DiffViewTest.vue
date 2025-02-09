<template>
  <div class="diff-container">
    ffff
    <Diff
      :mode="'split'"
      :theme="'light'"
      :prev="'old version\nline 2\nline 3'"
      :current="'old version\nline 2 changed\nline 3'"
    />
  </div>
</template>

<script>
import { Diff } from "vue-diff";
import "vue-diff/dist/index.css";

export default {
  components: {
    Diff,
  },
};
</script>

<style>
/* .diff-container {
  max-width: 100%;
  overflow-x: auto;
  min-height: 200px;
} */
</style>