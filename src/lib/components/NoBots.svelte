<script lang="ts">
  // No Bots Section
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid md:grid-cols-2 gap-16 items-center">
      <div>
        <h2 class="text-3xl font-bold mb-6">No more intermediaries—direct expert engagement</h2>
        <p class="text-gray-600 mb-8">
          With Amini, your technical projects benefit from direct, hands-on involvement by senior engineers. No layers. No bots. Just streamlined engineering delivery:
        </p>
        
        <ul class="space-y-4">
          {#each [
            'Pause project reviews to allow candid internal discussions',
            'Immediate course correction if requirements change or resources are underused',
            'Split project phases flexibly as priorities shift',
            'Maintain clear stakeholder roles and detailed project records for accountability'
          ] as item}
            <li class="flex items-start gap-3">
              <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center mt-0.5 shrink-0">
                <svg class="w-3 h-3 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
                </svg>
              </div>
              <span class="text-gray-700 text-sm">{item}</span>
            </li>
          {/each}
        </ul>
      </div>
      
      <div class="relative">
        <!-- Laptop/Screen Mockup -->
        <div class="bg-gradient-to-br from-blue-100 to-pink-100 rounded-2xl p-8 shadow-lg">
           <div class="bg-gray-900 rounded-xl overflow-hidden shadow-2xl relative aspect-video flex items-center justify-center">
              <!-- Dynamic Island UI -->
              <div class="absolute top-4 left-1/2 -translate-x-1/2 bg-black rounded-full px-4 py-2 flex items-center gap-4 shadow-2xl border border-gray-800 z-10 w-fit">
                 <div class="flex items-center gap-2 border-r border-gray-700 pr-4">
                   <div class="w-2 h-2 rounded-full bg-red-500 animate-pulse"></div>
                   <span class="text-white text-xs font-medium">Architecture Review</span>
                 </div>
                 <div class="text-gray-400 text-xs font-mono">0:13</div>
                 <div class="flex gap-2">
                   <div class="w-6 h-6 rounded-full bg-gray-800 flex items-center justify-center text-white text-[10px]">⏸</div>
                   <div class="w-6 h-6 rounded-full bg-red-600 flex items-center justify-center text-white text-[10px]">■</div>
                 </div>
              </div>

              <!-- Fake Meeting Grid -->
              <div class="grid grid-cols-2 gap-2 w-full h-full p-4 pt-16 opacity-50">
                 <div class="bg-gray-800 rounded-lg"></div>
                 <div class="bg-gray-800 rounded-lg"></div>
                 <div class="bg-gray-800 rounded-lg"></div>
                 <div class="bg-gray-800 rounded-lg"></div>
              </div>
           </div>
        </div>
        <p class="text-xs text-gray-500 mt-4 text-center">
          If your team needs an alternative interface, Amini provides flexible collaboration options. Upgrade your delivery by working directly with senior architects.
        </p>
      </div>
    </div>
    
    <div class="mt-16 p-6 bg-green-50 rounded-xl border border-green-100">
      <p class="text-sm text-green-800">
        <span class="font-bold">The unobtrusive consultation experience is both efficient and empowering</span>, ensuring clear communication and actionable insights in real time. Multilingual expertise and instant next-step recommendations dramatically accelerated our infrastructure rollout.
      </p>
      <div class="mt-2 text-xs text-green-600 font-medium">Gabriel Sallard • Head of IT Engineering</div>
    </div>
  </div>
</section>
