<template>
	<view class="warp">
		<view class="title">业务内容</view>
		<view class="content">
			<view>
				财税咨询、尽职调查、审计报告
			</view>
			<view>
				股权设计、内控管理、评估报告
			</view>
			<view>
				公司注册、乱账整理、代理记账
			</view>
		</view>
		<view class="job">让一切美好变得更有可能</view>
		<view class="job">用心让一切美好变得更有可能</view>
		<view class="job">联系方式：15209890187(微信同号)</view>
		<!-- <image class="logo" src="/static/img.jpg"></image> -->
		<!-- <view class="title title1">业务内容</view>
		<view class="content">
			<view>
				财税咨询、尽职调查、审计报告
			</view>
			<view>
				股权设计、内控管理、评估报告
			</view>
			<view>
				公司注册、乱账整理、代理记账
			</view>
		</view> -->
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: ''
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	
	.warp {
		color: white;
		text-align: center;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		height: 100vh;
	}
	.title {
		font-size: 76rpx;
		font-weight: bold;
		background-color: royalblue;
		padding: 100rpx 100rpx 20rpx;
		margin-bottom: 20rpx;
	}
	.content {
		padding: 0 80rpx;
		color: #4169E1;
		font-size: 40rpx;
	}
	.job {
	    background-color: royalblue;
	    border-radius: 6rpx;
	    margin-top: 30rpx;
	    font-size: 40rpx;
	    padding: 10rpx 0;
	    color: white;
		text-align: center;
		padding: 20px 0;
	}
	.title1 {
		font-size: 56rpx;
		text-align: center;
		padding: 0;
		line-height: 160rpx;
	}
	
</style>
