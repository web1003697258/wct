<template>
	<view>
		<view class="max">
			<view class="top">
				<image src="../../static/shezji.png"></image>
			</view>
			<view class="tx">
				<image src="../../static/a7.jpg"></image>
				<label>中国第一深情</label>
				<uni-icons class="ss" type="right" size="35" color="#b7b7b7"></uni-icons>
			</view>
			<view class="top-gg">
				<image src="../../static/喇叭.png"></image>
				<label>关于内容审核和图片不展示</label>
				<uni-icons class="sss" type="right" size="35" color="#b7b7b7"></uni-icons>
				<span>公告详情</span>
			</view>
			<view class="datop-zj">
			<view class="top-zj">
				<table class="bg">
					<tr class="sdfd">
						<td>18</td>
						<td>20</td>
						<td class="tppp">
							<image src="../../static/shoucang1.png"></image>
						</td>
					</tr>
					<tr class="sfdsg">
						<td>我的专辑</td>
						<td>文章/视频</td>
						<td>我的收藏</td>
					</tr>
				</table>
			</view>
			</view>
			<view class="jrdt1">
				<view class="jrdt">
					<image src="../../static/xunzhang.png"></image>
					<label>加入堆糖VIP</label>
					<span>VIP免广告，首月只要1.99元起</span>
					<button>立即开通</button>
				</view>
			</view>
			<view class="center-xx1">
				<view class="center-xx2">
					<label>我的消息</label>
					<uni-icons class="dsd" type="right" size="35" color="#b7b7b7"></uni-icons>
					<image src="../../static/xiaoxi.png"></image>
					<span>今天还未收到赞/收藏/粉丝关</span>
				</view>
			</view>
			<view class="bottom1">
				<view class="bottom2">
					<table class="bggg">
						<tr class="dy">
							<td>图文工具</td>
						</tr>
						<tr class="de">
							<td>
								<image src="../../static/文案库.png"></image>
							</td>
							<td>
								<image src="../../static/花字体.png"></image>
							</td>
							<td>
								<image src="../../static/朋友圈动图.png"></image>
							</td>
							<td>
								<image src="../../static/情头测试.png"></image>
							</td>
						</tr>
						<tr class="ds">
							<td>文案库</td>
							<td>花字体</td>
							<td>朋友圈动图</td>
							<td>情头测试</td>
						</tr>
					</table>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style>
	.max{
		width: 100%;
		height: 1400px;
		background-color: #F8F8F8;
	}
	.top{
		width: 750px;
		height: 100px;
		background-color: #FFFFFF;
	}
	.top image{
		width: 43px;
		height: 40px;
		float: right;
		margin-top: 26px;
		margin-right: 35px;
	}
	.tx{
		width: 750px;
		height: 160px;
		background-color:#FFFFFF;
		border-top: 2px solid #f8f8f8;
		border-bottom: 1px solid #f8f8f8;
	}
	.tx image{
		width: 122px;
		height: 122px;
		border-radius: 50%;
		margin-left: 35px;
		margin-top: 18px;
	}
	.tx label{
		position: relative;
		font-size: 34px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #2B2B2B;
		top: -48px;
		left: 16px;
	}
	.ss{
		float: right;
		margin-right: 50px;
		margin-top: 58px;
	}
	.top-gg{
		width: 750px;
		height: 70px;
		background: #FFFFFF;
		margin-top: 20px;
	}
	.top-gg image{
		width: 32px;
		height: 31px;
		margin-top: 19px;
		margin-left: 58px;
	}
	.top-gg label{
		position: relative;
		font-size: 28px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #4B4B4B;
		line-height: 36px;
		margin-left: 20px;
		top: -4px;
	}
	.top-gg span{
		font-size: 25px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #707070;
		float: right;
		margin-top: 19px;
		margin-right: 10px;
	}
	.sss{
		float: right;
		margin-right: 50px;
		margin-top: 19px;
		/* margin-top: 58px; */
	}
	.datop-zj{
		/* position: fixed; */
		width: 750px;
		height: 138px;
		/* background: #D09FF1; */
		border-radius: 26px;
		margin-top: 20px;
		text-align: center;
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.top-zj{
		width: 682px;
		height: 138px;
		background: #FFFFFF;
		border-radius: 26px;
		/* margin-top: 20px; */
	}
	.bg{
		border-radius: 26px;
		text-align: center;
		width: 682px;
		height: 138px;
	}
	/* .sdfd{
		background-color: #18BC37;
	} */
	.sdfd td{
		font-size: 34px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #2B2B2B;
		padding: 17px 0 0 0;
	}
	.sfdsg td{
		font-size: 28px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #909090;
		padding: 0 0 17px 0;
	}
	.tppp image{
		width: 40px;
		height: 38px;
	}
	.jrdt1{
		display: flex;
		justify-content: center;
		align-items: center;
		width: 750px;
		height: 198px;
		/* background-color: #F0AD4E; */
		margin-top: 20px;
		
	}
	.jrdt{
		width: 682px;
		height: 198px;
		 background-size:100% 100%;
		background-repeat: no-repeat;
		background-image:url(../../static/底图.png) ;
	}
	.jrdt image{
		width: 57px;
		height: 57px;
		margin-top: 40px;
		margin-left: 37px;
	}
	.jrdt label{
		position: relative;
		font-size: 48px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #FFFFFF;
		line-height: 36px;
		top: -15px;
		left: 16px;
	}
	.jrdt span{
		display: block;
		font-size: 26px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #FFFFFF;
		line-height: 36px;
		margin-left: 37px;
		margin-top: 13px;
	}
	.jrdt button{
		/* display: inline; */
		width: 156px;
		height: 64px;
		font-size: 26px;
		color: #FF5858;
		font-family: PingFang SC;
		font-weight: bold;
		background-color: #FFFFFF;
		float: right;
		border-radius: 20px;
		margin-right: 35px;
		margin-top: -52px;
	}
	.center-xx1{
		width: 750px;
		height: 222px;
		/* background-color: #2979FF; */
		margin-top: 20px;
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.center-xx2{
		width: 682px;
		height: 222px;
		/* background-color: #18BC37; */
		background-color: #FFFFFF;
		border-radius: 26px;
	}
	.center-xx2 label{
		position: relative;
		font-size: 34px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #2B2B2B;
		margin-left: 37px;
		top: 45px;
	}
	.dsd{
		float: right;
		margin-right: 30px;
		margin-top: 45px;
	}
	.center-xx2 image{
		position: relative;
		width: 26px;
		height: 28px;
		top: 120px;
		right: 130px;
	}
	.center-xx2 span{
		position: relative;
		font-size: 28px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #707070;
		line-height: 36px;
		top: 117px;
		right: 112px;
	}
	.bottom1{
		width: 750px;
		height: 266px;
		/* background-color: #2979FF; */
		margin-top: 20px;
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.bottom2{
		width: 682px;
		height: 266px;
		/* background-color: #18BC37; */
		background-color: #FFFFFF;
		border-radius: 26px;
	}
	.dy td{
		position: relative;
		width: 171px;
		font-size: 34px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #2B2B2B;
		line-height: 36px;
		padding: 40px 0 0 0;
		left: 22px;
	}
	.de image{
		width: 72px;
		height: 72px;
		background: #FEDE9C;
		border-radius: 50%;
	}
	.de td{
		width: 171px;
		padding: 25px 0 0 0;
	}
	.ds td{
		width: 171px;
		font-size: 28px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #646464;
		padding: 0 0 20px 0;
	}
	.bggg{
		text-align: center;
		width: 682px;
		height: 266px;
	}
</style>
