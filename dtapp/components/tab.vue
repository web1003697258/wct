<template>
	<view class="tab">
		<navigator class="tab-view" url="/pages/index/index" open-type="switchTab">

			<image src="../static/shouye.png" v-if="index!=0"></image>
			<label class="syy" v-if="index!=0">首页</label>
			<image src="../static/shouye1.png" v-if="index==0"></image>
			<label class="sy" v-if="index==0">首页</label>

		</navigator>
		<navigator class="tab-view" url="/pages/fx/fx" open-type="switchTab">
			<image src="../static/faxian.png" v-if="index!=1"></image>
			<label class="syy" v-if="index!=1">发现</label>
			<image src="../static/faxian1.png" v-if="index==1"></image>
			<label class="sy" v-if="index==1">发现</label>
		</navigator>
		<view id="sdg" class="tab-view" open-type="switchTab">
			<image @click="open" src="../static/十字.png"></image>
			<uni-popup ref="popup" type="center" :mask-click="false">
				<view class="sssws">
					<!-- <image @click="close" src="../static/guangbi.png"
						style="width: 48px;height: 48px;float: right;margin-top: -510px;margin-right: 50px;"></image> -->
					 </view>
				<!-- <view class="xx"> -->
				<image @click="close" src="../static/guangbi.png"
					style="width: 48px;height: 48px;float: right;margin-top: -1250px;opacity: 0.8; margin-right: 50px;"></image>
				<!-- </view> -->
				<view class="zjtp">
					<table class="bgsj">
						<tr class="sctp">
							<td>
								<image src="../static/上传图片.png" style="width: 110px;height: 110px;"></image>
							</td>
							<td>
								<image src="../static/图片电影.png"></image>
							</td>
							<td>
								<image src="../static/写文章.png"></image>
							</td>
						</tr>
						<tr class="tpwz">
							<td>
								上传图片
							</td>
							<td>
								图片电影
							</td>
							<td>
								写文章
							</td>
						</tr>
					</table>
				</view>
                
			</uni-popup>
		</view>
		<navigator class="tab-view" url="/pages/zx/zx" open-type="switchTab">
			<image src="../static/zhuanxiang.png" v-if="index!=2"></image>
			<label class="syy" v-if="index!=2">专享</label>
			<image src="../static/zhuanxiang1.png" v-if="index==2"></image>
			<label class="sy" v-if="index==2">专享</label>
		</navigator>
		<navigator class="tab-view" url="/pages/wd/wd" open-type="switchTab">
			<image src="../static/wode.png" v-if="index!=3"></image>
			<label class="syy" v-if="index!=3">我</label>
			<image src="../static/wode@2x.png" v-if="index==3"></image>
			<label class="sy" v-if="index==3">我</label>
		</navigator>
	</view>
</template>

<script>
	export default {
		name: "tab",
		data() {
			return {

			};
		},
		props: {
			index: Number
		}, // ["index"]
		methods: {
			open() {
				// 通过组件定义的ref调用uni-popup方法 ,如果传入参数 ，type 属性将失效 ，仅支持 ['top','left','bottom','right','center']
				this.$refs.popup.open('center')
			},
			close() {
				this.$refs.popup.close()
			}
		}

	}
</script>

<style>
	.tab {
		/* height: 98px;
	width: 748.5px; */
		position: fixed;
		left: 0;
		bottom: 0;
		width: 749px;
		height: 98px;
		background: #FFFFFF;
		z-index: 500;

		/* box-shadow: 0px -1px 4px 0px rgba(0, 0, 0, 0.11); */
	}

	.tab-view {
		float: left;
		width: 20%;
		color: #999999;
		text-align: center;
		background: #FFFFFF;
		/* background-color: #007AFF; */
		height: 98px;
		font-size: 20px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #909090;
		bottom: 0;
	}

	#sdg image {
		width: 108px;
		height: 108px;
		margin-top: -24px;
	}

	.tab-view image {
		margin-top: 12px;
		width: 48px;
		height: 48px;
		/* margin-top: 8px; */
	}

	.sy {
		display: block;
		color: #ff5858;
	}
    .syy{
		display: block;
		
	}
	.bgsj {
		width: 750px;
		height: 160px;
	}

	.zjtp {
		position: relative;
		width: 750px;
		height: 160px;
		/* background-color: #18BC37; */
		top: -800px;
	}

	.sctp image {
		width: 110px;
		height: 110px;
	}

	.tpwz td {
		padding: 0 40px;
		font-size: 33px;
		font-family: PingFang SC;
		/* font-weight: bold; */
		color: #646464;
		/* color: #FFFFFF; */
	}

	.xxx {
		width: 35px;
		height: 35px;
	}

	.xx {
		width: 48px;
		height: 48px;
		background-color: #2979FF;
	}
	.sssws{
		/* position: relative; */
		width: 750px;
		height: 1500px;
		/* background-color: #007AFF; */
		filter: blur(20px);
		background-image:url(../static/g.png) ;
		z-index: 999;
		opacity: 0.6;
	}
</style>
