<template>
  <div class="container">
    <Table></Table>
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue'
import Table from './Table.vue';

  export default defineComponent({ components: { Table } });
</script>
