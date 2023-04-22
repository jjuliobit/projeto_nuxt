<template>
<div>
  <AppHeader />
  <AppContent />
  <AppFooter />
</div>
</template>

<script>

import AppHeader from '~/components/AppHeader.vue';
import AppContent from '~/components/AppContent.vue';
import AppFooter from '~/components/AppFooter.vue';


export default {
  layouts: {
    name: 'Default',
  },
  components: {
    AppHeader,
    AppContent,
    AppFooter
  }
}
</script>


