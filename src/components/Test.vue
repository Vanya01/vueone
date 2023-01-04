<template>
  <h1>Test {{text}}</h1>
</template>

<script>
export default {
  name: "Test",
  props: {
    text: {
      type: String,
      required: true
    }
  }
}
</script>

<style>

</style>