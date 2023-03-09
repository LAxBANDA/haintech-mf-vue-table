<template>
    <div>
        <input type="checkbox" :name="name" :id="name" :placeholder="name">
        <label for="Nombre">{{ name }}</label>
    </div>
</template>

<script lang="ts">
export default {
    props: ['name']
}
</script>