<template>
    <div class="d-flex">
        <div class="col-2 d-flex- flex-column">
            <Filtros />
            <Campos />
        </div>
        <div class="col-10">
            <TablePreHeader />
            <Table></Table>
        </div>
    </div>
</template>

<script lang="ts">
import Filtros from '../Filtros.vue';
import Campos from '../Campos.vue';
import Table from '../Table.vue';
import TablePreHeader from '../DynamicTable/TablePreHeader.vue'

export default {
    components: {
        Filtros,
        Campos,
        Table,
        TablePreHeader
    }
}
</script>