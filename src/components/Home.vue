<template>
  <div class="home">
  	<div class="pc">
		<div class="selection selection-1">
			<video class="video1" src="../assets/video.mp4" autoplay="" loop=""></video>
			<div class="con">
				<app-header></app-header>
			  	<div class="cont">
				  	<div class="cont_">
				  		<h1>顺风递,<strong>0</strong>抽成的顺风车速递服务平台！</h1>
				  		<p>微信小程序一键下单<br/>同城快送，极速达！跨城直送，当日达！</p>
				  		<div class="down-con" @click="slideDown">
					  		<div class="down"></div>
					  		<div class="slidedown">Scroll Down</div>
				  		</div>
				  	</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-2">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>关于顺风递<i class="right_bor"></i></h2>
					<div class="con_p">
						<div class="con_p_">
							<p style="margin-bottom: 0.99vh"><strong>【顺风递】</strong>是一款基于顺风车司机及私家车主自身资源打造的一款<strong>顺风速递服务</strong>微信小程序，旨在构建服务商与用户间的信息对接，在共享经济模式中，实现用户目标化和服务商收入的双赢。</p>
							<p>城市中，随着顺风车用户数量快速增长，顺风车司机越来越多，利用顺风车解决同城、短途，长途的物品流通、货物取送，俨然成为了一个新的“风口”。顺风递平台提供用户需求信息，通过竞价抢单方式，司机仅需支付1元信息费，收益100%归司机所有，实现共享经济模式下的互利共赢。</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-3">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>平台展示<i class="right_bor"></i></h2>
					<div class="pictureSlider poster-main">
						<div class="poster-btn poster-prev-btn"></div>
						<ul id="zturn" class="poster-list clearfix">
							<li class="poster-item  zturn-item">
								<img src="../assets/7.jpg" alt="">
								<p>首页</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/12.jpg" alt="">
								<p>填写收货地址</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/13.jpg" alt="">
								<p>填写订单信息</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/10.jpg" alt="">
								<p>司机接单</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/11.jpg" alt="">
								<p>我的订单</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/9.jpg" alt="">
								<p>选择司机</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/8.jpg" alt="">
								<p>用户中心</p>
							</li>
						</ul>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-4">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>平台优势<i class="right_bor"></i></h2>
					<p class="discr">1元抢单，平台0抽成，收益100%归司机所有！</p>
					<div class="conts">
						<div class="list_div bg_01">
							竞价机制
						</div>
						<div class="list_div bg_02">
							一对一服务
						</div>
						<div class="list_div bg_03">
							实时位置跟踪
						</div>
						<div class="list_div bg_04">
							包裹安全保障
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-5">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>产品服务<i class="right_bor"></i></h2>
					<div class="conts">
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/18.svg" alt="">
								<h4>帮取件</h4>
								<p>证件、合同、生鲜、特产，省心又便捷<br/>聪明人都把时间放在重要的事情上</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/19.svg" alt="">
								<h4>代送件</h4>
								<p>吃的、喝的、用的、玩的，快速又安全<br/>足不出户省时省力轻松完成任务</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-6">
			<div class="cont">
				<div class="discr-con">
					<h2 class="title"><i class="left_bor"></i>服务城市<i class="right_bor"></i></h2>
					<p class="discr">顺风递在短短上线一个多月的时间内，区域认购已覆盖25个省、自治区、直辖市的500多个区县，其中江苏、山东的认购率达50%以上。加上和国内已经覆盖全国各地网点保险企业合作，对用户无缝的对接服务。让您和您的家人朋友享受到闪送的极速服务。</p>
				</div>
				<div class="map">
					<img src="../assets/20.png" alt="">
					<span class="c_01">北<br/>京</span> 
					<span class="c_02">河<br/>南</span>
					<span class="c_03">江<br/>苏</span>
					<span class="c_04">上<br/>海</span>
					<span class="c_05">浙<br/>江</span>
					<span class="c_06">湖<br/>南</span>
					<span class="c_07">江<br/>西</span>
					<span class="c_08">福<br/>建</span>
					<span class="c_09">广<br/>东</span>
					<span class="c_10">广<br/>西</span>
					<span class="c_11">湖<br/>北</span>
					<span class="c_12">山<br/>东</span>
					<span class="c_13">陕<br/>西</span>
					<span class="c_14">甘<br/>肃</span>
					<span class="c_15">四<br/>川</span>
					<span class="c_16">贵<br/>州</span>
					<span class="c_17">云<br/>南</span>
					<span class="c_19">内<br/>蒙<br/>古</span>
					<span class="c_20">黑<br/>龙<br/>江</span>
					<span class="c_21">辽<br/>宁</span>
					<span class="c_22">天<br/>津</span>
					<span class="c_23">河<br/>北</span>
					<span class="c_24">山<br/>西</span>
					<span class="c_25">重<br/>庆</span>
				</div>
				<ul>
					<li><i class="y_dot"></i>首批已覆盖区域</li>
					<li><i class="b_dot"></i>业务布局中</li>
				</ul>
			</div>
		</div>
		<div class="selection selection-7">
			<div class="cont">
				<div class="discr-con">
					<div class="discr-con_">
						<h2 class="title"><i class="left_bor"></i>顺风递风云榜<i class="right_bor"></i></h2>
					</div>
				</div>
				<div class="top_con">
					<ul class="top_tit clearfix">
						<li class="li_l"><img src="../assets/22.svg" alt=""><span>排名</span></li>
						<li><img src="../assets/23.svg" alt=""><span>用户名</span></li>
						<li><img src="../assets/24.svg" alt=""><span>接单数</span></li>
						<li class="li_r"><img src="../assets/25.svg" alt=""><span>收入（元）</span></li>
					</ul>
					<div class="bor_bottom"></div>
					<div class="top_scroll">
						<div class="top_data">
							<div class="top_data_con">
								<ul class="clearfix">
									<li><i class="gold">1</i></li>
									<li>CSW182299772</li>
									<li>14325</li>
									<li>234135</li>
								</ul>
								<ul class="clearfix">
									<li><i class="silver">2</i></li>
									<li>CSW182299772</li>
									<li>14325</li>
									<li>234135</li>
								</ul>
								<ul class="clearfix">
									<li><i class="copper">3</i></li>
									<li>CSW182299772</li>
									<li>14325</li>
									<li>234135</li>
								</ul>
								<ul class="clearfix">
									<li><i class="iron">4</i></li>
									<li>CSW182299772</li>
									<li>14325</li>
									<li>234135</li>
								</ul>
								<ul class="clearfix">
									<li><i class="iron">5</i></li>
									<li>CSW182299772</li>
									<li>14325</li>
									<li>234135</li>
								</ul>
								<ul class="clearfix">
									<li><i class="iron">6</i></li>
									<li>CSW182299772</li>
									<li>14325</li>
									<li>234135</li>
								</ul>
								<ul class="clearfix">
									<li><i class="iron">7</i></li>
									<li>CSW182299772</li>
									<li>14325</li>
									<li>234135</li>
								</ul>
								<ul class="clearfix">
									<li><i class="iron">8</i></li>
									<li>CSW182299772</li>
									<li>14325</li>
									<li>234135</li>
								</ul>
							</div>
						</div>
					</div>
					<div class="mask"></div>
				</div>
			</div>
		</div>
		<div class="selection selection-8">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>使用流程<i class="right_bor"></i></h2>
					<div class="conts">
						<img src="../assets/38.png" alt="">
						<img src="../assets/39.png" alt="">
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-9">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>服务保障<i class="right_bor"></i></h2>
					<div class="conts">
						<div class="list_div">
							<div class="list_div_">
								<div class="img_bg">
									<img src="../assets/71.svg" alt="">
								</div>
								<p>专业的企业管理公司<br/>
								参与平台运营管理</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="img_bg">
									<img src="../assets/72.svg" alt="">
								</div>
								<p>签约律师事务所<br/>
								作为平台的法律顾问</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-10">
			<div class="cont">
				<div class="cont_">
					<div class="discr">
						<h3>我们的宗旨是</h3>
						<h4>为您提供优质快捷的服务！</h4>
					</div>
					<div class="code">
						<div class="code_">
							<img src="../assets/40.png" alt="">
							<p>立即扫码体验<br/>（小程序二维码）</p>
						</div>
					</div>
				</div>
			</div>
			<app-footer></app-footer>
		</div>
		<div class="fixed">
			<div class="cont">
				<div class="left">
					<p>马上提交加盟，享受专属客户经理一对一咨询服务</p>
					<div class="reply">
						<div class="input_ city">
							<input type="text" placeholder="请选择代理区域">
						</div>
						<div class="input_ comp-name">
							<input type="text" placeholder="请输入公司或姓名">
						</div>
						<div class="input_ tel">
							<input type="text" placeholder="请输入手机号码">
						</div>
						<div class="button">提交申请</div>
					</div>
				</div>
				<!-- <div class="bor_c"></div> -->
				<div class="right">
					<!-- <p>统一客服热线</p>
					<h3>400-XXX-XXX</h3> -->
					<i class="icon-gb"></i>
				</div>
			</div>
		</div>
		<div class="fixed-right fixed-right_">
		  <!-- <p>400-XXX-XXX</p> -->
		</div>
  	</div>
  	<div class="mob">
  		<div class="selection selection-1">
			<img class="video1" src="../assets/video.gif">
			<div class="con">
				<app-header></app-header>
			  	<div class="cont">
				  	<div class="cont_">
				  		<h1>顺风递,<strong>0</strong>抽成的顺风车<br/>速递服务平台！</h1>
				  		<p>微信小程序一键下单<br/>同城快送，极速达！跨城直送，当日达！</p>
				  		<div class="down-con" @click="slideDown">
					  		<div class="down"></div>
					  		<div class="slidedown">Scroll Down</div>
				  		</div>
				  	</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-2">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>关于顺风递<i class="right_bor"></i></h2>
					<div class="con_p">
						<div class="con_p_">
							<p style="margin-bottom: 3.45vh"><strong>【顺风递】</strong>是一款基于顺风车司机及私家车主自身资源打造的一款<strong>顺风速递服务</strong>微信小程序，旨在构建服务商与用户间的信息对接，在共享经济模式中，实现用户目标化和服务商收入的双赢。</p>
							<p>城市中，随着顺风车用户数量快速增长，顺风车司机越来越多，利用顺风车解决同城、短途，长途的物品流通、货物取送，俨然成为了一个新的“风口”。顺风递平台提供用户需求信息，通过竞价抢单方式，司机仅需支付1元信息费，收益100%归司机所有，实现共享经济模式下的互利共赢。</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-3">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>平台展示<i class="right_bor"></i></h2>
					<div class="pictureSlider poster-main">
						<div class="poster-btn poster-prev-btn"></div>
						<ul id="zturns" class="poster-list clearfix">
							<li class="poster-item  zturn-item">
								<img src="../assets/7.jpg" alt="">
								<p>首页</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/12.jpg" alt="">
								<p>填写收货地址</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/13.jpg" alt="">
								<p>填写订单信息</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/10.jpg" alt="">
								<p>司机接单</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/11.jpg" alt="">
								<p>我的订单</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/9.jpg" alt="">
								<p>选择司机</p>
							</li>
							<li class="poster-item  zturn-item">
								<img src="../assets/8.jpg" alt="">
								<p>用户中心</p>
							</li>
						</ul>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-4">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>平台优势<i class="right_bor"></i></h2>
					<p class="discr">1元抢单，平台0抽成，收益100%归司机所有！</p>
					<div class="conts">
						<div class="conts_">
							<div class="list">
								<div class="list_div bg_01">
									竞价机制
								</div>
								<div class="list_div bg_02">
									一对一服务
								</div>
							</div>
							<div class="list">
								<div class="list_div bg_03">
									实时位置跟踪
								</div>
								<div class="list_div bg_04">
									包裹安全保障
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-5">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>产品服务<i class="right_bor"></i></h2>
					<div class="list_div" style="margin-bottom: 5.85vh">
						<div class="list_div_">
							<img src="../assets/18.svg" alt="">
							<h4>帮取件</h4>
							<p>证件、合同、生鲜、特产，省心又便捷<br/>聪明人都把时间放在重要的事情上</p>
						</div>
					</div>
					<div class="list_div">
						<div class="list_div_">
							<img src="../assets/19.svg" alt="">
							<h4>代送件</h4>
							<p>吃的、喝的、用的、玩的，快速又安全<br/>足不出户省时省力轻松完成任务</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-6">
			<div class="cont">
				<div class="cont_">
					<div class="discr-con">
						<h2 class="title"><i class="left_bor"></i>服务城市<i class="right_bor"></i></h2>
						<p class="discr">顺风递在短短上线一个多月的时间内，区域认购已覆盖25个省、自治区、直辖市的500多个区县，其中江苏、山东的认购率达50%以上。加上和国内已经覆盖全国各地网点保险企业合作，对用户无缝的对接服务。让您和您的家人朋友享受到闪送的极速服务。</p>
					</div>
					<div class="map">
						<img src="../assets/08.png" alt="">
						<span class="c_01">北<br/>京</span> 
						<span class="c_02">河<br/>南</span>
						<span class="c_03">江<br/>苏</span>
						<span class="c_04">上<br/>海</span>
						<span class="c_05">浙<br/>江</span>
						<span class="c_06">湖<br/>南</span>
						<span class="c_07">江<br/>西</span>
						<span class="c_08">福<br/>建</span>
						<span class="c_09">广<br/>东</span>
						<span class="c_10">广<br/>西</span>
						<span class="c_11">湖<br/>北</span>
						<span class="c_12">山<br/>东</span>
						<span class="c_13">陕<br/>西</span>
						<span class="c_14">甘<br/>肃</span>
						<span class="c_15">四<br/>川</span>
						<span class="c_16">贵<br/>州</span>
						<span class="c_17">云<br/>南</span>
						<span class="c_19">内<br/>蒙<br/>古</span>
						<span class="c_20">黑<br/>龙<br/>江</span>
						<span class="c_21">辽<br/>宁</span>
						<span class="c_22">天<br/>津</span>
						<span class="c_23">河<br/>北</span>
						<span class="c_24">山<br/>西</span>
						<span class="c_25">重<br/>庆</span>
					</div>
					<ul>
						<li><i class="y_dot"></i>首批已覆盖区域</li>
						<li><i class="b_dot"></i>业务布局中</li>
					</ul>
				</div>
			</div>
		</div>
		<div class="selection selection-7">
			<div class="cont">
				<div class="cont_">
					<div class="discr-con">
						<div class="discr-con_">
							<h2 class="title"><i class="left_bor"></i>顺风递风云榜<i class="right_bor"></i></h2>
						</div>
					</div>
					<div class="top_con">
						<ul class="top_tit clearfix">
							<li class="li_l">
								<div class="li_">
									<img src="../assets/22.svg" alt=""><span>排名</span>
								</div>
							</li>
							<li>
								<div class="li_">
									<img src="../assets/23.svg" alt=""><span>用户名</span>
								</div>
							</li>
							<li>
								<div class="li_">
									<img src="../assets/24.svg" alt=""><span>接单数</span>
								</div>
							</li>
							<li class="li_r">
								<div class="li_">
									<img src="../assets/25.svg" alt=""><span>收入（元）</span>
								</div>
							</li>
						</ul>
						<div class="bor_bottom"></div>
						<div class="top_scroll">
							<div class="top_data">
								<div class="top_data_con">
									<ul class="clearfix">
										<li><i class="gold">1</i></li>
										<li>CSW182299772</li>
										<li>14325</li>
										<li>234135</li>
									</ul>
									<ul class="clearfix">
										<li><i class="silver">2</i></li>
										<li>CSW182299772</li>
										<li>14325</li>
										<li>234135</li>
									</ul>
									<ul class="clearfix">
										<li><i class="copper">3</i></li>
										<li>CSW182299772</li>
										<li>14325</li>
										<li>234135</li>
									</ul>
									<ul class="clearfix">
										<li><i class="iron">4</i></li>
										<li>CSW182299772</li>
										<li>14325</li>
										<li>234135</li>
									</ul>
									<ul class="clearfix">
										<li><i class="iron">5</i></li>
										<li>CSW182299772</li>
										<li>14325</li>
										<li>234135</li>
									</ul>
									<ul class="clearfix">
										<li><i class="iron">6</i></li>
										<li>CSW182299772</li>
										<li>14325</li>
										<li>234135</li>
									</ul>
									<ul class="clearfix">
										<li><i class="iron">7</i></li>
										<li>CSW182299772</li>
										<li>14325</li>
										<li>234135</li>
									</ul>
									<ul class="clearfix">
										<li><i class="iron">8</i></li>
										<li>CSW182299772</li>
										<li>14325</li>
										<li>234135</li>
									</ul>
								</div>
							</div>
						</div>
						<div class="mask"></div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-8">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>使用流程<i class="right_bor"></i></h2>
					<div class="conts">
						<img src="../assets/38.png" alt="">
						<img src="../assets/39.png" alt="">
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-9">
			<div class="cont">
				<div class="cont_">
					<h2 class="title"><i class="left_bor"></i>服务保障<i class="right_bor"></i></h2>
					<div class="conts">
						<div id="swiper" class="swiper-container">
			          		<div class="swiper-wrapper">
			            		<div class="swiper-slide">
									<div class="list_div">
										<div class="list_div_">
											<div class="img_bg">
												<img src="../assets/71.svg" alt="">
											</div>
											<p>专业的企业管理公司<br/>
											参与平台运营管理</p>
										</div>
									</div>
			            		</div>
			            		<div class="swiper-slide">
									<div class="list_div">
										<div class="list_div_">
											<div class="img_bg">
												<img src="../assets/72.svg" alt="">
											</div>
											<p>签约律师事务所<br/>
											作为平台的法律顾问</p>
										</div>
									</div>
			            		</div>
			            	</div>
			            	<div class="swiper-pagination"></div>
			            </div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-10">
			<div class="cont">
				<div class="cont_">
					<div class="discr">
						<h3>我们的宗旨是</h3>
						<h4>为您提供优质快捷的服务！</h4>
					</div>
					<div class="code">
						<div class="code_">
							<img src="../assets/40.png" alt="">
							<p>长按识别<br/>（小程序二维码）</p>
						</div>
					</div>
				</div>
			</div>
			<app-footer></app-footer>
		</div>
  	</div>
  </div>
</template>

<script>
import '../../static/js/jquery.liMarquee.js'
import '../../static/js/zturn.js'
import '../../static/css/liMarquee.css'

import Header from './Header'
import Footer from './Footer'

export default {
  name: 'Home',
  data () {
    return {
    }
  },
  created() {

  },
  methods: {
    slideDown() {
      let downHeight = document.documentElement.clientHeight || document.body.clientHeight;
      window.scrollTo(0, downHeight);
      this.slideShow = true;
    }
  },
  components: {
    'app-header': Header,
    'app-footer': Footer
  },
  mounted() {
  	$(document).ready(function() {
	  	if($('.fixed-right').hasClass('fixed-right_')) {
			$('.fixed, .fixed-right').css({
				'display': 'none'
			});
		} else {
			$('.fixed').css({
				'display': 'block'
			});
		}
  	});

  	$('.icon-gb').on('click', function() {
		$('.fixed').css({
			'display': 'none'
		});
		$('.fixed-right').css({
			'display': 'block'
		});
		$('.fixed-right').removeClass('fixed-right_');
  	});
  	$('.fixed-right').on('click', function() {
  		$('.fixed').css({
			'display': 'block'
		});
    	$('.fixed-right').addClass('fixed-right_');
  	});

  	$(window).scroll(function() {
	　　 var scrollTop = $(this).scrollTop();
	　　 var scrollHeight = $(document).height();
	　　 var windowHeight = $(this).height();
		if(scrollTop < scrollHeight / 9) {
			$('.fixed').css({
				'display': 'none'
			});
			$('.fixed-right').css({
				'display': 'none'
			});
		} else if(scrollTop + windowHeight == scrollHeight) {
			if($('.fixed-right').hasClass('fixed-right_')) {
				$('.fixed').css({
					'display': 'block'
				});
				$('.fixed-right').css({
					'display': 'none'
				});
			} else {
				$('.fixed').css({
					'display': 'none'
				});
				$('.fixed-right').css({
					'display': 'block'
				});
			};

	　　　　  $('.fixed').css({
				'position': 'absolute',
				'bottom': '20.9vh'
			});
			$('.fixed-right').css({
				'position': 'absolute',
				'bottom': '28vh'
			});
	　　 } else {
			if($('.fixed-right').hasClass('fixed-right_')) {
				$('.fixed').css({
					'display': 'block'
				});
				$('.fixed-right').css({
					'display': 'none'
				});
			} else {
				$('.fixed').css({
					'display': 'none'
				});
				$('.fixed-right').css({
					'display': 'block'
				});
			};

			$('.fixed').css({
				'position': 'fixed',
				'bottom': '0'
			});
			$('.fixed-right').css({
				'position': 'fixed',
				'bottom': '28px'
			})
		}
	});

 	let zTurn = new zturn({
		id: "zturn",
		opacity: 1,
		width: 18.73,
		Awidth: 60,
		scale: 0.9
	});

  	// 第二屏图片轮播
	let timer = setInterval(function(){
	    zTurn.next_();
	},2000);

	$('.poster-list').hover(function() {
		clearTimeout(timer);
	}, function() {
		timer = setInterval(function(){
		    zTurn.next_();
		},5000);
	});

	let zTurns = new zturn({
		id: "zturns",
		opacity: 1,
		width: 30.53,
		Awidth: 120,
		scale: 0.9
	});

  	// 第二屏图片轮播
	let timers = setInterval(function(){
	    zTurns.next_();
	},2000);



	//第七屏风云榜滚动
	$(function(){
		$('.top_scroll').liMarquee({
			direction: 'up'
		});
	});

	let swiper = new Swiper('#swiper', {
      slidesPerView: 1,
      spaceBetween: 30,
      speed: 1000,
      releaseOnEdges: true,
      paginationClickable: true,
      pagination: '.swiper-pagination',
    });

 	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	.video1 {
	    position: relative;
	    z-index: -1;
	    width: 100%;
	    height: 100%;
	    -o-object-fit: fill;
	    object-fit: fill;
	}
	/*selection-1*/
	.selection-1 {
	}
	.selection-1 .con {
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
		height: 100vh;
		background: rgba(0, 0, 0, 0.65);
	}
	.selection-1 h1 {
		height: 5.69vw;
		margin-bottom: 8.7vh;
		color: #FFFFFF;
		text-align: center;
		line-height: 3.39vw;
		font-size: 3.75vw;
		font-family: 'PingFangSC-Regular';
	}
	.selection-1 h1 strong {
		display: inline-block;
		width: 4.69vw;
		height: 4.69vw;
		color: #FBBB02;
		text-align: center;
		line-height: 4.69vw;
		font-size: 6.25vw;
		font-weight: 600;
	}
	.selection-1 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 55%;
		color: #FFFFFF;
		text-align: center;
		line-height: 2.34vw;
		font-size: 1.3vw;
	}
	.selection-1 .cont_ {

	}
	/*selection-2*/
	.selection-2 {
		background: url('../assets/31.jpg') center center  no-repeat;
		background-size: cover;
	}
	.selection-2 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 95%;
	}
	.selection-2 .con_p {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 73.8vw;
		height: 41.67vh;
		margin: 0 auto;
		background: url('../assets/30.png') center center  no-repeat;
		background-size: 100% 100%;
	}
	.selection-2 .title {
		margin-bottom: 11.94vh;
		color: #fff;
	}
	
	.selection-2 p {
		width: 78%;
		margin: 0 auto;
		color: #fff;
		text-align: center;
		line-height: 2.34vw;
		font-size: 1.15vw;
		font-family: 'PingFangSC-Thin';
	} 
	.selection-2 p strong {
		color: #f6b704;
		text-align: center;
		line-height: 2.34vw;
		font-size: 1.15vw;
		font-family: 'PingFangSC-Semibold';
	}

	

	/*selection-3*/
	.selection-3 {
		background: url('../assets/32.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-3 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 90%;
	}
	.selection-3 .cont_ {
		width: 100%;
	}
	.selection-3 .title {
		margin-bottom: 6.07vh;
	}
	.pictureSlider {
	    height: 59.07vh;
	}
	.selection-3 .poster-list {
		width: 100%;
		height: 50vh;
	}
	.poster-item {
		position: relative;
		width: 15.73vw;
		box-shadow: 0 10px 50px 0 rgba(0,0,0,0.50);
		transition: all 0.5s;
		-moz-transition: all 0.5s;
		-webkit-transition: all 0.5s;
		-o-transition: all 0.5s;
		cursor: pointer;
	}
	.poster-item img {
		display: block;
		height: 28.02vw;
		margin: 0 auto;
	}
	.poster-item p {
		position: absolute;
		left: 0;
		bottom: -6vh;
		width: 100%;
		color: #fff;
		text-align: center;
		font-size: 1.15vw;
		font-family: 'PingFangSC-Thin';
	}

	/*selection-4*/
	.selection-4 {
		background: url('../assets/33.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-4 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 95%;
	}
	.selection-4 .conts {
		display: flex;
		justify-content: center;
	}
	.selection-4 .title {
		margin-bottom: 3.61vh;
	}
	.selection-4 .discr {
		margin-bottom: 16.67vh;
		color: #FFFFFF;
		text-align: center;
		line-height: 2.34vw;
		font-size: 1.82vw;
	}

	.selection-4 .list_div {
		width: 15.05vw;
		height: 22.78vh;
		margin: 0 2.19vw;
		text-align: center;
		line-height: 30.78vh;
		font-size: 1.6vw;
		cursor: pointer;
		-webkit-transition: all 0.8s;
      	transition: all 0.8s;
      	font-family: 'PingFangSC-Light';
	}
	.selection-4 .bg_01 {
		background: url('../assets/15.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-4 .bg_02 {
		background: url('../assets/16.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-4 .bg_03 {
		background: url('../assets/16.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-4 .bg_04 {
		background: url('../assets/17.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	
	
	/*selection-5*/
	.selection-5 {
		background: url('../assets/34.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-5 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 95%;
	}
	.selection-5 .conts {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-5 .title {
		margin-bottom: 13.8vh;
	}
	.selection-5 .list_div {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 22.4vw;
		height: 22.4vw;
		margin: 0 8.44vw;
		border-radius: 50%;
		box-shadow: 0 10px 50px 0 rgba(0,0,0,0.50);
		background: #FFFFFF;
		cursor: pointer;
		-webkit-transition: all 0.8s;
      	transition: all 0.8s;
	}
	.selection-5 .list_div img {
		display: block;
		width: 2.14vw;
		margin: 0 auto 1.67vh;
	}
	.selection-5 .list_div h4 {
		margin: 0 auto 2.22vh;
		color: #FBBB02;
		text-align: center;
		line-height: 2.34vw;
		font-size: 1.88vw;
		font-family: 'PingFangSC-Regular';
	}
	
	.selection-5 .list_div p {
		width: 80%;
		margin: 0 auto;
		color: #000000;
		text-align: center;
		font-size: 1.4vw;
		font-family: 'PingFangSC-Thin';
	}

	

	/*selection-6*/
	.selection-6 {
		background: url('../assets/35.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-6 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 95%;
	}
	.selection-6 .discr-con {
		position: absolute;
		left: 10.13vw;
		bottom: 14.81vh;
		width: 23.44vw;
	}
	.selection-6 .title {
		margin-bottom: 4.17vh;
		text-align: left;
	}
	.selection-6 .discr {
		color: #FFFFFF;
		font-size: 0.94vw;
	}
	.selection-6 .map {
		position: relative;
		width: 55.68vw;
	}
	.selection-6 .map img {
		display: block;
		width: 100%;
		margin: 0 auto;
	}
	.selection-6 ul {
		position: absolute;
		right: 11.04vw;
		bottom: 14.81vh;
	}
	.selection-6 li {
		margin-bottom: 2.5vh;
		color: #FFFFFF;
		font-size: 1.04vw;
	}
	.selection-6 li i {
		display: inline-block;
		width: 0.83vw;
		height: 0.83vw;
		margin-right: 0.63vw;
		border-radius: 50%;
	}
	.selection-6 .y_dot {
		background: #FFB800;
	}
	.selection-6 .b_dot {
		background: #65C7F1;
	}
	.selection-6 .g_dot {
		background: #999999;
	}
	.selection-6 .map span {
		position: absolute;
		color: #000000;
		line-height: 1.1vw;
		font-size: 0.9vw;
		font-family: 'PingFangSC-Regular';
	}
	.map .c_01 {
		right: 24.5%;
    	bottom: 57.5%;
    	-webkit-animation: float_01 2.6s infinite;
    	animation: float_01 2.6s infinite;
	}
	.map .c_02 {
		right: 28.5%;
    	bottom: 37.5%;
    	-webkit-animation: float_02 1.6s infinite;
    	animation: float_02 1.6s infinite;
	}
	.map .c_03 {
		right: 16.2%;
    	bottom: 37.5%;
    	-webkit-animation: float_02 2s infinite;
    	animation: float_02 2s infinite;
	}
	.map .c_04 {
		right: 13%;
    	bottom: 32.5%;
    	-webkit-animation: float_01 1.6s infinite;
    	animation: float_01 1.6s infinite;
	}
	.map .c_05 {
		right: 15%;
    	bottom: 26.5%;
    	-webkit-animation: float_02 3s infinite;
    	animation: float_02 3s infinite;
	}
	.map .c_06 {
		right: 30.5%;
    	bottom: 19.5%;
    	-webkit-animation: float_01 3s infinite;
    	animation: float_01 3s infinite;
	}
	.map .c_07 {
		right: 23.5%;
    	bottom: 19%;
    	-webkit-animation: float_02 2.3s infinite;
    	animation: float_02 2.3s infinite;
	}
	.map .c_08 {
		right: 18.5%;
    	bottom: 15.5%;
    	-webkit-animation: float_02 1.3s infinite;
    	animation: float_02 1.3s infinite;
	}
	.map .c_09 {
		right: 26.5%;
    	bottom: 8.5%;
    	-webkit-animation: float_01 2.5s infinite;
    	animation: float_01 2.5s infinite;
	}
	.map .c_10 {
		right: 36.5%;
    	bottom: 7.5%;
    	-webkit-animation: float_01 1.5s infinite;
    	animation: float_01 1.5s infinite;
	}
	.map .c_11 {
		right: 30.5%;
    	bottom: 29.5%;
    	-webkit-animation: float_01 1.5s infinite;
    	animation: float_01 1.5s infinite;
	}
	.map .c_12 {
		right: 20.5%;
    	bottom: 46.5%;
    	-webkit-animation: float_02 3.5s infinite;
    	animation: float_02 3.5s infinite;
	}
	.map .c_13 {
		right: 36.5%;
    	bottom: 39.5%;
    	-webkit-animation: float_01 1.8s infinite;
    	animation: float_01 1.8s infinite;
	}
	.map .c_14 {
		right: 46.5%;
    	bottom: 42.5%;
    	-webkit-animation: float_01 1s infinite;
    	animation: float_01 1s infinite;
	}
	.map .c_15 {
		right: 48.5%;
    	bottom: 26.5%;
    	-webkit-animation: float_02 2.8s infinite;
    	animation: float_02 2.8s infinite;
	}
	.map .c_16 {
		right: 40.5%;
    	bottom: 16.5%;
    	-webkit-animation: float_02 2s infinite;
    	animation: float_02 2s infinite;
	}
	.map .c_17 {
		right: 51.5%;
    	bottom: 9.5%;
    	-webkit-animation: float_01 1.5s infinite;
    	animation: float_01 1.5s infinite;
	}
	.map .c_19 {
		right: 38.5%;
    	bottom: 53.5%;
    	-webkit-animation: float_01 2.1s infinite;
    	animation: float_01 2.1s infinite;
	}
	.map .c_20 {
		right: 8.5%;
    	bottom: 78.5%;
    	-webkit-animation: float_02 1.5s infinite;
    	animation: float_02 1.5s infinite;
	}
	.map .c_21 {
		right: 14%;
    	bottom: 61.5%;
    	-webkit-animation: float_01 2.5s infinite;
    	animation: float_01 2.5s infinite;
	}
	.map .c_22 {
		right: 23%;
    	bottom: 54.5%;
    	-webkit-animation: float_01 2.5s infinite;
    	animation: float_01 2.5s infinite;
	}
	.map .c_23 {
		right: 27%;
    	bottom: 52.5%;
    	-webkit-animation: float_01 2.5s infinite;
    	animation: float_01 2.5s infinite;
	}
	.map .c_24 {
		right: 32%;
    	bottom: 49.5%;
    	-webkit-animation: float_01 2.5s infinite;
    	animation: float_01 2.5s infinite;
	}
	.map .c_25 {
		right: 39%;
    	bottom: 26.5%;
    	-webkit-animation: float_01 2.5s infinite;
    	animation: float_01 2.5s infinite;
	}

	/*selection-7*/
	.selection-7 {
		background: url('../assets/36.jpg') center center no-repeat;
		background-size: cover; 
	}
	.selection-7 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 95%;
	}
	.selection-7 .discr-con {
		position: relative;
		width: 26.15vw;
		height: 39.54vh;
		margin-right: 0.85vw;
		background: url('../assets/21.svg') center center no-repeat;
		background-size: 100% 100%; 
		z-index: 2;
	}
	.selection-7 .discr-con_ {
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
	}
	.selection-7 .discr-con .title {
		height: 39.54vh;
		line-height: 54.54vh;
	}
	.selection-7 .top_scroll {
		overflow: hidden;
		height: 44vh;
	}
	.selection-7 .top_con {
		width: 52.45vw;
	}
	.selection-7 .top_tit {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100%;
		color: #FFFFFF;
		height: 4vw;
		font-size: 1.3vw;
		text-align: center;
	}
	.bor_bottom {
		width: 45.45vw;
		height: 1px;
		margin: 0 0 2.97vh 4vw;
		background: rgba(255,255,255,0.46);
	}
	.selection-7 .top_tit li {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 25%;
		height: 2.33vw;
		text-align: center;
		font-family: 'PingFangSC-Regular';
	}
	.selection-7 .top_tit img {
		width: 1.77vw;
		height: 1.77vw;
		margin-right: 0.52vw;
	}

	.selection-7 .top_data {
		text-align: center;
	}
	.selection-7 .top_data ul {
		display: flex;
		justify-content: center;
		align-items: center;
		margin-bottom: 2.08vh;
	}
	.selection-7 .top_data li {
		width: 25%;
		color: #FFFFFF;
		font-size: 1.3vw;
	}
	.selection-7 .top_data i {
		display: block;
		width: 2.29vw;
		height: 2.76vw;
		margin: 0 auto;
		color: #000;
		line-height: 2.5vw;
		font-size: 1.15vw;
	}
	.selection-7 .gold {
		background: url('../assets/26.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-7 .silver {
		background: url('../assets/27.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-7 .copper {
		background: url('../assets/28.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-7 .iron {
		background: url('../assets/29.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-7 .mask {
		position: absolute;
		left: 0;
		bottom: 0;
		width: 100%;
		height: 53vh;
		background: url('../assets/29.png') top center no-repeat;
		background-size: 100% 100%;
		z-index: 1;
	}
	
	/*selection-8*/
	.selection-8 {
		background: url('../assets/37.jpg') top center no-repeat;
		background-size: cover;
	}
	.selection-8 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 95%;
	}
	.selection-8 .title {
		margin-bottom: 6.94vh;
	}
	.selection-8 .conts {
	
	}
	.selection-8 .conts img {
		width: 17.76vw;
		margin: 0 6.98vw;
	}

	/*selection-9*/
	.selection-9 {
		background: url('../assets/73.jpg') top center no-repeat;
		background-size: cover;
	}
	.selection-9 .conts {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-9 .title {
		margin: 11.02vh auto 5.74vh;
	}
	.selection-9 .list_div {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 50vw;
		height: 82.07vh;
		background: #F7F7F7;
		cursor: pointer;
		-webkit-transition: all 0.8s;
	    transition: all 0.8s;
	}
	.selection-9 .list_div_ {
		width: 100%;
	}
	.selection-9 .img_bg {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 7.08vw;
		height: 7.08vw;
		margin: 0 auto 6.57vh;
		border-radius: 50%;
		background: #000000;
		-webkit-transition: all 0.8s;
	    transition: all 0.8s;
	}
	.selection-9 img {
		width: 4.06vw;
	}
	.selection-9 .list_div p {
		color: #000000;
		text-align: center;
		font-family: 'PingFangSC-Light';
		font-size: 1.46vw;
		-webkit-transition: all 0.8s;
	    transition: all 0.8s;
	}
	
	
	/*selection-10*/
	.selection-10 { 
		color: #FFFFFF;
		font-size: 1.3vw;
	}
	.selection-10 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 79.07vh;
		background: url('../assets/61.jpg') top center no-repeat;
		background-size: cover;
	}
	.selection-10 .cont_ {
		display: inline-flex;
		margin-top: -15vh;
	}
	.selection-10 .discr {
		margin-right: 30.36vw;
	}
	.selection-10 .discr h3 {
		color: #FFFFFF;
		line-height: 4.53vw;
		font-size: 2.86vw;
		font-weight: 600;
	}
	.selection-10 .discr h4 {
		color: #FFFFFF;
		line-height: 4.53vw;
		font-size: 2.86vw;
	}
	.selection-10 .code {
		display: flex;
		justify-content: center;
		align-items: center;
		text-align: center;
	}
	.selection-10 .code img {
		width: 12.34vw;
		height: 12.34vw;
		margin-bottom: 2.69vh;
	}

	@media screen and (max-width: 750px) {
	    .mob {
	      	display: block;
	    }
		
		/*selection-1*/
		.selection-1 h1 {
			height: 26.2vw;
			margin-bottom: 6.3vh;
			line-height: 12vw;
			font-size: 6.67vw;
		}
		.selection-1 h1 strong {
			width: 12vw;
			height: 12vw;
			line-height: 12vw;
			font-size: 13.33vw;
			font-family: 'PingFangSC-Semibold';
		}
		.selection-1 p {
			color: #FFFFFF;
			text-align: center;
			line-height: 6.67vw;
			font-size: 4.27vw;
		}
		.selection-1 .cont {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 50%;
			color: #FFFFFF;
			text-align: center;
			line-height: 2.34vw;
			font-size: 1.3vw;
		}

		/*selection-2*/
		.selection-2 {
			background: url('../assets/03.jpg') center center  no-repeat;
			background-size: cover;
		}
		.selection-2 .cont {
			height: 100%;
		}
		.selection-2 .con_p {
			width: 87.4vw;
    		height: 75.52vh;
			margin: 0 auto;
			background: url('../assets/02.svg') center center  no-repeat;
			background-size: 100% 100%;
		}
		.selection-2 .title {
			margin-bottom: 4.8vh;
			color: #fff;
		}
		
		.selection-2 p {
			text-align: left;
			width: 74%;
			color: #FFFFFF;
			line-height: 6.67vw;
			font-size: 3.73vw;
		} 
		.selection-2 p strong {
			color: #FFB800;
			line-height: 6.67vw;
			font-size: 3.73vw;
			font-family: 'PingFangSC-Semibold';
		}

		/*selection-3*/
		.selection-3 {
			background: url('../assets/04.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-3 .cont {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100%;
		}
		.selection-3 .cont_ {
			width: 100%;
		}
		.selection-3 .title {
			margin-bottom: 12.74vh;
		}
		.pictureSlider {
		    height: 59.07vh;
		}
		.selection-3 .poster-list {
			position: absolute;
			left: -55%;
			width: 200%;
			height: 50vh;
		}
		.poster-item {
			position: relative;
			width: 40.53vw;
		}
		.poster-item img {
			display: block;
			width: 100%;
			height: 40.93vh;
			margin: 0 auto;
		}
		.poster-item p {
			position: absolute;
			left: 0;
			bottom: -6vh;
			font-size: 3.73vw;
			font-family: 'PingFangSC-Light';
		}
		

		/*selection-4*/
		.selection-4 {
			background: url('../assets/05.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-4 .cont {
			height: 100%;
		}
		.selection-4 .conts {
			display: flex;
			justify-content: center;
		}
		.selection-4 .title {
			margin-bottom: 3.61vh;
		}
		.selection-4 .discr {
			margin-bottom: 10.67vh;
			line-height: 6.67vw;
			font-size: 3.73vw;
		}
		.selection-4 .list {
			display: flex;
			justify-content: center;
			align-items: center;
			margin-bottom: 7.5vh;
		}
		.selection-4 .list_div {
			width: 35.47vw;
			height: 16.49vh;
			margin: 0 2.19vw;
			color: #000000;
			line-height: 38.33vw;
			font-size: 3.73vw;
			font-family: 'PingFangSC-Light';
		}
		

		/*selection-5*/
		.selection-5 {
			height: 114.69vh;
			background: url('../assets/06.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-5 .cont {
			height: 100%;
		}
		.selection-5 .title {
			margin-bottom: 9.6vh;
		}
		.selection-5 .list_div {
			width: 56.27vw;
			height: 56.27vw;
			margin: 0 8.44vw;
			border-radius: 50%;
		}
		.selection-5 .list_div img {
			display: block;
			width: 6.13vw;
			margin: 0 auto 1.95vh;
		}
		.selection-5 .list_div h4 {
			margin: 0 auto 1.2vh;
			line-height: 5.33vw;
			font-size: 4.8vw;
		}
		
		.selection-5 .list_div p {
			width: 80%;
			margin: 0 auto;
			font-size: 3.73vw;
		}

		/*selection-6*/
		.selection-6 {
			background: url('../assets/07.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-6 .cont {
			height: 100%;
		}
		.selection-6 .cont_ {
			width: 100%;
		}
		.selection-6 .discr-con {
			position: static;
			width: 100vw;
			margin: 0 auto;
		}
		.selection-6 .title {
			margin-bottom: 4.17vh;
			text-align: center;
		}
		.selection-6 .discr {
			width: 86%;
			margin: 0 auto;
			line-height: 5.87vw;
			font-size: 3.73vw;
		}
		.selection-6 .map {
			width: 100%;
		}
		.selection-6 .map img {
			height: 68.47vh;
		}
		.selection-6 ul {
			position: absolute;
			right: 63.04vw;
    		bottom: 58.81vh;
		}
		.selection-6 li {
			margin-bottom: 0.3vh;
			font-size: 3.73vw;
		}
		.selection-6 li i {
			width: 3.2vw;
			height: 3.2vw;
			margin-right: 0.63vw;
		}
		.selection-6 .map span {
			line-height: 3.73vw;
			font-size: 3.2vw;
		}
		.map .c_01 {
			right: 35.5%;
	    	bottom: 57.5%;
		}
		.map .c_02 {
			right: 38.5%;
	    	bottom: 37.5%;
		}
		.map .c_03 {
			right: 23.2%;
	    	bottom: 38.5%;
		}
		.map .c_04 {
			right: 19%;
	    	bottom: 34.5%;
		}
		.map .c_05 {
			right: 21%;
	    	bottom: 28.5%;
		}
		.map .c_06 {
			right: 42.5%;
	    	bottom: 21.5%;
		}
		.map .c_07 {
			right: 33.5%;
	    	bottom: 21%;
		}
		.map .c_08 {
			right: 25.5%;
	    	bottom: 17.5%;
		}
		.map .c_09 {
			right: 35.5%;
	    	bottom: 10.5%;
		}
		.map .c_10 {
			right: 50.5%;
	    	bottom: 9.5%;
		}
		.map .c_11 {
			right: 41.5%;
	    	bottom: 30.5%;
		}
		.map .c_12 {
			right: 29.5%;
	    	bottom: 46.5%;
		}
		.map .c_13 {
			right: 51.5%;
	    	bottom: 39.5%;
		}
		.map .c_14 {
			right: 64.5%;
	    	bottom: 42.5%;
		}
		.map .c_15 {
			right: 68.5%;
	    	bottom: 28.5%;
		}
		.map .c_16 {
			right: 57.5%;
	    	bottom: 18.5%;
		}
		.map .c_17 {
			right: 71.5%;
	    	bottom: 11.5%;
		}
		.map .c_19 {
			right: 54.5%;
	    	bottom: 53.5%;
		}
		.map .c_20 {
			right: 12.5%;
	    	bottom: 78.5%;
		}
		.map .c_21 {
			right: 20%;
	    	bottom: 61.5%;
		}
		.map .c_22 {
			right: 32%;
	    	bottom: 54.5%;
		}
		.map .c_23 {
			right: 37%;
	    	bottom: 52.5%;
		}
		.map .c_24 {
			right: 44%;
	    	bottom: 49.5%;
		}
		.map .c_25 {
			right: 54%;
	    	bottom: 26.5%;
		}

		/*selection-7*/
		.selection-7 {
			background: url('../assets/09.jpg') center center no-repeat;
			background-size: cover; 
		}
		.selection-7 .cont {
			height: 100%;
		}
		.selection-7 .cont_ {
			width: 100%;
		}
		.selection-7 .discr-con {
			width: 75.2vw;
			height: 35.83vh;
			margin: 0 auto 2.65vh;
			background: url('../assets/21.svg') center center no-repeat;
			background-size: 100% 100%; 
		}
		.selection-7 .discr-con_ {
			position: static;

		}
		.selection-7 .discr-con .title {
			height: 39.54vh;
			line-height: 54.54vh;
		}
		.selection-7 .top_scroll {
			overflow: hidden;
			height: 30vh;
		}
		.selection-7 .top_con {
			width: 90vw;
			margin: 0 auto;
		}
		.selection-7 .top_tit {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 100%;
			color: #FFFFFF;
			height: 18vw;
			font-size: 1.3vw;
			text-align: center;
		}
		.bor_bottom {
			width: 86vw;
			height: 1px;
			margin: 0 0 2.97vh 4vw;
			background: rgba(255,255,255,0.46);
		}
		.selection-7 .top_tit li {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 25%;
			height: 19.2vw;
			text-align: center;
			font-family: 'PingFangSC-Regular';
		}
		.selection-7 .top_tit img {
			display: block;
			width: 6.67vw;
			height: 6.67vw;
			margin: 0 auto;
		}
		.selection-7 .top_tit span {
			display: block;
			margin: 0 auto;
			text-align: center;
			font-size: 3.73vw;
			font-family: 'PingFangSC-Light';
		}

		

		.selection-7 .top_data {
			text-align: center;
		}
		.selection-7 .top_data ul {
			display: flex;
			justify-content: center;
			align-items: center;
			margin-bottom: 2.08vh;
		}
		.selection-7 .top_data li {
			width: 25%;
			font-size: 3.2vw;
		}
		.selection-7 .top_data i {
			width: 6.67vw;
			height: 6.67vw;
			line-height: 6.67vw;
			font-size: 3.2vw;
		}
		.selection-7 .mask {
			position: absolute;
			left: 0;
			bottom: 0;
			width: 100%;
			height: 20vh;
			background: url('../assets/29.png') top center no-repeat;
			background-size: 100% 100%;
			z-index: 1;
		}

		/*selection-8*/
		.selection-8 {
			background: url('../assets/010.jpg') top center no-repeat;
			background-size: cover;
		}
		.selection-8 .cont {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100%;
		}
		.selection-8 .title {
			margin-bottom: 11.54vh;
		}
		.selection-8 .conts img {
			width: 42.93vw;
			margin: 0 1.06vw;
		}

		/*selection-9*/
		.selection-9 {
			background: url('../assets/73.jpg') top center no-repeat;
			background-size: cover;
		}
		.selection-9 .conts {
		}
		.selection-9 .title {
			margin: 11.02vh auto 5.74vh;
		}

		.selection-9 .list_div {
			width: 73.07vw;
			height: 50.97vh;
			margin: 0 auto;
			border-radius: 5px;
			background: rgba(255,255,255,0.90);
		}
		.selection-9 .list_div_ {
			width: 100%;
		}
		.selection-9 .img_bg {
			width: 23.73vw;
			height: 23.73vw;
			margin: 0 auto 6.57vh;
		}
		.selection-9 img {
			width: 12.8vw;
		}
		.selection-9 .list_div p {
			font-size: 5.33vw;
		}
		#swiper {
			height: 58.32vh;
		}
		
		/*selection-10*/
		.selection-10 .cont {
			height: 73.76vh;
			background: url('../assets/014.jpg') top center no-repeat;
			background-size: cover;
		}
		.selection-10 .cont_ {
			display: block;
			margin-top: 0;
		}
		.selection-10 .discr {
			width: 100%;
			margin-right: 30.36vw;
			text-align: center;
		}
		.selection-10 .discr h3 {
			line-height: 12vw;
			font-size: 6.67vw;
		}
		.selection-10 .discr h4 {
			margin-bottom: 10.19vh;
			line-height: 12vw;
			font-size: 6.67vw;
		}
		.selection-10 .code img {
			width: 33.33vw;
			height: 33.33vw;
			margin-bottom: 2.69vh;
		}
		.selection-10 .code p {
			font-size: 3.2vw;
		}

	    
	}
	@media screen and (min-width: 751px) {
		.selection-4 .list_div:hover {
			-webkit-transform: scale(1.1);
	      	transform: scale(1.1);
	      	-webkit-transition: all 0.8s;
	      	transition: all 0.8s;
		}

		.selection-5 .list_div:hover {
			-webkit-transform: scale(1.1);
	      	transform: scale(1.1);
	      	-webkit-transition: all 0.8s;
	      	transition: all 0.8s;
		}

		.selection-9 .list_div:hover {
			background: rgba(0,0,0,0.30);
			-webkit-transition: all 0.8s;
	      	transition: all 0.8s;
		}
		.selection-9 .list_div:hover .img_bg {
			background: #FFFFFF;
			-webkit-transition: all 0.8s;
	      	transition: all 0.8s;
		}
		.selection-9 .list_div:hover p {
			color: #fff;
			-webkit-transition: all 0.8s;
	      	transition: all 0.8s;
		}
	}
</style>
