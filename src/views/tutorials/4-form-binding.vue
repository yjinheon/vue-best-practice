<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      // update component state
      // script 에 선언된 요소들을 String으로 받는다는게 핵심
      this.count++ // this를 통해 component instance에 접근
    }
  }
}
</script>

<template>
  <!-- make this button work -->
  <button @click="increment">count is: {{ count }}</button>
</template>
