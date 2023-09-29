<script>
  import Card from './client/Card.svelte';
  import Bulletin from './client/Bulletin.svelte';
</script>

<main class="main">
  <div class="nav">
    <div class="cardContainer">
      <Card titleName="Home" />
      <Card titleName="MyProfile" />
      <Card titleName="LeaderBoard" />
    </div>
  </div>
  <div class="bulletin">
    <Bulletin num="1" />
    <Bulletin num="2" />
    <Bulletin num="3" />
    <Bulletin num="4" />
    <Bulletin num="5" />
  </div>
</main>

<style>
  /* navigaion bar 구현해야함 */
  .main {
    position: absolute;
    top: 5em;
    left: 2em;
  }

  .cardContainer {
    display: flex;
    flex-direction: row;
    position: absolute;
    top: 1em;
    right: 1em;
    position: fixed;
    background-color: white;
  }

  .bulletin {
    display: flex;
    flex-direction: column;
  }
</style>
