<script>
  export let hover = true;
</script>

<main>
  <p>This box should be green:</p>
  <div
    class="{$$restProps.class} w-40 h-40 bg-red-500"
    class:bg-green-500={hover}
  />
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
