<script>
  import { isOverlayOpen } from "../stores/OverlayStore";
  import Overlay from "../components/Overlay.svelte";
  import "../app.css";
</script>

{#if $isOverlayOpen}
  <Overlay>
    <p class="text-white text-4xl">this is the coolset overlay ever!</p>
	<p class="">super cool!</p>
  </Overlay>
{/if}
<main>
  <slot />
</main>
