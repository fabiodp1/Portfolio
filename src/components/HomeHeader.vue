<template>
	<div class="home-page">
		<div class="text-zone">
			<h1>
				<span class="blast" style="opacity: 1;">H</span>
				<span class="blast" style="opacity: 1;">i</span>
				<span class="blast" style="opacity: 1;">,</span>
				<br />
				<span class="blast" style="opacity: 1;">I</span>
				<span class="blast" style="opacity: 1;">'</span>
				<span class="blast" style="opacity: 1;">m</span>
				<img
					src="@/assets/logo.png"
					alt="Fabio | Front End Developer"
					class="animation-logo"
				/> // TODO modificare logo
				<span class="blast" aria-hidden="true" style="opacity: 1;">a</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">b</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">i</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">o</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">,</span>
				<br />
				<span class="blast" aria-hidden="true" style="opacity: 1;">W</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">e</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">b</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">d</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">e</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">v</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">e</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">l</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">o</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">p</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">e</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">r</span>
				<span class="blast" aria-hidden="true" style="opacity: 1;">.</span>
			</h1>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style scoped>
.home-page .text-zone {
	position: absolute;
	left: 10%;
	top: 50%;
	transform: translateY(-50%);
	width: 40%;
	max-height: 90%;
}
h1 {
	font-size: 60px !important;
	display: block;
	margin-block-start: 0.67em;
	margin-block-end: 0.67em;
	margin-inline-start: 0px;
	margin-inline-end: 0px;
}
.home-page h1 {
	color: #fff;
	line-height: 53px;
	margin: 0;
	font-family: "Assistant", sans-serif;
	font-weight: 400;
}
.home-page .blast {
	display: inline-block;
	transition: all 0.3s ease-out;
}
.home-page h1 img {
	position: relative;
	margin-left: 0.5em;
	top: -11px;
	opacity: 0;
	width: 32px;
	height: auto;
	border: 0;
	max-width: 100%;
	vertical-align: middle;
}
.animation-logo {
	animation: animation2 1s linear both;
	opacity: 1 !important;
}
</style>
