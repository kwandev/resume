<template>
  <section class="section">
    <h2 class='section__title'>
      <slot name="section_title"></slot>
    </h2>

    <slot></slot>
  </section>
</template>

<script>
export default {
  name: 'sections'
}
</script>

<style lang="scss" scoped>
.section { margin-bottom: 1rem; }
</style>
