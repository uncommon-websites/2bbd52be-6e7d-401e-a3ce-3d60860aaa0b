<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-20 md:py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center">
    <h1 class="font-serif text-5xl md:text-7xl text-gray-900 mb-6 leading-tight">
      Make homeownership <br/> affordable again
    </h1>
    <p class="text-gray-500 text-lg md:text-xl max-w-2xl mx-auto mb-10 leading-relaxed font-light">
      Genrae pairs a below-market mortgage with a simple option agreement. Get up to 1.5% off your rate permanently, in exchange for sharing a capped portion of your home's future appreciation.
    </p>
    <a href="#" class="inline-flex items-center px-6 py-3 bg-gray-900 text-white font-medium rounded hover:bg-gray-800 transition-colors">
      Calculate Your Savings <span class="ml-2">→</span>
    </a>
  </div>

  <div class="mt-16 md:mt-20 px-4 md:px-12">
    <div class="relative w-full aspect-[16/9] md:aspect-[21/9] rounded-lg overflow-hidden bg-gray-200">
      <!-- Hero Image -->
      <img 
        src="/generated/image-happy-young-couple-holding-house-keys-in-1765831409378-0.webp" 
        alt="Happy couple with keys to their new home" 
        class="w-full h-full object-cover"
      />
    </div>
  </div>
</SectionWrapper>
