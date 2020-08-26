<template>
  <footer class="footer">
    Powered by <a href="https://github.com/gin-gonic/gin" target="_blank">gin</a> •
    <a href="https://github.com/88250/pipe" target="_blank">Pipe</a> {{$store.state.version}}
  </footer>
</template>

<style lang="sass">
  @import '~assets/scss/_variables'

  .footer
    padding: 17px 15px
    border-top: 1px solid $border-color
    font-size: 16px
    background-color: $white
</style>
