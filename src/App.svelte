<script>
  import { onMount } from 'svelte';
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
  import app from './main'
</script>

<main>
  <h1>DashPal</h1>
  <div class="menu">
    <body>
      <h2>Google Calendar API</h2>

      <button id="authorize_button">Authorize</button>
      <button id="signout_button">Sign Out</button>
  
    </body>
  </div>
</main>

<style>

</style>
