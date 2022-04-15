<script>
  import { onMount } from 'svelte';
  import Nav from '../src/Nav.svelte';
  import Footer from '../src/Footer.svelte';
  import Section from '../src/Section.svelte';
  import NotFound from '../src/NotFound.svelte';
  import Connexion from '../src/Connexion.svelte';
  let photos = [];

	onMount(async () => {
		const res = await fetch(`http://localhost:8000/users/`);
		photos = await res.json();
    console.log(photos)
	});
   const pkg = {
    titresite: 'Telegram Genius'
  };
</script>
<Nav {...pkg} />
<Section/>
<Footer/>
{#each photos as photo}
	<p>{photo}</p>
{/each}
<p>WSH</p>

