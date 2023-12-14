<script>
import PageHeader from "./components/PageHeader.vue";
import Carosello from "./components/Carosello.vue";
import NextMatch  from "./components/NextMatch.vue";
import Matchs from "./components/Matchs.vue";
import Players from "./components/Players.vue";
import Banner from "./components/Banner.vue";
import Clients from "./components/clients.vue"
import PageFooter from "./components/PageFooter.vue"


export default {
	components: {
    PageHeader,
	Carosello,
	NextMatch,
	Matchs,
	Players,
	Banner,
	Clients,
	PageFooter,
	
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
  <Banner />	
  <Clients /> 
  <PageFooter />
  	
  


</template>
<style lang="scss">
@use './Styles/general.scss'
</style>


<style scoped>
</style>
