<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center mb-16">
    <div class="text-xs font-mono uppercase tracking-widest text-gray-500 mb-4">
      Simple Process
    </div>
    <h2 class="font-serif text-4xl text-gray-900 mb-6">
      From application to closing
    </h2>
    <p class="text-gray-500 leading-relaxed max-w-2xl mx-auto">
      Genrae integrates seamlessly into the standard mortgage process, adding value without complexity.
    </p>
  </div>

  <div class="px-4 md:px-12 relative">
    <!-- Connecting Line -->
    <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -translate-y-1/2 hidden md:block"></div>

    <!-- Process Steps -->
    <div class="flex flex-wrap md:flex-nowrap items-start justify-center md:justify-between gap-8 md:gap-4 relative z-10">
      
      <!-- Step 1 -->
      <div class="flex flex-col items-center text-center max-w-[140px]">
        <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-200 flex items-center justify-center mb-3">
          <div class="text-2xl font-bold text-gray-900">1</div>
        </div>
        <div class="text-xs font-bold text-gray-900 mb-1">Apply</div>
        <div class="text-[10px] text-gray-500 leading-relaxed">Work with your lender to apply for a Genrae mortgage</div>
      </div>

       <!-- Step 2 -->
      <div class="flex flex-col items-center text-center max-w-[140px]">
        <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-200 flex items-center justify-center mb-3">
          <div class="text-2xl font-bold text-gray-900">2</div>
        </div>
        <div class="text-xs font-bold text-gray-900 mb-1">Get Approved</div>
        <div class="text-[10px] text-gray-500 leading-relaxed">Receive your reduced rate and loan terms</div>
      </div>

       <!-- Step 3 -->
      <div class="flex flex-col items-center text-center max-w-[140px]">
        <div class="w-16 h-16 bg-primary-600 rounded-full shadow-lg border-2 border-primary-400 flex items-center justify-center mb-3">
          <div class="text-2xl font-bold text-white">3</div>
        </div>
        <div class="text-xs font-bold text-gray-900 mb-1">Sign Agreement</div>
        <div class="text-[10px] text-gray-500 leading-relaxed">Simple option agreement for appreciation sharing</div>
      </div>

       <!-- Step 4 -->
      <div class="flex flex-col items-center text-center max-w-[140px]">
        <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-200 flex items-center justify-center mb-3">
          <div class="text-2xl font-bold text-gray-900">4</div>
        </div>
        <div class="text-xs font-bold text-gray-900 mb-1">Close & Move In</div>
        <div class="text-[10px] text-gray-500 leading-relaxed">Enjoy lower payments in your new home</div>
      </div>

       <!-- Step 5 -->
      <div class="flex flex-col items-center text-center max-w-[140px]">
        <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-200 flex items-center justify-center mb-3">
          <div class="text-2xl font-bold text-gray-900">5</div>
        </div>
        <div class="text-xs font-bold text-gray-900 mb-1">Settle Later</div>
        <div class="text-[10px] text-gray-500 leading-relaxed">At sale, refinance, or after 30 years</div>
      </div>

    </div>
  </div>
</SectionWrapper>
