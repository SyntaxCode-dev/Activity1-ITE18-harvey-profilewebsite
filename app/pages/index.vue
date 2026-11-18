<!-- eslint-disable vue/multi-word-component-names -->
 import _imports_0 from '/public/images/profilepic.jpeg'
<template>
  <section class="rounded-3xl border border-blue-100 bg-white p-8 shadow-sm sm:p-12">
    <div class="flex flex-col items-center gap-8 text-center sm:flex-row sm:text-left">
      <div
        class="flex size-36 shrink-0 items-center justify-center rounded-full bg-blue-100 text-4xl font-bold text-blue-700 ring-8 ring-blue-50"
        role="img"
        aria-label="Profile avatar placeholder"
      >
        <img
          src="/images/profilepic.jpeg"
          alt="Profile avatar"
          class="h-full w-full rounded-full object-cover"
        />
      </div>

      <div>
        <p class="font-semibold text-blue-700">
          Welcome to my personal website
        </p>
        <h1 class="mt-2 text-4xl font-bold tracking-tight text-slate-900 sm:text-5xl">
          Hi, I'm Harvey Kent B. Tanilon
        </h1>
        <p class="mt-4 max-w-xl text-lg leading-8 text-slate-600">
          I am eager to learn and explore new technologies, and always looking for ways
           to improve my skills and knowledge. 
           I am passionate about web development and programming, 
           and enjoy working on projects that challenge me to think 
           creatively and solve problems.
        </p>
        <NuxtLink
          to="/profile"
          class="mt-6 inline-flex rounded-lg bg-blue-600 px-5 py-3 font-semibold text-white transition hover:bg-blue-700"
        >
          Get to know me
        </NuxtLink>
      </div>
    </div>
  </section>
</template>
