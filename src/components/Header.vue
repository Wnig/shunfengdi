<template>
  <header>
  <div class="pc">
	  <div class="cont">
		<a class="logo" @click="jump" ><img src="../assets/1.svg" alt=""></a>
	  	<nav>
	  		<ul>
				<li v-for="(navs, index) in navData" v-bind:class="{'btn_sel': index == num}" @click="selMenus(index)">
	              <router-link :to="navs.links">{{navs.tit}}</router-link>
	            </li>
	            <li class="backstage">
	              <a href="https://sfd.fjmxtz.com/sfd/" target="_blank">后台登录</a>
	            </li>
	  		</ul>
	  	</nav>
	  </div>
  </div>
  <div class="mob">
  	<div class="cont">
		<a class="logo" @click="jump" ><img src="../assets/1.svg" alt=""></a>
		<div class="list-con clearfix">
			<img @click="isShow" class="list" src="../assets/menu.svg" alt="">
		</div>
		<div class="nav-con" v-if="show" @click="isShow">
	  		<nav>
	  			<ul>
					<li v-for="(navs, index) in navData" v-bind:class="{'btn_sel': index == num}" @click="selMenus(index)">
		              <router-link :to="navs.links">{{navs.tit}}</router-link>
		            </li>
	            	<li>
	              		<a href="https://sfd.fjmxtz.com/sfd/" target="_blank">后台登录</a>
	            	</li>
	  			</ul>
	  			<div class="code">
		  			<img src="../assets/40.png" alt="">
		  			<p>长按识别小程序码</p>	
	  			</div>
	  			
	  			<!-- <div class="hot">
		            <p>统一客服热线</p>
		            <h2>400-XXX-XX</h2>
		         </div> -->
	  		</nav>
		</div>
  	</div>
  </div>
  </header>
</template>

<script>
let storage = window.sessionStorage;
export default {
  name: 'Header',
  data () {
    return {
    	navData: [
	        {tit: '首页', links:'/'},
	        {tit: '招商加盟', links:'/Join'},
        ],
      	num: '',
      	show: false
    }
  },
  created: function() {
    if(storage['selNumsfd']) {
      this.num= storage['selNumsfd'];
    } else {
      this.num = 0;
    };
  },
  methods: {
    selMenus(index) {
      storage['selNumsfd'] = index;
      this.selShow = false;
    },
    isShow() {
      //点击：左侧菜单栏 收起-展开
      this.show = ! this.show;
    },
    jump() {
      storage['selNumsfd'] = 0;
      this.selShow = false;
      this.$router.push({path: '/'});
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	header {
		display: flex;
		justify-content: center;
		height: 9.79vw;
	}
	.cont {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 90%;
		margin: 0 auto;
	}
	.logo {
		display: flex;
		justify-content: center;
		width: 11.3vw;
		margin-right: 20vw;
		cursor: pointer;
	}
	.logo img {
		display: block;
		width: 100%;
	}
	nav {
		display: flex;
		justify-content: center;
		align-items: center;
		text-align: center;
	}
	nav ul {
		display: flex;
		justify-content: center;
	}
	nav li {
		margin: 0 4vw;	
	}
	nav li a {
		color: #fff;
		font-size: 1.3vw;
	}
	nav a {
		display: block;
		width: 11.41vw;
		height: 2.76vw;
		line-height: 2.76vw;
		cursor: pointer;
	}
	nav .btn_sel a {
		color: #FBBB02;
		font-family: 'PingFangSC-Regular';
	}
	.backstage a {
		color: #FFFFFF;
	}
	.backstage {
		margin-left: 7vw;
		margin-right: 1vw;
		background: url('../assets/03.svg') center center no-repeat;
		background-size: 100% 100%;
	}

	@media screen and (max-width: 750px) {
	    .mob {
	      	display: block;
	    }

	    header {
			height: 34vw;
		}
		.cont {
			width: 90vw;
			height: 24vw;
		}
		.logo {
			justify-content: flex-start;
			width: 80%;
			margin-right: 5vw;
		}
		.logo img {
			width: 31.2vw;
		}
		.list-con {
			float: right;
			display: flex;
			justify-content: center;
			align-items: center;
		}
		.list {
			width: 8.8vw;
		}
		.nav-con {
			position: fixed;
	        left: 0;
	        top: 0;
	        width: 100%;
	        height: 100vh;
	        background: rgba(0, 0, 0, 0.65);
	        z-index: 9999999999;
		}
		nav {
			position: relative;
			text-align: left;
			width: 61.67vw;
	        height: 100vh;
	        background: #FFFFFF;
	        box-shadow: 0 7px 10px 0 rgba(0, 0, 0, 0.44);
		}
		nav ul {
			display: block;
			width: 100%;
			height: 100%;
			padding-top: 16.64vh;
			padding-left: 7.47vw;
		}
		nav li {
			width: 100%;
			margin: 0 0 7.83vh 0;
		}
		nav li a {
			display: block;
			width: 100%;
			height: 100%;
			color: #6A6A6A;
			line-height: 5vw;
			font-size: 4.8vw;
			font-family: 'PingFangSC-Regular';
		}
		nav p {
	      margin-bottom: 1.05vh;
	      color: #797979;
	      font-size: 3.2vw;
	    }
	    nav h2 {
	      color: #000000;
	      line-height: 6.67vw;
	      font-size: 6.5vw;
	      font-family: 'PingFangSC-Semibold';
	    }
	    nav .hot {
	      position: absolute;
	      left: 7.47vw;
	      bottom: 9.45vh;
	    }

	    .code {
		  position: absolute;
	      left: 0;
	      bottom: 9.45vh;
	      width: 100%;
	    }
	    .code img {
	    	display: block;
	    	width: 33.33vw;
		    height: 33.33vw;
		    margin: 0 auto 1.69vh;
	    }
	    .code p {
	    	text-align: center;
			font-size: 3.2vw;
	    }
	}
</style>
