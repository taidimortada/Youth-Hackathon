<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Baosala Tangier — Project Documentation</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
  <style>
    html { scroll-behavior: smooth; }
    body { font-family: 'DM Sans', sans-serif; background:#f8f5ef; color:#172a3a; }
    h1,h2,h3 { font-family:'Playfair Display',serif; }
    .hero { background:linear-gradient(135deg,#0f2b48 0%,#17466a 55%,#8c4937 100%); }
    .pattern {
      background-image:
        linear-gradient(45deg, rgba(244,191,67,.12) 25%, transparent 25%),
        linear-gradient(-45deg, rgba(244,191,67,.12) 25%, transparent 25%);
      background-size:24px 24px;
    }
    .card { background:white; border:1px solid #e6e1d8; box-shadow:0 8px 30px rgba(15,43,72,.07); }
    .accent { color:#b65b43; }
    .section { scroll-margin-top:90px; }
    code { background:#eef1f4; padding:2px 6px; border-radius:5px; }
    pre { overflow:auto; }
  </style>
</head>

<body>

<!-- ========================= HERO ========================= -->
<header class="hero text-white pattern">
  <div class="max-w-6xl mx-auto px-6 py-20">
    <div class="max-w-4xl">
      <p class="uppercase tracking-[.25em] text-amber-300 font-bold text-sm mb-5">
        Project Documentation · Tangier · Morocco
      </p>

      <h1 class="text-5xl md:text-7xl leading-tight mb-6">
        Baosala Tangier
      </h1>

      <p class="text-xl md:text-2xl text-slate-200 max-w-3xl leading-relaxed">
        Discover Tangier differently — connecting travelers with heritage,
        local culture, food, artisans, activities and authentic experiences.
      </p>

      <div class="flex flex-wrap gap-3 mt-8">
        <span class="px-4 py-2 rounded-full bg-white/10 border border-white/20">🇲🇦 Morocco</span>
        <span class="px-4 py-2 rounded-full bg-white/10 border border-white/20">📱 Mobile-first</span>
        <span class="px-4 py-2 rounded-full bg-white/10 border border-white/20">🌍 Cultural Tourism</span>
        <span class="px-4 py-2 rounded-full bg-white/10 border border-white/20">🚀 Prototype</span>
      </div>
    </div>
  </div>
</header>

<!-- ========================= NAV ========================= -->
<nav class="sticky top-0 z-50 bg-white/95 backdrop-blur border-b border-slate-200">
  <div class="max-w-6xl mx-auto px-6 py-3 flex gap-4 overflow-x-auto text-sm font-semibold">
    <a href="#introduction" class="whitespace-nowrap hover:text-[#b65b43]">Introduction</a>
    <a href="#problem" class="whitespace-nowrap hover:text-[#b65b43]">Problem</a>
    <a href="#solution" class="whitespace-nowrap hover:text-[#b65b43]">Solution</a>
    <a href="#objectives" class="whitespace-nowrap hover:text-[#b65b43]">Objectives</a>
    <a href="#features" class="whitespace-nowrap hover:text-[#b65b43]">Features</a>
    <a href="#innovation" class="whitespace-nowrap hover:text-[#b65b43]">Innovation</a>
    <a href="#technology" class="whitespace-nowrap hover:text-[#b65b43]">Technology</a>
    <a href="#workflow" class="whitespace-nowrap hover:text-[#b65b43]">How It Works</a>
    <a href="#impact" class="whitespace-nowrap hover:text-[#b65b43]">Impact</a>
    <a href="#future" class="whitespace-nowrap hover:text-[#b65b43]">Future</a>
    <a href="#conclusion" class="whitespace-nowrap hover:text-[#b65b43]">Conclusion</a>
  </div>
</nav>

<main class="max-w-6xl mx-auto px-6 py-12 space-y-20">

<!-- ========================= 1 INTRODUCTION ========================= -->
<section id="introduction" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">01 · Introduction</p>
    <h2 class="text-4xl md:text-5xl mt-2">Discover Tangier Beyond the Tourist Map</h2>
  </div>

  <div class="grid md:grid-cols-2 gap-8 items-start">
    <div class="card rounded-3xl p-8">
      <p class="text-lg leading-8 text-slate-600">
        Baosala Tangier is a tourism web application designed to help visitors
        discover Tangier through a more local and personalized experience.
      </p>
      <p class="text-lg leading-8 text-slate-600 mt-5">
        The project brings together places, Moroccan food, artisan workshops,
        activities, stays, trip planning and traveler experiences inside one
        digital platform.
      </p>
    </div>

    <div class="hero rounded-3xl p-8 text-white">
      <p class="text-amber-300 font-bold mb-3">PROJECT VISION</p>
      <h3 class="text-3xl mb-4">Don't just visit Tangier. Experience it.</h3>
      <p class="text-slate-200 leading-7">
        The application aims to create a stronger connection between visitors
        and the cultural identity of Tangier.
      </p>
    </div>
  </div>
</section>

<!-- ========================= 2 PROBLEM ========================= -->
<section id="problem" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">02 · Problem</p>
    <h2 class="text-4xl md:text-5xl mt-2">The Problem We Want to Address</h2>
  </div>

  <div class="card rounded-3xl p-8 md:p-10">
    <div class="border-l-4 border-[#b65b43] pl-6 mb-8">
      <h3 class="text-2xl mb-2">The disconnection between mass tourism and authentic cultural experiences.</h3>
      <p class="text-slate-600 leading-7">
        Visitors can find famous attractions online, but discovering local
        crafts, food, hidden places, cultural activities and meaningful
        experiences can be more difficult.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-5">
      <div class="p-5 rounded-2xl bg-slate-50">
        <div class="text-3xl mb-3">🗺️</div>
        <h3 class="font-bold text-lg mb-2">Scattered Information</h3>
        <p class="text-sm text-slate-600">Travel information is spread across different platforms.</p>
      </div>
      <div class="p-5 rounded-2xl bg-slate-50">
        <div class="text-3xl mb-3">🏛️</div>
        <h3 class="font-bold text-lg mb-2">Culture Can Be Missed</h3>
        <p class="text-sm text-slate-600">Visitors may miss local heritage and artisan experiences.</p>
      </div>
      <div class="p-5 rounded-2xl bg-slate-50">
        <div class="text-3xl mb-3">🎯</div>
        <h3 class="font-bold text-lg mb-2">Generic Trips</h3>
        <p class="text-sm text-slate-600">Standard recommendations do not always fit individual interests.</p>
      </div>
      <div class="p-5 rounded-2xl bg-slate-50">
        <div class="text-3xl mb-3">🤝</div>
        <h3 class="font-bold text-lg mb-2">Limited Connection</h3>
        <p class="text-sm text-slate-600">Travelers have fewer tools to connect around shared experiences.</p>
      </div>
    </div>
  </div>
</section>

<!-- ========================= 3 SOLUTION ========================= -->
<section id="solution" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">03 · Solution</p>
    <h2 class="text-4xl md:text-5xl mt-2">Our Solution: Baosala</h2>
  </div>

  <div class="grid lg:grid-cols-3 gap-6">
    <div class="card rounded-3xl p-7 lg:col-span-2">
      <h3 class="text-2xl mb-4">One platform for a complete Tangier experience</h3>
      <p class="text-slate-600 leading-8">
        Baosala combines discovery, planning, cultural assistance and traveler
        interaction in a single mobile-first interface.
      </p>

      <div class="grid sm:grid-cols-2 gap-4 mt-7">
        <div class="flex gap-3">
          <span>🏛️</span><span><strong>Discover:</strong> heritage, places and culture.</span>
        </div>
        <div class="flex gap-3">
          <span>🍲</span><span><strong>Taste:</strong> Moroccan food and local experiences.</span>
        </div>
        <div class="flex gap-3">
          <span>🧑‍🎨</span><span><strong>Connect:</strong> artisan workshops and local activities.</span>
        </div>
        <div class="flex gap-3">
          <span>🗺️</span><span><strong>Plan:</strong> build a personalized itinerary.</span>
        </div>
        <div class="flex gap-3">
          <span>🤝</span><span><strong>Meet:</strong> discover travelers with similar interests.</span>
        </div>
        <div class="flex gap-3">
          <span>💬</span><span><strong>Learn:</strong> traveler notes and cultural tools.</span>
        </div>
      </div>
    </div>

    <div class="hero rounded-3xl p-7 text-white">
      <p class="text-amber-300 font-bold text-sm mb-3">CORE IDEA</p>
      <h3 class="text-3xl mb-4">People → Places → Culture → Stories</h3>
      <p class="text-slate-200 leading-7">
        Baosala transforms a simple tourism search into a more connected
        cultural journey.
      </p>
    </div>
  </div>
</section>

<!-- ========================= 4 OBJECTIVES ========================= -->
<section id="objectives" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">04 · Objectives</p>
    <h2 class="text-4xl md:text-5xl mt-2">What We Want to Achieve</h2>
  </div>

  <div class="grid md:grid-cols-2 gap-5">
    <div class="card rounded-2xl p-6">
      <span class="text-3xl">🎯</span>
      <h3 class="text-xl mt-4 mb-2">Personalize Travel</h3>
      <p class="text-slate-600">Help visitors build experiences according to their interests, budget and travel style.</p>
    </div>
    <div class="card rounded-2xl p-6">
      <span class="text-3xl">🇲🇦</span>
      <h3 class="text-xl mt-4 mb-2">Promote Local Culture</h3>
      <p class="text-slate-600">Make heritage, crafts, food and local experiences easier to discover.</p>
    </div>
    <div class="card rounded-2xl p-6">
      <span class="text-3xl">🤝</span>
      <h3 class="text-xl mt-4 mb-2">Create Connections</h3>
      <p class="text-slate-600">Give travelers tools to discover people with similar interests and itineraries.</p>
    </div>
    <div class="card rounded-2xl p-6">
      <span class="text-3xl">📱</span>
      <h3 class="text-xl mt-4 mb-2">Make Travel Simpler</h3>
      <p class="text-slate-600">Bring essential tourism tools together in one accessible mobile interface.</p>
    </div>
  </div>
</section>

<!-- ========================= 5 FEATURES ========================= -->
<section id="features" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">05 · Features</p>
    <h2 class="text-4xl md:text-5xl mt-2">How the App Helps the Traveler</h2>
  </div>

  <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 hero flex items-center justify-center text-6xl">🏠</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">Home</h3>
        <p class="text-slate-600">A central dashboard with Tangier imagery, instant search, categories and featured experiences.</p>
      </div>
    </article>

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 bg-[#ead7bd] flex items-center justify-center text-6xl">🔎</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">Explore</h3>
        <p class="text-slate-600">Browse heritage, food, workshops, tours, stays, shopping and other local experiences.</p>
      </div>
    </article>

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 bg-[#d7e5df] flex items-center justify-center text-6xl">🗺️</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">My Plan</h3>
        <p class="text-slate-600">Create a trip according to duration, interests, budget, group and preferred travel style.</p>
      </div>
    </article>

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 bg-[#e8d8df] flex items-center justify-center text-6xl">🤝</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">Traveler Match</h3>
        <p class="text-slate-600">Compare interests, vibes, budget and group preferences to find compatible travelers.</p>
      </div>
    </article>

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 bg-[#dce6ee] flex items-center justify-center text-6xl">💬</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">Traveler Notes</h3>
        <p class="text-slate-600">A space for traveler experiences and recommendations. Current entries are prototype/demo content.</p>
      </div>
    </article>

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 bg-[#f0e4c5] flex items-center justify-center text-6xl">🗣️</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">Darija Translator</h3>
        <p class="text-slate-600">Useful Moroccan Arabic expressions to help visitors communicate locally.</p>
      </div>
    </article>

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 bg-[#dfe9d8] flex items-center justify-center text-6xl">💱</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">Currency</h3>
        <p class="text-slate-600">A tourism-oriented currency conversion interface centered around Moroccan Dirham.</p>
      </div>
    </article>

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 bg-[#e5ddea] flex items-center justify-center text-6xl">🌐</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">Multilingual</h3>
        <p class="text-slate-600">Interface translations for English, French, Arabic and Spanish.</p>
      </div>
    </article>

    <article class="card rounded-3xl overflow-hidden">
      <div class="h-32 bg-[#dce5e7] flex items-center justify-center text-6xl">🌙</div>
      <div class="p-6">
        <h3 class="text-2xl mb-2">Dark Mode</h3>
        <p class="text-slate-600">A responsive dark/light interface designed for comfortable use in different conditions.</p>
      </div>
    </article>

  </div>
</section>

<!-- ========================= 6 INNOVATION ========================= -->
<section id="innovation" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">06 · Innovation</p>
    <h2 class="text-4xl md:text-5xl mt-2">What Makes the Concept Different?</h2>
  </div>

  <div class="card rounded-3xl p-8 md:p-10">
    <div class="grid md:grid-cols-3 gap-8">
      <div>
        <div class="text-4xl mb-4">🧩</div>
        <h3 class="text-xl mb-2">All-in-One Experience</h3>
        <p class="text-slate-600 leading-7">
          Discovery, planning, cultural tools and traveler interaction are brought together.
        </p>
      </div>
      <div>
        <div class="text-4xl mb-4">🎯</div>
        <h3 class="text-xl mb-2">Personalization</h3>
        <p class="text-slate-600 leading-7">
          The trip planner uses visitor preferences rather than presenting only generic routes.
        </p>
      </div>
      <div>
        <div class="text-4xl mb-4">🇲🇦</div>
        <h3 class="text-xl mb-2">Local Identity</h3>
        <p class="text-slate-600 leading-7">
          The visual language and content focus on Tangier and Moroccan culture.
        </p>
      </div>
    </div>
  </div>
</section>

<!-- ========================= 7 TECHNOLOGY ========================= -->
<section id="technology" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">07 · Technology</p>
    <h2 class="text-4xl md:text-5xl mt-2">Technical Implementation</h2>
  </div>

  <div class="grid lg:grid-cols-2 gap-6">

    <div class="card rounded-3xl p-8">
      <h3 class="text-2xl mb-5">Frontend</h3>
      <div class="space-y-3">
        <div class="p-4 bg-slate-50 rounded-xl"><strong>HTML5</strong> — application structure and pages.</div>
        <div class="p-4 bg-slate-50 rounded-xl"><strong>CSS / Tailwind CSS</strong> — responsive visual design.</div>
        <div class="p-4 bg-slate-50 rounded-xl"><strong>JavaScript</strong> — application logic and interactions.</div>
        <div class="p-4 bg-slate-50 rounded-xl"><strong>Google Fonts</strong> — typography.</div>
      </div>
    </div>

    <div class="card rounded-3xl p-8">
      <h3 class="text-2xl mb-5">Application Logic</h3>
      <pre class="bg-[#0f2b48] text-slate-100 rounded-2xl p-5 text-sm"><code>Application State
       ↓
Navigation
       ↓
Home / Explore / Plan
       ↓
Traveler Match / Profile
       ↓
Search + Language + Theme
       ↓
Dynamic UI Rendering</code></pre>
    </div>

    <div class="card rounded-3xl p-8">
      <h3 class="text-2xl mb-5">Important Data Structures</h3>
      <pre class="bg-slate-900 text-slate-100 rounded-2xl p-5 text-sm"><code>PLACES_DATA
MATCH_PROFILES
USER_NOTES
T
S</code></pre>
      <p class="text-slate-600 mt-4">
        Tourism content, traveler profiles, notes, translations and application state are currently handled in JavaScript.
      </p>
    </div>

    <div class="card rounded-3xl p-8">
      <h3 class="text-2xl mb-5">Main Functions</h3>
      <pre class="bg-slate-900 text-slate-100 rounded-2xl p-5 text-sm"><code>navigate()
renderMainContent()
renderHomeView()
renderExploreView()
renderPlanView()
renderMatchView()
renderProfileView()
changeLanguage()
toggleTheme()
handleSearchInput()
generatePlanItinerary()</code></pre>
    </div>

  </div>
</section>

<!-- ========================= 8 WORKFLOW ========================= -->
<section id="workflow" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">08 · How It Works</p>
    <h2 class="text-4xl md:text-5xl mt-2">A Typical Traveler Journey</h2>
  </div>

  <div class="space-y-4">
    <div class="card rounded-2xl p-5 flex items-center gap-5">
      <div class="w-12 h-12 rounded-full hero text-white flex items-center justify-center font-bold">1</div>
      <div><h3 class="text-xl">Discover</h3><p class="text-slate-600">The traveler enters Baosala and explores Tangier through the Home and Explore sections.</p></div>
    </div>
    <div class="card rounded-2xl p-5 flex items-center gap-5">
      <div class="w-12 h-12 rounded-full hero text-white flex items-center justify-center font-bold">2</div>
      <div><h3 class="text-xl">Choose Interests</h3><p class="text-slate-600">The traveler selects interests such as heritage, food, crafts, activities or coastal experiences.</p></div>
    </div>
    <div class="card rounded-2xl p-5 flex items-center gap-5">
      <div class="w-12 h-12 rounded-full hero text-white flex items-center justify-center font-bold">3</div>
      <div><h3 class="text-xl">Build a Plan</h3><p class="text-slate-600">My Plan uses trip preferences to generate an itinerary.</p></div>
    </div>
    <div class="card rounded-2xl p-5 flex items-center gap-5">
      <div class="w-12 h-12 rounded-full hero text-white flex items-center justify-center font-bold">4</div>
      <div><h3 class="text-xl">Connect</h3><p class="text-slate-600">Traveler Match introduces profiles with similar interests and travel preferences.</p></div>
    </div>
    <div class="card rounded-2xl p-5 flex items-center gap-5">
      <div class="w-12 h-12 rounded-full hero text-white flex items-center justify-center font-bold">5</div>
      <div><h3 class="text-xl">Experience</h3><p class="text-slate-600">The visitor discovers local places, food, workshops and cultural experiences.</p></div>
    </div>
  </div>
</section>

<!-- ========================= 9 IMPACT ========================= -->
<section id="impact" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">09 · Impact</p>
    <h2 class="text-4xl md:text-5xl mt-2">Expected Impact</h2>
  </div>

  <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-5">
    <div class="hero rounded-3xl p-6 text-white">
      <div class="text-4xl mb-5">🧑‍🎨</div>
      <h3 class="text-xl mb-2">Local Artisans</h3>
      <p class="text-slate-200 text-sm leading-6">Increase visibility of local craft and workshop experiences.</p>
    </div>
    <div class="hero rounded-3xl p-6 text-white">
      <div class="text-4xl mb-5">🍲</div>
      <h3 class="text-xl mb-2">Local Food</h3>
      <p class="text-slate-200 text-sm leading-6">Help visitors discover Moroccan culinary culture.</p>
    </div>
    <div class="hero rounded-3xl p-6 text-white">
      <div class="text-4xl mb-5">🏛️</div>
      <h3 class="text-xl mb-2">Heritage</h3>
      <p class="text-slate-200 text-sm leading-6">Encourage exploration of Tangier's cultural and historical identity.</p>
    </div>
    <div class="hero rounded-3xl p-6 text-white">
      <div class="text-4xl mb-5">🤝</div>
      <h3 class="text-xl mb-2">Travelers</h3>
      <p class="text-slate-200 text-sm leading-6">Create a more personalized and socially connected travel experience.</p>
    </div>
  </div>
</section>

<!-- ========================= 10 LIMITATIONS ========================= -->
<section class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">10 · Current Status</p>
    <h2 class="text-4xl md:text-5xl mt-2">Prototype Limitations</h2>
  </div>

  <div class="card rounded-3xl p-8">
    <p class="text-slate-600 leading-7 mb-6">
      The current version is a frontend prototype. Several concepts are
      represented through demo data and interface interactions and would
      require backend services for a production application.
    </p>

    <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-3">
      <span class="p-3 rounded-xl bg-slate-50">Real authentication</span>
      <span class="p-3 rounded-xl bg-slate-50">Database</span>
      <span class="p-3 rounded-xl bg-slate-50">Real user profiles</span>
      <span class="p-3 rounded-xl bg-slate-50">Real-time chat</span>
      <span class="p-3 rounded-xl bg-slate-50">Real bookings</span>
      <span class="p-3 rounded-xl bg-slate-50">Production AI assistant</span>
      <span class="p-3 rounded-xl bg-slate-50">Live maps/GPS</span>
      <span class="p-3 rounded-xl bg-slate-50">Push notifications</span>
      <span class="p-3 rounded-xl bg-slate-50">Server-side security</span>
    </div>
  </div>
</section>

<!-- ========================= 11 FUTURE ========================= -->
<section id="future" class="section">
  <div class="mb-8">
    <p class="uppercase tracking-widest text-sm font-bold accent">11 · Future Development</p>
    <h2 class="text-4xl md:text-5xl mt-2">From Prototype to Real Platform</h2>
  </div>

  <div class="grid md:grid-cols-2 gap-6">
    <div class="card rounded-3xl p-7">
      <h3 class="text-2xl mb-4">🗺️ Smart Maps</h3>
      <ul class="space-y-2 text-slate-600">
        <li>• Interactive Tangier map</li>
        <li>• Walking routes</li>
        <li>• Nearby experiences</li>
        <li>• GPS-based recommendations</li>
      </ul>
    </div>

    <div class="card rounded-3xl p-7">
      <h3 class="text-2xl mb-4">🤖 AI Personalization</h3>
      <ul class="space-y-2 text-slate-600">
        <li>• Personalized itinerary generation</li>
        <li>• AI tourism assistant</li>
        <li>• Natural-language search</li>
        <li>• Intelligent recommendations</li>
      </ul>
    </div>

    <div class="card rounded-3xl p-7">
      <h3 class="text-2xl mb-4">👥 Community</h3>
      <ul class="space-y-2 text-slate-600">
        <li>• Real traveler reviews</li>
        <li>• Verified traveler notes</li>
        <li>• Local guide profiles</li>
        <li>• Artisan profiles</li>
      </ul>
    </div>

    <div class="card rounded-3xl p-7">
      <h3 class="text-2xl mb-4">📲 Production PWA</h3>
      <ul class="space-y-2 text-slate-600">
        <li>• Installable mobile application</li>
        <li>• Offline support</li>
        <li>• Push notifications</li>
        <li>• Production backend and database</li>
      </ul>
    </div>
  </div>
</section>

<!-- ========================= 12 CONCLUSION ========================= -->
<section id="conclusion" class="section">
  <div class="hero rounded-[2rem] p-10 md:p-16 text-white text-center">
    <p class="uppercase tracking-[.25em] text-amber-300 font-bold text-sm mb-5">12 · Conclusion</p>
    <h2 class="text-4xl md:text-6xl mb-6">A Different Way to Discover Tangier</h2>
    <p class="max-w-3xl mx-auto text-lg md:text-xl text-slate-200 leading-8">
      Baosala Tangier is more than a list of tourist attractions.
      It is a concept for connecting visitors with the places, people,
      food, crafts, stories and culture that make Tangier unique.
    </p>

    <div class="mt-10 text-2xl font-semibold">
      🧭 Baosala — Discover Tangier Differently.
    </div>
  </div>
</section>

</main>

<footer class="bg-[#0f2b48] text-white mt-10">
  <div class="max-w-6xl mx-auto px-6 py-10 flex flex-col md:flex-row justify-between gap-6">
    <div>
      <h3 class="text-2xl">Baosala Tangier</h3>
      <p class="text-slate-300 mt-2">Cultural tourism · Tangier, Morocco 🇲🇦</p>
    </div>
    <div class="text-sm text-slate-400">
      Project Documentation · Prototype Version
    </div>
  </div>
</footer>

</body>
</html>
