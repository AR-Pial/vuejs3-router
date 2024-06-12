<template>
	<h1>Jobs</h1>
  <div v-for="job in jobs" :key="job.id">
	{{ job.title }}
  </div>
</template>

<script>
export default {
	data(){
		return{
			jobs: [
				{id: 1, title: "Doing Jihad", details: "Jihad"},
				{id: 2, title: "Fighting for Country", details: "Country"},
				{id: 3, title: "Self control", details: "Control"},
			]
		}
	}
}
</script>

<style>

</style>