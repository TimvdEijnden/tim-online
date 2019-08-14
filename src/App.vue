<template>
  <div id="app">
    <top-animation/>
    <div class="content">
      <page-title/>
      <router-view/>
    </div>
    <bottom-navigation/>
  </div>
</template>

<script>
// @ is an alias to /src
import TopAnimation from '@/components/TopAnimation.vue';
import BottomNavigation from '@/components/BottomNavigation.vue';
import PageTitle from '@/components/PageTitle.vue';

export default {
  name: 'app',
  components: {
    TopAnimation,
    BottomNavigation,
    PageTitle
  }
}
</script>


<style>
html, body, #app {
  height: 100%;
  margin: 0;
}
#app {
  display: flex;
  flex-direction: column;
}
.content {
  flex: 1 0 auto;
  margin: 0 20px;
  font: 14px Verdana;
}

@font-face {
    font-family: 'OCR-B-web';
    src:url('assets/fonts/ocr-b/OCR-B-regular-web.eot');
    src:url('assets/fonts/ocr-b/OCR-B-regular-web.eot?#iefix') format('embedded-opentype'),
		url('assets/fonts/ocr-b/OCR-B-regular-web.svg#ocrbregular') format('svg'),
		url('assets/fonts/ocr-b/OCR-B-regular-web.woff') format('woff'),
		url('assets/fonts/ocr-b/OCR-B-regular-web.ttf') format('truetype');
    font-weight: 400;
    font-style: normal;
}
</style>
