<template>
	<view>
		<view class="max">
			<view class="top">
				<label>SVIP专享</label>
				<image class="xing" src="../../static/星.png"></image>
				<span>我的SVIP</span>
				<image class="svip"  src="../../static/SVIP.png"></image>
			</view>
			<view class="bjtp">
				<!-- <image class="bj" src="../../static/背景.jpg"></image> -->
				<view class="sfzt">
					<ul class="ds">
						<li>·去除广告</li>
						<li>·专属模板</li>
						<li>·精美素材</li>
					</ul>
				</view>
				<view class="top-top">
					<view class="top-left">
						<label class="fsf">MEMBERSHIP</label>
						<view>
							<label class="sad">成为SVIP会员</label>
						</view>
					</view>
					<view class="top-right">
						<image src="../../static/宇航员.png"></image>
						<button>加入会员享专属权益></button>
					</view>
				</view>
				<view class="center">
					<view class="center-left">
						<image src="../../static/开始作图.png"></image>
						<label>开始作图</label>
					</view>
					<view class="center-right">
						<image src="../../static/收藏夹.png"></image>
						<label>收藏夹</label>
					</view>
				</view>
				<view class="moban">
					<view class="mgfl">
						<label>模板分类</label>
						</view>
						<view class="tuzb">
							<view class="sfdfs">
							<view class="hudon">
							<view class="zuo">
								<view class="zuok">
									<image src="../../static/q1.png"></image>
								</view>
								<image class="txzb" src="../../static/头像装扮.png"></image>
								<label>头像装扮</label>
							</view>
							
							<view class="zuoo">
								<view class="zuok">
									<image src="../../static/q2.png"></image>
								</view>
								<image class="txzb" src="../../static/壁纸背景.png"></image>
								<label>壁纸背景</label>
							</view>
							
							<view class="zuooo">
								<view class="zuok">
									<image src="../../static/q3.png"></image>
								</view>
								<image class="txzb" src="../../static/配图心情.png"></image>
								<label>配图心情</label>
							</view>
							
							<view class="zuooo">
								<view class="zuok">
									<image src="../../static/q1.png"></image>
								</view>
								<image class="txzb" src="../../static/花.png"></image>
								<label>头像装扮</label>
							</view>
							</view>
							</view>
						</view>
						<view class="bottomzt">
							<label>[扩列闺蜜卡]</label>
							<!-- <image src="../../static/you.png"></image> -->
							<uni-icons class="ss" type="right" size="35" color="#b7b7b7"></uni-icons>
							<span>全部</span>
						</view>
						<view class="cnm">
						<view class="bottom-zh">
							<view class="bottom1">
								<image src="../../static/q4.png"></image>
							</view>
							<view class="bottom1">
								<image src="../../static/q5.png"></image>
							</view>
							<view class="bottom1">
								<image src="../../static/q4.png"></image>
							</view>
						</view>
						</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style>
	.max {
		width: 100%;
		height: 1590px;
		background-color: #F8F8F8;
	}
	.top{
			width: 750px;
			height: 80px;
			background-color: #FFFFFF;
		}
		.top label{
			font-size: 38px;
			font-family: PingFang SC;
			font-weight: bold;
			color: #D09FF1;
			line-height: 36px;
			line-height: 80px;
			margin-left: 25px;
		}
		.xing{
			width: 43px;
			height: 32px;
			margin-left: 10px;
		}
		.svip{
			width: 39px;
			height: 39px;
			float: right;
			margin-top: 20px;
			margin-right: 11px;
		}
		.top span{
			font-size: 28px;
			font-family: PingFang SC;
			font-weight: bold;
			color: #2B2B2B;
			float: right;
			line-height: 80px;
			margin-right: 25px;
		}
		.bjtp{
			background-image:url(../../static/背景.jpg) ;
			width: 750px;
			height: 1029px;
		}
		.sfzt{
			width: 750px;
			height: 50px;
			/* background-color: #18BC37; */
		}
		.ds{
			float: right;
			line-height: 50px;
           /* display: inline;			 */
		}
		.ds li{
			 display: inline;
			 margin: 0px 5px;
			 font-size: 28px;
			 font-family: PingFang SC;
			 font-weight: bold;
			 color: #667FA9;
			 line-height: 36px;
			 margin-right: 25px;
		}
		.top-top{
			width: 750px;
			height: 190px;
			/* background-color: #007AFF; */
		}
		.top-left{
			width: 50%;
			height: 190px;
			/* background-color: #667FA9; */
			float: left;
		}
		.top-right{
			width: 50%;
			height: 190px;
			/* background-color: #F38769; */
			float: right;
			text-align: center;
		}
		.fsf{
			position: relative;
			font-size: 32px;
			font-family: PingFang SC;
			font-weight: 800;
			color: #2B2B2B;
			top: 30px;
			left: 26px;
		}
		.sad{
			position: relative;
			font-size: 49px;
			font-family: PingFang SC;
			font-weight: 500;
			color: #2B2B2B;
			/* line-height: 36px; */
			top: 30px;
			left: 26px;
		}
		.top-right image{
			width: 137px;
			height: 111px;
			margin-left: 130px;
			margin-top: 5px;
		}
		.top-right button{
			width: 242px;
			height: 56px;
			background: #2B2B2B;
			border-radius: 28px;
			font-size: 20px;
			font-family: PingFang SC;
			font-weight: 800;
			color: #FFFFFF;
			line-height: 56px;
			margin-right: 25px;
			margin-top: -30px;
		}
		.center{
			width: 750px;
			height: 290px;
			/* background-color: #007AFF; */
		}
		.center-left{
			width: 410px;
			height: 240px;
			background: #FFFFFF;
			border-radius: 20px;
			margin-left: 22px;
			float: left;
			text-align: center;
			
		}
		.center-left image{
			width: 80px;
			height: 77px;
			margin-top: 50px;
		}
		.center-left label{
			display: block;
			font-size: 28px;
			font-family: PingFang SC;
			font-weight: 500;
			color: #B79FC7;
			/* line-height: 36px; */
			margin-top: 40px;
		}
		.center-right{
			width: 268px;
			height: 240px;
			background: #FFFFFF;
			border-radius: 20px;
			float: right;
			margin-right: 22px;
			text-align: center;
		}
		.center-right image{
			width: 77px;
			height: 77px;
			margin-top: 50px;
		}
		.center-right label{
			display: block;
			font-size: 28px;
			font-family: PingFang SC;
			font-weight: 500;
			color: #FFD249;
			margin-top: 40px;
		}
		.moban{
			width: 750px;
			/* background-color: #18BC37; */
			height: 780px;
			background: #FFFFFF;
			border-radius: 30px 30px 0px 0px;
		}
		.mgfl{
			border-radius: 30px 30px 0px 0px;
			width: 750px;
			height: 90px;
			/* background-color: #007AFF; */
			line-height: 90px;
		}
		.mgfl label{
			font-size: 34px;
			font-family: PingFang SC;
			font-weight: 800;
			color: #2B2B2B;
			margin-left: 25px;
		}
		.tuzb{
			width: 750px;
			height: 300px;
			/* background-color: #DD524D; */
			margin-top: 5px;
			/* overflow: ; */
		}
		.zuo{
			width: 198px;
			height: 250px;
			background: #FFFFFF;
			margin-left: 25px;
			border-radius: 20px 20px 0 0;
			/* float: left; */
		}
		.zuoo{
			width: 198px;
			height: 250px;
			background: #FFFFFF;
			/* margin-left: 25px; */
			border-radius: 20px 20px 0 0;
			/* float: right; */
			/* margin-right: 110px; */
			/* margin-right: 80px; */
			margin-left: 17px;
		}
		.zuooo{
			width: 198px;
			height: 250px;
			background: #FFFFFF;
			/* margin-left: 25px; */
			border-radius: 20px 20px 0 0;
			/* float: right; */
			/* margin-right: 25px; */
			margin-left: 17px;
		}
		.zuok{
			width: 198px;
			height: 198px;
			background: #FAF8FD;
			text-align: center;
			border-radius: 20px;
		}
		.zuok image{
			width: 150px;
			height: 150px;
			margin-top: 21px;
		}
		.txzb{
			width: 33px;
			height: 28px;
			margin-left: 25px;
			margin-top: 10px;
		}
		.zuo label{
			font-size: 25px;
			font-family: PingFang SC;
			font-weight: 500;
			color: #707070;
			margin-left: 8px;
		}
		.zuoo label{
			position: relative;
			font-size: 25px;
			font-family: PingFang SC;
			font-weight: 500;
			color: #707070;
			margin-left: 8px;
			top: -5px;
		}
		.zuooo label{
			position: relative;
			font-size: 25px;
			font-family: PingFang SC;
			font-weight: 500;
			color: #707070;
			margin-left: 8px;
			top: -5px;
		}
		.hudon{
			display: flex;
			width: 895px;
			height: 250px;
			/* background-color: #18BC37; */
		}
		.sfdfs{
			overflow-x: scroll;
		}
		.sfdfs::-webkit-scrollbar{
			display: none;
		}
		.bottomzt{
			width: 750px;
			height: 80px;
			/* background-color: #18BC37; */
			line-height: 80px;
		}
		.bottomzt label{
			font-size: 34px;
			font-family: PingFang SC;
			font-weight: 800;
			color: #2B2B2B;
			margin-left: 28px;
		}
		.bottomzt span{
			font-size: 26px;
			font-family: PingFang SC;
			font-weight: 500;
			color: #909090;
			float: right;
			margin-right: 10px;
		}
		.ss{
			width: 14px;
			height: 25px;
			/* background: #B4B4B4; */
			float: right;
			/* margin-top: 27px; */
			margin-right: 35px;
		}
		.cnm{
		   overflow-x: scroll;
		}
		.cnm::-webkit-scrollbar{
			display: none;
		}
		.bottom-zh{
			display: flex;
			width: 850px;
			height: 350px;
			/* background-color: #2979FF; */
		
		}
		.bottom1{
			border-radius: 20px;
			width: 250px;
			height: 350px;
			/* background-color: #F38769; */
			margin-left: 22px;
		}
		.bottom1 image{
			width: 250px;
			height: 350px;
			border-radius: 20px;
		}
</style>
