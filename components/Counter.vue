<template>
  <div v-if="c">
    <p>Counter: {{ c }}</p>
    <a @click="c--">Click Me!!</a>
  </div>
  <div v-else>Hello world</div>
</template>

<script lang="ts">
export default defineComponent({
  name: "Counter",
  props: {
    count: Number,
  },
  data() {
    return { c: this.$props.count ?? 0 };
  },
});
</script>
