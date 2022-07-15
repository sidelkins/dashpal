<script>
  import { gapiLoaded, gisLoaded, handleAuthClick, handleSignoutClick } from '../gapi';
</script>

<svelte:head>
  <script async defer src="https://apis.google.com/js/api.js" on:load={gapiLoaded}></script>
  <script async defer src="https://accounts.google.com/gsi/client" on:load={gisLoaded}></script>
</svelte:head>

<main>
  <button id="authorize_button">Authorize</button>
  <button id="signout_button">Sign Out</button>
</main>