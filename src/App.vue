<script>
	export default {
		data() {
      return {
        text: 'xxx',
        text1: 'zzz'
	}
  },
  methods: {
		change: function() {
		this.text = 'yyy';
    this.text1 = 'zzz';
	}
}
	}
</script>
<template>
  {{ text }}
  {{ text1 }}
	<button @click="change">Yunus Mustafaev</button>
  <button @click="change">2</button>
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
