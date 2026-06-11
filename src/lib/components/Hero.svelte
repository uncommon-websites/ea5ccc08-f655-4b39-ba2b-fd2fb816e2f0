<script lang="ts">
  // Hero Section
</script>

<section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto flex flex-col items-center text-center">
  <h1 class="text-5xl md:text-7xl font-bold tracking-tight text-gray-900 max-w-4xl mb-8 leading-[1.1]">
    Launch production-ready <span class="text-[#0099ff]">architecture and AI systems</span> with senior engineers
  </h1>

  <div class="flex flex-col sm:flex-row gap-4 mb-16">
    <button class="bg-[#0099ff] text-white px-8 py-3 rounded-full text-lg font-medium hover:bg-blue-600 transition-colors">
      Start your technical audit
    </button>
    <button class="bg-white text-gray-900 border border-gray-200 px-8 py-3 rounded-full text-lg font-medium hover:bg-gray-50 transition-colors flex items-center gap-2">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-play-circle"><circle cx="12" cy="12" r="10"/><polygon points="10 8 16 12 10 16 10 8"/></svg>
      Schedule a call
    </button>
  </div>

  <!-- Hero Image Placeholder (App Interface) -->
  <div class="w-full max-w-5xl bg-white rounded-xl shadow-2xl border border-gray-200 overflow-hidden relative aspect-[16/10] text-left">
    <!-- Fake Browser Header -->
    <div class="bg-gray-50 border-b border-gray-200 p-3 flex items-center gap-2">
      <div class="flex gap-1.5">
        <div class="w-3 h-3 rounded-full bg-red-400"></div>
        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
        <div class="w-3 h-3 rounded-full bg-green-400"></div>
      </div>
      <div class="mx-auto text-xs text-gray-400 font-medium">Solution Design Workshop</div>
    </div>
    
    <!-- App Content -->
    <div class="flex h-full">
      <!-- Sidebar -->
      <div class="w-64 border-r border-gray-100 bg-gray-50/50 p-4 hidden md:block">
        <div class="space-y-4">
          <div class="h-4 w-24 bg-gray-200 rounded"></div>
          <div class="space-y-2">
             <div class="h-8 w-full bg-white border border-gray-200 rounded-lg shadow-sm"></div>
             <div class="h-8 w-full bg-transparent rounded-lg"></div>
             <div class="h-8 w-full bg-transparent rounded-lg"></div>
          </div>
        </div>
      </div>
      
      <!-- Main Content -->
      <div class="flex-1 p-8 bg-white">
        <div class="max-w-3xl mx-auto">
           <h2 class="text-2xl font-bold mb-6">Solution Design Workshop</h2>
           
           <div class="prose prose-sm max-w-none text-gray-600 space-y-4">
             <p class="text-gray-900 font-medium">Project Overview</p>
             <p>Amini guided infrastructure upgrades for improved scale, cloud migration, and integrated AI—cutting time-to-production by 6 weeks. Stakeholder feedback highlights clear delivery and sustained knowledge transfer. Next: Rollout of automation modules via proprietary platform.</p>
             
             <ul class="list-disc pl-5 space-y-2">
               <li>Technical debt audit identified high-impact upgrade paths</li>
               <li>Rapid PoC for Zero Trust and Cloudflare SASE completed; enterprise migration scheduled</li>
               <li>Overall build velocity up 18% due to embedded senior involvement</li>
             </ul>

             <div class="mt-8 p-4 bg-gray-50 rounded-lg border border-gray-100">
               <div class="flex justify-between items-center mb-4">
                 <h3 class="font-medium text-gray-900">Next Steps</h3>
                 <button class="text-xs text-gray-500">Share summary</button>
               </div>
               <div class="space-y-3">
                 <div class="flex items-center gap-3">
                   <div class="w-4 h-4 border border-gray-300 rounded"></div>
                   <span class="text-sm">Initiate rollout for Platform X modules</span>
                   <div class="ml-auto w-6 h-6 rounded-full bg-gray-200"></div>
                 </div>
                 <div class="flex items-center gap-3">
                    <div class="w-4 h-4 border border-gray-300 rounded"></div>
                    <span class="text-sm">Plan AI readiness workshop with internal team</span>
                    <div class="ml-auto w-6 h-6 rounded-full bg-gray-200"></div>
                 </div>
               </div>
             </div>
           </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Trusted By -->
  <div class="mt-20 relative w-full max-w-5xl">
    <p class="text-sm text-gray-500 mb-6 text-left ml-4">Chosen by forward-thinking engineering teams</p>
    <div class="flex flex-wrap justify-between items-center gap-8 opacity-50 grayscale">
       <!-- Simple text placeholders for logos for now, or SVGs if I had them. Using text for speed/accuracy of layout first. -->
       <span class="font-bold text-xl">SwissRE</span>
       <span class="font-bold text-xl">Helvetia</span>
       <span class="font-bold text-xl">PostFinance</span>
       <span class="font-bold text-xl">Baloise</span>
       <span class="font-bold text-xl">UBS</span>
       <span class="font-bold text-xl">FinTechPro</span>
       <span class="font-bold text-xl">Nestle</span>
       <span class="font-bold text-xl">Zurich Insurance</span>
    </div>
    
    <!-- Handwritten Note -->
    <div class="absolute -bottom-12 -left-4 hidden lg:block">
      <div class="relative">
        <svg class="absolute -top-4 -right-8 w-12 h-12 text-gray-300 transform rotate-12" viewBox="0 0 100 100" fill="none" stroke="currentColor">
           <path d="M10,80 Q50,10 90,80" stroke-width="2" />
           <path d="M90,80 L80,70 M90,80 L85,90" stroke-width="2" />
        </svg>
        <p class="font-serif italic text-gray-400 text-sm whitespace-nowrap transform -rotate-6">
          * Several of these teams deploy Amini solutions in production
        </p>
      </div>
    </div>
  </div>
</section>
