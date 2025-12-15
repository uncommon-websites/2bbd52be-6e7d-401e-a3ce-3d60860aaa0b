<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
  import SolutionBlock from './SolutionBlock.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="">
  <div class="px-4 md:px-12">
    <div class="py-16 text-center">
      <h2 class="font-serif text-4xl text-gray-900">How Genrae works</h2>
    </div>

    <!-- Block 1 -->
    <SolutionBlock
      label="For Homebuyers"
      title="Lower your monthly payment"
      description="Reduce your mortgage rate by up to 1.5 percentage points permanently. That means hundreds less per month, making homeownership accessible even in today's high-rate environment. The rate reduction is funded upfront and lasts the life of your loan."
    >
      <!-- Visual for Block 1: Rate Comparison -->
      <div class="relative w-full h-full flex items-center justify-center gap-8">
        <!-- Traditional Rate -->
        <div class="bg-white rounded-lg shadow-lg p-6 border border-gray-200 w-40">
            <div class="text-xs text-gray-500 mb-2 text-center">Traditional Rate</div>
            <div class="text-3xl font-bold text-gray-900 text-center mb-1">7.5%</div>
            <div class="text-xs text-gray-500 text-center">$2,797/mo</div>
        </div>
        
        <!-- Arrow -->
        <div class="text-4xl text-primary-500">→</div>
        
        <!-- Genrae Rate -->
        <div class="bg-primary-50 rounded-lg shadow-xl p-6 border-2 border-primary-400 w-40 relative">
            <div class="absolute -top-3 left-1/2 -translate-x-1/2 bg-primary-600 text-white text-[10px] font-bold px-3 py-1 rounded-full">
                GENRAE
            </div>
            <div class="text-xs text-primary-700 mb-2 text-center font-medium">Your Rate</div>
            <div class="text-3xl font-bold text-primary-900 text-center mb-1">6.0%</div>
            <div class="text-xs text-primary-700 text-center font-medium">$2,398/mo</div>
            <div class="text-xs text-primary-600 text-center mt-2 font-bold">Save $399/mo</div>
        </div>
      </div>
    </SolutionBlock>

    <!-- Block 2 -->
    <SolutionBlock
      label="For Mortgage Professionals"
      title="Differentiate your offering"
      description="Stand out in a commoditized market by offering borrowers a truly innovative solution to rate anxiety. Genrae integrates seamlessly into your existing workflow, giving you a powerful tool to win more business and serve clients who might otherwise be priced out."
      reversed={true}
    >
      <!-- Visual for Block 2: Broker Dashboard -->
      <div class="bg-white rounded-lg shadow-xl p-6 w-3/4 max-w-sm border border-gray-100">
        <div class="flex items-center justify-between mb-4 pb-3 border-b border-gray-100">
            <div class="text-xs font-bold text-gray-900">Loan Application</div>
            <div class="text-[10px] text-primary-600 font-medium">GENRAE ELIGIBLE</div>
        </div>
        <div class="space-y-3 mb-6">
            <div class="flex justify-between text-xs">
                <span class="text-gray-500">Borrower</span>
                <span class="font-medium text-gray-900">Sarah & Mike Chen</span>
            </div>
            <div class="flex justify-between text-xs">
                <span class="text-gray-500">Loan Amount</span>
                <span class="font-medium text-gray-900">$400,000</span>
            </div>
            <div class="flex justify-between text-xs">
                <span class="text-gray-500">Standard Rate</span>
                <span class="font-medium text-gray-900">7.5%</span>
            </div>
            <div class="flex justify-between text-xs border-t pt-2">
                <span class="text-primary-700 font-medium">Genrae Rate</span>
                <span class="font-bold text-primary-900">6.0%</span>
            </div>
        </div>
        <button class="w-full bg-gray-900 text-white py-2 rounded text-sm font-medium hover:bg-gray-800 transition-colors">
            Present Genrae Option
        </button>
      </div>
    </SolutionBlock>

    <!-- Block 3 -->
    <SolutionBlock
      label="Homeowner-First Structure"
      title="Keep your upside"
      description="Genrae's appreciation sharing is capped and fair. You retain significant upside from your home's value growth, and the structure is designed to align our success with yours. Settlement typically occurs at sale, refinance, or after 30 years—giving you full control and flexibility."
    >
       <!-- Visual for Block 3: Appreciation Split -->
       <div class="bg-white rounded-lg shadow-lg p-6 w-2/3 max-w-xs border border-gray-100">
          <div class="mb-4 pb-3 border-b border-gray-100">
              <div class="font-bold text-sm text-gray-900">Home Value Growth</div>
              <div class="text-[10px] text-gray-500 mt-1">Example: $400K → $500K</div>
          </div>
          
          <!-- Bar Chart -->
          <div class="space-y-3">
              <div>
                  <div class="flex justify-between text-xs mb-1">
                      <span class="text-gray-900 font-medium">Your Share</span>
                      <span class="font-bold text-gray-900">$75,000</span>
                  </div>
                  <div class="h-8 bg-gray-900 rounded flex items-center justify-center text-white text-xs font-bold">
                      75%
                  </div>
              </div>
              <div>
                  <div class="flex justify-between text-xs mb-1">
                      <span class="text-primary-700 font-medium">Genrae Share</span>
                      <span class="font-bold text-primary-900">$25,000</span>
                  </div>
                  <div class="h-6 bg-primary-400 rounded flex items-center justify-center text-white text-xs font-bold">
                      25% (capped)
                  </div>
              </div>
          </div>
          
          <div class="mt-4 pt-3 border-t border-gray-100 text-[10px] text-gray-500 text-center">
              Settlement at sale, refinance, or 30 years
          </div>
       </div>
    </SolutionBlock>
  </div>
</SectionWrapper>
