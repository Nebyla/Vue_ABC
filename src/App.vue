<script>
	export default {
		data() {
	  return {
      num1: 1,
		num2: 2,
		num3: 3,
	}
}
	}
</script>
<template>
  <div>{{ num1 + num2 + num3 }}</div>
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

  div
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
