<script>
  import Image from './Image.svelte';
</script>

<section class="w-full bg-black text-white py-20">
  <div class="container mx-auto px-4">
    <div class="grid grid-cols-1 md:grid-cols-12 gap-8">
      <!-- Title -->
      <div class="md:col-span-3">
        <h3 class="text-xl font-bold uppercase tracking-widest sticky top-10">Catalog</h3>
      </div>

      <!-- Gallery -->
      <div class="md:col-span-9 grid grid-cols-1 md:grid-cols-2 gap-4 md:gap-8">
        <!-- Item 1 -->
        <div class="relative aspect-[4/5] group overflow-hidden">
          <Image src="https://images.unsplash.com/photo-1567538096630-e0c55bd6374c?q=80&w=1000" alt="Pink Chair" />
          <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Lounge Chair</p>
            <p class="text-xs text-gray-400">01</p>
          </div>
        </div>

        <!-- Item 2 -->
        <div class="relative aspect-[4/5] group overflow-hidden mt-12 md:mt-24">
          <Image src="https://images.unsplash.com/photo-1595515106967-1e6db522337e?q=80&w=1000" alt="Interior" />
          <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Living Set</p>
            <p class="text-xs text-gray-400">02</p>
          </div>
        </div>

        <!-- Item 3 -->
        <div class="relative aspect-[4/5] group overflow-hidden">
           <Image src="https://images.unsplash.com/photo-1533090481720-856c6e3c1fdc?q=80&w=1000" alt="Abstract" />
           <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Minimalist</p>
            <p class="text-xs text-gray-400">03</p>
          </div>
        </div>

        <!-- Item 4 -->
        <div class="relative aspect-[4/5] group overflow-hidden mt-12 md:mt-24">
           <Image src="https://images.unsplash.com/photo-1505693314120-0d443867891c?q=80&w=1000" alt="Bed" />
           <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Bedroom</p>
            <p class="text-xs text-gray-400">04</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
