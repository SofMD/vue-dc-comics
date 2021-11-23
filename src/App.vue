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

    </main>

  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '@/components/Banner.vue';
import Nav from '@/components/Nav.vue';

export default {
  name: 'App',
  components: {
    Header,
    Banner,
    Nav,

  }
}
</script>

<style lang="scss">

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
