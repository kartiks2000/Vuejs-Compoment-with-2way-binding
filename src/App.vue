<template>
  <div>
    <myheader></myheader>
      <myinfo v-for="i in 4"></myinfo>
    <myfooter></myfooter>
  </div>
</template>

<script>
import Header from './Components/Header';
import Footer from './Components/Footer';
import Info from './Components/Info';
export default {
  components:{
    myheader : Header,
    "myfooter" : Footer,
    myinfo : Info
  }
}
</script>

<style>

</style>
