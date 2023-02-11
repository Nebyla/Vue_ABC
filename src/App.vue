<script>
	export default {
		data() {
      return {
        choice: '',
	} 
},

  }
</script>
<template >
<input name="radio" type="radio" v-model="choice" value="v1">
<p>Python {{ choice }}</p>
	<input name="radio" type="radio" v-model="choice" value="v2">
  <p>CSS {{ choice }}</p>
	<input name="radio" type="radio" v-model="choice" value="v3">
  <p>HTML {{ choice }}</p>
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
ul
{
  text-transform:uppercase;
}
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
