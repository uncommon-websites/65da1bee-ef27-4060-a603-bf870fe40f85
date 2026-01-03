<script>
  import Image from './Image.svelte';
</script>

<footer class="w-full bg-black text-white pt-20 pb-10">
  <div class="container mx-auto px-4">
    <!-- Call to Action -->
    <div class="mb-20">
      <h2 class="text-3xl md:text-5xl font-bold uppercase leading-tight mb-10 max-w-3xl">
        Your celebration deserves unforgettable florals. Let's create magic together.
      </h2>
      
      <a href="mailto:amber@bloomandhue.co" class="bg-white text-black w-40 h-40 flex flex-col items-center justify-center hover:bg-gray-200 transition-colors">
        <span class="text-sm font-bold uppercase mb-2">Let's</span>
        <span class="text-2xl font-bold uppercase">Connect</span>
      </a>
    </div>

    <!-- Recent Work Section -->
    <div class="border-t border-gray-800 pt-10 mb-20">
      <div class="flex justify-between items-end mb-8">
        <h3 class="text-xl font-bold uppercase">Recent Work</h3>
        <span class="text-sm text-gray-500">Long Beach, CA</span>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="/generated/image-elegant-wedding-tablescape-with-pink-and-1767414106241-8.webp" alt="Wedding Tablescape" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">Romantic Wedding</h4>
        </div>
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="/generated/image-close-up-of-hands-arranging-vibrant-purp-1767414108869-9.webp" alt="Floral Design Process" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">Behind the Blooms</h4>
        </div>
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="/generated/image-dramatic-floral-installation-with-cascad-1767414111616-10.webp" alt="Outdoor Installation" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">Garden Celebration</h4>
        </div>
      </div>
    </div>

    <!-- Footer Links -->
    <div class="flex flex-col md:flex-row justify-between items-center text-xs text-gray-500 uppercase tracking-widest border-t border-gray-800 pt-10">
      <div class="mb-4 md:mb-0">
        &copy; 2024 Bloom & Hue · Black-Owned Business
      </div>
      <div class="flex gap-8">
        <a href="mailto:amber@bloomandhue.co" class="hover:text-white">Contact</a>
        <a href="https://www.instagram.com/bloomandhue" target="_blank" rel="noopener noreferrer" class="hover:text-white">Instagram</a>
        <span class="text-gray-700">Long Beach, CA</span>
      </div>
    </div>
  </div>
</footer>
