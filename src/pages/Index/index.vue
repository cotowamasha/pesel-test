<template>
  <section class="index">
    <div class="container">
      <div class="index__box">
        <filter-block />
        <images />
      </div>
    </div>
  </section>
</template>

<script>
import FilterBlock from '@/components/page-parts/filter'
import Images from '@/components/page-parts/images'

export default {
  name: 'IndexPage',
  components: {
    Images,
    FilterBlock
  }
}
</script>
