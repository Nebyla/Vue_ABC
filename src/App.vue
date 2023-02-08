<script>
	export default {
		data() {
      return {
        day: 7,
	}
  }
  

  
	}
</script>
<template>
  <p v-if="day === 1 || day === 7">
		Воскресение
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
