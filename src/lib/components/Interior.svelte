<script>
  import Image from './Image.svelte';
</script>

<section class="w-full relative min-h-screen flex items-center">
  <div class="absolute inset-0">
    <Image 
      src="https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?q=80&w=2000" 
      alt="Interior Living Room" 
    />
    <div class="absolute inset-0 bg-black/10"></div>
  </div>

  <div class="container mx-auto px-4 relative z-10">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div class="hidden md:block"></div>
      <div class="bg-white p-8 md:p-12 max-w-lg">
        <h3 class="text-2xl font-bold uppercase mb-4">Interior Design</h3>
        <p class="text-gray-600 leading-relaxed mb-6">
          We believe that design should be accessible to everyone. Our products are crafted with care and attention to detail, ensuring that they not only look good but also stand the test of time.
        </p>
        <p class="text-gray-600 leading-relaxed">
          From the initial concept to the final product, we work closely with our designers to bring their vision to life.
        </p>
      </div>
    </div>
  </div>
</section>
