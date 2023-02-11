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
 <p style="{font-weight: bold;}">Yunus Mustafev</p>
 <p>2</p>
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
    border: '1px solid green'

    
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
