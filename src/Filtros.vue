<template>
    <div>
        <h3>Filtros</h3>
        <CustomSelect id="name" name="name" placeholder="Nombre">
    
        </CustomSelect>
    </div>
</template>

<script>
import CustomSelect from './CustomSelect.vue';

export default {
    components: {
        CustomSelect
    }
}
</script>