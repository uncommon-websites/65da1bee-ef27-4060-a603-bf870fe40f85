<script>
  import Image from './Image.svelte';
</script>

<section class="relative h-screen w-full overflow-hidden bg-stone-900 text-white">
  <div class="absolute inset-0">
    <Image 
      src="/generated/image-stunning-abstract-floral-arrangement-wit-1767414085411-0.webp" 
      alt="Abstract Floral Arrangement" 
      className="opacity-80"
    />
    <div class="absolute inset-0 bg-black/20"></div>
  </div>
  
  <div class="relative z-10 flex h-full items-center justify-center">
    <h1 class="font-display text-5xl md:text-7xl lg:text-9xl font-bold uppercase tracking-tighter text-center px-4">
      Bloom & Hue
    </h1>
  </div>
  
  <!-- Blurry foreground element simulation -->
  <div class="absolute -bottom-20 -left-20 w-1/2 h-1/2 bg-gray-300/20 blur-3xl rounded-full pointer-events-none"></div>
</section>
