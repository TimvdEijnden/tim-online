<template>
  <div :class="$route.name">
    This website is a <em>remaster</em> of my old website on AngelFire created in <strong>1999</strong>.<br/>
    The <strong>authentic design</strong> remains the same only the techniques and content is different.<br/>
    It contained <strong>flash</strong> animations, which are re-created in CSS and SVG.<br/>
    The page used a <strong>frameset</strong>, now it's build with Vue.js.

    <HomeAnimation/>
  </div>
</template>

<script>
import HomeAnimation from '@/components/HomeAnimation.vue';

export default {
  components: {
    HomeAnimation
  }
}
</script>
