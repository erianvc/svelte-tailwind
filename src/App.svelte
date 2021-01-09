<script>
    export let world
</script>

<main>
    <section>
        <h1>¡Hola {world}!</h1>
        <p>
            Visita el
            <a
                target="_blank"
                rel="noopener noreferrer"
                href="https://svelte.dev/tutorial">tutorial de Svelte</a>
            para aprender a construir aplicaciones con Svelte.
        </p>
    </section>
</main>

<style>
    main {
        @apply grid w-screen h-screen p-4 mx-auto my-0 text-center place-items-center dark:bg-gray-800 dark:text-white;
    }

    h1 {
        @apply max-w-lg mb-4 text-6xl font-thin text-red-500 uppercase;
    }

    a {
        @apply text-red-600 underline;
    }
</style>
