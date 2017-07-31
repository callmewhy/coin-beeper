<template>
  <div id="wrapper">
    hello
  </div>
</template>

<script>
  export default {
    methods: {
      open(link) {
        this.$electron.shell.openExternal(link)
      },
    },
  }
</script>

<style>

</style>
