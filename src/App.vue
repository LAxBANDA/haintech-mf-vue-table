<template>
  <head>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500&display=swap" rel="stylesheet">
  </head>

  <div class="container">
    <h2>Contactos</h2>
    <DynamicTableBase />
  </div>
</template>

<script lang="ts">

import DynamicTableBase from './components/DynamicTable/Base.vue';

export default { 
  components: { DynamicTableBase },
}
</script>