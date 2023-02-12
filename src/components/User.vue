<script>
	export default {
	emits: ['show'],
	data() {
		return {
			
		}
	},
	methods: {
	handle() {
		this.$emit('show');
	}
}
}
</script>
<template>
	
	<button @click="handle">btn</button>
</template>