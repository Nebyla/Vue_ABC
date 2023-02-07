<script>
	export default {
		data() {
      return {
		text: '15',
	}
  },
  methods: {
	show: function() {
		let text = this.cape(this.text);
		alert(text);
	},
	cape: function(str) {
		return str[0].toUpperCase() + str.slice(1);
	}
}
	}
</script>
<template>
  <button @mouseover="show">Yunus Mustafaev</button>
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
