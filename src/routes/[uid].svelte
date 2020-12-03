<script context="module">
  export async function preload(page) {
    const { uid } = page.params;
    return { uid };
  }
</script>

<script>
  export let uid;
</script>

<main>
  <h1>{JSON.stringify(uid)}</h1>
</main>
