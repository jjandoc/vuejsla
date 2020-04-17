<template>
  <component
    :is="tag"
    class="border border-solid inline-block no-underline rounded py-2 px-8 hover:text-white"
    :class="{
      'border-green hover:bg-green': variant === 'primary',
      'border-grey hover:bg-grey': variant === 'secondary'
    }"
  >
    <slot />
  </component>
</template>

<script>
export default {
  props: {
    tag: {
      type: String,
      default: 'button'
    },
    variant: {
      type: String,
      default: 'primary'
    }
  }
}
</script>
