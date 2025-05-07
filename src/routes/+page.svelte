<script>
    import Navbar from '$lib/components/navbar.svelte'
    import Footer from '$lib/components/footer.svelte'
    import {setLocale} from "$lib/paraglide/runtime.js";
    import {m} from '$lib/paraglide/messages.js'
</script>
<Navbar></Navbar>
<div class="max-w-screen-xl items-center mx-auto">
    <h1>HOLA</h1>
    <h2>HOLA</h2>
    <h3>HOLA</h3>

    <p>{m.intento()}</p>
    <button onclick={() => setLocale('en')}> English</button>
    <button onclick={() => setLocale('es')}>Español</button>
</div>
<Footer></Footer>
