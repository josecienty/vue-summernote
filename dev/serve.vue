<script>
import Vue from 'vue';
import VueSummernote from '@/vue-summernote.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueSummernote
  }
});
</script>

<template>
  <div id="app">
    <vue-summernote />
  </div>
</template>
