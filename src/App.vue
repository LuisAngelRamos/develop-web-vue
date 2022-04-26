<template>
  <div class="main">
    <HeaderMain />
    <BodyContent />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeaderMain from './components/HeaderMain.vue';
import BodyContent from './components/BodyContent.vue';

export default defineComponent({
  name: 'App',
  components: {
    HeaderMain,
    BodyContent
  },
});
</script>