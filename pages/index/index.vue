<template>
	<view class="app bg1">
		<view class="home">
			<view class="content">
				<view class="address">
					<navigator url="">
						<text class="address-1">收货地址</text>
						<text class="iconfont address-2">添加收货地址&#xe648;</text>
					</navigator>
				</view>
			</view>
			<view class="list">
				<view class="hei">
					<view class="list-1">
						<view class="l1">共1件商品</view>
						<view class="detailed">
							<view class="pic">
								<image src="../../static/img/guo.png" ></image>
							</view>
							<text class="l2">哈密瓜(8元1盒约500克)</text>
							<text class="l3">&times;1</text>
							<view class="l4">
								<text class="l5">&yen;6.5</text>
								<text class="l6">&yen;8.00</text>
							</view>
						</view>
						<view class="detailed">
							<view class="pic">
								<image src="../../static/img/guo.png" ></image>
							</view>
							<text class="l2">哈密瓜(8元1盒约500克)</text>
							<text class="l3">&times;1</text>
							<view class="l4">
								<text class="l5">&yen;6.5</text>
								<text class="l6">&yen;8.00</text>
							</view>
						</view>
						<view class="total">
							<text>合计 &yen;6.5</text>
						</view>
					</view>
					<view class="remarks">
						<view class="remarks-1">
								<text >备注</text>
								<text class="iconfont remarks-2">填写备注&#xe648;</text>
								<textarea ></textarea>
						</view>
					</view>
					<view class="pay">
						<view class="pay-2">
							<text >合计</text>
							<text class="t1"> &yen;6.50</text>
						</view>
						<text class="pay-3">去支付</text>
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
</style>
