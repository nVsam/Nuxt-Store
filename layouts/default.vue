<template>
    <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4 flex justify-between">
            <nuxt-link to="/" class="font-bold">Nuxt Store</nuxt-link>
            <ul class="flex gap-4">
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">Sobre</NuxtLink></li>
                <li><NuxtLink to="/products" class="btn">Produtos</NuxtLink></li>
            </ul>
        </nav>
    </header>

    <div class="container mx-auto p-4">
        <slot />
    </div>
</template>

<style scoped>
    .router-link-exact-active {
    }
</style>