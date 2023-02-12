<script>
import User from './components/User.vue'
	export default {
    
		components: {
			User
		},
    data() {
	return {
		users: [
			{
				id: 1,
				name: 'Yunus',
				surn: 'Mustafaev'
			},
			{
				id: 2,
				name: 'name2',
				surn: 'surn2'
			},
			{
				id: 3,
				name: 'name3',
				surn: 'surn3'
			},
		],
	}
},
    methods: {
	remove(id) {
		this.users = this.users.filter((user) => {
			return user.id !== id;
		})
	}
}
}
</script>
<template >
	<User
		v-for   ="user in users"
		:id     ="user.id"
		:name   ="user.name"
		:surn   ="user.surn"
		@remove ="remove"
		:key    ="user.id"/>
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
