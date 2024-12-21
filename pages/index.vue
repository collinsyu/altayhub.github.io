<template>
    <div class="main-container">
        <h1>Welcome to the homepage</h1>
        <AppAlert>
            This is an auto-imported component
        </AppAlert>
        <NuxtLink to="/about">About</NuxtLink>
        <NuxtLink to="/test/1">Test</NuxtLink>
    </div>
</template>

<style lang="scss">
.main-container{
    background-color: $primary-color;
}
</style>
    
