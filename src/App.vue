<template>
	<div>
		<app-nav-bar></app-nav-bar>
		<app-home></app-home>
	</div>
</template>

<script>
import AppNavBar from "./components/NavBar.vue";
import AppHome from '@/views/Home.vue'

export default {
	components: {
		AppNavBar,
		AppHome,
	},
};
</script>

<style>
body {
	background-color: #1d1d1d;
	user-select: none;
	font: 300 11px/1.4 "Helvetica Neue", Helvetica, Arial, sans-serif;
	color: #444;
}
</style>
