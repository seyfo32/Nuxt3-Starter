<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.
             Repudiandae eius explicabo, suscipit tenetur quibusdam labore!</p>

    </div>
</template>

<script setup>
const { id }=useRoute().params

definePageMeta({
    layout: 'products'
});

</script>

<style scoped>

</style>