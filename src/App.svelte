<script>
  import logo from './assets/svelte.png'
  import Counter from './lib/Counter.svelte'
</script>

<main class="bg-gray-300 h-full flex flex-col justify-center items-center">
  <img src={logo} alt="Svelte Logo" />
  <h1 class="py-3">Hello world!</h1>
  <Counter />

  <p class="pb-3 pt-3">
    Visit <a class="border-b-4 border-purple-500" href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte
    apps.
  </p>

  <p class="pb-3">
    Check out <a href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
    the officially supported framework, also powered by Vite!
  </p>
  <p class="words">Windi CSS is added!</p>
</main>

<style>
  .words {
    @apply font-bold border-b-4 border-red-500
  }
</style>