<template lang="html">
  <div class="test-1">
    <h1 class="heading">{{ msg }}</h1>
    <div class="input-box">
      <button></button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'list',
  data () {
    return {
      msg: 'Testing!'
    }
  }
}
</script>

<style scoped>

.heading {
  color: pink;
}

</style>
