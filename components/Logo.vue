<template>
  <div class="logo relative max-w-full w-40">
    <VueLogo class="vue-logo w-full" />
    <DodgersLogo class="dodgers-logo absolute w-7/12 right-0 bottom-0" />
  </div>
</template>
<script>
import DodgersLogo from '@/assets/los-angeles-dodgers.svg'
import VueLogo from '@/assets/vue-logo.svg'

export default {
  components: { DodgersLogo, VueLogo }
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

.dodgers-logo {
  color: rgb(52, 73, 94);
  margin-right: -15%;
}
</style>
