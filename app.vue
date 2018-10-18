<template>
  <span>
    {{ message }}
  </span>
</template>

<script>
export default {
  data () {
    return {
      message: 'Hello Vue!'
    }
  }
}
</script>

<style scoped>
  span {
    color: #2e9704;
  }
</style>
