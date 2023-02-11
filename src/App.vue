<script>
	export default {
		data() {
      return {
        selected: 'Не указан',
	} 
},

  }
</script>
<template >
  <P>в каком городе ты живешь</P>
<select v-model="selected">
		<option>Симферополь</option>
		<option>Севастополь</option>
		<option>Москва</option>
	</select>
	
	<p>{{ selected }}</p>
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
