<script>
  import { create_slot } from "svelte/internal";
</script>

<div class="hero">
  <div class="banner">
    <h1>foam, shave, grow</h1>
    <p>Embrace your choices - we do</p>
    <slot>
      <!-- optional fallback -->
    </slot>
  </div>
</div>
