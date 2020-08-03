<template>
	<div>
		<app-nav-bar></app-nav-bar>
	</div>
</template>

<script>
import AppNavBar from "./components/NavBar.vue";

export default {
	components: {
		AppNavBar,
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
