<template>
	<view>
		<view class="max">
			<view class="tp">
			<view class="ssjj">
				<uni-icons class="ss" type="search" size="45" color="#b7b7b7"></uni-icons>
				<input class="ssd" type="text" placeholder="搜索感兴趣的内容..." />
				<uni-icons class="ssw" type="camera" size="45" color="#b7b7b7"></uni-icons>
			</view>
			<view class="tbdhl">
				<view class="option-box">
					<view class="option" :style="style1" @click="click(1)">
						热门搜索
					</view>
					<view class="option" :style="style2" @click="click(2)">
						原创
					</view>
					<view class="option" :style="style3" @click="click(3)">
						主题
					</view>
					<view class="option" :style="style4" @click="click(4)">
						头像
					</view>
					<view class="option" :style="style5" @click="click(5)">
						墙纸
					</view>
					<view class="option" :style="style6" @click="click(6)">
						表情
					</view>
					<view class="option" :style="style7" @click="click(7)">
						影视
					</view>
				</view>
				<image src="../../static/xiala.png"></image>
			</view>
			</view>
			<view class="gdt">
			<view class="centerzt">
				<image src="../../static/shuaxin.png"></image>
				<label>今日推荐</label>
			</view>
			<view class="bottom">
				<view class="bottom-1">
					<image src="../../static/b1.png"></image>
					<span class="ssss">明星热销</span>
					<label>易烊千玺,高清墙纸分享</label>
				</view>
				<view class="bottom-2">
					<image src="../../static/b2.png"></image>
					<span class="ssss">热门头像</span>
					<label>搞怪头像,奇奇怪怪可可爱爱</label>
				</view>
				<view class="bottom-3">
					<image src="../../static/b3.png"></image>
					<span class="ssss">热度飙升</span>
					<label>原神人物情头,动漫情头</label>
				</view>
				<view class="bottom-4">
					<image src="../../static/b4.png"></image>
					<span class="ssss">热门头像</span>
					<label>情侣头像,原创动漫情头</label>
				</view>
				<view class="bottom-5">
					<image src="../../static/b6.png"></image>
					<span class="ssss">明星热推</span>
					<label>迪丽热巴,头像墙纸分享</label>
				</view>
				<view class="bottom-6">
					<image src="../../static/b5.png"></image>
					<span class="ssss">热门头像</span>
					<label>欧美头像,神秘气质、高冷</label>
				</view>
			</view>
			<view class="bottom-zj">
				<label>往期热门</label>
				<button>更多
				<image src="../../static/you.png"></image>
				</button>
			</view>
			<view class="bottom1">
				<view class="bottom-1">
					<image src="../../static/a2.jpg"></image>
					<span class="ssss">热门头像</span>
					<label>秋刀鱼,高清头像分享</label>
				</view>
				<view class="bottom-2">
					<image src="../../static/a3.jpg"></image>
					<span class="ssss">热门头像</span>
					<label>沐浴露,奇奇怪怪可可爱爱</label>
				</view>
				<view class="bottom-3">
					<image src="../../static/a4.jpg"></image>
					<span class="ssss">热度飙升</span>
					<label>原神人物情头,美女头像</label>
				</view>
				<view class="bottom-4">
					<image src="../../static/a5.jpg"></image>
					<span class="ssss">热门头像</span>
					<label>情侣头像,原创动漫情头</label>
				</view>
				<view class="bottom-5">
					<image src="../../static/a6.jpg"></image>
					<span class="ssss">明星热推</span>
					<label>迪丽热巴,头像墙纸分享</label>
				</view>
				<view class="bottom-6">
					<image src="../../static/a7.jpg"></image>
					<span class="ssss">热门头像</span>
					<label>欧美头像,神秘气质、高冷</label>
				</view>
			</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				style1: "border-bottom: 5px solid #FF5858;",
				style2: "",
				style3: "",
				style4: "",
				style5: "",
				style6: "",
				style7: "",
			};
		},
		methods: {
			click(id) {
				if (id == 1) {
					this.style1 = "border-bottom: 5px solid #FF5858;color: #FF5858;"
					this.style2 = "";
					this.style3 = "";
					this.style4 = "";
					this.style5 = "";
					this.style6 = "";
					this.style7 = "";
				}
				if (id == 2) {
					this.style2 = "border-bottom: 5px solid #FF5858;color: #FF5858;"
					this.style1 = "";
					this.style3 = "";
					this.style4 = "";
					this.style5 = "";
					this.style6 = "";
					this.style7 = "";
				}
				if (id == 3) {
					this.style3 = "border-bottom: 5px solid #FF5858;color: #FF5858;"
					this.style2 = "";
					this.style1 = "";
					this.style4 = "";
					this.style5 = "";
					this.style6 = "";
					this.style7 = "";
				}
				if (id == 4) {
					this.style4 = "border-bottom: 5px solid #FF5858;color: #FF5858;"
					this.style2 = "";
					this.style1 = "";
					this.style3 = "";
					this.style5 = "";
					this.style6 = "";
					this.style7 = "";
				}
				if (id == 5) {
					this.style5 = "border-bottom: 5px solid #FF5858;color: #FF5858;"
					this.style6 = "";
					this.style7 = "";
					this.style2 = "";
					this.style1 = "";
					this.style3 = "";
					this.style4 = "";
					
				}
				if (id == 6) {
					this.style6 = "border-bottom: 5px solid #FF5858;color: #FF5858;"
					this.style7 = "";
					this.style5 = "";
					this.style4 = "";
					this.style3 = "";
					this.style2 = "";
					this.style1 = "";
					
				}
				if (id == 7) {
					this.style7 = "border-bottom: 5px solid #FF5858;color: #FF5858;"
					this.style2 = "";
					this.style1 = "";
					this.style3 = "";
					this.style5 = "";
					this.style6 = "";
					this.style4 = "";
				}
			}
		}
	}
</script>

<style>
	.max {
		width: 100%;
		height: 1800px;
		background-color: #F8F8F8;
	}	
	.ssjj {
		display: inline-block;
		width: 600px;
		height: 60px;
		background: #EEEEEE;
		/* background-color: #DD524D; */
		border-radius: 30px;
		line-height: 60px;
		margin-top: 25px;
		margin-left: 76px;
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
		float: left;
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
	.tbdhl{
		width: 750px;
		height: 78px;
		background-color: #FFFFFF;
		/* background-color: #18BC37; */
		margin-top: 15px;
		box-shadow: 0px 1px 4px 0px rgba(0, 0, 0, 0.11);
		
	}
	.tbdhl image{
		position: relative;
		width: 26px;
		height: 14px;
		margin-left: 14px;
		top: -26px;
	}
	.tp{
		background-color: #FFFFFF;
	}
	.option-box {
		width: 100%;
		height: 50px;
		line-height: 50px;
		/* margin-bottom: 10px; */
	}
	
	.option {
		/* width: 25%; */
		padding: 7px 19px;
		height: 50px;
		line-height: 50px;
		color: #999999;
		float: left;
		text-align: center;
		font-size: 26px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #646464;
	}
	.centerzt{
		width: 750px;
		height: 110px;
		/* background-color: #F0AD4E; */
		/* background-color: #F8F8F8; */
		line-height: 120px;
	}
	.centerzt image{
		width: 33px;
		height: 35px;
		margin-left: 30px;
	}
	.centerzt label{
		position: relative;
		font-size: 34px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #2B2B2B;
		margin-left: 14px;
		top: -5px;
		/* line-height: 36px; */
	}
	.bottom{
		width: 750px;
		height: 660px;
		/* background-color: #18BC37; */
	}
	.bottom1{
		width: 750px;
		height: 660px;
		/* background-color: #18BC37; */
		margin-top: 15px;
	}
	.bottom-1{
		width: 215px;
		height: 296px;
		/* background-color: #2979FF; */
		margin-left: 28px;
		float: left;
		border-radius: 20px 20px 20px 0px;
	}
	.bottom-1 image{
		width: 215px;
		height: 215px;
		border-radius: 20px;
	}
	.bottom-1 label{
		position: relative;
		font-size: 22px;
		line-height: 32px;
		top: 3px; 
		font-weight: 500;
		color: #2B2B2B;
		/* float: right; */
	}
	.ssss{
		display: inline-block;
		width: 95px;
		height: 32px;
		line-height: 32px;
		background-color: #fbebe9;
		color: #f38769;
		border: 0;
		border-radius: 11px;
		text-align: center;
		margin: 8px 10px 0px 0px;
		font-size: 19px;
	}
	.bottom-2{
		width: 215px;
		height: 296px;
		/* background-color: #DD524D; */
		float: right;
		margin-right: 28px;
		border-radius: 20px 20px 20px 0px;
	}
	.bottom-2 image{
		width: 215px;
		height: 215px;
		border-radius: 20px;
	}
	.bottom-2 label{
		position: relative;
		font-size: 22px;
		line-height: 32px;
		top: 3px; 
		font-weight: 500;
		color: #2B2B2B;
	}
	.bottom-3{
		width: 215px;
		height: 296px;
		float: right;
		/* background-color: #8E8E8E; */
		margin-right: 24px;
		border-radius: 20px 20px 20px 0px;
	}
	.bottom-3 image{
		width: 215px;
		height: 215px;
		border-radius: 20px;
	}
	.bottom-3 label{
	position: relative;
	font-size: 22px;
	line-height: 32px;
	top: 3px; 
	font-weight: 500;
	color: #2B2B2B;
	}
	.bottom-4{
		width: 215px;
		height: 296px;
		/* background-color: #2979FF; */
		margin-left: 28px;
		float: left;
		margin-top: 20px;
		bborder-radius: 20px 20px 20px 0px;
	}
	.bottom-4 image{
		width: 215px;
		height: 215px;
		border-radius: 20px;
	}
	.bottom-4 label{
		position: relative;
		font-size: 22px;
		line-height: 32px;
		top: 3px; 
		font-weight: 500;
		color: #2B2B2B;
	}
	.bottom-5{
		width: 215px;
		height: 296px;
		/* background-color: #DD524D; */
		float: right;
		margin-right: 28px;
		margin-top: 20px;
		border-radius: 20px 20px 20px 0px;
	}
	.bottom-5 image{
		width: 215px;
		height: 215px;
		border-radius: 20px;
	}
	.bottom-5 label{
		position: relative;
		font-size: 22px;
		line-height: 32px;
		top: 3px; 
		font-weight: 500;
		color: #2B2B2B;
	}
	.bottom-6{
		width: 215px;
		height: 296px;
		float: right;
		/* background-color: #8E8E8E; */
		margin-right: 24px;
		margin-top: 20px;
		border-radius: 20px 20px 20px 0px;
	}
	.bottom-6 image{
		width: 215px;
		height: 215px;
		border-radius: 20px;
	}
	.bottom-6 label{
		position: relative;
		font-size: 22px;
		line-height: 32px;
		top: 3px; 
		font-weight: 500;
		color: #2B2B2B;
	}
	.bottom-zj{
		width: 750px;
		height: 90px;
		/* background-color: #FF5A5F; */
	}
	.bottom-zj label{
		font-size: 34px;
		font-family: PingFang SC;
		font-weight: bold;
		color: #2B2B2B;
		line-height: 90px;
		margin-left: 28px;
	}
	.bottom-zj button{
		display: inline-block;
		width: 106px;
		height: 54px;
		line-height: 54px;
		/* background-color: #18BC37; */
		float: right;
		margin-top: 21px;
		margin-right: 28px;
		border: 0;
		font-size: 26px;
		font-family: PingFang SC;
		font-weight: 500;
		color: #2B2B2B;
		border: 1px solid #909090;
		border-radius: 27px;
	}
	.bottom-zj image{
		width: 17px;
		height: 17px;
		margin-left: 7px;
	}
	/* .gdt{
		overflow: auto;
		overflow-y: scroll;
		overflow-x: hidden;
	} */
	/* .option:hover{
		border-bottom: 5px solid #FF5858;
		color: #FF5858;
		width: 10px;
	} */
</style>
