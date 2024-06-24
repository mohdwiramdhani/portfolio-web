<script setup>
import { Head, Link } from '@inertiajs/vue3';
import Frontend from '@/Layouts/Frontend.vue';
import Hero from '@/Components/Frontend/Hero.vue';
import Promote from '@/Components/Frontend/Promote.vue';
import About from '@/Components/Frontend/About.vue';
</script>

<template>
    <Head title="Welcome to" />
    <Frontend>
        <!--Hero Primary-->
        <Hero />
        <!--Promote-->
        <Promote />
        <!--About-->
        <About />
        <!--Abcd efgh-->
        <!--Abcd efgh-->
    </Frontend>
</template>
