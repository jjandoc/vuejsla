<template>
  <div
    class="min-h-screen flex justify-center items-center text-center mx-auto"
  >
    <div class="p-4">
      <Logo />
      <header class="my-8">
        <h1 class="text-2xl md:text-3xl lg:text-5xl">
          Vue.js Monthly Meetups in Los Angeles
        </h1>
        <h2 class="text-lg">Every 2nd Tuesday of the Month</h2>
      </header>
      <div
        class="flex flex-col md:flex-row max-w-xs md:max-w-none justify-center md:-mx-2 m-auto"
      >
        <BaseButton
          tag="a"
          href="https://www.meetup.com/VuejsLA/"
          target="_blank"
          class="mb-2 md:mx-2"
        >
          Upcoming Events
        </BaseButton>
        <BaseButton
          tag="a"
          variant="secondary"
          href="https://www.youtube.com/channel/UCl6IhXxuQrGlQ8Iwf8395Vg"
          target="_blank"
          class="mb-2 md:mx-2"
        >
          Past Talks
        </BaseButton>
        <BaseButton
          tag="a"
          variant="secondary"
          href="https://join.slack.com/t/vuejsla/shared_invite/zt-dc78dwhj-H6itbCHLNjYtkc8~PrU59g"
          target="_blank"
          class="mb-2 md:mx-2"
        >
          Slack
        </BaseButton>
      </div>
    </div>
  </div>
</template>

<script>
import BaseButton from '@/components/BaseButton'
import Logo from '@/components/Logo.vue'

export default {
  components: { BaseButton, Logo }
}
</script>
