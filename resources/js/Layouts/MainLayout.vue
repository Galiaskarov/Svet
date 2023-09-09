<script setup>
import Header from "@/Components/Header.vue";
</script>

<template>
    <div class="min-h-screen bg-[url('/resources/js/Components/bg.svg')] bg-no-repeat bg-bottom bg-fixed bg-gray-50">
        <Header/>
        <slot />
    </div>
</template>

<style scoped>

</style>
