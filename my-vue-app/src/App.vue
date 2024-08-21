<script setup>
  import Header from './components/Header.vue';
  import Main from './components/Main.vue';
  import Footer from './components/Footer.vue';
</script>

<template>
  
  <div class="font-sans text-lg text-center">
    <div id="header" class="bg-blue-700">
      <Header></Header>
    </div>
    <div id="main">
      <Main></Main>
    </div>
    <div id="footer" class="bg-blue-700">
      <Footer></Footer>
    </div>
  </div>

</template>

<style scoped>
  #header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    /*background-color: #333;*/
    color: #fff;
    padding: 10px;
  } 

  #main {
    margin-top: 100px;
    margin-bottom: 100px;
    padding: 10px;
  }

  #footer {
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    /*background-color: #333;*/
    color: white;
    padding: 10px;
  }
</style>
