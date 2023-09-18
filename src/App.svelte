<script>
  import Card from './client/Card.svelte';
</script>

<main>
  <div class="cardContainer">
    <Card titleName="Home" />
    <Card titleName="MyProfile" />
    <Card titleName="LeaderBoard" />
  </div>
</main>

<style>
  .cardContainer {
    display: flex;
    flex-direction: row;
    position: absolute;
    top: 1em;
    right: 1em;
  }
</style>
