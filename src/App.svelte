<script>
  export let name;
</script>

<main>
  <h1 class="flex justify-center italic font-bold">Hello {name}!</h1>
  <p class="flex justify-center">
    Visit the <a href="https://svelte.dev/tutorial">&nbsp;Svelte tutorial</a>
    &nbsp; to learn how to build Svelte apps, and to Design the App with
    <a href="https://tailwindcss.com/docs">&nbsp;Tailwind css Tutorials</a>
  </p>
</main>

<style global lang="postcss">
  /* only apply purgecss on utilities, per Tailwind docs */
  /* purgecss start ignore */
  @tailwind base;
  @tailwind components;
  /* purgecss end ignore */

  @tailwind utilities;
</style>
