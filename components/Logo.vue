<template>
  <div class="logo max-w-full w-40">
    <VueLALogo class="vue-logo w-full" />
  </div>
</template>
<script>
import VueLALogo from '@/assets/vuela-logo.svg'

export default {
  components: { VueLALogo }
}
</script>
<style>
.logo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
