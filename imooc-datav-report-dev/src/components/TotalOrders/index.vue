<template>
  <div class="total_orders">
     <common-card
      :title="title"
      :value="value"
    >
     <div class="compare">222</div>
      <template v-slot:footer>
        <div class="emphasis">333</div>
      </template>
    </common-card>
  </div>
</template>
<script>
import CommonCardMixins from '../../mixins/CommonCardMixins'
export default {
  mixins: [ CommonCardMixins ],
  data() {
    return {
      title: '累计订单量',   // 标题
      value: '$ 111111'
    }
  }
}
</script>
<style lang="scss" scoped>

</style>