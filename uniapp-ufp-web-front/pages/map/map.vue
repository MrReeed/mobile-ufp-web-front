<template>
	<view class="map">
		<map :scale='scale' :latitude="latitude" :longitude="longitude" :markers="markers"></map>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				longitude: 121.348868,
				latitude: 37.467872,
				scale: 16,
				markers: [{
					longitude: 121.348608,
					latitude: 37.468072,
					iconPath: '../../static/marker.png',
					width: 30,
					height: 30
				}],
				enablezoom:true,
				enableindoorMap: true,
				enable3D:true,
			}
		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.map {
		map {
			width: 750rpx;
			height: 1524rpx;
		}
	}
</style>
