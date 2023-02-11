<script>
	export default {
		data() {
      return {
        arr: [],
	} 
},

  }
</script>
<template >
<input type="checkbox" v-model="arr" value="Python">
<p>{{ arr }}Python</p>
	<input type="checkbox" v-model="arr" value="CSS">
  <p>{{ arr }}CSS</p>
	<input type="checkbox" v-model="arr" value="html">
  <p>{{ arr }}html</p>
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
