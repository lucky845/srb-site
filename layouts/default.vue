<template>
  <div>
    <!-- 公共头部 -->
    <app-header />
    <!-- 页面占位符 -->
    <Nuxt />
    <!-- 公共尾部 -->
    <app-footer />
  </div>
</template>
<script>
import '~/assets/css/common.css'
import AppHeader from '~/components/AppHeader'
import AppFooter from '~/components/AppFooter'

export default {
  components: {
    AppHeader,
    AppFooter,
  },
}
</script>
