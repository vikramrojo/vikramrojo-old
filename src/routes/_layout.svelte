<script>
  import Header from "../components/Header.svelte";

  export let segment;
</script>

<style>

</style>

<div class="layout">
  <Header {segment} />

  <main>
    <slot />
  </main>

  <footer class="cols">
    <span>&copy; {new Date().getFullYear()} Your Blog.</span>
  </footer>
</div>
