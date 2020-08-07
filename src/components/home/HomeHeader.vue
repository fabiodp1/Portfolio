<template>
  <div class="container home-page">
    <span class="tags top-tags">&nbsp;&nbsp;&nbsp;&lt;body&gt;</span>
    <div class="text-zone">
      <h1>
        <span class="blast" style="opacity: 1;">H</span>
        <span class="blast" style="opacity: 1;">i</span>
        <span class="blast" style="opacity: 1;">,</span>
        <br />
        <span class="blast" style="opacity: 1;">I</span>
        <span class="blast" style="opacity: 1;">'</span>
        <span class="blast" style="opacity: 1;">m</span>&nbsp;
        <img
          src="@/assets/logoPOnB.png"
          alt="Fabio | Front End Developer"
          class="animation-logo"
        />
        <span class="blast" aria-hidden="true" style="opacity: 1;">a</span>
        <span class="blast" aria-hidden="true" style="opacity: 1;">b</span>
        <span class="blast" aria-hidden="true" style="opacity: 1;">i</span>
        <span class="blast" aria-hidden="true" style="opacity: 1;">o</span>
        <span class="blast" aria-hidden="true" style="opacity: 1;">,</span>
        <br />
        <span class="blast" aria-hidden="true" style="opacity: 1;">w</span>
        <span class="blast" aria-hidden="true" style="opacity: 1;">e</span>
        <span class="blast" aria-hidden="true" style="opacity: 1;">b</span>&nbsp;
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
      <h2>Front End Developer | Freelancer</h2>
    </div>
    <span class="tags">
      <!-- TODO - fix the spacing -->
      &nbsp;&nbsp;&nbsp;&lt;/body&gt;
      <br />&lt;/html&gt;
    </span>
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
.container {
  width: 100%;
  will-change: contents;
  height: 90%;
  min-height: 566px;
  position: absolute;
  top: 5%;
  margin: 0 auto;
  z-index: 1;
  transform-style: preserve-3d;
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
.home-page h1:before {
  content: "<h1>";
  font-family: "La Belle Aurore", cursive;
  color: #515152;
  font-size: 18px;
  position: absolute;
  margin-top: -40px;
  left: -15px;
}
.home-page h1:after {
  content: "<h1/>";
  font-family: "La Belle Aurore", cursive;
  color: #515152;
  font-size: 18px;
  position: absolute;
  margin-top: 18px;
  margin-left: 20px;
  animation: myanim2 1s 1.7s backwards;
}
.home-page h2 {
  color: #8d8d8d;
  margin-top: 20px;
  font-weight: 400;
  font-size: 11px;
  font-family: "Open Sans", sans-serif;
  letter-spacing: 3px;
}
.tags {
  color: #515152;
  position: absolute;
  bottom: 0;
  left: 80px;
  font-size: 18px;
  font-family: "La Belle Aurore", cursive;
}
.top-tags {
  bottom: auto;
  top: 0;
}
</style>
