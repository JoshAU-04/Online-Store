<script lang="ts">
    import Navbar from './Navbar.svelte';
    let { children } = $props();
</script>

<Navbar />

{@render children()}
