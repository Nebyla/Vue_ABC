<script>
	export default {
		data() {
      return {
        obj: {
          isValid: true,
		      isDisabled: true,
		},
	} 
}

  
	}

</script>
<template >
 <p :class="{active: isValid, error: isDisabled}">Yunus Mustafev</p>
 <p :class="obj">2</p>
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

  p {
    color: red;
    display: block;
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
