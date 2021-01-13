<script>
  let count = 0;

  function handleClick() {
    count += 1;
  }
</script>

<style>
</style>

<button on:click={handleClick}>
  Clicked
  {count}
  {count === 1 ? 'time' : 'times'}
</button>
