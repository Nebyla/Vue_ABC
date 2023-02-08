<script>
	export default {
		data() {
      return {
        isAuth: true,
	}
  },
  methods: {
    toggle: function() {
	this.isAuth = !this.isAuth;
}
}
  

  
	}
</script>
<template>
  <button @click="toggle">toggle</button>
  <div v-if="isAuth">
		<p>Yunus Mustafaev</p>
		<p>+++</p>
	</div>
	
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

  p
  {
    color:red
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
