<template>
  <div id="app">

    <!-- header -->
    <Header/>

    <!-- main -->
    <main>

      <!-- banner nero -->
      <Main/>
      <!-- nav -->
      <Nav/>
      <!-- Banner -->
      <Banner/> 

    </main>

    <Footer/>

  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Main from '@/components/Main.vue';
import Nav from '@/components/Nav.vue';
import Banner from '@/components/Banner.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Nav,
    Banner,
    Footer,

  }
}
</script>

<style lang="scss">

@import '@/style/utility.scss';
@import '@/style/variables.scss';

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Oswald', sans-serif;
}

.container {
  width: 70%;
  margin: 0 auto;
}

</style>
