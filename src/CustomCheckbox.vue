<template>
    <div>
        <input type="checkbox" :name="name" :id="name" :placeholder="name">
        <label for="Nombre">{{ name }}</label>
    </div>
</template>

<script>
export default {
    props: ['name']
}
</script>