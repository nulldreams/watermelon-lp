<template>
  <body>
    <div class="section">
      <div class="container">
        <div class="tile is-ancestor">
          <div class="tile is-vertical is-8">
            <div class="tile">
              <div class="tile is-parent is-vertical">
                <article class="tile is-child notification is-dark">
                  <p class="title">Vertical...</p>
                  <p class="subtitle">Top tile</p>
                </article>
                <article class="tile is-child notification is-warning">
                  <p class="title">...tiles</p>
                  <p class="subtitle">Bottom tile</p>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child notification is-info">
                  <p class="title">Middle tile</p>
                  <p class="subtitle">With an image</p>
                  <figure class="image is-4by3">
                    <img
                      src="data:image/png;base64,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"
                    />
                  </figure>
                </article>
              </div>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child notification is-danger">
                <p class="title">Wide tile</p>
                <p class="subtitle">Aligned with the right tile</p>
                <div class="content">
                  <!-- Content -->
                </div>
              </article>
            </div>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child notification is-success">
              <div class="content">
                <p class="title">Tall tile</p>
                <p class="subtitle">With even more content</p>
                <div class="content">
                  <!-- Content -->
                </div>
              </div>
            </article>
          </div>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
