<template>
	<view class="app">
		<view class="infor">
			<view class="infor-1">
				<view class="infor-2">
					<view class="posi">
						<navigator url="" hover-class="hover-class">
							<text class="pi">地址</text>
							<view class="fr">
								<text class="di">请选择地址</text>
								<text class="iconfont">&#xe648;</text>
							</view>
						</navigator>
					</view>
					<view class="posi-1">
						<text class="p1">门牌号</text>
						<input type="text" value=""  placeholder="请输入门牌号码"/>
					</view>
					<view class="posi-1">
						<text class="p1">收货人</text>
						<input type="text" value="" placeholder="请输入姓名"/>
					</view>
					<view class="posi-2">
						<text class="p1"></text>
						<view class="p4">
							<view class="p5" @click="age=1">
								<text :class="['iconfont', {'icon-xuanzhong':age==1, 'icon-xuanzhong1':age==0}]"></text>
								<text>男士</text>
							</view>
							<view class="p5" @click="age=0">
								<text :class="['iconfont', {'icon-xuanzhong':age==0, 'icon-xuanzhong1':age==1}]"></text>
								<text>女士</text>
							</view>
						</view>
							
					</view>
					<view class="posi-1">
						<text class="p1">手机号</text>
						<input type="text" value="" placeholder="请输入手机号" />
					</view>
					<view class="biaq">
						<view class="b1">
							<text class="b2">标签</text>
							<text @click="label=0" :class="['b3', {'active': label==0}]">家</text>
							<text @click="label=1" :class="['b3', {'active': label==1}]">公司</text>
							<text @click="label=2" :class="['b3', {'active': label==2}]">学校</text>
						</view>
					</view>
				</view>
				<view class="infor-3">
					<view class="save">
						<text>保存</text>
					</view>
					<view class="dele">
						<text>删除</text>
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
				age: 1,
				label: 0,
			}
		},
		created() {
			
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
