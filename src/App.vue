<script>
	export default {
		data() {
      return {
       isDisable: false,
       isDisabled: true,
       selected: 'Расблокировать',
	} 
},

  }
</script>
<template >
  <select v-model="selected">
		<option v-bind:disabled="isDisable">Разблокировать</option>
		<option v-bind:disabled="isDisabled">Блокировать</option>

	</select>
  <button v-bind:disabled="isDisable">btn</button>
 <button v-bind:disabled="isDisabled">btn</button>
	
	
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
