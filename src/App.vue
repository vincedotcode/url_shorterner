<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800&display=swap');
* {
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
  margin: 0;
  padding: 0;
}
body{
  background-color: #047857;
}
</style>


<template>


  <Main />
  
  <Footer />
</template>




<script>
import Footer from './components/Footer.vue';
import Main from './components/Main.vue';
export default {
  name: 'URL Shortener',
  components: {
    Footer,
    Main,
  },
  data() {
    
  }
}
</script>