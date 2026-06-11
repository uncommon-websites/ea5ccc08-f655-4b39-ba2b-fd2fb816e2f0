<script lang="ts">
  let activeTab = 'Today';
  const tabs = ['Today', 'Day 3', 'Day 7'];
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <h2 class="text-4xl font-bold mb-12">
      What you can accomplish with<br />Amini <span class="bg-blue-100 text-blue-600 px-2 rounded">in your first 7 days</span>
    </h2>
    
    <div class="flex justify-center gap-4 mb-16">
      {#each tabs as tab}
        <button 
          class="px-6 py-2 rounded-full text-sm font-medium transition-colors {activeTab === tab ? 'bg-gray-800 text-white' : 'bg-gray-200 text-gray-500 hover:bg-gray-300'}"
          on:click={() => activeTab = tab}
        >
          {tab}
        </button>
      {/each}
    </div>
    
    <div class="grid md:grid-cols-3 gap-8 text-left">
      <!-- Card 1 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Kick off your audit</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Begin your technical discovery call with senior architects</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Receive actionable audit findings within days of kickoff</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Map out initial production-ready technical roadmap</span>
          </li>
        </ul>
      </div>

      <!-- Card 2 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Accelerate modernization</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Leverage expertise in AI, cloud and infrastructure modernization</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Connect with best-in-class engineering for rapid solution design</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Go from assessment to implementation without losing momentum</span>
          </li>
        </ul>
      </div>

      <!-- Card 3 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Deliver working results</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Deploy solutions and infrastructure with full expert oversight</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Transfer production-ready code, configurations, and documentation</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-green-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Enable seamless handover to your internal teams for long-term ownership</span>
          </li>
        </ul>
      </div>
    </div>
    
    <div class="mt-16">
       <button class="bg-[#0099ff] text-white px-8 py-3 rounded-full text-lg font-medium hover:bg-blue-600 transition-colors">
        Start your engagement
      </button>
    </div>
  </div>
</section>
