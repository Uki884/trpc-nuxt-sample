<template>
  <div>
    {{ test }}
  </div>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  setup() {
    const test = 'hello world'
    return {
      test
    }
  },
})
</script>

