<script lang="ts">
  // Shareable Pages Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-purple-500 font-medium">Collaboration Pages</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-6">Easily Share Insights with Team and Stakeholders</h2>
  
  <p class="text-gray-600 max-w-3xl mb-8">
    Having an up-to-date architecture map is just the beginning. Most consultancies leave behind documentation, but Amini ensures ongoing value by connecting project context and technical rationale.
  </p>
  
  <p class="text-gray-600 max-w-3xl mb-12">
    Our approach lets you ask focused questions—from infrastructure choices to AI integration strategies—with immediate, contextual answers. No matter where you are in your transformation, tap into Amini’s expertise at any time.
  </p>
  
  <div class="border-l-4 border-purple-500 pl-6 py-2 mb-16">
    <p class="text-lg font-medium text-gray-900 italic mb-2">
      The clarity and transparency Amini brings is something rare. Their collaborative briefs feel more like blueprints you can act on—not just static reports.
    </p>
    <div class="text-sm text-gray-500">Maya Wolf • CTO, Swiss Finserv</div>
  </div>
  
  <!-- Interface Mockup -->
  <div class="bg-gray-200 rounded-t-2xl p-1 pb-0 overflow-hidden">
    <div class="bg-gray-400/20 p-2 flex gap-4 text-xs text-white font-medium justify-center">
      <div class="flex items-center gap-1">Collaborate securely</div>
      <div class="flex items-center gap-1">Share technical briefs</div>
      <div class="flex items-center gap-1">Access context on demand</div>
    </div>
    
    <div class="bg-white rounded-t-xl mt-2 p-8 h-[500px] flex shadow-2xl relative">
       <!-- Sidebar -->
       <div class="w-64 border-r border-gray-100 pr-4 hidden md:block">
         <div class="space-y-4">
           <!-- Fake List Items -->
           <div class="flex items-center justify-between text-sm text-gray-700 p-2 bg-blue-50 rounded">
             <div class="flex items-center gap-2">
               <div class="w-4 h-4 bg-blue-500 rounded-full"></div>
               <span>zurich-ai.com</span>
             </div>
             <span class="text-gray-400">1</span>
           </div>
           
           {#each ['swissfintech.com', 'insureexpert.ch', 'workflowhub', 'm365migration.ch', 'cloudflare2024', 'platform-x', 'azim x team', 'globalinsure.net', 'digitaltrans.ch', 'platformai.ch', 'architecture'] as item}
            <div class="flex items-center justify-between text-sm text-gray-600 p-2 hover:bg-gray-50 rounded">
             <div class="flex items-center gap-2">
               <div class="w-4 h-4 bg-gray-200 rounded-full"></div>
               <span>{item}</span>
             </div>
             <span class="text-gray-400">1</span>
           </div>
           {/each}
         </div>
       </div>
       
       <!-- Main Area -->
       <div class="flex-1 pl-8 relative">
         <div class="absolute inset-0 flex items-center justify-center">
           <!-- Connecting Lines Annotation -->
           <div class="absolute left-[-40px] top-[100px] flex items-center">
             <span class="text-orange-500 text-xs font-bold mr-2">Engineering Briefs</span>
             <div class="w-8 h-px bg-orange-500"></div>
             <div class="w-2 h-2 bg-orange-500 rounded-full"></div>
           </div>
           
           <div class="absolute left-[-40px] bottom-[100px] flex items-center">
             <span class="text-orange-500 text-xs font-bold mr-2">Custom Solutions</span>
             <div class="w-8 h-px bg-orange-500"></div>
             <div class="w-2 h-2 bg-orange-500 rounded-full"></div>
           </div>
         </div>
       </div>
    </div>
  </div>
  
  <!-- Bottom Grid -->
  <div class="grid md:grid-cols-3 gap-8 mt-16">
    <div>
      <h3 class="font-bold text-lg mb-2">Organized by Initiative</h3>
      <p class="text-sm text-gray-600 mb-4">Track how your digital transformation milestones develop over time.</p>
      <div class="bg-gray-50 p-4 rounded-lg border border-gray-100 h-24 flex items-center justify-center">
        <div class="w-full space-y-2">
          <div class="h-2 bg-gray-200 rounded w-3/4"></div>
          <div class="h-2 bg-gray-200 rounded w-1/2"></div>
        </div>
      </div>
    </div>
    
    <div>
      <h3 class="font-bold text-lg mb-2">By Client Domain</h3>
      <p class="text-sm text-gray-600 mb-4">Ensure each partner receives tailored technical guidance and follow-through.</p>
      <div class="bg-gray-50 p-4 rounded-lg border border-gray-100 h-24 flex items-center justify-center">
        <div class="w-full space-y-2">
          <div class="h-2 bg-gray-200 rounded w-full"></div>
          <div class="h-2 bg-gray-200 rounded w-2/3"></div>
        </div>
      </div>
    </div>
    
    <div>
      <h3 class="font-bold text-lg mb-2">On Demand</h3>
      <p class="text-sm text-gray-600 mb-4">Maintain oversight of AI evaluations, infrastructure migrations, or unique business cases.</p>
      <div class="bg-gray-50 p-4 rounded-lg border border-gray-100 h-24 flex items-center justify-center">
        <div class="w-full space-y-2">
          <div class="h-2 bg-gray-200 rounded w-1/2"></div>
          <div class="h-2 bg-gray-200 rounded w-3/4"></div>
        </div>
      </div>
    </div>
  </div>
</section>
