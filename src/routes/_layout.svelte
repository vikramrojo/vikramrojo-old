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
        <a href="https://dribbble.com/atav1k">Github</a>
        <a href="https://www.linkedin.com/in/atav1k/">LinkedIn</a>
        <a href="https://medium.com/@atav1k/">Medium</a>
        <a href="https://twitter.com/atav1k">Twitter</a>
        <a href="/">&copy; {new Date().getFullYear()} Vikram B Rojo.</a>
      </div>
    </nav>
  </footer>
</div>
