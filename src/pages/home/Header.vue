<template>
	  <header class="header">
	  	<div class="header-left iconfont icon-arrowleft"></div>
	  	<div class="header-title">
	  		输入城市/景点/游玩主题
	  	</div>
	  	<div class="header-right">
	  		<div class="header-city-wrapper">
	  			<span class="header-city">北京</span>	
	  		</div>
	  		
	  	</div>
	  </header>
</template>

<script>

export default{
	
}
</script>

<style>
	.header{
		height:.88rem;
		background: #00dcb4;
	}
	.header-left{
		color: #FFFFFF;
		width: .4rem;
		padding:0 .2rem;
		line-height: .88rem;
		font-size: .4rem;
		float: left;
	}
	.header-title{
		position: absolute;
		left:.8rem;
		right: 1.3rem;
		top: .14rem;
		background: #FFFFFF;
		line-height: .6rem;
		border-radius: .06rem;
		text-indent: .2rem;
		color: #ccc;
	}
	.header-right{
		float: right;
		width: 1.28rem;
		line-height: .88rem;
		text-align: center;
		color: #fff;
	}
	
	.header-city-wrapper{
		position: relative;
		padding-right: .3rem;
		
	}
	.header-city{
		display: inline-block;
		width: 1rem;
		overflow: hidden;
		text-overflow: ellipsis;
		white-space: nowrap;		
	}
	.header-city::after{
		content: "\0020";
		position: absolute;
		top:.4rem;
		right:.14rem;
		width: 0;
		height: 0;
		background: #FFFFFF;
		border: .1rem solid #00dcb4;
		border-top: .1rem solid #fff;		
	}
</style>
