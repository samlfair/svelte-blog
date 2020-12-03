<script>
  import Header from "$components/Header.svelte";
  import Footer from "$components/Footer.svelte";
</script>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
      Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }
</style>

<main>
  <Header />
  <slot />
  <Footer />
</main>
