
<template>
  <div class=" social-media flex-hv-center social-media" >
    <facebook :url="url" scale="3"></facebook>
    <twitter :url="url" title="Play Harmony, play more, earn more!! Check out the link -" scale="3"></twitter>
  </div>
</template>
<script>
import {
  Facebook,
  Twitter

} from "vue-socialmedia-share";
export default {
  name: "SocialMedia",
  components: {
    Facebook,
    Twitter

  },
  data() {
    return {
      url: "https://puzzle.harmony.one"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}

.social-media > span {
  padding: 0.5em;
}

</style>

