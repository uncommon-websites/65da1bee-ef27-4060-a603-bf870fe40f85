<script>
  import Image from './Image.svelte';
</script>

<footer class="w-full bg-black text-white pt-20 pb-10">
  <div class="container mx-auto px-4">
    <!-- Call to Action -->
    <div class="mb-20">
      <h2 class="text-3xl md:text-5xl font-bold uppercase leading-tight mb-10 max-w-3xl">
        Our product deserves the right space. Let's do it together.
      </h2>
      
      <button class="bg-white text-black w-40 h-40 flex flex-col items-center justify-center hover:bg-gray-200 transition-colors">
        <span class="text-sm font-bold uppercase mb-2">Let's</span>
        <span class="text-2xl font-bold uppercase">Do This</span>
      </button>
    </div>

    <!-- Journal Section -->
    <div class="border-t border-gray-800 pt-10 mb-20">
      <div class="flex justify-between items-end mb-8">
        <h3 class="text-xl font-bold uppercase">Journal</h3>
        <a href="#" class="text-sm underline">View All</a>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?q=80&w=800" alt="Journal 1" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">Design Trends 2024</h4>
        </div>
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="https://images.unsplash.com/photo-1517841905240-472988babdf9?q=80&w=800" alt="Journal 2" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">Sustainable Living</h4>
        </div>
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=800" alt="Journal 3" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">Meet the Maker</h4>
        </div>
      </div>
    </div>

    <!-- Footer Links -->
    <div class="flex flex-col md:flex-row justify-between items-center text-xs text-gray-500 uppercase tracking-widest border-t border-gray-800 pt-10">
      <div class="mb-4 md:mb-0">
        &copy; 2024 Fictional Spaces
      </div>
      <div class="flex gap-8">
        <a href="#" class="hover:text-white">Privacy</a>
        <a href="#" class="hover:text-white">Terms</a>
        <a href="#" class="hover:text-white">Contact</a>
      </div>
    </div>
  </div>
</footer>
