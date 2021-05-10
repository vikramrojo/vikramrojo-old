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

  <footer class="wid100">
    <nav class="nav cols">
      <div class="navLeft col">
        <a href="https://github.com/vikramrojo">Github</a>
        <a href="https://www.linkedin.com/in/vikramrojo/">LinkedIn</a>
        <a href="https://medium.com/@vikramrojo/">Medium</a>
        <a href="https://twitter.com/vikramrojo">Twitter</a>
        <a href="/">&copy; {new Date().getFullYear()}</a>
      </div>
    </nav>
  </footer>
</div>
