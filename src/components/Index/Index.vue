<template>
  <div class="index">
    {{msg}}
  </div>
</template>
<script>
export default {
  name: 'index',
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
