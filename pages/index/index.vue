<template>
	<view class="content">
		<firstnav></firstnav>
		<video-list></video-list>
		<tab></tab>
	</view>
</template>

<script>
	import tab from "../../components/tab.vue"
	import firstnav from "../../components/first-nav.vue"
	import videoList from "../../components/videoList.vue"
	export default {
		components: {
			tab,
			firstnav,
			videoList
		},
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		/* display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center; */
		height:100%;
		width:100%;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
