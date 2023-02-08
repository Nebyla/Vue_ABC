<script>
	export default {
		data() {
      return {
        user1: '100$',
	      user2: '200$',
	      user3: '300$',
	}
  }
	}
</script>
<template>
  <ul>
    <li v-for="elem in user1">
		{{ elem }}
    </li>
    <li v-for="elem in user2">
		{{ elem }}
    </li>
    <li v-for="elem in user3">
		{{ elem }}
    </li>
</ul>
	
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
