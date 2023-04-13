<script lang="ts">
	import '../app.css';
	import Footer from '../libs/components/Footer.svelte';
	import Navbar from '../libs/components/Navbar.svelte';
</script>

<!-- Navbar -->
<!-- Change color here -->
<Navbar />

<slot />

<Footer />
<!-- Change footer -->
