<template>
	<view>
	  
	  <index></index>
	  <tab :index="0"></tab>
	</view>
</template>

<script>
	import tab from '../../components/tab.vue'
	import index from '../../components/indextest/indextest.vue'
	export default{
		components:{
			tab,
			index
		}
	}
</script>

<style>
	
</style>
