<svelte:head>
	<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Lexend+Mega&display=swap" rel="stylesheet">
	<link rel="preconnect" href="https://fonts.gstatic.com" />
	<link
		href="https://fonts.googleapis.com/css2?family=raleway&display=swap"
		rel="stylesheet"
	/>
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
		href="https://cdn.jsdelivr.net/npm/@ionic/core/css/ionic.bundle.css"
	/>
</svelte:head>

<ion-header >
	<ion-toolbar color='#333'>
		<ion-grid>
			<ion-row class="ion-justify-content-center">
				<ion-col size='2'>
					<ion-img
					src="https://i.ibb.co/1RdX8rV/Illustration.png"
					margin="auto"
					/>
					
				</ion-col>
				<ion-col size-lg><form action="https://www.google.com/search" method="get">
					<ion-searchbar
					color="light"
					
					search-Icon="logo-google"
					placeholder="Google"
					name="q"
					class="ion-margin-auto"
						animated="true"
					/>
				</form>
			</ion-col>
			</ion-row>
		</ion-grid>
	</ion-toolbar>
</ion-header>

<main>
	<h1>
		BLACKMAIL 
		
	</h1>
	<ion-card class="font-effect-neon">
		
		<ion-label font-size="24" position="stacked">Email</ion-label>
		<ion-input style="background-color:#333;" inset class="inset" />
		<Button>button</Button>
	</ion-card>
</main>

<style>
	main {
		text-align: center;
		padding: 0px;
		max-width: 95%;
		margin: auto;
		font-family: "Indie Flower", sans-serif;
		font-size: 40px;
	}

	h1 {
		font-family: 'Lexend Mega', sans-serif;
		color: rgb(23,27,31);
		text-shadow:2px 2px 4px black;
		text-transform: uppercase;
		font-size: .8em;
		font-weight: 500;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
