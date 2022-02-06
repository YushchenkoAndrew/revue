<template>
  <div>
    <Counter :count="9" />
  </div>
</template>

<script lang="ts">
import Counter from "../components/Counter.vue";
export default defineComponent({
  components: { Counter },
});
</script>
