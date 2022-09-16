<template>
  <div>
    <header class="title">
      <NuxtLink class="logo" to="/">SHOPPING</NuxtLink>
    </header>
    <Nuxt />
    <!-- <router-view></router-view> -->
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
header {
  height: 60px;
  display: flex;
  align-items: center;
  padding: 0 0.5rem;
}
.logo {
  font-weight: 900;
}
.logo:visited {
  color: inherit;
}
</style>
