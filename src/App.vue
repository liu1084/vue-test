<template lang="jade">
	div#app
	h1 {{msg}}
	div#app1
	h2 {{message}}
</template>

<script>
	import Hello from './hello.vue'
	export default {
		components: {
			Hello
		},
		name: 'app',
		data () {
			return {
				msg: 'Welcome to Your Vue.js App'
			}
		}
	}
</script>

<style>
	#app h1 {
		font-size: 2rem;
	}
</style>
