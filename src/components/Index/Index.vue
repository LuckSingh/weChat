<template>
  <div class="index">
    <IndexHeader></IndexHeader>
    
  </div>
</template>
<script>
import IndexHeader from './IndexHeader'
export default {
  name: 'indexHeader',
  components:{IndexHeader},
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
