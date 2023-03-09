<template>
    <div class="d-flex flex-column table-container">
        <DynamicTablePrimaryHeader />
        <DynamicTablePrimaryContent />
    </div>
</template>

<script lang="ts">
import DynamicTablePrimaryHeader from './PrimaryHeader.vue';
import DynamicTablePrimaryContent from './PrimaryContent.vue';

export default { 
    components: { DynamicTablePrimaryHeader, DynamicTablePrimaryContent },
};
</script>

<style scoped>
</style>