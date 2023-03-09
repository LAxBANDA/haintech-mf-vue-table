<template>
    <div>
        <h3>Filtros</h3>
        <CustomSelectList :items="filters" />
    </div>
</template>

<script>
import CustomSelectList from '../../CustomSelect/List.vue';
import dataFilters from '../../../data-filters';

export default {
    components: {
        CustomSelectList
    },
    data() { 
        return {
            filters: dataFilters
        }
    }
}
</script>