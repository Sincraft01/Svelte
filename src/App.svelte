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
<ion-toolbar>
<ion-grid>
<ion-row class="justify-content-center">

<ion-img class="ion-justify-content-center" src="https://i.ibb.co/1RdX8rV/Illustration.png" margin="auto"></ion-img>
</ion-toolbar>
</ion-header>
<main>
<ion-searchbar animated=true></ion-searchbar>
<ion-card class="font-effect-neon">
text
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