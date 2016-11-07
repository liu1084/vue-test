<template>
	<div id="app1">
		{{message}}
	</div>
</template>

<script>
	module.exports = new Vue({
		data: {
			message: 'hello'
		}
	});
</script>

<style>
	#app1 {
		border: 2px solid #f0ad4e;
	}
</style>