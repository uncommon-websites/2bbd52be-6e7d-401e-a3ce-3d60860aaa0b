<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 mb-16 text-center">
    <h2 class="font-serif text-4xl text-gray-900">Trusted by mortgage professionals</h2>
  </div>

  <div class="px-4 md:px-12 max-w-5xl mx-auto">
    <div class="flex flex-col md:flex-row gap-12 items-center">
      <!-- Image -->
      <div class="w-full md:w-1/3">
        <div class="aspect-[3/4] bg-gray-200 rounded-lg overflow-hidden relative">
          <img 
            src="/generated/image-professional-mortgage-broker-in-business-1765831411563-1.webp" 
            alt="Jennifer Martinez" 
            class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500"
          />
        </div>
      </div>

      <!-- Quote -->
      <div class="w-full md:w-2/3">
        <blockquote class="font-light text-xl md:text-2xl text-gray-500 leading-relaxed mb-8">
          "In today's rate environment, so many qualified buyers are getting priced out. <span class="text-gray-900">Genrae gives me a real solution to offer them—lower payments without gimmicks, just smart financing that works for everyone.</span>"
        </blockquote>
        
        <div class="border-t border-gray-200 border-dashed pt-6">
          <div class="font-serif text-lg font-bold text-gray-900">Jennifer Martinez</div>
          <div class="text-sm text-gray-500">Senior Loan Officer</div>
          <div class="text-sm text-gray-500">Pacific Home Lending</div>
        </div>
      </div>
    </div>
  </div>
</SectionWrapper>
