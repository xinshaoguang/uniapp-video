<template>
	<view class="videoList">
		<view class="swiper-box">
			<swiper :indicator-dots="true" :vertical="true" :autoplay="true" :interval="3000" :duration="1000">
				<swiper-item>
					<view class="swiper-item">1</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item">2</view>
				</swiper-item>
			</swiper>
		</view>
	</view>
</template>

<script>
	export default {
		name:"videoList",
		data() {
			return {
				
			};
		}
	}
</script>

<style>
.videoList{
	height:100%;
	width:100%;
}
</style>
