<script>
	export default {
		data() {
      return {
        items: [1, 2, 3],
	}
  }
	}
</script>
<template >
  <template v-for="elem in items">
		<ul>{{ elem }}</ul>
	</template>
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
