<script>
import PageHeader from "./components/PageHeader.vue";
import Carosello from "./components/Carosello.vue";
import NextMatch  from "./components/NextMatch.vue";

export default {
	components: {
    PageHeader,
	Carosello,
	NextMatch,
},

	
	methods: {
		
	}
}
</script>

<template>
  <PageHeader />
  <Carosello />
  <NextMatch />


</template>
<style lang="scss">
@use './Styles/general.scss'
</style>


<style scoped>
</style>
