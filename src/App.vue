<script>
import PageHeader from "./components/PageHeader.vue";
import Carosello from "./components/Carosello.vue";
import NextMatch  from "./components/NextMatch.vue";
import Matchs from "./components/Matchs.vue";
import Players from "./components/Players.vue"

export default {
	components: {
    PageHeader,
	Carosello,
	NextMatch,
	Matchs,
	Players,
},

	
	methods: {
		
	}
}
</script>

<template>
  <PageHeader />
  <Carosello />
  <NextMatch />
  <Matchs />
  <Players />


</template>
<style lang="scss">
@use './Styles/general.scss'
</style>


<style scoped>
</style>
