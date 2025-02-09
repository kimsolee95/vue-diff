<template lang="">
  <div>
    <CodeDiff
      old-string="12345"
      new-string="3456"
      output-format="side-by-side"
      filename="olfile"
      newFilename="ddd"
      hideStat="false"
    />
  </div>
</template>
<script setup>
import { CodeDiff } from 'v-code-diff'
</script>
<style lang="">
  
</style>