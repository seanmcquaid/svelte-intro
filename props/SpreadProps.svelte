<script>
  import ArraysObjects from "../reactivity/ArraysObjects.svelte";
  import Statements from "../reactivity/Statements.svelte";
  import DeclaringProps from "./DeclaringProps.svelte";
  import DefaultValues from "./DefaultValues.svelte";
  import Info from "./Info.svelte";
  import Nested from "./Nested.svelte";

  const pkg = {
    name: "svelte",
    version: 3,
    speed: "blazing",
    website: "https://svelte.dev",
  };
</script>

<Info {...pkg} />
