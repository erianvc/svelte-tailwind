<main>
    <section>
        <h1>Svelte with TailwindCSS Template</h1>
        <p>
            Visit the
            <a
                target="_blank"
                rel="noopener noreferrer"
                href="https://svelte.dev/tutorial">svelte.dev</a>
            to learn how to build web applications with Svelte.
        </p>
    </section>
</main>

<style>
    main {
        @apply grid min-h-screen text-center place-items-center dark:bg-gray-800;
    }

    h1 {
        @apply text-4xl font-thin uppercase lg:text-6xl;
        color: #ff3e00;
    }

    p {
        @apply mx-auto my-4 leading-5 dark:text-white;
    }

    a {
        @apply underline;
        color: #ff3e00;
    }
</style>
