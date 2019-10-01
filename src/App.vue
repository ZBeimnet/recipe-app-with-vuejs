<template>
  <v-app>
    <Header/>
    <v-content>
      <Home/>
    </v-content>
    <Footer/>
  </v-app>
</template>

<script>
import Home from './components/Home';
import Header from './components/Header';
import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
    Home,
    Header,
    Footer
  },
  data: () => ({
    //
  }),
};
</script>

