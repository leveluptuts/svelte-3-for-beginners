<script>
  import GlobalVars from "./GlobalVars.svelte";

  export let name;
</script>

<style>
  h1 {
    font-size: 4rem;
    color: var(--teal);
  }
</style>

<GlobalVars />
<h1>Hello {name}!</h1>
