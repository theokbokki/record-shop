<script>
    import { inertia } from "@inertiajs/svelte";

    let { children } = $props();
</script>

<main>
    {@render children()}
</main>
