<template>
  <div class="hello">
    <m-button label="Default button" />
  </div>
</template>

<script>
import MButton from "@mozaic-ds/vue/src/components/button/MButton";

export default {
  name: "HelloWorld",
  components: {
    MButton,
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
h3 {
  margin: 40px 0 0;
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
