<template>
  <div>
    <!--<group title="switch the type">-->
      <!--<radio title="type" v-model="type" :options="['1', '2', '3', '4', '5']"></radio>-->
    <!--</group>-->
    <panel header="对话列表"  :list="list" ></panel>
    <!--<panel header="对话列表" :footer="footer" :list="list" ></panel>-->

  </div>
</template>

<script>
  import { Panel, Group, Radio } from 'vux'
  export default {
    name: 'user-list',
    components: {
      Panel,
      Group,
      Radio
    },
    data () {
      return {
        type: '1',
        list: [{
          src: 'http://placeholder.qiniudn.com/60x60/3cc51f/ffffff',
          title: '用户一',
          desc: '这是我和你的对话',
          url: '/component/cell'
        }, {
          src: 'http://placeholder.qiniudn.com/60x60/3cc51f/ffffff',
          title: '用户二',
          desc: '哩个系俄同你葛对话',
          url: {
            path: '/component/radio',
            replace: false
          },
          meta: {
            source: '来源信息',
            date: '时间',
            other: '其他信息'
          }
        }],
        footer: {
          title: '查看更多',
          url: 'http://vux.li'
        }
      }
    }
  }
</script>
