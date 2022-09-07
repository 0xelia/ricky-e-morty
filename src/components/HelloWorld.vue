<template>
  <div class="hello">
    <h1 class="text-center pt-5">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import '../style/generals.scss';
  h1{
    font-weight: 700;
  }
</style>
