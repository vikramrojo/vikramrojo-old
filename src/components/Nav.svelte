<script>
  export let segment;
</script>

<style>

</style>

<nav class="nav cols">
  <div class="col navLeft">
    <a class={segment === undefined ? 'selected' : ''} href=".">home</a>
    <a class={segment === 'about' ? 'selected' : ''} href="about">about</a>
    <a rel="prefetch" class={segment === 'blog' ? 'selected' : ''} href="blog">
      blog
    </a>
  </div>
</nav>
