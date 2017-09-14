<template>
  <div class="indexHeader">
  	<a class="unbundling" href="unbundling.html">解绑账号</a>
  	<a class="time" href="javascript:;" id="open">{{time}}</a>
  </div>
</template>
<script>
export default {
  name: 'indexHeader',
  data () {
    return {
      time: '2017-27-14'
    }
  }
}
</script>
<style scoped lang='less'>
.indexHeader{
  	width: 100%;
    height: 7.9227rem;
    background: #499a76;
    position: relative;
    background: url(../../assets/524980347691454594.png)no-repeat 0 0;
    background-size: cover;
    .unbundling{
    	position: absolute;
	    left: 0.438rem;
	    top: 0.438rem;
	    background: url(../../assets/icon_home_lock.png) no-repeat 0 0;
	    background-size: 0.8244rem 0.8244rem;
	    height: 0.8244rem;
	    line-height: 0.8244rem;
	    font-size: 0.6183rem;
	    padding-left: 1.0048rem;
	    color: #fff;
    }
    .time{
    	position: absolute;
	    right: 0.438rem;
	    top: 0.438rem;
	    background: url(../../assets/icon_home_date.png) no-repeat 0 0;
	    background-size: 0.8244rem 0.8244rem;
	    height: 0.8244rem;
	    line-height: 0.8244rem;
	    font-size: 0.6183rem;
	    padding-left: 1.0048rem;
	    color: #fff;
    }
}
</style>
