<template>
	<view>
		<tab :index="1"></tab>
		<fxtest></fxtest>
	</view>
</template>

<script>
	import tab from '../../components/tab.vue'
	import fxtest from '../../components/fxtest/fxtest.vue'
	export default{
		components:{
			tab,
			fxtest
		}
	}
</script>

<style>
</style>
