<script>
  import NavBar from './client/NavBar.svelte';
  import Bulletin from './client/Bulletin.svelte';
</script>

<main class="main">
  <div class="nav">
    <NavBar />
  </div>
  <div class="bulletin">
    <Bulletin num="1" />
    <Bulletin num="2" />
    <Bulletin num="3" />
    <Bulletin num="4" />
    <Bulletin num="5" />
    <Bulletin num="6" />
    <Bulletin num="7" />
    <Bulletin num="8" />
    <Bulletin num="9" />
    <Bulletin num="10" />
    <Bulletin num="11" />
    <Bulletin num="12" />
    <Bulletin num="13" />
  </div>
</main>

<style>
  .main {
    z-index: 1;
  }

  .nav {
    display: flex;
    position: fixed;
    width: 100%;
    height: 5rem;
    z-index: 3;
    background-color: white;
    border-bottom: 0.1rem #ABB8C3 solid;
  }

  .bulletin {
    display: grid;
    justify-content: center;
    align-items: center;
    grid-template-columns: repeat(3, 1fr);
    margin-top: 0.5rem;
    position: absolute;
    top: 5rem;
    left: 0;
    width: 100%;
  }
</style>
