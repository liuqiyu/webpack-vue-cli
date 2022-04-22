<template>
  <div id="app"
       class="container">
    {{message}}
  </div>
</template>

<script>
export default {
  data () {
    return {
      message: '123321321'
    }
  }
}
</script>

<style lang="scss">
#container {
  background: red;
}
</style>