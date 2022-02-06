<template>
  <div>
    <Counter :count="9" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Counter from '../components/Counter.vue'

export default defineComponent({
  setup() {
  },
  components: { Counter }
})
</script>
