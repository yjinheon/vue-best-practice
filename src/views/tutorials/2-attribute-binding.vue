<template>
  <h1 v-bind:class="titleClass">Make me red</h1> <!-- add dynamic class binding here -->
</template>


<script>
export default {
  data() {
    return {
      titleClass: 'title'
    }
  }
}
</script>


<style>
.title {
  color: red;
}
</style>
