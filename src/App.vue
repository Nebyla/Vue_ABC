<script>
	export default {
		data() {
      return {
        obj: {
          hidden: true,
		},
	} 
  },
  methods: {
	setDone: function() {
		this.obj.hidden = false ;
	}
},
  Cata:{
    sickret: function() {
		this.obj.hidden = true ;
	}
  }

  
	}

</script>
<template >
 <p :class="obj">Yunus Mustafev</p>
 <p :class="obj">2</p>
 <button @click="setDone">hide</button>
 
 <button @click="sickret">smoke</button>
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

  p.hidden {
    color: red;
	display: none;
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
