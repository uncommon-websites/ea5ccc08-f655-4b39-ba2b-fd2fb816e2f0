<script lang="ts">
  let openIndex: number | null = null;
  
  const faqs = [
    "Can Amini provide technical audits for my organization?",
    "How do I get support for specialized architecture or AI engagements?",
    "How does Amini ensure the confidentiality of our enterprise data?",
    "Is Amini's hands-on engineering available for my tech stack?",
    "How can I suggest a service feature or report an issue?",
    "Which cloud platforms and migration services does Amini support?"
  ];
  
  function toggle(index: number) {
    openIndex = openIndex === index ? null : index;
  }
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-3xl mx-auto px-4">
    <h2 class="text-4xl font-bold text-center mb-4">Frequently Asked Questions</h2>
    <p class="text-center text-gray-500 mb-12 text-sm">
      For inquiries not answered below, please contact us at <span class="text-black font-medium">care@amini.so</span>
    </p>
    
    <div class="space-y-4">
      {#each faqs as faq, i}
        <div class="bg-white rounded-xl overflow-hidden shadow-sm">
          <button 
            class="w-full flex justify-between items-center p-6 text-left font-medium text-gray-900 hover:bg-gray-50 transition-colors"
            on:click={() => toggle(i)}
          >
            {faq}
            <svg 
              class="w-5 h-5 text-gray-400 transform transition-transform {openIndex === i ? 'rotate-180' : ''}" 
              fill="none" 
              viewBox="0 0 24 24" 
              stroke="currentColor"
            >
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
            </svg>
          </button>
          {#if openIndex === i}
            <div class="px-6 pb-6 text-gray-600 text-sm">
              {#if i === 0}
                Yes, Amini specializes in conducting comprehensive technical audits for organizations of all sizes. Contact us to discuss your infrastructure and readiness needs.
              {:else if i === 1}
                Amini offers direct access to senior architects for complex architecture and AI projects. Reach out to us to explore custom engagements tailored to your enterprise.
              {:else if i === 2}
                We prioritize privacy and data security by adhering to best practices. All advisory and engineering projects are handled with strict confidentiality and compliance standards.
              {:else if i === 3}
                Our team supports a broad range of tech stacks for both architecture review and AI deployments. Get in touch to confirm compatibility with your environment.
              {:else if i === 4}
                Please email care@amini.so with your service requests, feedback, or to report any issues. We strive for rapid response and resolution.
              {:else if i === 5}
                Amini supports major cloud platforms, including specialized expertise in Cloudflare SASE, Zero Trust, and Microsoft 365 migrations. Let us know your migration or platform needs.
              {/if}
            </div>
          {/if}
        </div>
      {/each}
    </div>
  </div>
</section>
