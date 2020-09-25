<template>
  <view>
    <!-- collections -->
    <uni-list>
      <!-- <uni-list-item title="Collections" note="personal"></uni-list-item> -->
      <!-- 标题卡片模式 -->
      <uni-card
        title="xx"
        subtitle="yy"
        mode="title"
        :is-shadow="true"
        thumbnail="https://img-cdn-qiniu.dcloud.net.cn/uniapp/images/muwu.jpg"
        note="Tips"
      >
        <text class="test">xx</text>
        <text>yy</text>
      </uni-card>
    </uni-list>
  </view>
</template>

<script>
import { uniList, uniCard } from '@dcloudio/uni-ui'
export default {
  components: {
    uniList,
    uniCard,
    // uniListItem,
  },
}
</script>

<style lang="scss" scoped>
.test {
}
</style>
