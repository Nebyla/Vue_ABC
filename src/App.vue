<script>
	export default {
		data() {
      return {
		num1: 2,
    num2: 4,
	}
  },
  methods: {
	show: function(str) {
		alert(str*this.num1,str*this.num2);
	}
}
	}
</script>
<template>
  <button @click="show(num1)">Yunus Mustafaev</button>
	<button @click="show(num2)">Bottom 2</button>
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

  div
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
