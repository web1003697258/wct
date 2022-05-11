<template>
	<view>
		<tab :index="2"></tab>
		<zxtest></zxtest>
	</view>
</template>

<script>
	import tab from '../../components/tab.vue'
	import zxtest from '../../components/zxtest/zxtest.vue'
	export default{
		components:{
			tab,
			zxtest
		}
	}
</script>

<style>
</style>
