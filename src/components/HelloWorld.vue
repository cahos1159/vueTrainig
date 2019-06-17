<template>
  <div class="hello">
    <navbar/>
    <div>
      <contentB/>
    </div>
  </div>
</template>

<script>
import navbar from "./header/navbar";
import contentB from './content/contentB';

export default {
  name: "cdb",
  components: {
    navbar,
    contentB,
  },
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
  color: #f5aa0a;
}
</style>
