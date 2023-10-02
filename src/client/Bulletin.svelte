<script lang="ts">
  export let num = "";
</script>

<div class="container">
  <p class="bulletin-num">#{parseInt(num)}</p>
  <h2>Given words</h2>
</div>

<style>
  .container {
    display: flex;
    flex-direction: row;
    margin: 0.2em 0.1rem;
    padding: 5px 10px;
    border: 0.1em solid #91c9ad;
    border-radius: 5px;
    width: 30vw;
    height: 30vh;
  }

  .container:hover {
    background-color: #E0E2E1;
  }

  .bulletin-num {
    margin: 0;
    align-items: flex-start;
  }

  h2 {
    position: relative;
    margin-top: 0;
    top: 0;
    left: 1rem;
    font-size: 1.2em;
  }
</style>