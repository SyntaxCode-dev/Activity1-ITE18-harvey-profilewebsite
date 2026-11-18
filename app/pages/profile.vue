<!-- eslint-disable vue/multi-word-component-names -->
 
<template>
  <div>
    <section class="mb-8">
      <p class="font-semibold text-blue-700">
        A little more about me
      </p>
      <h1 class="mt-2 text-4xl font-bold tracking-tight text-slate-900">
        My Profile
      </h1>
      
    </section>

    <div class="grid gap-5 md:grid-cols-2">
      <section class="rounded-2xl border border-blue-100 bg-white p-6 shadow-sm">
        <h2 class="text-xl font-semibold text-blue-800">
          Personal Information
        </h2>
        <dl class="mt-4 space-y-3 text-slate-600">
          <div>
            <dt class="font-medium text-slate-800">
              Full name
            </dt>
            <dd>Harvey Kent B. Tanilon</dd>
          </div>
          <div>
            <dt class="font-medium text-slate-800">
              Email
            </dt>
            <dd>harveykenttanilon@gmail.com</dd>
          </div>
          <div>
            <dt class="font-medium text-slate-800">
              Location
            </dt>
            <dd>Tungao, Butuan City, Philippines</dd>
          </div>
        </dl>
      </section>

      <section class="rounded-2xl border border-blue-100 bg-white p-6 shadow-sm">
        <h2 class="text-xl font-semibold text-blue-800">
          Education
        </h2>
        <p class="mt-4 font-medium text-slate-800">
          Caraga State University - Main Campus
        </p>
        <p class="mt-1 text-slate-600">
          4th Year Student, Bachelor of Science in Information Technology
        </p>
        <p class="mt-2 text-sm text-slate-500">
          2023- present
        </p>

        <p class="mt-4 font-medium text-slate-800">
          Tungao National High School
        </p>
        <p class="mt-1 text-slate-600">
          Senior High School, General Academic Strand
        </p>
        <p class="mt-2 text-sm text-slate-500">
          2018-2023
        </p>

      </section>

      <section class="rounded-2xl border border-blue-100 bg-white p-6 shadow-sm">
        <h2 class="text-xl font-semibold text-blue-800">
          Skills &amp; Interests
        </h2>
        <p class="mt-4 leading-7 text-slate-600">
          Web Development
        </p>
        <p class="mt-4 leading-7 text-slate-600">
          Basic Video editing
        </p>
        <p class="mt-4 leading-7 text-slate-600">
          Coding and Programming
        </p>
      </section>

      <section class="rounded-2xl border border-blue-100 bg-white p-6 shadow-sm">
        <h2 class="text-xl font-semibold text-blue-800">
          Hobbies
        </h2>
        <p class="mt-4 leading-7 text-slate-600">
          Solving puzzles and brain teasers(rubik's cube, sudoku, chess, etc.)
        </p>
        <p class="mt-4 leading-7 text-slate-600">
          Playing video games
        </p>
        <p class="mt-4 leading-7 text-slate-600">
          Watching anime
        </p>
      </section>
    </div>

    <NuxtLink
      to="/"
      class="mt-8 inline-flex rounded-lg bg-blue-600 px-5 py-3 font-semibold text-white transition hover:bg-blue-700"
    >
      Back to Home
    </NuxtLink>
  </div>
</template>
