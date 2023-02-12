<script>
	export default {
	emits: ['show', 'xxx', 'yyy'],
	data() {
		return {
			arg1: 3,
			arg2: 4
		}
	},
	methods: {
		handle() {
		this.$emit('show', 'xxx', 'yyy');
	}
}
}
</script>
<template>
	
	<button @click="handle">btn</button>
</template>