<svelte:options tag="demo-widget-app" />

<script lang="ts">
  import DemoWidget from './lib/DemoWidget.svelte'
</script>

<main>
  <div class="card">
    <DemoWidget param_one="Demo Widget value set in App.svelte" />
  </div>

</main>