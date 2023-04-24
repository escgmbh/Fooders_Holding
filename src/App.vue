<script setup>
import Header from '@/components/Design/Default/Header.vue';
</script>

<template>
    <div class="">

        <div class="flex flex-col mx-auto max-w-7xl min-h-screen items-center justify-start bg-baseoffwhite shadow-xl ">

            <Header />
            <router-view></router-view>
        </div>
    </div>
</template>
