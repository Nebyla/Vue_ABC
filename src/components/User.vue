<script>
	export default {
		props: {
		name: String,
		surn: String
	},
		data() {
			return {
				name: 'Yunus',
		surn: 'Mustafaev',
			}
		}
	}
</script>
<template>
	{{ name }}
	{{ surn }}
	
</template>