<script>
  import Home from '../src/Home.svelte';
  import Connexion from '../src/Connexion.svelte';
  import NotFound from '../src/NotFound.svelte';
  import Router from 'svelte-spa-router';

 
</script>

<Router routes={{
  '/connexion': Connexion,
  '/': Home,
  '*': NotFound
}}
/>
<hr>



