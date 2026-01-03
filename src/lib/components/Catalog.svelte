<script>
  import Image from './Image.svelte';
</script>

<section class="w-full bg-black text-white py-20">
  <div class="container mx-auto px-4">
    <div class="grid grid-cols-1 md:grid-cols-12 gap-8">
      <!-- Title -->
      <div class="md:col-span-3">
        <h3 class="text-xl font-bold uppercase tracking-widest sticky top-10">Our Work</h3>
      </div>

      <!-- Gallery -->
      <div class="md:col-span-9 grid grid-cols-1 md:grid-cols-2 gap-4 md:gap-8">
        <!-- Item 1 -->
        <div class="relative aspect-[4/5] group overflow-hidden">
          <Image src="/generated/image-elegant-wedding-ceremony-arch-with-casca-1767414088499-1.webp" alt="Wedding Ceremony" />
          <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Wedding Ceremony</p>
            <p class="text-xs text-gray-400">01</p>
          </div>
        </div>

        <!-- Item 2 -->
        <div class="relative aspect-[4/5] group overflow-hidden mt-12 md:mt-24">
          <Image src="/generated/image-sophisticated-wedding-reception-centerpi-1767414091199-2.webp" alt="Reception Centerpiece" />
          <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Reception Design</p>
            <p class="text-xs text-gray-400">02</p>
          </div>
        </div>

        <!-- Item 3 -->
        <div class="relative aspect-[4/5] group overflow-hidden">
           <Image src="/generated/image-modern-bridal-bouquet-with-abstract-desi-1767414093878-3.webp" alt="Bridal Bouquet" />
           <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Bridal Bouquet</p>
            <p class="text-xs text-gray-400">03</p>
          </div>
        </div>

        <!-- Item 4 -->
        <div class="relative aspect-[4/5] group overflow-hidden mt-12 md:mt-24">
           <Image src="/generated/image-vibrant-corporate-event-floral-installat-1767414096345-4.webp" alt="Corporate Event" />
           <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Corporate Event</p>
            <p class="text-xs text-gray-400">04</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
