<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/"> Nuxt Dojo </NuxtLink>
            </nav>
        </header>
        <div>
            <slot />
        </div>
    </div>

    <footer>
        <ul>
            <li><NuxtLink to="/" >Home</NuxtLink></li>
            <li><NuxtLink to="/about" >About</NuxtLink></li>
            <li><NuxtLink to="/products" >products</NuxtLink></li>
        </ul>
    </footer>
</template>

<style scoped>
.router-link-exact-active {
    color: #12b488
}
</style>
