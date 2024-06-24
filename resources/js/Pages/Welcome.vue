<script setup>
import { Head, Link } from '@inertiajs/vue3';
import Frontend from '@/Layouts/Frontend.vue';
import Hero from '@/Components/Frontend/Hero.vue';
import Promote from '@/Components/Frontend/Promote.vue';
import About from '@/Components/Frontend/About.vue';
import Skills from '@/Components/Frontend/Skills.vue';
import Portfolio from '@/Components/Frontend/Portfolio.vue';

defineProps({
  skills: Object,
  projects: Object,
});
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
        <!-- Skills tail-100 -->
        <Skills :skills="skills" />
        <!-- Portfolio primary -->
        <Portfolio :skills="skills" :projects="projects" />
        <!--Abcd efgh-->
    </Frontend>
</template>
