<template>
  <div class="index">
    <IndexHeader></IndexHeader>
    <IndexShopping></IndexShopping>
  </div>
</template>
<script>
import IndexHeader from './IndexHeader'
import IndexShopping from './IndexShopping'

export default {
  name: 'indexHeader',
  components:{IndexHeader,IndexShopping},
  data () {
    return {
      msg: '首页'
    }
  }
}
</script>
<style scoped lang='less'>
.index{
  color:red;
}
</style>
