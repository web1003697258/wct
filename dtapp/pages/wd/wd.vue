<template>
	<view>
		<tab :index="3"></tab>
		<wdtest></wdtest>
	</view>
</template>

<script>
	import tab from '../../components/tab.vue'
	import wdtest from '../../components/wdtest/wdtest.vue'
	export default{
		components:{
			tab,
			wdtest
		}
	}
</script>

<style>
</style>
