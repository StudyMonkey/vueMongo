<template>
  <div class="home">
    <nav-header />
    <nav-bread>
      <span>Goods</span>
    </nav-bread>
    vue init page
    <nav-footer />
  </div>
</template>

<script>
import NavHeader from '@/components/Header'
import NavBread from '@/components/Bread'
import NavFooter from '@/components/Footer'

export default {
  name: 'home',
  components: {
    NavHeader,
    NavBread,
    NavFooter
  }
}
</script>
