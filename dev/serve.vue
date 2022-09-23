<script lang="ts">
import { defineComponent } from 'vue';
import NjhhMap from '@/njhh-map.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    NjhhMap
  }
});
</script>

<template>
  <div id="app">
    <njhh-map />
  </div>
</template>
