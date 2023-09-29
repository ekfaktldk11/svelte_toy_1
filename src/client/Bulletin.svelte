<script lang="ts">
  import Title from "./Title.svelte";

  export let num = "";
</script>

<div class="main-container">
  <p class="bulletin-num">#{parseInt(num)}</p>
  <div class="title-container">
    <h2>Given words</h2>
  </div>
</div>

<style>
  .main-container {
    display: inherit;
    flex-direction: row;
    margin: 0.4em;
    padding: 5px 10px;
    border: 0.1em solid magenta;
    border-radius: 5px;
    width: 20em;
    height: 10em;
  }

  .main-container:hover {
    background-color: #E0E2E1;
  }

  .bulletin-num {
    margin: 0;
    align-items: flex-start;
  }

  h2 {
    position: relative;
    top: 0;
    font-size: 1.5em;
  }
</style>