<template>
  <div id="page" class="en">
    <home-header></home-header>
	<home-icon></home-icon>
  </div>
</template>

<script lang="ts">
import HomeHeader from "@/components/home/HomeHeader.vue";
import HomeIcon from '@/components/home/HomeIcon.vue';

export default {
  name: "Home",
  components: {
	HomeHeader,
	HomeIcon,
  },
};
</script>
<style>
div {
  display: block;
}
#page {
  width: 100%;
  height: 100%;
  position: absolute;
}
</style>
