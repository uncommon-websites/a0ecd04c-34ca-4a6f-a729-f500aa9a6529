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
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">LA's Smartest Nightlife Discovery App</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Stop scrolling. <br class="hidden md:block" /> Start vibing.
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      AI-powered nightlife discovery that matches you with the perfect events based on your vibe. 
      Real-time crowd predictions, personalized recommendations, and zero FOMO.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#" type="primary">Download App</Button>
      <Button href="#" type="outline">See How It Works</Button>
    </div>

    <!-- Hero Image Placeholder -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-gradient-to-br from-gray-900 to-gray-800 aspect-[16/9] mb-16 group">
      <!-- Mock Phone UI -->
      <div class="absolute inset-0 flex items-center justify-center p-8">
        <div class="w-full max-w-sm h-full bg-black rounded-3xl border-4 border-gray-700 shadow-2xl p-4 flex flex-col">
            <!-- Status Bar -->
            <div class="flex justify-between items-center mb-4 text-white text-xs">
                <span>9:41</span>
                <div class="flex gap-1">
                    <div class="w-4 h-3 bg-white/30 rounded-sm"></div>
                    <div class="w-4 h-3 bg-white/30 rounded-sm"></div>
                    <div class="w-4 h-3 bg-white/30 rounded-sm"></div>
                </div>
            </div>
            <!-- Search Bar -->
            <div class="bg-gray-800 rounded-full px-4 py-2 mb-4 flex items-center gap-2">
                <div class="w-4 h-4 bg-orange-brand/50 rounded-full"></div>
                <span class="text-gray-400 text-xs">Find your vibe tonight...</span>
            </div>
            <!-- Event Cards -->
            <div class="flex-1 space-y-3 overflow-hidden">
                <div class="bg-gradient-to-br from-purple-600 to-pink-600 rounded-2xl p-4 relative h-32">
                    <div class="absolute top-2 right-2 bg-black/50 backdrop-blur px-2 py-1 rounded-full text-white text-[8px] font-bold">🔥 HOT</div>
                    <div class="absolute bottom-2 left-2 text-white">
                        <div class="text-xs font-bold">Rooftop Vibes</div>
                        <div class="text-[10px] opacity-80">Downtown LA • 10pm</div>
                    </div>
                </div>
                <div class="bg-gradient-to-br from-blue-600 to-cyan-600 rounded-2xl p-4 relative h-32">
                    <div class="absolute top-2 right-2 bg-black/50 backdrop-blur px-2 py-1 rounded-full text-white text-[8px] font-bold">95% Match</div>
                    <div class="absolute bottom-2 left-2 text-white">
                        <div class="text-xs font-bold">House Music Night</div>
                        <div class="text-[10px] opacity-80">Arts District • 11pm</div>
                    </div>
                </div>
            </div>
        </div>
      </div>
      
      <!-- Decorative Elements -->
      <div class="absolute -left-12 bottom-12 w-24 h-24 bg-orange-brand rounded-full blur-2xl opacity-30"></div>
      <div class="absolute -right-12 top-12 w-32 h-32 bg-purple-400 rounded-full blur-2xl opacity-30"></div>

      <!-- Floating Vibe Indicator -->
      <div class="absolute bottom-8 right-8 bg-white rounded-2xl p-4 shadow-xl hidden md:block">
          <div class="text-xs font-bold text-gray-600 mb-2">Live Vibe Score</div>
          <div class="flex items-center gap-2">
              <div class="text-3xl font-bold text-orange-brand">94</div>
              <div class="text-xs text-gray-500">Perfect<br/>match!</div>
          </div>
      </div>
    </div>

    <!-- Logos -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Featured in LA's top nightlife venues and event platforms</p>
      <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
        <!-- The Fonda -->
        <span class="font-bold text-xl">The Fonda</span>
        <!-- Exchange LA -->
        <span class="font-bold text-xl">Exchange LA</span>
        <!-- Sound Nightclub -->
        <span class="font-bold text-xl">Sound</span>
        <!-- Academy LA -->
        <span class="font-bold text-xl">Academy LA</span>
        <!-- Resident Advisor -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-black rounded"></div> RA</span>
        <!-- DICE -->
        <span class="font-bold text-xl">DICE</span>
      </div>
    </div>
  </section>

  <!-- Stats Section -->
  <section class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-3xl mx-auto">
        Discover LA's hottest events with AI-powered precision
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">500+</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Events Weekly</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">50K+</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Active Users</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">95%</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Match Accuracy</div>
        </div>
      </div>

      <!-- Event Cards Carousel Mockup -->
      <div class="flex gap-4 overflow-hidden relative">
        <div class="absolute inset-y-0 left-0 w-20 bg-gradient-to-r from-white to-transparent z-10"></div>
        <div class="absolute inset-y-0 right-0 w-20 bg-gradient-to-l from-white to-transparent z-10"></div>
        
        <div class="flex gap-4 animate-scroll">
            <!-- Card 1 -->
            <div class="w-64 h-80 bg-gradient-to-br from-purple-600 to-pink-600 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-pink-500 rounded-full"></div> House
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/80 to-transparent p-4 text-white">
                    <div class="font-bold">Rooftop Sessions</div>
                    <div class="text-xs opacity-80">Downtown LA • Tonight 10pm</div>
                    <div class="text-xs mt-2 bg-orange-brand/80 inline-block px-2 py-1 rounded">🔥 95% Match</div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="w-64 h-80 bg-gradient-to-br from-blue-600 to-cyan-600 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-blue-500 rounded-full"></div> Techno
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/80 to-transparent p-4 text-white">
                    <div class="font-bold">Underground Vibes</div>
                    <div class="text-xs opacity-80">Arts District • Fri 11pm</div>
                    <div class="text-xs mt-2 bg-orange-brand/80 inline-block px-2 py-1 rounded">🔥 92% Match</div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="w-64 h-80 bg-gradient-to-br from-orange-500 to-red-600 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-red-500 rounded-full"></div> Hip-Hop
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/80 to-transparent p-4 text-white">
                    <div class="font-bold">Late Night Grooves</div>
                    <div class="text-xs opacity-80">Hollywood • Sat 12am</div>
                    <div class="text-xs mt-2 bg-orange-brand/80 inline-block px-2 py-1 rounded">🔥 88% Match</div>
                </div>
            </div>
             <!-- Card 4 -->
            <div class="w-64 h-80 bg-gradient-to-br from-green-600 to-teal-600 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-green-500 rounded-full"></div> Live Music
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/80 to-transparent p-4 text-white">
                    <div class="font-bold">Jazz & Cocktails</div>
                    <div class="text-xs opacity-80">West Hollywood • Thu 9pm</div>
                    <div class="text-xs mt-2 bg-orange-brand/80 inline-block px-2 py-1 rounded">🔥 90% Match</div>
                </div>
            </div>
             <!-- Card 5 -->
            <div class="w-64 h-80 bg-gradient-to-br from-yellow-500 to-orange-600 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-yellow-500 rounded-full"></div> EDM
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/80 to-transparent p-4 text-white">
                    <div class="font-bold">Electric Nights</div>
                    <div class="text-xs opacity-80">DTLA • Sat 11pm</div>
                    <div class="text-xs mt-2 bg-orange-brand/80 inline-block px-2 py-1 rounded">🔥 94% Match</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Disrupted Section -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">Finding nightlife plans <br /> shouldn't be this hard</h2>
      <p class="text-center text-gray-400 mb-16">We're fixing the broken nightlife discovery experience.</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- The Old Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">The Old Way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Scrolling through fragmented event listings, checking multiple apps, asking friends, and still ending up at the wrong vibe. Hours wasted, FOMO guaranteed.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 relative">
             <div class="space-y-3">
                <div class="flex items-center gap-3 text-sm text-gray-400">
                    <div class="w-8 h-8 bg-blue-500/20 rounded flex items-center justify-center">📱</div>
                    <span>Check Instagram</span>
                </div>
                <div class="flex items-center gap-3 text-sm text-gray-400">
                    <div class="w-8 h-8 bg-green-500/20 rounded flex items-center justify-center">🎫</div>
                    <span>Browse Eventbrite</span>
                </div>
                <div class="flex items-center gap-3 text-sm text-gray-400">
                    <div class="w-8 h-8 bg-red-500/20 rounded flex items-center justify-center">💬</div>
                    <span>Text 5 friends</span>
                </div>
                <div class="flex items-center gap-3 text-sm text-gray-400">
                    <div class="w-8 h-8 bg-purple-500/20 rounded flex items-center justify-center">🔍</div>
                    <span>Google "events near me"</span>
                </div>
                <div class="flex items-center gap-3 text-sm text-red-400 font-bold mt-6">
                    <div class="w-8 h-8 bg-red-500/20 rounded flex items-center justify-center">😓</div>
                    <span>2 hours wasted, still no plans</span>
                </div>
             </div>
          </div>
        </div>

        <!-- The New Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">The NOC/TURNA Way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            AI matches you with perfect events based on your vibe. Real-time crowd predictions tell you exactly what to expect. One app, zero FOMO.
          </p>
          <div class="relative h-64 flex items-center justify-center">
             <!-- Central Phone Icon -->
             <div class="relative z-10 w-32 h-32 bg-gradient-to-br from-orange-brand to-pink-500 rounded-3xl flex items-center justify-center shadow-2xl">
                <svg class="w-16 h-16 text-white" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path opacity="0.7" d="M9.22279 15.2235C12.6595 15.2235 15.4456 12.4375 15.4456 9.00075C15.4456 5.56399 12.6595 2.77795 9.22279 2.77795C5.78604 2.77795 3 5.56399 3 9.00075C3 12.4375 5.78604 15.2235 9.22279 15.2235Z" fill="currentColor"/>
                    <path opacity="0.7" d="M14.5566 20.5574C17.9933 20.5574 20.7794 17.7713 20.7794 14.3346C20.7794 10.8978 17.9933 8.11179 14.5566 8.11179C11.1198 8.11179 8.3338 10.8978 8.3338 14.3346C8.3338 17.7713 11.1198 20.5574 14.5566 20.5574Z" fill="currentColor"/>
                </svg>
             </div>
             <!-- Orbiting Features -->
             <div class="absolute inset-0 animate-spin-slow">
                <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-4 bg-white rounded-lg px-3 py-2 shadow-lg text-xs font-bold text-dark">AI Match</div>
                <div class="absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-4 bg-white rounded-lg px-3 py-2 shadow-lg text-xs font-bold text-dark">Live Vibes</div>
                <div class="absolute left-0 top-1/2 -translate-x-4 -translate-y-1/2 bg-white rounded-lg px-3 py-2 shadow-lg text-xs font-bold text-dark">Instant</div>
                <div class="absolute right-0 top-1/2 translate-x-4 -translate-y-1/2 bg-white rounded-lg px-3 py-2 shadow-lg text-xs font-bold text-dark">Zero FOMO</div>
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section 1 (Purple) -->
  <section class="py-24 bg-cream" id="features">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Your perfect night out, powered by AI
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: AI Matching -->
        <div class="lg:col-span-2 bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">AI-powered event matching</h3>
                <p class="text-gray-500 text-sm">Tell us your vibe and our AI instantly matches you with events you'll love. No more endless scrolling through listings that don't fit.</p>
            </div>
            <div class="bg-purple-50 rounded-xl p-6 h-64 relative border border-purple-100">
                <!-- Mock Search Bar -->
                <div class="bg-white rounded-full p-2 shadow-sm flex items-center gap-2 mb-4 w-3/4 mx-auto">
                    <div class="w-8 h-8 bg-purple-100 rounded-full flex items-center justify-center text-purple-600">✨</div>
                    <div class="text-sm text-gray-400">House music, chill vibes</div>
                    <div class="ml-auto bg-black text-white px-4 py-1.5 rounded-full text-xs font-bold">Find</div>
                </div>
                <!-- Results Mockup -->
                <div class="flex gap-4 justify-center">
                    <div class="bg-gradient-to-br from-purple-500 to-pink-500 p-3 rounded-xl shadow-sm w-32 text-white">
                        <div class="text-xs font-bold mb-1">Rooftop Sessions</div>
                        <div class="text-[10px] opacity-80">95% Match</div>
                        <div class="mt-2 bg-white/20 rounded px-2 py-1 text-[8px]">Tonight 10pm</div>
                    </div>
                    <div class="bg-gradient-to-br from-blue-500 to-cyan-500 p-3 rounded-xl shadow-sm w-32 text-white">
                        <div class="text-xs font-bold mb-1">Underground</div>
                        <div class="text-[10px] opacity-80">92% Match</div>
                        <div class="mt-2 bg-white/20 rounded px-2 py-1 text-[8px]">Fri 11pm</div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Card 2: Coverage -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">All of LA nightlife in one app</h3>
                <p class="text-gray-500 text-sm">From underground raves to rooftop lounges. House, techno, hip-hop, live music, and everything in between.</p>
            </div>
            <div class="bg-purple-50 rounded-xl h-48 relative overflow-hidden flex items-center justify-center">
                <div class="flex gap-2 flex-wrap justify-center p-4">
                    <span class="bg-white px-3 py-1.5 rounded-full shadow-sm text-xs font-medium">🎵 House</span>
                    <span class="bg-white px-3 py-1.5 rounded-full shadow-sm text-xs font-medium">🎧 Techno</span>
                    <span class="bg-white px-3 py-1.5 rounded-full shadow-sm text-xs font-medium">🎤 Hip-Hop</span>
                    <span class="bg-white px-3 py-1.5 rounded-full shadow-sm text-xs font-medium">🎸 Live</span>
                    <span class="bg-white px-3 py-1.5 rounded-full shadow-sm text-xs font-medium">🍸 Lounges</span>
                    <span class="bg-white px-3 py-1.5 rounded-full shadow-sm text-xs font-medium">🎭 Events</span>
                </div>
            </div>
        </div>

        <!-- Card 3: Event Details -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 relative">
                <div class="bg-gradient-to-br from-purple-600 to-pink-600 rounded-xl shadow-lg p-4 h-full w-full relative transform rotate-[-2deg]">
                    <div class="flex items-center gap-3 mb-3 text-white">
                        <div class="w-10 h-10 bg-white/20 rounded-full"></div>
                        <div>
                            <div class="text-sm font-bold">Rooftop Vibes</div>
                            <div class="text-xs opacity-80">Downtown LA</div>
                        </div>
                    </div>
                    <div class="flex gap-2 mt-4">
                        <div class="h-16 w-1/3 bg-white/20 rounded-lg flex items-center justify-center text-white text-xs">🔥 Hot</div>
                        <div class="h-16 w-1/3 bg-white/20 rounded-lg flex items-center justify-center text-white text-xs">95%</div>
                        <div class="h-16 w-1/3 bg-white/20 rounded-lg flex items-center justify-center text-white text-xs">10pm</div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Rich event details</h3>
             <p class="text-gray-500 text-sm">See lineup, venue info, crowd predictions, and real user reviews all in one place.</p>
        </div>

        <!-- Card 4: Vibe Predictions -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 flex items-center justify-center">
                <div class="bg-white p-4 rounded-xl shadow-sm w-full max-w-[200px]">
                    <div class="text-xs text-gray-600 font-bold mb-3">Live Vibe Score</div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-xs text-gray-500">Crowd Energy</span>
                        <div class="flex gap-1">
                            <div class="w-2 h-6 bg-orange-brand rounded"></div>
                            <div class="w-2 h-6 bg-orange-brand rounded"></div>
                            <div class="w-2 h-6 bg-orange-brand rounded"></div>
                            <div class="w-2 h-6 bg-gray-200 rounded"></div>
                        </div>
                    </div>
                    <div class="flex justify-center mt-4">
                        <div class="text-3xl font-bold text-orange-brand">94</div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Real-time vibe predictions</h3>
             <p class="text-gray-500 text-sm">Know the crowd energy, music vibe, and atmosphere before you go. No more surprises.</p>
        </div>

        <!-- Card 5: Personalization -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 flex items-center justify-center relative">
                 <div class="bg-white p-4 rounded-xl shadow-sm w-full max-w-[220px]">
                    <div class="text-xs text-gray-600 font-bold mb-3">Your Preferences</div>
                    <div class="space-y-2">
                        <div class="flex items-center justify-between text-xs">
                            <span class="text-gray-500">House Music</span>
                            <span class="text-orange-brand font-bold">❤️</span>
                        </div>
                        <div class="flex items-center justify-between text-xs">
                            <span class="text-gray-500">Late Night</span>
                            <span class="text-orange-brand font-bold">❤️</span>
                        </div>
                        <div class="flex items-center justify-between text-xs">
                            <span class="text-gray-500">Rooftops</span>
                            <span class="text-orange-brand font-bold">❤️</span>
                        </div>
                    </div>
                    <div class="mt-4 pt-3 border-t border-gray-100">
                        <div class="w-10 h-10 rounded-full border-4 border-green-400 flex items-center justify-center text-xs font-bold text-green-600 mx-auto">95</div>
                    </div>
                 </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Learns your taste</h3>
             <p class="text-gray-500 text-sm">The more you use it, the smarter it gets. Your recommendations improve with every swipe.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 -->
  <section class="py-16 bg-cream">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="text-4xl">⭐⭐⭐⭐⭐</div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "Finally, an app that actually gets my vibe. No more wasting Friday nights at the wrong spot. NOC/TURNA's predictions are scary accurate."
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <div class="w-12 h-12 rounded-full bg-gradient-to-br from-purple-500 to-pink-500"></div>
            <div class="text-left">
                <div class="font-bold text-sm">Maya Rodriguez</div>
                <div class="text-xs text-gray-500">LA Nightlife Enthusiast</div>
            </div>
        </div>
    </div>
  </section>

  <!-- Features Section 2 (Blue) -->
  <section class="py-24 bg-cream" id="how-it-works">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        From discovery to <br /> door in minutes
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 relative overflow-hidden flex items-center justify-center">
                <!-- Swipe Interface Mockup -->
                <div class="relative w-48 h-56">
                    <div class="absolute inset-0 bg-gradient-to-br from-blue-600 to-cyan-600 rounded-2xl shadow-xl transform rotate-[-5deg] opacity-50"></div>
                    <div class="absolute inset-0 bg-gradient-to-br from-purple-600 to-pink-600 rounded-2xl shadow-xl p-4 text-white">
                        <div class="text-sm font-bold mb-1">Rooftop Sessions</div>
                        <div class="text-xs opacity-80 mb-4">Downtown LA • 10pm</div>
                        <div class="absolute bottom-4 left-4 right-4 flex gap-2">
                            <div class="flex-1 bg-white/20 rounded-lg py-2 text-center text-xs">👎</div>
                            <div class="flex-1 bg-white/20 rounded-lg py-2 text-center text-xs">❤️</div>
                        </div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Swipe to discover</h3>
            <p class="text-gray-500 text-sm">Tinder for nightlife. Swipe through personalized event recommendations and save the ones you love.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                 <div class="bg-white rounded-xl shadow-lg p-4 w-3/4">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="w-10 h-10 bg-gradient-to-br from-purple-500 to-pink-500 rounded-lg"></div>
                        <div>
                            <div class="text-xs font-bold">Rooftop Sessions</div>
                            <div class="text-[10px] text-gray-500">Tonight 10pm</div>
                        </div>
                    </div>
                    <div class="space-y-2 mb-4">
                        <div class="h-2 w-full bg-gray-100 rounded"></div>
                        <div class="h-2 w-5/6 bg-gray-100 rounded"></div>
                    </div>
                    <div class="flex gap-2">
                        <div class="flex-1 bg-gray-100 rounded py-2 text-center text-xs">Share</div>
                        <div class="flex-1 bg-orange-brand text-white rounded py-2 text-center text-xs font-bold">Get Tickets</div>
                    </div>
                 </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Seamless ticket booking</h3>
            <p class="text-gray-500 text-sm">Found the perfect event? Book tickets instantly without leaving the app. No more juggling multiple platforms.</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Friends Mockup -->
                <div class="bg-white rounded-xl shadow-sm p-4 w-3/4">
                    <div class="text-xs font-bold mb-3 text-gray-600">Friends Going</div>
                    <div class="space-y-2">
                        <div class="flex items-center gap-2">
                            <div class="w-6 h-6 bg-gradient-to-br from-blue-400 to-cyan-400 rounded-full"></div>
                            <span class="text-xs">Alex</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <div class="w-6 h-6 bg-gradient-to-br from-purple-400 to-pink-400 rounded-full"></div>
                            <span class="text-xs">Jordan</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <div class="w-6 h-6 bg-gradient-to-br from-orange-400 to-red-400 rounded-full"></div>
                            <span class="text-xs">Sam</span>
                        </div>
                    </div>
                    <div class="mt-4 pt-3 border-t border-gray-100">
                        <button class="w-full bg-orange-brand text-white rounded-lg py-2 text-xs font-bold">Invite Friends</button>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">See who's going</h3>
            <p class="text-gray-500 text-sm">Know which friends are attending before you commit. Coordinate plans and never go alone.</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Notification Mockup -->
                <div class="w-full max-w-sm space-y-3">
                    <div class="bg-white p-4 rounded-2xl shadow-lg border-l-4 border-orange-brand">
                        <div class="flex items-center gap-2 mb-2">
                            <div class="text-lg">🔥</div>
                            <div class="text-xs font-bold">Hot Event Alert!</div>
                        </div>
                        <div class="text-xs text-gray-600">Underground Vibes is 95% your vibe and starts in 2 hours</div>
                    </div>
                    <div class="bg-white p-4 rounded-2xl shadow-lg border-l-4 border-purple-500">
                        <div class="flex items-center gap-2 mb-2">
                            <div class="text-lg">👥</div>
                            <div class="text-xs font-bold">Friends Update</div>
                        </div>
                        <div class="text-xs text-gray-600">3 friends just saved Rooftop Sessions for tonight</div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Smart notifications</h3>
            <p class="text-gray-500 text-sm">Get alerted about perfect-match events, friend activity, and last-minute opportunities. Never miss out again.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Thousands of campaigns -->
  <section class="py-24 bg-cream relative overflow-hidden">
    <!-- Floating Icons Background (Simplified) -->
    <div class="absolute inset-0 opacity-10 pointer-events-none">
        <div class="absolute top-10 left-10 w-12 h-12 bg-black rounded-lg transform rotate-12"></div>
        <div class="absolute top-20 right-20 w-12 h-12 bg-blue-500 rounded-lg transform -rotate-6"></div>
        <div class="absolute bottom-20 left-1/3 w-12 h-12 bg-pink-500 rounded-lg transform rotate-45"></div>
        <div class="absolute bottom-10 right-1/4 w-12 h-12 bg-orange-500 rounded-lg transform -rotate-12"></div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-green-100 text-green-800 px-4 py-1 rounded-full text-xs font-bold mb-6">
            Join 50K+ LA nightlife seekers
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Your best nights out <br /> start here</h2>
        <p class="text-gray-500 mb-10">Download NOC/TURNA and never waste another Friday night</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Download App</Button>
            <Button href="#" type="white">Learn More</Button>
        </div>
    </div>
  </section>

  <!-- Payments Section (Green) -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Built for the way <br /> you actually go out
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Large Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 md:row-span-2 flex flex-col">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Last-minute plans? We got you</h3>
                <p class="text-gray-500 text-sm">It's 9pm and you have no plans? Browse events happening tonight with real-time availability and instant booking.</p>
            </div>
            <div class="flex-1 bg-green-50 rounded-2xl relative overflow-hidden min-h-[300px] p-6">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-green-200/50 to-transparent"></div>
                <!-- Time-based Event Cards -->
                <div class="relative space-y-3">
                    <div class="bg-white p-4 rounded-xl shadow-sm">
                        <div class="flex items-center justify-between mb-2">
                            <div class="text-sm font-bold">Rooftop Sessions</div>
                            <div class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-bold">Tonight</div>
                        </div>
                        <div class="text-xs text-gray-500">Starts in 1 hour • 95% match</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-sm">
                        <div class="flex items-center justify-between mb-2">
                            <div class="text-sm font-bold">Underground Vibes</div>
                            <div class="bg-orange-100 text-orange-700 px-2 py-1 rounded text-xs font-bold">Soon</div>
                        </div>
                        <div class="text-xs text-gray-500">Starts in 2 hours • 92% match</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-sm">
                        <div class="flex items-center justify-between mb-2">
                            <div class="text-sm font-bold">Late Night Grooves</div>
                            <div class="bg-purple-100 text-purple-700 px-2 py-1 rounded text-xs font-bold">Later</div>
                        </div>
                        <div class="text-xs text-gray-500">Starts at midnight • 88% match</div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Right Top Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="flex justify-between items-start mb-4">
                <div>
                     <h3 class="text-xl font-serif mb-2">Track your night out history</h3>
                     <p class="text-gray-500 text-sm">Remember that amazing venue from last month? All your past events, ratings, and memories in one place.</p>
                </div>
                <span class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-bold">Your Stats</span>
            </div>
            <div class="bg-green-50 rounded-xl h-40 p-4 space-y-2">
                <div class="flex items-center justify-between text-sm">
                    <span class="text-gray-600">Events Attended</span>
                    <span class="font-bold">47</span>
                </div>
                <div class="flex items-center justify-between text-sm">
                    <span class="text-gray-600">Favorite Genre</span>
                    <span class="font-bold">House</span>
                </div>
                <div class="flex items-center justify-between text-sm">
                    <span class="text-gray-600">Top Venue</span>
                    <span class="font-bold">Exchange LA</span>
                </div>
                <div class="flex items-center justify-between text-sm">
                    <span class="text-gray-600">Avg. Match Score</span>
                    <span class="font-bold text-orange-brand">94%</span>
                </div>
            </div>
        </div>

        <!-- Right Bottom Card (Testimonial) -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 flex gap-6 items-center">
            <div class="w-24 h-24 bg-gradient-to-br from-orange-400 to-pink-500 rounded-full flex-shrink-0 overflow-hidden flex items-center justify-center text-white text-3xl font-bold">
                JC
            </div>
            <div>
                <div class="text-green-600 text-4xl font-serif leading-none mb-2">"</div>
                <p class="text-sm text-gray-600 italic mb-4">I used to spend hours every week planning nights out. NOC/TURNA does it in seconds. Game changer.</p>
                <div class="text-xs font-bold">James Chen</div>
                <div class="text-[10px] text-gray-400">Tech Professional, Venice Beach</div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Powering People Grid -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Loved by LA's nightlife community
      </h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
         <!-- Row 1 -->
         <div class="aspect-square bg-gradient-to-br from-purple-600 to-pink-600 rounded-2xl relative overflow-hidden group flex items-center justify-center">
            <div class="text-white text-center p-4">
                <div class="text-4xl mb-2">⭐⭐⭐⭐⭐</div>
                <div class="text-sm font-bold">4.9 Rating</div>
            </div>
         </div>
         <div class="aspect-square bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-6">
            <div class="text-center">
                <div class="text-3xl font-bold text-orange-brand mb-2">50K+</div>
                <div class="text-sm text-gray-600">Active Users</div>
            </div>
         </div>
         <div class="col-span-2 bg-[#FFF9C4] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-yellow-600">"</div>
            <p class="text-lg font-serif leading-relaxed">This app literally changed my social life. I've discovered so many amazing events I never would have found otherwise.</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Sarah Martinez</div>
                    <div class="text-gray-500">Silver Lake Resident</div>
                </div>
                <div class="text-xl">⭐</div>
            </div>
         </div>

         <!-- Row 2 -->
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
            <span class="text-3xl font-bold text-gray-700">HubSpot</span>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Munch</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Freshbooks</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>

         <!-- Row 3 -->
         <div class="col-span-2 bg-[#E6F0FF] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-blue-600">"</div>
            <p class="text-lg font-serif leading-relaxed">The vibe predictions are insanely accurate. Saved me from so many bad nights out. This app just gets me.</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Marcus Johnson</div>
                    <div class="text-gray-500">DTLA Regular</div>
                </div>
                <div class="text-xl">⭐</div>
            </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <div class="text-center">
                 <div class="text-3xl font-bold text-orange-brand mb-2">95%</div>
                 <div class="text-sm text-gray-600">Match Accuracy</div>
             </div>
         </div>
         
         <!-- Row 4 -->
         <div class="aspect-square bg-gradient-to-br from-green-600 to-teal-600 rounded-2xl relative overflow-hidden group flex items-center justify-center text-white p-4">
             <div class="text-center">
                 <div class="text-3xl mb-2">👥</div>
                 <div class="text-sm font-bold">See Friends</div>
                 <div class="text-xs opacity-80 mt-1">Who's Going</div>
             </div>
         </div>
         <div class="aspect-square bg-gradient-to-br from-yellow-500 to-orange-600 rounded-2xl relative overflow-hidden group flex items-center justify-center text-white p-4">
             <div class="text-center">
                 <div class="text-3xl mb-2">🔔</div>
                 <div class="text-sm font-bold">Smart Alerts</div>
                 <div class="text-xs opacity-80 mt-1">Never Miss Out</div>
             </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <div class="text-center">
                 <div class="text-2xl font-bold mb-2">🏆 Featured in</div>
                 <div class="text-sm text-gray-600">LA Weekly • TimeOut LA</div>
             </div>
         </div>
      </div>
    </div>
  </section>

  <!-- Orange CTA Section -->
  <section class="bg-orange-brand py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-dark">Stop wasting nights. <br /> Start living them.</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-dark/80">
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                AI-powered event matching
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Real-time vibe predictions
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Download App</Button>
            <Button href="#" type="white">Learn More</Button>
        </div>
    </div>

    <!-- Bottom Illustration (Cartoon Line) -->
    <div class="absolute bottom-0 left-0 right-0 h-32 opacity-20 pointer-events-none flex items-end justify-center overflow-hidden">
        <!-- Abstract representation of the cartoon line -->
        <svg width="1200" height="100" viewBox="0 0 1200 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M0 100 C 50 50, 100 50, 150 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="75" cy="80" r="10" stroke="black" stroke-width="2"/>
            <path d="M150 100 C 200 60, 250 60, 300 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="225" cy="85" r="12" stroke="black" stroke-width="2"/>
            <path d="M300 100 C 350 40, 400 40, 450 100" stroke="black" stroke-width="2" fill="none"/>
             <circle cx="375" cy="70" r="15" stroke="black" stroke-width="2"/>
             <!-- Repeat pattern -->
             <path d="M450 100 C 500 50, 550 50, 600 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M600 100 C 650 60, 700 60, 750 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M750 100 C 800 40, 850 40, 900 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M900 100 C 950 50, 1000 50, 1050 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M1050 100 C 1100 60, 1150 60, 1200 100" stroke="black" stroke-width="2" fill="none"/>
        </svg>
    </div>
  </section>

  <!-- Case Studies -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">Case Studies</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Large Card Top -->
        <div class="md:col-span-2 bg-[#FFCCBC] rounded-3xl p-10 md:p-16 flex flex-col md:flex-row items-center gap-10">
            <div class="flex-1">
                <div class="text-4xl font-bold text-white mb-8">guidde.</div>
            </div>
            <div class="flex-1 bg-white/90 backdrop-blur rounded-2xl p-8 shadow-sm">
                <div class="text-xs font-bold text-gray-400 uppercase mb-4">Customer Story</div>
                <h3 class="text-2xl font-serif mb-4">How Marcus discovered 50+ events in his first month</h3>
                <p class="text-gray-500 text-sm mb-6">Guidde is the generative AI platform for business that helps teams create video documentation in a matter...</p>
                <div class="flex justify-between items-center">
                    <span class="text-xs text-gray-400">4 min read</span>
                    <button class="bg-black text-white px-4 py-2 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>

        <!-- Bottom Left -->
        <div class="bg-[#B3E5FC] rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="flex items-center gap-2 font-bold opacity-80 mb-8">
                <div class="w-6 h-6 bg-black rounded"></div> INTERCOM
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Customer Story</div>
                <h3 class="text-xl font-serif mb-4">Becoming the definitive AI-first Customer Service Platform</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">3 min read</span>
                    <button class="bg-black text-white px-3 py-1.5 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>

        <!-- Bottom Right -->
        <div class="bg-[#FFCC80] rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="flex items-center gap-2 font-bold opacity-80 mb-8 text-blue-900">
                <div class="w-6 h-6 bg-blue-600 rounded"></div> Freshbooks
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Customer Story</div>
                <h3 class="text-xl font-serif mb-4">How Freshbooks reached 2M+ impressions with Passionfroot</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">3 min read</span>
                    <button class="bg-black text-white px-3 py-1.5 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-16">Frequently Asked Questions</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "What is NOC\/TURNA??",
            "Is NOC\/TURNA free to use??",
            "How does the AI matching work??",
            "Which LA neighborhoods do you cover??",
            "How do I discover the right creators for my brand?",
            "How accurate are the vibe predictions??",
            "Is my data private and secure??",
            "How do I download NOC\/TURNA??"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-orange-brand transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-orange-brand transition-colors">+</div>
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

