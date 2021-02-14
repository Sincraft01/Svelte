<script>
	export let name;
</script>
<svelte:head>
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=raleway&display=swap" rel="stylesheet">
  <script
    type="module"
    src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.esm.js">

  </script>
  <script
    nomodule
    src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.js">

  </script>
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/@ionic/core/css/ionic.bundle.css" />

</svelte:head>

<ion-header>
<ion-toolbar color="medium">
<ion-grid>
<ion-row class="ion-justify-content-center">

<ion-img src="https://i.ibb.co/1RdX8rV/Illustration.png" margin="auto"></ion-img>
</ion-row>
</ion-grid>
</ion-toolbar>
</ion-header>

<main>
<form action="https://www.google.com/search" method='get'>
<ion-searchbar name='q' animated=true></ion-searchbar>
</form>

<ion-card class="font-effect-neon">
<ion-label value="Email"></ion-label>
<ion-input style="background-color:#333;" inset class="inset"></ion-input>
</ion-card>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
        margin: 0 auto;
        font-family:'raleway',sans-serif;
        font-size:30px;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>