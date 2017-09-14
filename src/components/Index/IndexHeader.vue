<template>
  <div class="indexHeader">
  {{msg}}
  </div>
</template>
<script>
export default {
  name: 'indexHeader',
  data () {
    return {
      msg: '首页-头部'
    }
  }
}
</script>
<style scoped lang='less'>
.indexHeader{
  color:red;
}
</style>
