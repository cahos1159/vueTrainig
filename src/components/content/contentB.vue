<template>
  <div id="cont">
    <b-jumbotron  id="jumb" lead="Computer DataBase">
      <tableauOrdi :ordinateurs="ordinateurs"/>
    </b-jumbotron>
  </div>
</template>

<script>
import tableauOrdi from "./tableauOrdi";

export default {
  name: "contentB",
  components: {
    tableauOrdi
  },
  props: {},
  data(){
    return{
    ordinateurs : [{model:'ESSAI',prix:'300'}],
    }
  }
};
</script>

<style>

#cont{
  margin: 3%;
  box-shadow: 10px 5px 5px grey;
}

#jumb{
  background-color: #e2f0f3a4;
}
</style>
