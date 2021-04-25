<script>
  export let hover = true;
</script>

<main>
  <div
    class:text-green-500={hover}
  >
    This text should be green.
  </div>
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
