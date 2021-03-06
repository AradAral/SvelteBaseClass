<script lang="ts">
    import Button from "./Button.svelte";
    import type { SvelteComponent, SvelteComponentTyped } from 'svelte';

    let comp1: SvelteComponentTyped = Button;
    let comp2: SvelteComponent = Button;
</script>

<Button label="Submit" />
