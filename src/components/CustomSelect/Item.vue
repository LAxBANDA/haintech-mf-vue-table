<template>
    <select :name="name" :id="id" :placeholder="placeholder">
        <option selected>
            {{ placeholder }}
        </option>
        <option v-for="(option, index) of options" :key="index" :value="option.value">{{ option.name }}</option>
    </select>
</template>

<script>
export default {
    props: {
        name: String,
        id: String,
        placeholder: String,
        options: {
            type: Array,
            default: []
        }
    }
}
</script>