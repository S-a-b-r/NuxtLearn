<template>
    <header>
      <nav>
        <ul>
          <li><NuxtLink to="/">Main</NuxtLink></li>
        </ul>
      </nav>
    </header>
    
    <div>
        <slot />
    </div>

    <footer>
        <ul>
            <li><NuxtLink to="/">Main</NuxtLink></li>
            <li><NuxtLink to="/about">About</NuxtLink></li>
            <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
    </footer>
</template>

<style>
    .router-link-exact-active {
        color: #12b488;
    }
</style>