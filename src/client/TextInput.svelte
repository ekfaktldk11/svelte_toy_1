<script lang="ts">
  export let text = '';

  function inputHandler (event): void {
    text = event.target.value;
  }
</script>

<div>
  <input class="text-input" type="text" value={text} on:input={() => {inputHandler}}/>
</div>

<style>
  input {
    font-size: 0.8em;
  }
</style>