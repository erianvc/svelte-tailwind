<script>
  export let name
</script>

<main>
  <section>
    <h1>¡Hola {name}!</h1>
    <p>
      Visita el
      <a href="https://svelte.dev/tutorial">tutorial de Svelte</a>
      para aprender a construir aplicaciones con Svelte.
    </p>
  </section>
</main>

<style>
  main {
    @apply grid h-screen max-w-lg p-4 mx-auto my-0 text-center place-items-center;
  }

  h1 {
    @apply mb-4 text-6xl font-thin text-red-500 uppercase;
  }
</style>
