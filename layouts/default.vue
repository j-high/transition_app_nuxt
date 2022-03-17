<template>
  <div>
    <Nav />
    <Nuxt />
  </div>
</template>
<style>
.page-enter-active,
.page-leave-active {
  transition: all .7s ease;
}

.page-enter,
.page-leave-active {
  opacity: 0;
}
</style>