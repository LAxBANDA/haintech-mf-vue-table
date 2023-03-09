<template>
    <div>
        <h3>Campos</h3>
        <CustomCheckbox v-for="checkbox of checkboxs" :key="checkbox" :name="checkbox" />
    </div>
</template>

<script>
import CustomCheckbox from './CustomCheckbox.vue'
export default {
    data () {
        return {
            checkboxs: [
                'Nombre',
                'Apellido'
            ]
        }
    },
    components: {
        CustomCheckbox
    }
}
</script>