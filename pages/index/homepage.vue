<template>
	<view class="app">
		<view class="content-bar ">
			<view class="wrapper ">
				<view class="head-bar ">
					<view class="head">
						<image src="../../static/img/4.webp" mode=""></image>
					</view>
					<view class="nav">
						<view class="layout">
							<view class="layout-pic">
								<image src="../../static/img/4.webp" mode=""></image>
							</view>
							<navigator url="">
								<text class="layout-txt">润泰超市水果店</text>
								<text class="iconfont font">&#xe648;</text>
							</navigator>
						</view>
						<view class="msg">
							<text>主营：新鲜水果</text>
						</view>
					</view>	
				</view>
				<view class="subanv">
					<view class="sub-wrap">
						<text @click="label=0" :class="['sub-1', {'active': label==0}]">水果</text>
						<text @click="label=1" :class="['sub-2', {'active': label==1}]">蔬菜</text>
						<text @click="label=2" :class="['sub-3', {'active': label==2}]">饮料</text>
						<text @click="label=3" :class="['sub-4', {'active': label==3}]">其他</text>
					</view>
					<view class="sub-layout">
						<text>免费配送</text>
						<navigator url="">我的订单</navigator>
					</view>
				</view>
				<view class="menu">
					<view class="menu-list">
						<navigator url="">
							<view class="menu-pic">
								<image src="../../static/img/4.webp" mode=""></image>
							</view>
							<view class="prod">
								<text class="prod-desc">哈密瓜(1盒约500克)</text>
								<view class="prod-prices">
									<text class="iconfont">&yen;6.50</text>
									<text class="prices-1">8.1折</text>
								</view>
								<text class=" iconfont summary">&yen;8.00</text>
								<text class="iconfont icon-tianjia1 add"></text>
								<text class="add quantity">1</text>
								<text class="iconfont icon-jian1 add"></text>
							</view>
						</navigator>
					</view>
					<view class="menu-list">
						<navigator url="">
							<view class="menu-pic">
								<image src="../../static/img/4.webp" mode=""></image>
							</view>
							<view class="prod">
								<text class="prod-desc">哈密瓜(1盒约500克)</text>
								<view class="prod-prices">
									<text class="iconfont">&yen;6.50</text>
									<text class="prices-1">8.1折</text>
								</view>
								<text class=" iconfont summary">&yen;8.00</text>
								<text class="iconfont icon-tianjia1 add"></text>
								<text class="add quantity">1</text>
								<text class="iconfont icon-jian1 add"></text>
							</view>
						</navigator>
					</view>
				</view>
			</view>
		</view>
		<!-- <view class="alert-box">
			<view class="warpper">
				<view class="shop-name">
					<view class="shop-name-pic">
						<image src="../../static/img/4.webp" mode=""></image>
					</view>
					<text class="shop-infor">润泰超市水果店</text>
				</view>
				<view class="shop-phone">
					<text class="iconfont icon-dianhuaben"></text>
					<text class="number">1888888888</text>
					<text class="iconfont icon-xiangyoujiantou"></text>
				</view>
				<view class="shop-address">
					<view class="prompt">
						<text class="iconfont icon-dingwei"></text>
						<text class="fruit-shop">湖北省黄冈市蕲春县漕河镇金色家园</text>
						<text class="iconfont icon-xiangyoujiantou"></text>
					</view>
					<view class="default">
						<text >知道了</text>
					</view>
				</view>
			</view>	
		</view> -->
	</view>
</template>

<script>
	export default {
		data() {
			return {
				label: 0,
			}
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
