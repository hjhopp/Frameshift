<script>
    import { fade } from "svelte/transition";
</script>

<style>
    div {
        display: flex;
        flex-direction: column;
        align-items: center;

        position: absolute;
    }
    h1 {
        font-family: VtksHunt;
        font-size: 3.5em;
        letter-spacing: 0.25em;

        margin-bottom: 0;
    }

    h2 {
        align-self: flex-end;
        font-family: Tox;

        margin: 0;
    }
</style>

<div data-testid="home" transition:fade>
    <h1>Frameshift</h1>
    <h2>a dream journal</h2>
</div>
