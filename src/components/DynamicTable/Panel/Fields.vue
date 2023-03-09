<template>
    <div>
        <h3>Campos</h3>
        <CustomCheckboxList :items="checkboxs" />
    </div>
</template>

<script>
import CustomCheckboxList from '../../CustomCheckbox/List.vue';
import dataFields from '../../../data-fields';

export default {
    components: {
        CustomCheckboxList
    },
    data () {
        return {
            checkboxs: dataFields
        }
    }
}
</script>