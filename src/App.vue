<script>
	export default {
		data() {
      return {
        products: [
			{
				name: 'product1',
				price: 100,
				quantity: 5
			},
			{
				name: 'product2',
				price: 200,
				quantity: 4
			},
			{
				name: 'product3',
				price: 300,
				quantity: 3
			},
		]
	}
  }
	}
</script>
<template >
  <table v-for="product in products">
	<tr>
		<td>product1</td>
		<td>100</td>
		<td>5</td>
	</tr>
	<tr>
		<td>product2</td>
		<td>200</td>
		<td>4</td>
	</tr>
	<tr>
		<td>product3</td>
		<td>300</td>
		<td>3</td>
	</tr>
</table>
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
