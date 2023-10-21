<script lang="ts">
  import Bulletin from "../Bulletin.svelte";
</script>

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

<style>
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