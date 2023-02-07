<script>
	export default {
		data() {
      return {
        name: 'Yunus',
		    surn: 'Mustafaev',
        cost: 50,
        amount: 100,
	}
  },
  computed: {
	full: function() {
		return this.cost * this.amount;
	}
}
  
	}
</script>
<template>
  <p>{{ name }}</p>
	<p>{{ surn }}</p>
	<p>{{ full }}</p>
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
