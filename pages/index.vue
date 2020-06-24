<template>
  <div>
    <Navbar></Navbar>
    <Header></Header>
    <Card></Card>
    <section class="hero is-primary">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Primary title
          </h1>
          <h2 class="subtitle">
            Primary subtitle
          </h2>
        </div>
      </div>
    </section>
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>Bulma</strong> by
          <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is
          licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The
          website content is licensed
          <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/"
            >CC BY NC SA 4.0</a
          >.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
import Header from '~/components/landing-page/Header'
import Navbar from '~/components/landing-page/Navbar'
import Card from '~/components/landing-page/Card'

export default {
  name: 'HomePage',

  components: {
    Navbar,
    Header,
    Card,
  },
}
</script>
