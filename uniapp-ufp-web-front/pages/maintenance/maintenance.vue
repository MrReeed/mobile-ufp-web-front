<template>
	<view class="maintenance">
		<view class="maintenance_work">
			<view class="maintenance_work_item">
				<text>8</text>
				<text>例行维保任务</text>
			</view>
			<view class="maintenance_work_item">
				<text>52</text>
				<text>应急维保任务</text>
			</view>
			<view class="maintenance_work_item">
				<text>33</text>
				<text>逾期维保任务</text>
			</view>
			<view class="maintenance_work_item">
				<text>6</text>
				<text>本月完成例行维保</text>
			</view>
			<view class="maintenance_work_item">
				<text>5</text>
				<text>本月完成应急维保</text>
			</view>
			<view class="maintenance_work_item">
				<text>62</text>
				<text>告知单</text>
			</view>
		</view>
		<view class="YingJiWeiBao">
			<view class="yingjiweibao_bar">
				<view>
					<text>应急维保</text>
					<u-icon name='plus-circle-fill' size='40'></u-icon>
				</view>
				<view>
					<text>全部</text>
					<u-icon name="arrow-right"></u-icon>
				</view>
			</view>
			<view class="yingjiweibao_content">
				<view class="yingjiweibao_content_item">
					<image src='../../static/weibao_icon/daichuli.png'></image>
					<view>
						<text>待处理</text>
						<u-icon name="arrow-right" size='45'></u-icon>
					</view>
				</view>
				<view class="yingjiweibao_content_item">
					<image src='../../static/weibao_icon/jinxingzhong.png'></image>
					<view>
						<text>处理中</text>
						<u-icon name="arrow-right" size='45'></u-icon>
					</view>
				</view>
				<view class="yingjiweibao_content_item">
					<image src='../../static/weibao_icon/yiwancheng.png'></image>
					<view>
						<text>已处理</text>
						<u-icon name="arrow-right" size='45'></u-icon>
					</view>
				</view>
			</view>
		</view>
		<view class="YingJiWeiBao">
			<view class="yingjiweibao_bar">
				<text>例行维保</text>
				<view>
					<text>全部</text>
					<u-icon name="arrow-right"></u-icon>
				</view>
			</view>
			<view class="yingjiweibao_content">
				<view class="yingjiweibao_content_item">
					<image src='../../static/weibao_icon/daichuli.png'></image>
					<view>
						<text>待处理</text>
						<u-icon name="arrow-right" size='45'></u-icon>
					</view>
				</view>
				<view class="yingjiweibao_content_item">
					<image src='../../static/weibao_icon/jinxingzhong.png'></image>
					<view>
						<text>处理中</text>
						<u-icon name="arrow-right" size='45'></u-icon>
					</view>
				</view>
				<view class="yingjiweibao_content_item">
					<image src='../../static/weibao_icon/yiwancheng.png'></image>
					<view>
						<text>已处理</text>
						<u-icon name="arrow-right" size='45'></u-icon>
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

			}
		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.maintenance {
		margin-top: 10rpx;
		overflow: hidden;
		// 默认的icon是基线对齐，如果要中部对齐，用这个：
		// uni-view {
		// 	// display: inline-block;
		// 	vertical-align: middle;
		// }

		.maintenance_work {
			display: flex;
			flex-wrap: wrap;
			margin: 30rpx 20rpx 20rpx;
			background-color: #4e9bff;
			border-radius: 20rpx;

			.maintenance_work_item {
				display: flex;
				flex: 33.33%;
				flex-direction: column;


				text {
					text-align: center;
					color: #fff;
				}

				text:nth-child(1) {
					font-size: 50rpx;
					padding: 15rpx 15rpx 0;
				}

				text:nth-child(2) {
					font-size: 20rpx;
					padding: 0 10rpx 15rpx;
				}
			}
		}

		.YingJiWeiBao {
			overflow: hidden;

			.yingjiweibao_bar {
				display: flex;
				justify-content: space-between;
				height: 50rpx;
				line-height: 50rpx;
				padding: 5rpx 15rpx;
				margin-top: 10rpx;

				text {
					font-size: 30rpx;
				}

				view {
					text {
						display: inline-block;
						margin-right: 10rpx;
					}
				}
			}

			.yingjiweibao_content {
				.yingjiweibao_content_item {
					display: flex;
					justify-content: space-between;
					width: 400rpx;
					height: 120rpx;
					margin: 20rpx auto;
					image {
						margin: 10rpx;
						width: 100rpx;
						height: 100rpx;
					}
					view {
						height: 120rpx;
						text {
							font-weight: 800;
							display: inline-block;
							margin-right: 70rpx;
							vertical-align: middle;
						}
						uni-view {
							vertical-align: middle;
						}
					}
				}
			}
		}
	}
</style>
