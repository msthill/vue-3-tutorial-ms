<template>
    <ul>
        <li v-for="student in list" :key="student.id">
            {{ student.name }}
        </li>
    </ul>
</template>

<script setup>
defineProps(['list'])
</script>

<style scoped>

</style>