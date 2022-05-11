<template>
	<view>
		<view class="max">
			<view class="ssk">
				<label>关注</label>
				<view class="ssjj">
					<uni-icons class="ss" type="search" size="45" color="#b7b7b7"></uni-icons>
					<input class="ssd" type="text" placeholder="搜索感兴趣的内容..." />
					<uni-icons class="ssw" type="camera" size="45" color="#b7b7b7"></uni-icons>
				</view>
			</view>
			<view class="lbt">
				<view class="page-section swiper">
					<view>
						<swiper class="sdgf" :indicator-dots="indicatorDots"
							:indicator-active-color="indicatorActiveColor" :autoplay="autoplay" :interval="interval"
							:duration="duration">
							<swiper-item>
								<view>
									<image src="../../static/001.png"></image>
								</view>
							</swiper-item>
							<swiper-item>
								<view>
									<image src="../../static/002.png"></image>
								</view>
							</swiper-item>
						</swiper>
					</view>
				</view>
			</view>
			<view class="tubiao">
				<view class="index-vieww">
					<image src="../../static/今日专辑.png"></image>
					<label class="ass">今日编辑</label>
				</view>
				<view class="index-view">
					<image src="../../static/热门.png"></image>
					<label class="ass">热门</label>
				</view>
				<view class="index-view">
					<image src="../../static/约稿.png"></image>
					<label class="ass">约稿</label>
				</view>
				<view class="index-view">
					<image src="../../static/原创.png"></image>
					<label class="ass">原创</label>
				</view>
				<view class="index-view">
					<image src="../../static/最新活动.png"></image>
					<label class="ass">最新活动</label>
				</view>
			</view>
			<view class="xfsj">
				<view class="xfsj-left">
					<image src="../../static/003.png"></image>
					<table class="sfffr">
						<tr>
							<td class="ztdax">在这个星球上 你很重要</td>
					    </tr>
						<tr>
							<td class="bgtp">
								<image src="../../static/a2.jpg"></image>
								<label>小松雅稚</label>
								<label class="adw">1.5k</label>
								<image id="tpdsd" src="../../static/shoucang.png"></image>
								
							</td>
						</tr>
					</table>
				</view>
				<view class="xfsj-right">
                <image src="../../static/004.png"></image>
                <table class="sfffr">
                	<tr>
                		<td class="ztdax">可爱情头 侵权删</td>
                    </tr>
                	<tr>
                		<td class="bgtp">
                			<image src="../../static/a3.jpg"></image>
                			<label>虎虎丫丫</label>
							<label class="adw">206</label>
                			<image id="tpdsd" src="../../static/shoucang.png"></image>
                			
                		</td>
                	</tr>
                </table>
				</view>
				<view class="xfsj-leftt">
                 <image src="../../static/006.png"></image>
                 <table class="sfffr">
                 	<tr>
                 		<td class="ztdax">夏目友人账墙纸！</td>
                     </tr>
                 	<tr>
                 		<td class="bgtp">
                 			<image src="../../static/a4.jpg"></image>
                 			<label>Rosen</label>
                 			<label class="adw">96</label>
                 			<image id="tpdsd" src="../../static/shoucang.png"></image>
                 		</td>
                 	</tr>
                 </table>
				</view>
				<view class="xfsj-rightt">
                <image src="../../static/005.png"></image>
                <table class="sfffr">
                	<tr>
                		<td class="ztdax">索隆老公啊啊啊！</td>
                    </tr>
                	<tr>
                		<td class="bgtp">
                			<image src="../../static/a5.jpg"></image>
                			<label>罗罗诺亚.索隆</label>
							<label class="adw">2.6k</label>
                			<image id="tpdsd" src="../../static/shoucang.png"></image>
                		</td>
                	</tr>
                </table>
				</view>
				
				<view class="xfsj-righttt">
				<image src="../../static/007.png"></image>
				<table class="sfffr">
					<tr>
						<td class="ztdax">鞠婧祎</td>
				    </tr>
					<tr>
						<td class="bgtp">
							<image src="../../static/a7.jpg"></image>
							<label>Rosen</label>
							<label class="adw">23</label>
							<image id="tpdsd" src="../../static/shoucang.png"></image>
						</td>
					</tr>
				</table>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				indicatorDots: true,
				autoplay: true,
				interval: 3000,
				duration: 500,
				indicatorColor: "#292b40",
				indicatorActiveColor: "#ffffff"
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.max {
		width: 100%;
		height: 2300px;
		background-color: #F8F8F8;
	}

	.ssk {
		position: relative;
		width: 690px;
		height: 60px;
		margin-left: 32px;
		top: 22px;
	}
	.ssk label {
		position: relative;
		font-size: 36px;
		line-height: 60px;
		font-family: STHeiti;
		/* font-weight: 550; */
		color: #646464;
		top: -18px;
	}

	.ssjj {
		display: inline-block;
		width: 600px;
		height: 60px;
		background: #EEEEEE;
		border-radius: 30px;
		margin-left: 14px;
		line-height: 60px;
	}

	.ss {
		width: 32px;
		height: 32px;
		float: left;
		margin-left: 17px;
	}

	.ssd {
		width: 460px;
		height: 60px;
		/* background: #DD524D; */
		float: left;
		/* border-radius: 30px; */
		font-size: 26px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #909090;
		margin-left: 20px;
	}

	.ssw {
		width: 32px;
		height: 32px;
		float: right;
		margin-right: 31px;
	}

	.lbt {
		height: 240px;
		/* background-color: #DD524D; */
		position: relative;
		width: 690px;
		margin-left: 32px;
		top: 51px;
		border-radius: 16px;
	}

	.lbt image {
		height: 240px;
		width: 690px;
		border-radius: 16px;
		position: relative;
	}

	.sdgf {
		height: 240px;
		width: 690px;
	}

	.tubiao {
		height: 138px;
		/* background-color: #DD524D; */
		position: relative;
		/* position: fixed; */
		width: 690px;
		margin-left: 41px;
		top: 88px;
		left: 0;
		bottom: 0;
	}

	.index-vieww {
		float: left;
		padding: 0px 12px 0px 0px;
		color: #707070;
		text-align: center;
		height: 98px;
		font-size: 24px;
		font-family: PingFang SC;
		font-weight: 500;
	}

	.index-view {
		float: left;
		padding: 0px 22px;
		color: #707070;
		text-align: center;
		height: 98px;
		font-size: 24px;
		font-family: PingFang SC;
		font-weight: 500;
	}

	.tubiao image {
		width: 100px;
		height: 100px;
	}

	.ass {
		display: block;
	}

	.xfsj {
		height: 1300px;
		position: relative;
		width: 690px;
		margin-left: 32px;
		top: 132px;
		left: 0;
		bottom: 0;
		background-color: #F8F8F8;
	}

	.xfsj-left {
		width: 332px;
		height: 450px;
		background-color: #FFFFFF;
		float: left;
		border-radius: 10px;
	}

	.xfsj-right {
		width: 332px;
		height: 450px;
		background-color: #FFFFFF;
		float: right;
		border-radius: 10px;
	}

	.xfsj-leftt {
		width: 332px;
		height: 680px;
		background-color: #FFFFFF;
		/* float: right; */
		float: left;
		margin-top: 24px;
		border-radius: 10px;
	}
    .xfsj-leftt image{
		width: 332px;
		height: 560px;
		border-radius: 10px 10px 0px 0px;
	}
	.xfsj-rightt {
		width: 332px;
		height: 450px;
		background-color: #FFFFFF;
		float: right;
		margin-top: 24px;
		border-radius: 10px;
	}
    .xfsj-rightt image{
		width: 332px;
		height: 332px;
		border-radius: 10px 10px 0px 0px;
	}
	.xfsj-righttt {
		width: 332px;
		height: 640px;
		background-color: #FFFFFF;
		float: right;
		margin-top: 24px;
		border-radius: 10px;
	}
	.xfsj-righttt image{
		width: 332px;
		height: 513px;
		border-radius: 10px 10px 0px 0px;
	}
	.xfsj-left image {
		width: 332px;
		height: 332px;
		border-radius: 10px 10px 0px 0px;
	}
	.xfsj-right image{
		width: 332px;
		height: 332px;
		border-radius: 10px 10px 0px 0px;
	}
	.sfffr{
	   width: 332px;
	}
	.sfffr td{
		padding: 8px 15px;
	}
	.ztdax{
		font-size: 24px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #4D4D4D;
	}
	.bgtp image{
		width: 36px;
		height: 36px;
		border-radius: 25px;
	}
	.bgtp label{
		position: relative;
		font-size: 17px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #B4B4B4;
		top: -10px;
		left: 10px;
	}
	#tpdsd{
		float: right;
		width: 21px;
		height: 20px;
		margin-top: 7px;
		/* margin-right: 5px; */
	}
	.adw{
		float: right;
		font-size: 22px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #B4B4B4;
		margin-top: 16px;
		margin-right: 13px;
	}
</style>
