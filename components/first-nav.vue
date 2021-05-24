<template>
	<view>
		<view class="firstNav">
			<view class="middle">
				<view class="text">
					推荐
				</view>
				<view class="text">
					同城
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		name:"first-nav",
		data() {
			return {
				
			};
		}
	}
</script>

<style>
.firstNav{
	width:100%;
	position:absolute;
	top:25px;
	left:0;
	height:35px;
	line-height: 35px;
	background-color: #000;
}
.middle{
	text-align: center;
}
.text{
	display: inline-block;
	color:#fff;
	font-size:15px;
	margin:0 10px;
}
</style>
