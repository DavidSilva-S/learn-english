<script>
  import "../app.pcss";
  import { Button } from "$lib/components/ui/button";
  import { Input } from "$lib/components/ui/input"
</script>

<slot/>

<div>
  <h1 class="text-3xl font-bold underline">
    Hey handsome man type your name below
  </h1>
  <Input type="email" placeholder="email" class="max-w-xs" />
  <Button variant="destructive">Button</Button>
</div>
<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>
