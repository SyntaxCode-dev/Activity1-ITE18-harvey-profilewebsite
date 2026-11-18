<template>
  <header class="mb-10 flex flex-col gap-4 border-b border-blue-100 pb-5 sm:flex-row sm:items-center sm:justify-between">
    <NuxtLink to="/" class="text-lg font-bold tracking-tight text-slate-900">
      My Personal Website
    </NuxtLink>
    <nav aria-label="Main navigation" class="flex gap-5">
      <NuxtLink
        to="/"
        class="font-medium text-blue-700 transition hover:text-blue-900"
      >
        Home
      </NuxtLink>
      <NuxtLink
        to="/profile"
        class="font-medium text-blue-700 transition hover:text-blue-900"
      >
        Profile
      </NuxtLink>
    </nav>
  </header>
</template>
