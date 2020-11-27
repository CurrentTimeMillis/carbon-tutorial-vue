<template>
  <div id="app">
    <tutorial-header />
    <!--<router-view />-->
    <cv-content id="#main-content">
      <router-view />
    </cv-content>
  </div>
</template>
<script>
import { CvButton } from '@carbon/vue';
import TutorialHeader from "./components/TutorialHeader";
export default {
  name: 'app',
  components: {
    CvButton,
    TutorialHeader
  }
};
</script>
<style lang="scss">
@import './styles/carbon';
</style>
