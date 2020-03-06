<template>
  <div class="home">
    <Header/>
    <Cards/>
    <Footer class="footer"/>
  </div>
</template>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'
import Cards from '../components/Cards'

export default {
    components: {
      Header,
      Footer,
      Cards
    }
};
</script>
