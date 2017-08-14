<template>
  <div class="dialog-box">
    <div></div>
  </div>
</template>
<script>
  import { Panel } from 'vux '
  export default {
    name: 'dialog-box',
    components: {
      Panel
    },
    data () {
      return {
//        msg: 'Hello World!'
      }
    }
  }
</script>
<style>
  .dialog-box{
    border-top:1px solid #eee;
    border-bottom: 1px solid #eee;
  }
</style>
