<template>
	<div id="app">
		<div id="nav_bar">
			<a class="logo" href="#">
				<img
					src="/public/favicon.png"
					alt="F logo"
					style="width:48px;height:48px;"
				/>
			</a>
			<router-link to="/">Home</router-link>
			<router-link to="/about">About</router-link>
		</div>
		<router-view />
	</div>
</template>

<style>
#nav_bar {
	background: #181818;
	width: 60px;
	height: 100%;
	position: fixed;
	top: 0;
	left: 0;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
	z-index: 3;
	min-height: 500px;
}

.logo img {
	display: block;
	margin: 8px auto;
	width: 24px;
	height: auto;
}

body {
	background-color: #1d1d1d;
}
</style>
