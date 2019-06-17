<template>
  <div>
    <b-table striped hover :items="items"></b-table>
  </div>
</template>

<script>
  export default {
      name : 'tableauOrdi',
      props : ['ordinateurs'],
    data() {
      return {
        items:
          this.props.ordinateurs
        
      }
    }
  }
</script>

<style>

</style>
