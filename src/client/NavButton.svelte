<script lang="ts">
  // import TextInput from "./TextInput.svelte";
  import Title from "./Title.svelte";
  export let titleName = '';
</script>

<div class="nav-button">
  <Title title={titleName} />
</div>

<style>
  .nav-button {
    margin: 0 10px;
    padding: 5px 10px;
    border: 0.1em solid #91c9ad;
    border-radius: 5px;
  }

  .nav-button:hover {
    background-color: #E0E2E1;
  }
</style>