<script>
	export default {
		data() {
      return {
       
        items: ['a', 'b', 'c', 'd', 'e'],
	} 
},
methods: {
	removeItem: function(index) {
		this.items.splice(index, 1);
	}
}

  }
</script>
<template >
  <ul>
		<li v-for="(item, index) in items" :key="index">
			{{ item }}
			<button @click="removeItem(index)">remove</button>
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
