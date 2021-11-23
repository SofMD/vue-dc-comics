<template>
  <div id="app">

    <!-- header -->
    <Header/>

    <!-- main -->
    <main>

      <!-- banner nero -->
      <Banner/>

      <!-- nav -->
      <Nav/>

      <!-- hero -->
      <Hero/>
      

    </main>

    <Footer/>

  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '@/components/Banner.vue';
import Nav from '@/components/Nav.vue';
import Hero from '@/components/Hero.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Banner,
    Nav,
    Hero,
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
  font-family: 'Roboto', sans-serif;
}

.container {
  width: 70%;
  margin: 0 auto;
}

</style>
