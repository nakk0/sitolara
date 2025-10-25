<script>
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';
    import pfp from '$lib/photos/lara_front1.png' 
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>


  <!-- Header -->
  <header class="bg-gray-900 text-white py-10 shadow-md">
  <div class="flex flex-col items-center justify-center sm:flex-row sm:space-x-6">
    <!-- Immagine profilo -->
    <img src="{pfp}" alt="Foto profilo di Lara" 
         class="w-28 h-28 rounded-full object-cover border-4 border-white shadow-md mb-4 sm:mb-0">

    <!-- Testo -->
    <div class="text-center sm:text-left">
      <h1 class="text-3xl font-bold">Lara Fiordelisi</h1>
      <p class="text-gray-300 mt-2">Appassionata di lingue e recitazione</p>
    </div>
  </div>
</header>



{@render children?.()}
