<script>
	export default {
		props: ['name', 'surn'],
		data() {
			return {
				arg: [1,2,3]
			}
		}
	}
</script>
<template>
	{{ arg }}
	
</template>