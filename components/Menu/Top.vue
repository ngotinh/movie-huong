<script lang="ts" setup></script>
<template>
  <nav class="bg-gray-900 text-white py-5 border-b border-gray-700">
    <div
      class="container flex flex-col sm:flex-row justify-center gap-3 sm:gap-0 sm:justify-between items-center"
    >
      <NuxtLink to="#" class="text-2xl font-medium">Home</NuxtLink>
      <ul class="nav">
        <li>
          <NuxtLink to="#">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="#">News</NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style>
ul.nav {
  @apply flex gap-5 items-center justify-end;
}
ul.nav > li > a {
  @apply text-gray-300 hover:text-gray-50;
}
ul.nav > li > a.router-link-active {
  @apply text-primary-400;
}
</style>
