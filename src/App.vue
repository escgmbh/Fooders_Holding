<script setup>
import Header from '@/components/Design/Default/Header.vue';
</script>

<template>
    <div class="w-screen h-screen">
        <div class="ml-4 md:ml-6 flex justify-items-end"></div>
        <Header />
        <router-view></router-view>
    </div>
</template>
