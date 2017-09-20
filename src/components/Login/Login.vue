<template>
  <div class="login">
  <a class="btn" @click='show=!show'>点击我</a>
  <transition name='info'>
    <div v-if='show' class="test">我是弹出的额</div>
    </transition>
  </div>
</template>
<script>
export default {
  name: 'login',
  data () {
    return {
      show: false
    }
  }
}
</script>
<style scoped lang='less'>

.login{
  color:green;
  position: relative;
  height: 100%;
  .info-enter,.info-leave-active{
    height: 0;
    transform:translate3d(0,100%,0);
  }
  .info-enter-active,.info-leave-active{
    transition:all .5s ease-in-out;
  }
  .btn{
    width: 200px;
    height: 40px;
    background: #111;
  }
  .test{
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 400px;
    background: #000;
    text-align: center;
    line-height: 400px;
    font-size: 20px;
    color:#fff;
  }
}
</style>
