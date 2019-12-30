<script>
  import Header from "../components/Header.svelte";

  export let segment;
</script>

<style>

</style>

<div class="layout">
  <Header {segment} />

  <main class="padY4">
    <slot />
  </main>

  <footer class="cols">
    <div class="col">
      <span>&copy; {new Date().getFullYear()} Your Blog.</span>
    </div>
  </footer>
</div>
