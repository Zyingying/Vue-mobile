<template>
  <div>

    <user-list></user-list>
    <app-footer></app-footer>
  </div>

</template>

<script>
import { XButton, Box } from 'vux'
import AppFooter from '../components/appFooter'
import UserList from '../components/list.vue'
export default {
  components: {
    AppFooter,
    XButton,
    Box,
    UserList
  },
  data () {
    return {
      msg: 'Hello World!'
    }
  }
}
</script>

