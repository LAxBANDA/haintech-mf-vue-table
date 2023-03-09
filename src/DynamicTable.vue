<template>
    <div class="d-flex flex-column table-container">
        <DynamicTablePrimaryHeader />
        <DynamicTablePrimaryContent />
    </div>
</template>

<script lang="ts">
import DynamicTablePrimaryHeader from './DynamicTable/PrimaryHeader.vue';
import DynamicTablePrimaryContent from './DynamicTable/PrimaryContent.vue';

export default { 
    components: { DynamicTablePrimaryHeader, DynamicTablePrimaryContent },
};
</script>

<style scoped>
</style>