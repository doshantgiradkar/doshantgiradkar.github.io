<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import Navbar from '../components/Navbar.svelte';

    let title = "Doshant Giradkar";
    let description = "A personal portfolio website"
	let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    <meta name="description" content={description} />
    <!-- <link rel="icon" href="/favicon.ico" type="image/x-icon" /> -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous" />
    <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
        integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw=="
        crossorigin="anonymous"
        referrerpolicy="no-referrer"
    />
    <link
        href="https://fonts.googleapis.com/css2?family=Parisienne&family=Poppins:wght@300;400;700&display=swap"
        rel="stylesheet"
    />
    <title>{title}</title>
</svelte:head>
<Navbar />
{@render children()}
