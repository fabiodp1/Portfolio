<template>
	<div id="app">
		<div id="nav_bar">
			<a class="logo">
				<img
					src="./assets/logo.png"
					alt="F logo"
					style="width:25px;height:30px;"
				/>
				<img
					src="./assets/logo_sub.png"
					alt="FDP | FrontEnd Developer"
					style="width:30px;height:auto;"
				/>
			</a>
			<nav class="en">
				//TODO fix icons behaviour
				<a href="#" rel="index" class="home-link">
					<i class="fas fa-home icon-home"></i>
				</a>
				<a href="#" rel="about" class="about-link">
					<i class="fas fa-user-alt"></i>
				</a>
				<a href="#" rel="skills" class="skills-link">
					<i class="fas fa-cog"></i>
				</a>
				<a href="#" rel="my-work" class="my-work-link">
					<i class="far fa-eye"></i>
				</a>
				<a href="#" rel="contact" class="contact-link">
					<i class="far fa-envelope"></i>
				</a>
			</nav>
		</div>
	</div>
</template>

<style>
body {
	background-color: #1d1d1d;
	user-select: none;
	font: 300 11px/1.4 "Helvetica Neue", Helvetica, Arial, sans-serif;
	color: #444;
}
div {
	display: block;
}
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

#nav_bar nav {
	display: block;
	text-align: center;
}
#nav_bar nav a {
	font-size: 20px;
	color: #909096;
	margin-bottom: 15px;
	display: block;
	line-height: 51px;
	height: 51px;
	position: relative;
	text-decoration: none;
}
#nav_bar nav a i {
	transition: all 0.3s ease-out;
}

.logo img {
	display: block;
	margin: 8px auto;
	width: 24px;
	height: auto;
}

#nav_bar nav a:hover {
	color: #fc0893;
}
a {
	background-color: transparent;
	text-decoration: none;
}
</style>
