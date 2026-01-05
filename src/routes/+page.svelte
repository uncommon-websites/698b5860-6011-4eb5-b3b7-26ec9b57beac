<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<div class="min-h-screen font-sans text-dark bg-cream overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto text-center">
    <div class="mb-6">
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">AI-Automated Bookkeeping for Creators</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Financial clarity for <br class="hidden md:block" /> creators who build
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      AI-automated bookkeeping paired with dedicated human advisors. 
      Built for Swedish creators and founders who need accurate books without the admin chaos.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#" type="primary">Get Started</Button>
      <Button href="#" type="outline">Book a Call</Button>
    </div>

    <!-- Hero Image -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-white aspect-[16/9] mb-16">
      <img src="/generated/image-person-working-peacefully-at-home-with-o-1767636996630-4.webp" alt="Financial clarity and organized bookkeeping" class="w-full h-full object-cover" />
      
      <!-- Overlay with subtle gradient -->
      <div class="absolute inset-0 bg-gradient-to-t from-dark/20 to-transparent"></div>
    </div>

    <!-- Trust Indicators -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Trusted by creators and founders across Sweden</p>
      <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 text-gray-400">
        <div class="text-center">
          <div class="text-2xl font-serif font-bold text-dark">500+</div>
          <div class="text-xs uppercase tracking-wider">Active Clients</div>
        </div>
        <div class="text-center">
          <div class="text-2xl font-serif font-bold text-dark">98%</div>
          <div class="text-xs uppercase tracking-wider">Satisfaction Rate</div>
        </div>
        <div class="text-center">
          <div class="text-2xl font-serif font-bold text-dark">24h</div>
          <div class="text-xs uppercase tracking-wider">Response Time</div>
        </div>
        <div class="text-center">
          <div class="text-2xl font-serif font-bold text-dark">Stockholm</div>
          <div class="text-xs uppercase tracking-wider">Based</div>
        </div>
      </div>
    </div>
  </section>

  <!-- How It Works Section -->
  <section id="how-it-works" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4 max-w-3xl mx-auto">
        Your path to financial clarity
      </h2>
      <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">
        We blend AI automation with human expertise to give you accurate, proactive accounting without delay or complexity.
      </p>
      
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-16">
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-5xl font-serif font-medium mb-4">1</div>
          <div class="text-lg font-serif mb-2">Understand</div>
          <div class="text-sm text-gray-600">We start with your goals, not numbers</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-5xl font-serif font-medium mb-4">2</div>
          <div class="text-lg font-serif mb-2">Set Up</div>
          <div class="text-sm text-gray-600">Structure your accounts and systems for clarity</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-5xl font-serif font-medium mb-4">3</div>
          <div class="text-lg font-serif mb-2">Collaborate</div>
          <div class="text-sm text-gray-600">Your dedicated advisor is always reachable</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-5xl font-serif font-medium mb-4">4</div>
          <div class="text-lg font-serif mb-2">Grow</div>
          <div class="text-sm text-gray-600">We guide your next moves as you expand</div>
        </div>
      </div>

      <!-- Value Props -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white border border-gray-200 p-8 rounded-2xl">
          <div class="w-12 h-12 bg-dark rounded-lg mb-4 flex items-center justify-center text-white text-xl">🤖</div>
          <h3 class="text-xl font-serif mb-2">AI-Automated</h3>
          <p class="text-gray-600 text-sm">Smart automation handles the repetitive work so you don't have to</p>
        </div>
        <div class="bg-white border border-gray-200 p-8 rounded-2xl">
          <div class="w-12 h-12 bg-dark rounded-lg mb-4 flex items-center justify-center text-white text-xl">👥</div>
          <h3 class="text-xl font-serif mb-2">Human Advisors</h3>
          <p class="text-gray-600 text-sm">Real accountants who understand creative businesses and your ambitions</p>
        </div>
        <div class="bg-white border border-gray-200 p-8 rounded-2xl">
          <div class="w-12 h-12 bg-dark rounded-lg mb-4 flex items-center justify-center text-white text-xl">🇸🇪</div>
          <h3 class="text-xl font-serif mb-2">Built for Sweden</h3>
          <p class="text-gray-600 text-sm">Designed for Swedish tax laws, regulations, and the way you work</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Traditional vs Modern Accounting -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">Traditional accounting <br /> wasn't built for you</h2>
      <p class="text-center text-gray-400 mb-16">The paper-driven era is over. Modern creators need modern solutions.</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- The Old Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">Traditional Firms</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Built for a paper-driven era. Slow responses, complex jargon, and processes that don't match how modern creators work.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700">
             <div class="space-y-3">
                <div class="flex items-center gap-3 text-red-400">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
                  <span class="text-sm">Weeks to get responses</span>
                </div>
                <div class="flex items-center gap-3 text-red-400">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
                  <span class="text-sm">Speak in forms and filings</span>
                </div>
                <div class="flex items-center gap-3 text-red-400">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
                  <span class="text-sm">Manual, time-consuming processes</span>
                </div>
                <div class="flex items-center gap-3 text-red-400">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
                  <span class="text-sm">Don't understand creative work</span>
                </div>
             </div>
          </div>
        </div>

        <!-- The Bronn Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">The Bronn Way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            AI automation meets human expertise. Fast, clear, and built for how you actually work. We speak in goals, seasons, and decisions.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700">
             <div class="space-y-3">
                <div class="flex items-center gap-3 text-green-400">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                  <span class="text-sm">24-hour response time</span>
                </div>
                <div class="flex items-center gap-3 text-green-400">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                  <span class="text-sm">Clear language, no jargon</span>
                </div>
                <div class="flex items-center gap-3 text-green-400">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                  <span class="text-sm">AI handles the repetitive work</span>
                </div>
                <div class="flex items-center gap-3 text-green-400">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                  <span class="text-sm">Built for creators & founders</span>
                </div>
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section -->
  <section id="services" class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4 max-w-2xl mx-auto">
        Everything you need to stay in control
      </h2>
      <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">
        From daily bookkeeping to strategic guidance, we handle it all so you can focus on building.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: AI Automation -->
        <div class="lg:col-span-2 bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">AI-Automated Bookkeeping</h3>
                <p class="text-gray-500 text-sm">Our AI handles transaction categorization, receipt matching, and data entry automatically. You get accurate books without lifting a finger.</p>
            </div>
            <div class="bg-gray-50 rounded-xl p-6 h-64 relative border border-gray-200 overflow-hidden">
                <img src="/generated/image-person-working-peacefully-at-home-with-o-1767636996630-4.webp" alt="Automated bookkeeping" class="w-full h-full object-cover rounded-lg" />
            </div>
        </div>

        <!-- Card 2: Human Advisors -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Dedicated Human Advisors</h3>
                <p class="text-gray-500 text-sm">Real accountants who understand creative businesses and answer within 24 hours.</p>
            </div>
            <div class="bg-gray-50 rounded-xl h-48 relative overflow-hidden">
                <img src="/generated/image-friendly-accountant-or-financial-advisor-1767636993935-3.webp" alt="Human advisors" class="w-full h-full object-cover rounded-lg" />
            </div>
        </div>

        <!-- Card 3: Tax Filing -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-gray-50 rounded-xl mb-6 p-6 flex items-center justify-center">
                <div class="text-center">
                  <div class="text-6xl mb-4">📋</div>
                  <div class="text-sm font-medium text-gray-700">VAT, Tax Returns, Filings</div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Tax Filing & Compliance</h3>
             <p class="text-gray-500 text-sm">We handle all Swedish tax requirements, VAT, and regulatory filings so you stay compliant.</p>
        </div>

        <!-- Card 4: Financial Reports -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-gray-50 rounded-xl mb-6 p-4 flex items-center justify-center">
                <div class="w-full space-y-2">
                    <div class="flex justify-between items-center">
                        <span class="text-xs text-gray-500">Revenue</span>
                        <span class="text-sm font-bold text-green-600">+24%</span>
                    </div>
                    <div class="h-2 bg-green-100 rounded-full overflow-hidden">
                        <div class="h-full bg-green-500 w-3/4"></div>
                    </div>
                    <div class="flex justify-between items-center mt-4">
                        <span class="text-xs text-gray-500">Expenses</span>
                        <span class="text-sm font-bold text-gray-700">-12%</span>
                    </div>
                    <div class="h-2 bg-gray-100 rounded-full overflow-hidden">
                        <div class="h-full bg-gray-400 w-1/2"></div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Clear Financial Reports</h3>
             <p class="text-gray-500 text-sm">Real-time insights into your business health with reports that actually make sense.</p>
        </div>

        <!-- Card 5: Growth Guidance -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-gray-50 rounded-xl mb-6 p-6 flex items-center justify-center">
                <div class="text-center">
                  <div class="text-6xl mb-4">🚀</div>
                  <div class="text-sm font-medium text-gray-700">Strategic Planning</div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Growth Guidance</h3>
             <p class="text-gray-500 text-sm">Your advisor helps you plan next moves, understand cash flow, and make confident decisions.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 - Filippa -->
  <section class="py-16 bg-cream">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="text-sm font-medium text-gray-500 uppercase tracking-wider">Customer Story</div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "My documents used to be all over the place. Now everything just works. Bronn has built a system that lets me grow without losing control."
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <div class="w-16 h-16 rounded-full overflow-hidden bg-gray-200">
                <img src="/generated/image-professional-photographer-working-at-a-c-1767636984691-0.webp" alt="Filippa Trajkovski" class="w-full h-full object-cover" />
            </div>
            <div class="text-left">
                <div class="font-bold text-sm">Filippa Trajkovski</div>
                <div class="text-xs text-gray-500">Photographer</div>
            </div>
        </div>
    </div>
  </section>

  <!-- Core Values Section -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">
        Built on values that <br /> put you first
      </h2>
      <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">
        We're not just another accounting firm. We're building the future of financial clarity for modern creators.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gray-50 rounded-xl h-64 mb-8 overflow-hidden">
                <img src="/generated/image-friendly-accountant-or-financial-advisor-1767636993935-3.webp" alt="People first approach" class="w-full h-full object-cover" />
            </div>
            <h3 class="text-xl font-serif mb-2">People First</h3>
            <p class="text-gray-500 text-sm">We see you as an individual with dreams, worries, and ambitions—not just numbers or accounts. Your success is our mission.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gray-50 rounded-xl h-64 mb-8 p-6 flex items-center justify-center">
                <div class="text-center space-y-4">
                  <div class="text-6xl">✨</div>
                  <div class="text-sm font-medium text-gray-700">Simple. Natural. Clear.</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Design for Clarity</h3>
            <p class="text-gray-500 text-sm">We build systems that feel simple and natural. Technology should bring calm and control, not complexity.</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gray-50 rounded-xl h-64 mb-8 p-6 flex items-center justify-center">
                <div class="text-center space-y-4">
                  <div class="text-6xl">🤝</div>
                  <div class="text-sm font-medium text-gray-700">Your Partner in Growth</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Building Together</h3>
            <p class="text-gray-500 text-sm">We treat you as a partner, planning and adapting side by side with shared goals. Your growth is our growth.</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gray-50 rounded-xl h-64 mb-8 p-6 flex items-center justify-center">
                <div class="text-center space-y-4">
                  <div class="text-6xl">🎯</div>
                  <div class="text-sm font-medium text-gray-700">Accuracy That Empowers</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Precision with Purpose</h3>
            <p class="text-gray-500 text-sm">We value accuracy not for its own sake, but for what it enables: confidence, progress, and courage to keep building.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA Section -->
  <section class="py-24 bg-cream relative overflow-hidden">
    <!-- Subtle Background Pattern -->
    <div class="absolute inset-0 opacity-5 pointer-events-none">
        <div class="absolute top-10 left-10 w-12 h-12 bg-dark rounded-lg transform rotate-12"></div>
        <div class="absolute top-20 right-20 w-12 h-12 bg-dark rounded-lg transform -rotate-6"></div>
        <div class="absolute bottom-20 left-1/3 w-12 h-12 bg-dark rounded-lg transform rotate-45"></div>
        <div class="absolute bottom-10 right-1/4 w-12 h-12 bg-dark rounded-lg transform -rotate-12"></div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-gray-100 text-gray-700 px-4 py-1 rounded-full text-xs font-bold mb-6">
            Join Bronn Today
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Ready to take control <br /> of your finances?</h2>
        <p class="text-gray-600 mb-10">Start with a free consultation. No commitment required.</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Get Started</Button>
            <Button href="#" type="white">Book a Call</Button>
        </div>
    </div>
  </section>

  <!-- Why Choose Bronn Section -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Why creators choose Bronn
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Large Card -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-100 md:row-span-2 flex flex-col">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Freedom to Create</h3>
                <p class="text-gray-500 text-sm">Stop drowning in admin chaos. Bronn handles the bookkeeping so you can focus on what you love—building your creative business.</p>
            </div>
            <div class="flex-1 rounded-2xl relative overflow-hidden min-h-[300px]">
                <img src="/generated/image-creative-professional-celebrating-a-smal-1767636999435-5.webp" alt="Creative freedom" class="w-full h-full object-cover rounded-xl" />
            </div>
        </div>

        <!-- Right Top Card -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-100">
            <div class="mb-4">
                <h3 class="text-xl font-serif mb-2">Always in Control</h3>
                <p class="text-gray-500 text-sm">Real-time visibility into your finances. Know exactly where you stand, what's coming in, and what's going out.</p>
            </div>
            <div class="bg-white rounded-xl h-40 p-6 border border-gray-200">
                <div class="space-y-3">
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-gray-600">Current Balance</span>
                        <span class="text-lg font-bold text-dark">125,450 kr</span>
                    </div>
                    <div class="h-px bg-gray-200"></div>
                    <div class="flex justify-between items-center text-sm">
                        <span class="text-gray-600">This Month</span>
                        <span class="text-green-600 font-medium">+18,200 kr</span>
                    </div>
                    <div class="flex justify-between items-center text-sm">
                        <span class="text-gray-600">Pending</span>
                        <span class="text-gray-600 font-medium">12,500 kr</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Right Bottom Card (Testimonial) -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-100 flex gap-6 items-center">
            <div class="w-20 h-20 rounded-full flex-shrink-0 overflow-hidden bg-gray-200">
                <img src="/generated/image-young-creative-professional-age-23-worki-1767636988330-1.webp" alt="Kajsa Molund" class="w-full h-full object-cover" />
            </div>
            <div>
                <div class="text-primary-600 text-3xl font-serif leading-none mb-2">"</div>
                <p class="text-sm text-gray-600 mb-3">Bronn gave me the space to grow my brand while they handled the bookkeeping. It's been life-changing.</p>
                <div class="text-xs font-bold">Kajsa Molund</div>
                <div class="text-[10px] text-gray-500">Creator, Age 23</div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Customer Stories Grid -->
  <section id="stories" class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Real stories from real creators
      </h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
         <!-- Row 1 -->
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
            <img src="/generated/image-professional-photographer-working-at-a-c-1767636984691-0.webp" alt="Filippa" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent"></div>
            <div class="absolute bottom-4 left-4 text-white font-bold">Filippa</div>
            <div class="absolute top-4 right-4 text-white text-xs bg-white/20 backdrop-blur px-2 py-1 rounded">Photographer</div>
         </div>
         <div class="aspect-square bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-6">
            <div class="text-center">
              <div class="text-4xl font-serif mb-2">500+</div>
              <div class="text-sm text-gray-600">Happy Clients</div>
            </div>
         </div>
         <div class="col-span-2 bg-primary-50 rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-primary-700">"</div>
            <p class="text-lg font-serif leading-relaxed">My documents used to be all over the place. Now everything just works. Bronn has built a system that lets me grow without losing control.</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Filippa Trajkovski</div>
                    <div class="text-gray-600">Photographer</div>
                </div>
                <div class="text-xl">→</div>
            </div>
         </div>

         <!-- Row 2 -->
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
            <div class="text-center">
              <div class="text-5xl mb-4">🇸🇪</div>
              <div class="text-xl font-serif">Stockholm Based</div>
              <div class="text-sm text-gray-600 mt-2">Serving Swedish Creators</div>
            </div>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <img src="/generated/image-young-creative-professional-age-23-worki-1767636988330-1.webp" alt="Kajsa" class="w-full h-full object-cover" />
             <div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent"></div>
             <div class="absolute bottom-4 left-4 text-white font-bold">Kajsa</div>
             <div class="absolute top-4 right-4 text-white text-xs bg-white/20 backdrop-blur px-2 py-1 rounded">Creator</div>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <img src="/generated/image-confident-entrepreneur-working-energetic-1767636991171-2.webp" alt="Emil" class="w-full h-full object-cover" />
             <div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent"></div>
             <div class="absolute bottom-4 left-4 text-white font-bold">Emil</div>
             <div class="absolute top-4 right-4 text-white text-xs bg-white/20 backdrop-blur px-2 py-1 rounded">Founder</div>
         </div>

         <!-- Row 3 -->
         <div class="col-span-2 bg-gray-100 rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-gray-700">"</div>
            <p class="text-lg font-serif leading-relaxed">Bronn gave me the space to grow my brand while they handled the bookkeeping. Balance, honesty, and support—that's what I found.</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Kajsa Molund</div>
                    <div class="text-gray-600">Creator, Age 23</div>
                </div>
                <div class="text-xl">→</div>
            </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <div class="text-center">
               <div class="text-4xl font-serif mb-2">24h</div>
               <div class="text-sm text-gray-600">Response Time</div>
               <div class="text-xs text-gray-500 mt-2">Always reachable</div>
             </div>
         </div>
         
         <!-- Row 4 -->
         <div class="aspect-square bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-6">
            <div class="text-center">
              <div class="text-4xl font-serif mb-2">98%</div>
              <div class="text-sm text-gray-600">Satisfaction</div>
            </div>
         </div>
         <div class="col-span-2 bg-primary-100 rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-primary-800">"</div>
            <p class="text-lg font-serif leading-relaxed">Bronn turned admin stress into extra time for what I love. They understand fast-growing companies.</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Emil</div>
                    <div class="text-gray-700">Fast-Growing Company</div>
                </div>
                <div class="text-xl">→</div>
            </div>
         </div>
         <div class="aspect-square bg-dark rounded-2xl flex items-center justify-center p-6 text-white">
             <div class="text-center">
               <div class="text-3xl font-serif mb-2">AI + Human</div>
               <div class="text-xs text-gray-400">Best of Both Worlds</div>
             </div>
         </div>
      </div>
    </div>
  </section>

  <!-- Main CTA Section -->
  <section id="contact" class="bg-dark py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-white">Let's bring clarity to <br /> your finances</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-gray-300">
            <div class="flex items-center gap-2">
                <div class="bg-white text-dark rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                AI automation + human expertise
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-white text-dark rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Built for Swedish creators
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="white">Get Started</Button>
            <Button href="#" type="outline">Book a Call</Button>
        </div>
        
        <p class="text-gray-400 text-sm mt-8">Free consultation. No commitment required.</p>
    </div>
  </section>

  <!-- Customer Stories Featured -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">Customer Stories</h2>
      <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">
        See how creators and founders use Bronn to gain financial clarity and freedom.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Large Card Top -->
        <div class="md:col-span-2 bg-primary-100 rounded-3xl p-10 md:p-16 flex flex-col md:flex-row items-center gap-10">
            <div class="flex-1 relative h-64 md:h-auto">
                <img src="/generated/image-professional-photographer-working-at-a-c-1767636984691-0.webp" alt="Filippa Trajkovski" class="w-full h-full object-cover rounded-2xl" />
            </div>
            <div class="flex-1 bg-white/90 backdrop-blur rounded-2xl p-8 shadow-sm">
                <div class="text-xs font-bold text-gray-400 uppercase mb-4">Customer Story</div>
                <h3 class="text-2xl font-serif mb-4">Creating with freedom, not friction</h3>
                <p class="text-gray-600 text-sm mb-6">Filippa Trajkovski is a photographer who needed structure around her creativity. "My documents used to be all over the place. Now everything just works."</p>
                <div class="flex justify-between items-center">
                    <span class="text-xs text-gray-400">Published Nov 3, 2025</span>
                    <button class="bg-dark text-white px-4 py-2 rounded-lg text-xs font-bold hover:bg-gray-800 transition-colors">Read Story →</button>
                </div>
            </div>
        </div>

        <!-- Bottom Left -->
        <div class="bg-gray-100 rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="relative h-32 mb-4 rounded-xl overflow-hidden">
                <img src="/generated/image-young-creative-professional-age-23-worki-1767636988330-1.webp" alt="Kajsa Molund" class="w-full h-full object-cover" />
            </div>
            <div class="bg-white rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Customer Story</div>
                <h3 class="text-xl font-serif mb-4">Finding space to grow at 23</h3>
                <p class="text-gray-600 text-sm mb-4">Kajsa Molund runs a full-time creative business while Bronn handles her bookkeeping.</p>
                <div class="flex justify-between items-center">
                    <span class="text-xs text-gray-400">Nov 13, 2025</span>
                    <button class="bg-dark text-white px-3 py-1.5 rounded-lg text-xs font-bold hover:bg-gray-800 transition-colors">Read →</button>
                </div>
            </div>
        </div>

        <!-- Bottom Right -->
        <div class="bg-gray-100 rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="relative h-32 mb-4 rounded-xl overflow-hidden">
                <img src="/generated/image-confident-entrepreneur-working-energetic-1767636991171-2.webp" alt="Emil" class="w-full h-full object-cover" />
            </div>
            <div class="bg-white rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Customer Story</div>
                <h3 class="text-xl font-serif mb-4">Inside a fast-growing company</h3>
                <p class="text-gray-600 text-sm mb-4">Emil turned admin stress into extra time for what he loves with Bronn's support.</p>
                <div class="flex justify-between items-center">
                    <span class="text-xs text-gray-400">Nov 13, 2025</span>
                    <button class="bg-dark text-white px-3 py-1.5 rounded-lg text-xs font-bold hover:bg-gray-800 transition-colors">Read →</button>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-4 text-center">Frequently Asked Questions</h2>
      <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">
        Everything you need to know about Bronn's services.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "What is Bronn?",
            "Who is Bronn for?",
            "How does AI automation work?",
            "Do I get a dedicated advisor?",
            "What does bookkeeping include?",
            "How do you handle Swedish taxes?",
            "How quickly do you respond?",
            "How do I get started?"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-primary-600 transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-primary-600 transition-colors">+</div>
            </div>
        {/each}
      </div>
    </div>
  </section>

  <Footer />
</div>

<style>
  /* Custom Scroll Animation */
  @keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  .animate-scroll {
    animation: scroll 20s linear infinite;
  }
  
  @keyframes spin-slow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .animate-spin-slow {
    animation: spin-slow 20s linear infinite;
  }
</style>

