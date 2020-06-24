<template>
  <div class="container">
    <div class="column">
      <div class="card-custom notification is-success is-hidden-mobile"></div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.card-custom {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 60vh;
  width: 100%;
  border-radius: 28px;
  box-shadow: 0 14px 90px rgba(26, 87, 120, 0.26);
  margin-top: -16vh;
}
</style>
