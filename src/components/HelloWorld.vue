<template>
  <div class="hello">
    <h2>Loading anim</h2>

    <vcl-facebook></vcl-facebook>
    <br /><br />
    <vcl-facebook></vcl-facebook>
    <br /><br />
    <vcl-facebook></vcl-facebook>
    <br /><br />
    <!-- <vcl-instagram></vcl-instagram> -->
  </div>
</template>

<script>
import { VclFacebook, VclInstagram } from "vue-content-loading";
export default {
  components: {
    VclFacebook,
    VclInstagram
  },
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
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
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
