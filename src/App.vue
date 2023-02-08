<script>
	export default {
		data() {
      return {
        arr: ['x', 'y', 'z'],
	}
  }
	}
</script>
<template>
  <p v-for="(elem, key) in arr">
		 {{ key + 1 }} {{ elem }}
	</p>
	
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {

  p
  {
    color:red
  }
  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
