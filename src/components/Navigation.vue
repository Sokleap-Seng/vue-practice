<template>
    <nav class="h-16 flex items-center shadow-md justify-between">
        <div id="nav-item" class="flex items-center m-auto gap-12">
            <navigation-item v-for="item in navItems" :key="item.label" :item="item">
            </navigation-item>
        </div>
    </nav>
</template>

<script setup>
import { ref } from 'vue';
import NavigationItem from '../components/NavigationItem.vue'

const navItems = ref([
    { label: "Home", path: "/" },
    { label: "About", path: "/about"},
    { label: "Contact Us", path: "/contact"},
   
])

</script>

<style scoped></style>


