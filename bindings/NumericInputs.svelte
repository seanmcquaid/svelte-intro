<script>
  let a = 1;
  let b = 2;
</script>

<label>
  <input type="number" value={a} min="0" max="10" />
  <input type="range" value={a} min="0" max="10" />
</label>

<label>
  <input type="number" bind:value={b} min="0" max="10" />
  <input type="range" bind:value={b} min="0" max="10" />
</label>

<p>{a} + {b} = {a + b}</p>
