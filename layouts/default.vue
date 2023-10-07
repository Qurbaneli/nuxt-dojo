<template>

    <div>
        <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink to="/"> Nuxt Dojo</NuxtLink>
        <ul class="flex gap-4">
                <li><NuxtLink class="font-bold" to="/"> Home</NuxtLink></li>
                <li><NuxtLink to="/about"> About</NuxtLink></li>
                <li><NuxtLink class="btn" to="/products"> Products</NuxtLink></li>
                <li><NuxtLink class="btn" to="/products/abc"> Products abc</NuxtLink></li>
            </ul>

        </nav>
    </header>
    <!-- Output the page content  -->

    <div class="container mx-auto p-4">   
    <slot/>
    </div>

    </div>
    
</template>

<style>
.router-link-exact-active{
    color:#12b488;
}
</style>