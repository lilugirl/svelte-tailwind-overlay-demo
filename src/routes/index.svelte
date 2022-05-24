<script>
  import { isOverlayOpen } from "../stores/OverlayStore";
</script>

<h1 class="text-3xl font-bold underline">hello world</h1>
{$isOverlayOpen}
<button
  class="bg-purple-900 text-purple-100 p-4 rounded-md my-4"
  on:click={() => {
    isOverlayOpen.set(true);
  }}>Open Overlay</button
>
