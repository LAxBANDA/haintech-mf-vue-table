<template>
    <select :name="name" :id="id" :placeholder="placeholder">
        <option selected>
            {{ placeholder }}
        </option>
    <option v-if="options && options.length" v-for="option of options" :value="option.value">{{ option.name }}</option>
    </select>
</template>

<script>
export default {
    props: ['name', 'id', 'placeholder', 'options']
}
</script>