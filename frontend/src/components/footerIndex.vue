<template>
	<div id="footerIndex">
		© {{currentYear}} 海南南海云网络科技有限公司
	</div>

</template>

<script>
	export default {
	    data(){
	        return{
	            currentYear:(new Date()).getFullYear(),
			}
		}
	}

</script>

<style scoped>
	#footerIndex{height: 80px; line-height: 80px;background-color: #031537;color: #cfdcf5;font-size: 16px;text-align: center;}
</style>