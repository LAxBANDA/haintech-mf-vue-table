<template>
  <head>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500&display=swap" rel="stylesheet">
  </head>

  <div class="container">
    <h2>Contactos</h2>
    <DynamicTable />
  </div>
</template>

<script lang="ts">
import DynamicTable from './DynamicTable.vue';

export default { 
  components: { DynamicTable },
}
</script>