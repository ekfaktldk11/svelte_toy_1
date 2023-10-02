<script>
  import NavButton from "./NavButton.svelte";
</script>

<div class="btn-container">
  <NavButton titleName="Home" />
  <NavButton titleName="MyProfile" />
  <NavButton titleName="LeaderBoard" />
</div>

<style>
  .btn-container {
    display: flex;
    flex-direction: row;
    position: absolute;
    top: 1em;
    right: 1em;
    position: fixed;
    background-color: white;
  }
</style>