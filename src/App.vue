<script>
	export default {
		data() {
      return {
        selected: 'Не указан',
		options: ['Понедельник', 'Вторник', 'Среда','Четверг','Пятница','Суббота','Воскресение'],
	} 
},

  }
</script>
<template >
  <p>Выберите день недели</p>
<select v-model="selected">
		<option v-for="option in options">{{ option }}</option>
    
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
