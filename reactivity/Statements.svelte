<script>
  let count = 0;
  $: doubled = count * 2;
  $: console.log(`the count is ${count}`);
  $: {
    console.log(`the count is ${count}`);
    alert(`I SAID THE COUNT IS ${count}`);
  }

  function handleClick() {
    count += 1;
  }
</script>

<p>{count} doubled is {doubled}</p>
<button on:click={handleClick}>
  Clicked
  {count}
  {count === 1 ? 'time' : 'times'}
</button>
