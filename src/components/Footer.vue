<template>
  <footer>
  	<div class="pc">
	  	<div class="cont">
	  		<div class="cont_">
	  			<h2>福建省淼鑫投资管理有限公司</h2>	
			  	<h3><p class="add">ADD：厦门市思明区观音山营运中心18号楼402单元</p>
			  	<!-- <span>|</span><p class="hot">全国统一客服热线：400-XXX-XXX</p> -->
			  	</h3>
			  	<h4><p class="copyright">Copyright © 2017 ShunFengDi.All Rights</p><p class="icp">Reserved闽ICP备18004059号-1</p></h4>
	  		</div>
	  	</div>
  	</div>
  	<div class="mob">
  		<div class="cont">
	  		<div class="cont_">
	  			<h2>福建省淼鑫投资管理有限公司</h2>	
			  	<h3><p class="add">ADD：厦门市思明区观音山营运中心18号楼402单元</p>
			  	<!-- <p class="hot">统一客服热线：400-XXX-XXX</p> -->
			  	</h3>
			  	<h4><p class="copyright">Copyright © 2017 ShunFengDi.All Rights</p><p class="icp">Reserved闽ICP备18004059号-1</p></h4>
	  		</div>
	  	</div>
  	</div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	footer {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 20.93vh;
		text-align: center;
		background: #1A1A1A;
	}
	.cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	}
	.cont h2 {
		margin-bottom: 2.04vh;
		color: #999999;
		font-size: 1.3vw;
	}
	.cont h3 {
		margin-bottom: 2.04vh;
		color: #999999;
		font-size: 1.15vw;
	}
	.cont p, .cont span {
		display: inline-block;
		margin-right: 1.04vw;
	}
	.cont .hot, .cont .icp {
		margin-right: 0;
	}
	.cont h4 {
		color: #616161;
		font-size: 0.83vw;
	}

	@media screen and (max-width: 750px) {
	    .mob {
	      	display: block;
	    }

	    footer {
			height: 26.24vh;
		}
		.cont {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100%;
		}
		.cont h2 {
			margin-bottom: 1.02vh;
			color: #999999;
			font-family: 'PingFangSC-Regular';
			font-size: 4.27vw;
		}
		.cont h3 {
			margin-bottom: 3vh;
			color: #999999;
			font-family: 'PingFangSC-Regular';
			font-size: 3.2vw;
		}
		.cont .hot, .cont .icp {
			margin-right: 0;
		}
		.cont h4 {
			color: #616161;
			font-size: 3.2vw;
			font-family: 'PingFangSC-Light';
		}
	}
</style>
