<template>
  <tabbar>
    <tabbar-item>
      <!--<img slot="icon" src="../assets/demo/icon_nav_button.png">-->
      <span slot="label">微信</span>
    </tabbar-item>
    <tabbar-item show-dot>
      <!--<img slot="icon" src="../assets/demo/icon_nav_msg.png">-->
      <span slot="label">通讯录</span>
    </tabbar-item>
    <tabbar-item selected >
      <!--<img slot="icon" src="../assets/demo/icon_nav_article.png">-->
      <span slot="label">发现</span>
    </tabbar-item>
    <tabbar-item badge="2">
      <!--<img slot="icon" src="../assets/demo/icon_nav_cell.png">-->
      <span slot="label">我</span>
    </tabbar-item>
  </tabbar>
</template>
<script>
  import { Tabbar, TabbarItem } from 'vux'

  export default {
    name: 'app-footer',
    components: {
      Tabbar,
      TabbarItem
    },
    data () {
      return {
//        msg: 'Hello World!'
      }
    }
  }
</script>

