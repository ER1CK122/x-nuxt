<template>
  <div>
    <ul class="bg-black text-zinc-50 font-bold p-10 mb-4">
      <li>
        <NuxtLink href="/login">Login</NuxtLink>
      </li>
      <li>
        <NuxtLink href="/register">Register</NuxtLink>
      </li>
    </ul>

    <slot />
  </div>
</template>

<script lang="ts" setup>

</script>

<style>

</style>