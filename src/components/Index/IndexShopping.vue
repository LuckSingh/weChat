<template>
  <div class="indexShopping cleafix">
  	<a class="shop" href="javascript:;">健康商城</a>
  	<a class="healthy" href="javascript:;">健康咨询</a>
  	<a class="service" href="javascript:;">健康服务</a>
  </div>
</template>
<script>
export default {
  name: 'indexShopping',
  data () {
    return {
      time: '2017-27-14'
    }
  }
}
</script>
<style scoped lang='less'>
.indexShopping{
    padding: 0.38647rem 0;
    height: 4.8593rem;
    a{
    	float: left;
	    width: 4.7793rem;
	    height: 1.2523rem;
	    padding-top: 3.607rem;
	    margin-left: 0.4251rem;
	    text-align: center;
	    font-size: 0.7729rem;
	    color: #fff;
	    &.shop{
	    	background: url(../../assets/icon_home_market.png) no-repeat 0 0;
    		background-size: cover;
	    }

	    &.healthy {
		    background: url(../../assets/icon_home_consult.png) no-repeat 0 0;
		    background-size: cover;
		}

		&.service {
		    background: url(../../assets/icon_home_service.png) no-repeat 0 0;
		    background-size: cover;
		}
    }
}
</style>
