<template>
  <main>
    <HeaderLayout />
    <RouterView />
    <FooterLayout />
  </main>
</template>

<script>
import HeaderLayout from './layouts/HeaderLayouts/HeaderLayout.vue';
import FooterLayout from './layouts/FooterLayouts/FooterLayout.vue';

export default {
  components: {
    HeaderLayout,
    FooterLayout
  }
}
</script>

