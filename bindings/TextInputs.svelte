<script>
  let name = 'world';
</script>

<input value={name} />

<h1>Hello {name}!</h1>
<input bind:value={name} />
