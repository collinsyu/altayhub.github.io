<template>
    <section>
        <li>
            <NuxtLink to="/about">About</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/test/1">Post 1</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/test/2">Post 2</NuxtLink>
        </li>
        <p>test/{{ route.params.id }}</p>
    </section>
</template>

<script setup lang="ts">
const route = useRoute()

// When accessing /posts/1, route.params.id will be 1
console.log(route.params)
</script>
