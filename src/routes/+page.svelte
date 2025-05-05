<script>
import {setLocale} from "$lib/paraglide/runtime.js";
import {m} from '$lib/paraglide/messages.js'
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<p>{m.hello_world({name: "JESUS"})}</p>
<button onclick={() => setLocale('en')}> English</button>
<button onclick={() => setLocale('es')}>Español</button>