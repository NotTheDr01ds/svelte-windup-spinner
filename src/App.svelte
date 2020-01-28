<script>
  import Spinner from "./windup-spinner.svelte"
</script>

<main>
  <div class="placeholder">
    <Spinner></Spinner>
  </div>
</main>

<style>
  .placeholder {
    height: 100px;
    width: 100px;
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    margin: auto;
  }
</style>
