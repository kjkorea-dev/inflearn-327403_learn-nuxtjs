<template>
  <div class="container">
    <h1 class="list-title">카트 페이지</h1>
    <CartList></CartList>
    <div class="extra-panel">
      <button>Buy</button>
    </div>
  </div>
</template>

<script>
import CartList from '../components/CartList.vue'
export default {
  components: { CartList },
}
</script>

<style scoped>
.container {
  margin: 2rem 10rem;
}
.extra-panel {
  text-align: right;
  padding: 0.2rem 0;
}
</style>
