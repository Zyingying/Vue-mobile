<template>
  <div>

    <!--<x-button type="primary">登录</x-button>-->
    <!--<x-button type="default">注册</x-button>-->

    <!--<router-link to="https://qiye.163.com/m/login.htm">-->
      <!--<x-button type="primary">登录</x-button>-->
    <!--</router-link>-->
    <!--<dialog-box></dialog-box>-->
    <app-footer></app-footer>
  </div>

</template>

<script>
import { XButton, Box, Panel } from 'vux'
import AppFooter from '../components/appFooter'
export default {
  components: {
    AppFooter,
    XButton,
    Box,
    Panel
//    DialogBox
  },
  data () {
    return {
      msg: 'Hello World!'
    }
  }
}
</script>

<style>

</style>
