<script>
  // import TextInput from "./TextInput.svelte";
  import Title from "./Title.svelte";
  export let titleName = '';
</script>

<div class="card">
  <Title title={titleName} />
</div>

<style>
  .card {
    margin: 0 10px;
    padding: 5px 10px;
    border: 0.1em solid magenta;
    border-radius: 5px;
  }

  .card:hover {
    background-color: #E0E2E1;
  }
</style>