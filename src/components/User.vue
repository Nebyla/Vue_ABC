<script>
	export default {
	emits: ['show', 'xxx', 'yyy'],
	data() {
		return {
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
	
	<button @click="$emit('show', 'xxx', 'yyy')">
		btn
	</button>
</template>