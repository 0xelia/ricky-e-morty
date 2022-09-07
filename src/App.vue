<template>
  <div id="app">
    <HelloWorld :msg="title"></HelloWorld>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld
  },

  data(){
    return{
      title:'Ricky & Morty'
    }
  }
}
</script>

<style lang="scss">
  @import './style/generals.scss';

</style>
