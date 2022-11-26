<script>
  import Counter from "./lib/Counter.svelte";
  import Project from "./lib/Project.svelte";
</script>

<main class="">
  <h1
    class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white"
  >
    Cezary Kujath
  </h1>
  <div class="py-10">
    <div class="flex space-x-10 items-center">
      <Project />
      <Project />
      <Project />
    </div>
  </div>

  <div class="card">
    <Counter />
  </div>

  <p class="text-neutral-400 py-4">WEB DEV WEAPON</p>
</main>
