<script>
  import Image from './Image.svelte';
</script>

<section class="w-full relative min-h-screen flex items-center">
  <div class="absolute inset-0">
    <Image 
      src="/generated/image-black-woman-florist-working-in-bright-st-1767414103726-7.webp" 
      alt="Amber Minefee in Studio" 
    />
    <div class="absolute inset-0 bg-black/10"></div>
  </div>

  <div class="container mx-auto px-4 relative z-10">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div class="hidden md:block"></div>
      <div class="bg-white p-8 md:p-12 max-w-lg">
        <h3 class="text-2xl font-bold uppercase mb-4">Meet Amber</h3>
        <p class="text-gray-600 leading-relaxed mb-6">
          Founded by Amber Minefee, Bloom & Hue is a Black-owned boutique studio in the heart of Long Beach, California. Built from a deep passion for nature-inspired artistry and modern floral design, we transform celebrations into unforgettable moments.
        </p>
        <p class="text-gray-600 leading-relaxed">
          Our commitment to fresh, locally sourced blooms and personalized service has made us a beloved destination for clients seeking unique, high-quality arrangements that leave lasting impressions. From intimate gatherings to grand celebrations, we bring your vision to life with keen attention to detail.
        </p>
      </div>
    </div>
  </div>
</section>
