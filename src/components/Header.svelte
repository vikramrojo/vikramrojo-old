<script>
  import Logo from "./Logo.svelte";
  import Nav from "./Nav.svelte";

  export let segment;
</script>

<style>

</style>

<header class="cols">
  <Nav {segment} />
</header>
