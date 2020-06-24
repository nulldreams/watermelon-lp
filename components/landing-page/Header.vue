<template>
  <section class="hero pink-melon is-fullheight">
    <!-- Hero head: will stick at the top -->
    <div class="hero-head">
      <header class="navbar">
        <div class="container"></div>
      </header>
    </div>

    <!-- Hero content: will be in the middle -->
    <div class="hero-body">
      <div class="container has-text-centered">
        <div class="columns is-vcentered">
          <div class="column is-5">
            <figure class="image">
              <img
                src="https://cdn.iconscout.com/icon/free/png-512/watermelon-fruit-emoj-symbol-food-30691.png"
                alt="Description"
              />
            </figure>
          </div>
          <div class="column is-6 is-offset-1">
            <h1 class="title is-2">
              <span class="has-text-danger-custom">Water</span
              ><span class="has-text-success-custom">melon</span>
            </h1>
            <h2 class="subtitle is-4">
              Let this cover page describe a product or service.
            </h2>
            <br />
            <p class="has-text-centered">
              <a class="button is-medium is-danger-custom">
                Learn more
              </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Header',
}
</script>
