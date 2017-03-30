<template>
  <div id="app">
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      info: 'Sartura frontend task.'
    }
  }
}
</script>

<style lang="less">
@nice-blue: #5B83AD;
@light-blue: @nice-blue + #111;

#header {
  color: @light-blue;
}
</style>