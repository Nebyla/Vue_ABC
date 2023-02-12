<script>
	export default {
		data() {
      return {
        
	} 
},
  }
</script>
<template >
		<p>Работа с компонентами в Vue
Если мы посмотрим на какой-нибудь сайт, то можем выделить на нем некоторые блоки: хедер, контент, сайдбар, футер.

При создании сайта на Vue мы также можем использовать такие независимые блоки. Они позволят нам лучше организовать наш код и упростят его дальнейшую поддержку.

Во Vue такие блоки называются компонентами. В крупных приложениях разделение на компоненты становится обязательным условием для сохранения управляемости процесса разработки

Компоненты рекомендовано размещать в папке components. Каждый компонент в отдельном файле в виде модуля ES6.</p>
	
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
