<script>
	export default {
		data() {
      return {
        num: 0,
		res: 0
	} 
},
methods: {
	calc: function() {
		this.res = Math.sqrt(this.num);
	}
}
	}

</script>
<template >
<p>{{ res }}</p>
	<input v-model="num">
	<button v-on:click="calc">work</button>
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
