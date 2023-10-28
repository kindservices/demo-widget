<svelte:options tag="my-counter" />

<script lang="ts">
  let count: number = 0
  const increment = () => {
    count += 2
  }
</script>

<button on:click={increment}>
  demo widet counter: {count}
</button>
