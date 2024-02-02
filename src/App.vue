<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="flex flex-col py-2 px-5 gap-2">
    <nav class="">
      <RouterLink to="/" class="flex items-center justify-center cursor-pointer">
        <img alt="Laracamp Logo" class="w-20" src="@/assets/icons/laracamp-svgrepo-com.svg" />
        <h1 class="text-xl">Laracamp</h1>
      </RouterLink>
    </nav>
  </header>

  <main>
    <RouterView />
  </main>
</template>