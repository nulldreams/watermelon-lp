<template>
  <div>
    <Navbar></Navbar>
    <Header></Header>
    <!-- <Card></Card> -->
    <Content></Content>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from '~/components/landing-page/Header'
import Navbar from '~/components/landing-page/Navbar'
import Card from '~/components/landing-page/Card'
import Footer from '~/components/landing-page/Footer'
import Content from '~/components/landing-page/Content'

export default {
  name: 'HomePage',

  components: {
    Navbar,
    Header,
    Card,
    Footer,
    Content,
  },
}
</script>
