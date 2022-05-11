<script>
	export default {
		onLaunch: function() {
			uni.hideTabBar({
			})
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style lang="scss">
	html,body{
		width: 100%;
		height: 100vh;
		color: #007AFF;
		
	}
</style>
