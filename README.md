<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NextPhase Companies | Junk Removal, Demolition & Site Services Leamington</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter & Montserrat -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Montserrat:wght@700;800;900&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#0f172a',    // Dark slate body background
                            card: '#1e293b',    // Slate card container
                            light: '#334155',   // Slate borders/accents
                            orange: '#f97316',  // Primary construction orange
                            orangeHover: '#ea580c',
                            amber: '#fbbf24',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        .glow-orange {
            box-shadow: 0 0 25px -5px rgba(249, 115, 22, 0.4);
        }
        .bg-grid-pattern {
            background-image: radial-gradient(rgba(255, 255, 255, 0.08) 1px, transparent 1px);
            background-size: 24px 24px;
        }
    </style>
</head>
<body class="bg-brand-dark text-slate-100 font-sans antialiased selection:bg-brand-orange selection:text-white">

    <!-- TOP ANNOUNCEMENT BAR -->
    <div class="bg-brand-orange text-slate-950 font-bold text-xs sm:text-sm py-2 px-4 text-center tracking-wide flex items-center justify-center gap-2">
        <i class="fa-solid fa-bolt animate-pulse"></i>
        <span>SAME-DAY & EMERGENCY DEMO / HAULING AVAILABLE IN LEAMINGTON & ESSEX COUNTY</span>
        <a href="tel:5195550199" class="underline ml-2 hover:text-white transition-colors">(519) 555-0199</a>
    </div>

    <!-- MAIN NAVIGATION -->
    <nav class="sticky top-0 z-50 bg-brand-dark/95 backdrop-blur-md border-b border-brand-light/40 py-4 px-4 sm:px-8">
        <div class="max-w-7xl mx-auto flex items-center justify-between">
            <!-- Brand Logo -->
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-10 h-10 bg-brand-orange rounded-lg flex items-center justify-center text-slate-950 font-heading font-black text-xl shadow-lg group-hover:scale-105 transition-transform">
                    NP
                </div>
                <div>
                    <div class="font-heading font-extrabold text-lg sm:text-xl tracking-tight text-white leading-none">
                        NEXTPHASE<span class="text-brand-orange">.</span>
                    </div>
                    <div class="text-[10px] uppercase font-semibold text-slate-400 tracking-widest leading-tight">
                        COMPANIES
                    </div>
                </div>
            </a>

            <!-- Desktop Links -->
            <div class="hidden md:flex items-center gap-8 font-medium text-sm text-slate-300">
                <a href="#services" class="hover:text-brand-orange transition-colors">Divisions</a>
                <a href="#solutions" class="hover:text-brand-orange transition-colors">Who We Serve</a>
                <a href="#quote" class="hover:text-brand-orange transition-colors">Instant Quote</a>
                <a href="#coverage" class="hover:text-brand-orange transition-colors">Service Area</a>
            </div>

            <!-- Header CTAs -->
            <div class="flex items-center gap-3">
                <a href="tel:5195550199" class="hidden sm:flex items-center gap-2 bg-brand-card hover:bg-brand-light text-white text-xs sm:text-sm font-semibold py-2.5 px-4 rounded-lg border border-brand-light transition-all">
                    <i class="fa-solid fa-phone text-brand-orange"></i>
                    <span>(519) 555-0199</span>
                </a>
                <a href="#quote" class="bg-brand-orange hover:bg-brand-orangeHover text-slate-950 font-bold text-xs sm:text-sm py-2.5 px-5 rounded-lg shadow-md hover:shadow-brand-orange/30 transition-all transform active:scale-95">
                    Get Instant Quote
                </a>
            </div>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <header class="relative bg-grid-pattern py-16 sm:py-24 px-4 sm:px-8 overflow-hidden border-b border-brand-light/30">
        <div class="absolute inset-0 bg-gradient-to-b from-transparent via-brand-dark/80 to-brand-dark pointer-events-none"></div>
        
        <div class="max-w-7xl mx-auto relative z-10 grid lg:grid-cols-12 gap-12 items-center">
            
            <!-- Left Copy Column -->
            <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                <!-- Badges -->
                <div class="inline-flex items-center gap-2 bg-brand-orange/10 border border-brand-orange/30 rounded-full px-4 py-1.5 text-xs font-semibold text-brand-orange">
                    <span class="w-2 h-2 rounded-full bg-brand-orange animate-ping"></span>
                    Leamington & Essex County Commercial & Residential
                </div>

                <h1 class="font-heading text-4xl sm:text-5xl lg:text-6xl font-black text-white tracking-tight leading-[1.1]">
                    HEAVY DEMOLITION.<br/>
                    FAST JUNK REMOVAL.<br/>
                    <span class="text-transparent bg-clip-text bg-gradient-to-r from-brand-orange via-amber-400 to-brand-orange">
                        RELIABLE SITE SUPPORT.
                    </span>
                </h1>

                <p class="text-slate-300 text-base sm:text-lg max-w-2xl mx-auto lg:mx-0 font-normal leading-relaxed">
                    The scrappy, direct contractor choice for Leamington property managers, builders, and homeowners. Zero fluff, transparent rates, and spotless site cleanup on every job.
                </p>

                <!-- Action Buttons -->
                <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-2">
                    <a href="#quote" class="w-full sm:w-auto bg-brand-orange hover:bg-brand-orangeHover text-slate-950 font-extrabold text-base px-8 py-4 rounded-xl shadow-lg glow-orange transition-all flex items-center justify-center gap-3 group">
                        <span>FREE INSTANT ESTIMATE</span>
                        <i class="fa-solid fa-arrow-right group-hover:translate-x-1 transition-transform"></i>
                    </a>
                    <a href="tel:5195550199" class="w-full sm:w-auto bg-brand-card hover:bg-brand-light text-white font-bold text-base px-8 py-4 rounded-xl border border-brand-light transition-all flex items-center justify-center gap-3">
                        <i class="fa-solid fa-comment-dots text-brand-orange text-lg"></i>
                        <span>CALL / TEXT DIRECT</span>
                    </a>
                </div>

                <!-- Trust Badges Grid -->
                <div class="pt-6 grid grid-cols-2 sm:grid-cols-4 gap-4 text-left border-t border-brand-light/40 text-xs text-slate-400 font-medium">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-orange"></i>
                        <span>24-48 HR Turnaround</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-orange"></i>
                        <span>Equipped Truck Fleet</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-orange"></i>
                        <span>Spotless Job Sites</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-orange"></i>
                        <span>Fair Cash Rates</span>
                    </div>
                </div>
            </div>

            <!-- Right Quick Feature Card / Hero Display -->
            <div class="lg:col-span-5">
                <div class="bg-brand-card/90 backdrop-blur border border-brand-light p-6 sm:p-8 rounded-2xl shadow-2xl relative">
                    <div class="absolute -top-3 -right-3 bg-brand-orange text-slate-950 font-heading font-black text-xs px-3 py-1 rounded-full uppercase tracking-wider">
                        Direct Line
                    </div>

                    <h3 class="font-heading text-xl font-bold text-white mb-2">Need a Site Cleared Fast?</h3>
                    <p class="text-slate-400 text-sm mb-6">Skip the endless back-and-forth emails. We give straight-forward estimates for property cleanouts, interior gutting, and heavy hauling.</p>

                    <div class="space-y-4">
                        <div class="flex items-start gap-4 p-3 rounded-lg bg-brand-dark/60 border border-brand-light/30">
                            <div class="w-10 h-10 rounded-lg bg-brand-orange/20 text-brand-orange flex items-center justify-center shrink-0 text-lg">
                                <i class="fa-solid fa-truck-ramp-box"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Tenant Turnover Trash-Outs</h4>
                                <p class="text-slate-400 text-xs">Fast property manager turnarounds so your units are ready to show immediately.</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 p-3 rounded-lg bg-brand-dark/60 border border-brand-light/30">
                            <div class="w-10 h-10 rounded-lg bg-brand-orange/20 text-brand-orange flex items-center justify-center shrink-0 text-lg">
                                <i class="fa-solid fa-hammer"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Interior & Exterior Demo</h4>
                                <p class="text-slate-400 text-xs">Drywall, flooring, shed dismantling, decks, and structural prep work.</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 p-3 rounded-lg bg-brand-dark/60 border border-brand-light/30">
                            <div class="w-10 h-10 rounded-lg bg-brand-orange/20 text-brand-orange flex items-center justify-center shrink-0 text-lg">
                                <i class="fa-solid fa-dumpster"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Contractor Sub-Labor</h4>
                                <p class="text-slate-400 text-xs">Offload heavy site cleanup and haul-aways so your trade crew stays on schedule.</p>
                            </div>
                        </div>
                    </div>

                    <div class="mt-6 pt-6 border-t border-brand-light/40 text-center">
                        <a href="tel:5195550199" class="text-brand-orange hover:text-white font-bold text-sm transition-colors inline-flex items-center gap-2">
                            <span>Call Dispatch Directly: (519) 555-0199</span>
                            <i class="fa-solid fa-chevron-right text-xs"></i>
                        </a>
                    </div>
                </div>
            </div>

        </div>
    </header>

    <!-- SERVICE DIVISIONS TABBED SECTION -->
    <section id="services" class="py-20 px-4 sm:px-8 max-w-7xl mx-auto">
        <div class="text-center max-w-3xl mx-auto mb-12">
            <h2 class="text-xs uppercase font-bold text-brand-orange tracking-widest mb-2">OPERATIONAL DIVISIONS</h2>
            <p class="font-heading text-3xl sm:text-4xl font-black text-white">SPECIALIZED TRADE CAPABILITIES</p>
            <p class="text-slate-400 text-sm sm:text-base mt-3">NextPhase Companies operates structured, service-specific divisions designed to solve high-friction problems with zero downtime.</p>
        </div>

        <!-- Navigation Tabs -->
        <div class="flex flex-wrap justify-center gap-3 mb-10">
            <button onclick="switchTab('junk')" id="tab-junk" class="tab-btn bg-brand-orange text-slate-950 font-bold px-6 py-3 rounded-xl text-sm sm:text-base transition-all shadow-md flex items-center gap-2">
                <i class="fa-solid fa-trash-can"></i>
                <span>NextPhase Junk Removal</span>
            </button>
            <button onclick="switchTab('demo')" id="tab-demo" class="tab-btn bg-brand-card hover:bg-brand-light text-slate-300 font-bold px-6 py-3 rounded-xl text-sm sm:text-base transition-all border border-brand-light flex items-center gap-2">
                <i class="fa-solid fa-person-digging"></i>
                <span>NextPhase Demolition</span>
            </button>
            <button onclick="switchTab('site')" id="tab-site" class="tab-btn bg-brand-card hover:bg-brand-light text-slate-300 font-bold px-6 py-3 rounded-xl text-sm sm:text-base transition-all border border-brand-light flex items-center gap-2">
                <i class="fa-solid fa-truck-moving"></i>
                <span>NextPhase Site & Contracting</span>
            </button>
        </div>

        <!-- Tab Content Panels -->
        <!-- TAB 1: JUNK REMOVAL -->
        <div id="content-junk" class="tab-content bg-brand-card border border-brand-light rounded-2xl p-6 sm:p-10">
            <div class="grid lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-block bg-brand-orange/10 text-brand-orange text-xs font-bold px-3 py-1 rounded-md uppercase tracking-wider">
                        Division 01 • Hauling & Cleanouts
                    </div>
                    <h3 class="font-heading text-2xl sm:text-3xl font-bold text-white">Full-Scale Property Cleanouts & Heavy Hauling</h3>
                    <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                        Whether it’s a trashed tenant turnover, an estate liquidation, or a yard full of accumulated debris, we provide rapid haul-away services. We don't just dump—we clear, sweep, and leave the property in presentable condition.
                    </p>
                    <div class="grid sm:grid-cols-2 gap-4 text-sm text-slate-300">
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Tenant Turnover Trash-outs</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Construction Debris Removal</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Estate & Garage Cleanouts</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Appliance & Heavy Item Pickup</span>
                        </div>
                    </div>
                    <a href="#quote" class="inline-block bg-brand-orange hover:bg-brand-orangeHover text-slate-950 font-bold px-6 py-3 rounded-xl transition-all">
                        Book Junk Removal Estimate
                    </a>
                </div>
                <div class="lg:col-span-5 bg-brand-dark p-6 rounded-xl border border-brand-light/40 space-y-4">
                    <h4 class="font-heading text-lg font-bold text-white border-b border-brand-light/40 pb-2">Junk Removal Specs</h4>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Response Time:</span>
                        <span class="font-semibold text-brand-orange">Same-Day / 24-48 Hours</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Fleet Capacity:</span>
                        <span class="font-semibold text-white">Equipped Trucks & Heavy Trailers</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Disposal Protocol:</span>
                        <span class="font-semibold text-white">Eco-friendly Sorting & Landfill Trips</span>
                    </div>
                    <div class="bg-brand-orange/10 p-4 rounded-lg border border-brand-orange/20 text-xs text-brand-orange font-medium">
                        <i class="fa-solid fa-circle-info mr-1"></i>
                        Ask about our bulk contractor pricing for recurring property turnover accounts.
                    </div>
                </div>
            </div>
        </div>

        <!-- TAB 2: DEMOLITION -->
        <div id="content-demo" class="tab-content hidden bg-brand-card border border-brand-light rounded-2xl p-6 sm:p-10">
            <div class="grid lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-block bg-brand-orange/10 text-brand-orange text-xs font-bold px-3 py-1 rounded-md uppercase tracking-wider">
                        Division 02 • Selective Demolition
                    </div>
                    <h3 class="font-heading text-2xl sm:text-3xl font-bold text-white">Interior Tear-Outs & Exterior Structure Dismantling</h3>
                    <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                        Precision tear-outs for residential remodels and commercial build-outs. We tear down old sheds, strip interior drywall and flooring, remove concrete pads, and leave a pristine canvas for your builders.
                    </p>
                    <div class="grid sm:grid-cols-2 gap-4 text-sm text-slate-300">
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Interior Gutting (Drywall/Floors)</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Shed, Deck & Fence Dismantling</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Kitchen & Bath Strip-Outs</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Light Masonry & Concrete Tear-up</span>
                        </div>
                    </div>
                    <a href="#quote" class="inline-block bg-brand-orange hover:bg-brand-orangeHover text-slate-950 font-bold px-6 py-3 rounded-xl transition-all">
                        Request Demolition Quote
                    </a>
                </div>
                <div class="lg:col-span-5 bg-brand-dark p-6 rounded-xl border border-brand-light/40 space-y-4">
                    <h4 class="font-heading text-lg font-bold text-white border-b border-brand-light/40 pb-2">Demolition Standards</h4>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Safety Protocols:</span>
                        <span class="font-semibold text-brand-orange">Full PPE & Structural Pre-check</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Cleanup Guarantee:</span>
                        <span class="font-semibold text-white">Nail/Debris Magnetic Sweep</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Haul-Away:</span>
                        <span class="font-semibold text-white">Included in Every Quote</span>
                    </div>
                    <div class="bg-brand-orange/10 p-4 rounded-lg border border-brand-orange/20 text-xs text-brand-orange font-medium">
                        <i class="fa-solid fa-circle-info mr-1"></i>
                        We partner with local General Contractors for fast sub-contracted site preparation.
                    </div>
                </div>
            </div>
        </div>

        <!-- TAB 3: SITE SUPPORT -->
        <div id="content-site" class="tab-content hidden bg-brand-card border border-brand-light rounded-2xl p-6 sm:p-10">
            <div class="grid lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-block bg-brand-orange/10 text-brand-orange text-xs font-bold px-3 py-1 rounded-md uppercase tracking-wider">
                        Division 03 • Site & Contracting Support
                    </div>
                    <h3 class="font-heading text-2xl sm:text-3xl font-bold text-white">Sub-Contractor Labor & Heavy Material Transport</h3>
                    <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                        Don't waste high-value carpenters or tradesmen on basic site cleanup and hauling. NextPhase acts as your auxiliary site crew—keeping your job site clean, compliant, and prepped for the next phase of construction.
                    </p>
                    <div class="grid sm:grid-cols-2 gap-4 text-sm text-slate-300">
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Daily/Weekly Site Cleanups</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Material Transport & Towing</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Sub-Contractor Support</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-orange"></i>
                            <span>Punch-List Repairs & Prep</span>
                        </div>
                    </div>
                    <a href="#quote" class="inline-block bg-brand-orange hover:bg-brand-orangeHover text-slate-950 font-bold px-6 py-3 rounded-xl transition-all">
                        Schedule Site Support
                    </a>
                </div>
                <div class="lg:col-span-5 bg-brand-dark p-6 rounded-xl border border-brand-light/40 space-y-4">
                    <h4 class="font-heading text-lg font-bold text-white border-b border-brand-light/40 pb-2">Contractor Terms</h4>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Billing Structure:</span>
                        <span class="font-semibold text-brand-orange">Per Job or Day-Rate</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Equipment:</span>
                        <span class="font-semibold text-white">Full Rigging & Trailers</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Availability:</span>
                        <span class="font-semibold text-white">Scheduled or On-Call</span>
                    </div>
                    <div class="bg-brand-orange/10 p-4 rounded-lg border border-brand-orange/20 text-xs text-brand-orange font-medium">
                        <i class="fa-solid fa-circle-info mr-1"></i>
                        Ideal for restoration companies, roofers, framers, and multi-unit landlords.
                    </div>
                </div>
            </div>
        </div>

    </section>

    <!-- AUDIENCE-TAILORED SOLUTIONS -->
    <section id="solutions" class="py-16 bg-brand-card/50 border-y border-brand-light/30">
        <div class="max-w-7xl mx-auto px-4 sm:px-8">
            <div class="text-center max-w-3xl mx-auto mb-14">
                <h2 class="text-xs uppercase font-bold text-brand-orange tracking-widest mb-2">TAILORED WORKFLOWS</h2>
                <p class="font-heading text-3xl font-black text-white">BUILT TO SOLVE YOUR EXACT HEADACHE</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Card 1: Property Managers -->
                <div class="bg-brand-card border border-brand-light rounded-2xl p-8 hover:border-brand-orange/50 transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-brand-orange/10 text-brand-orange flex items-center justify-center text-xl font-bold mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-building-user"></i>
                    </div>
                    <h3 class="font-heading text-xl font-bold text-white mb-3">For Property Managers & Realtors</h3>
                    <p class="text-slate-300 text-sm leading-relaxed mb-4">
                        Vacant units lose money every day. We provide fast 24-48 hour trash-outs, tenant abandonments cleanup, and broom-clean prep so you can re-list immediately.
                    </p>
                    <ul class="text-xs text-slate-400 space-y-2 mb-6">
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> Direct Invoicing Options</li>
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> Photo Verification Upon Completion</li>
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> Emergency Lockout Cleanouts</li>
                    </ul>
                </div>

                <!-- Card 2: General Contractors -->
                <div class="bg-brand-card border border-brand-light rounded-2xl p-8 hover:border-brand-orange/50 transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-brand-orange/10 text-brand-orange flex items-center justify-center text-xl font-bold mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-helmet-safety"></i>
                    </div>
                    <h3 class="font-heading text-xl font-bold text-white mb-3">For General Contractors & Builders</h3>
                    <p class="text-slate-300 text-sm leading-relaxed mb-4">
                        Stop burning $45+/hr skilled labor on sweeping up or filling dumpsters. Offload interior demo, site debris, and heavy hauling to NextPhase.
                    </p>
                    <ul class="text-xs text-slate-400 space-y-2 mb-6">
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> Reliable Sub-Contractor Partner</li>
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> Magnetic Site Sweeps (No Nails Left)</li>
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> On-Demand Haul-Away Support</li>
                    </ul>
                </div>

                <!-- Card 3: Homeowners -->
                <div class="bg-brand-card border border-brand-light rounded-2xl p-8 hover:border-brand-orange/50 transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-brand-orange/10 text-brand-orange flex items-center justify-center text-xl font-bold mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-house-chimney"></i>
                    </div>
                    <h3 class="font-heading text-xl font-bold text-white mb-3">For Homeowners & Estate Owners</h3>
                    <p class="text-slate-300 text-sm leading-relaxed mb-4">
                        Straightforward, scrappy, fair-cash rates for basement cleanouts, old shed tear-downs, and yard waste clearing without hidden fees or overhead markups.
                    </p>
                    <ul class="text-xs text-slate-400 space-y-2 mb-6">
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> Upfront Cash/Card Estimates</li>
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> Respectful Estate Clearing</li>
                        <li><i class="fa-solid fa-check text-brand-orange mr-1.5"></i> Fast, Friendly Local Crew</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- INTERACTIVE ESTIMATE CALCULATOR / QUOTE FORM -->
    <section id="quote" class="py-20 px-4 sm:px-8 max-w-5xl mx-auto">
        <div class="bg-brand-card border border-brand-light rounded-3xl p-6 sm:p-12 shadow-2xl relative overflow-hidden">
            <div class="absolute top-0 right-0 w-64 h-64 bg-brand-orange/10 rounded-full blur-3xl pointer-events-none"></div>

            <div class="text-center max-w-2xl mx-auto mb-10">
                <span class="bg-brand-orange/20 text-brand-orange text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">
                    Instant Quote Generator
                </span>
                <h2 class="font-heading text-3xl sm:text-4xl font-black text-white mt-3">GET A FAST ESTIMATE</h2>
                <p class="text-slate-400 text-sm mt-2">Select your project parameters below for an instant rough estimate and immediate dispatcher callback.</p>
            </div>

            <form id="quote-form" onsubmit="handleQuoteSubmit(event)" class="space-y-8">
                <!-- STEP 1: SERVICE TYPE -->
                <div>
                    <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-3">
                        1. Select Service Division
                    </label>
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                        <label class="cursor-pointer">
                            <input type="radio" name="service_type" value="Junk Removal" class="peer sr-only" checked onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-orange peer-checked:bg-brand-orange/10 peer-checked:text-white transition-all text-center">
                                <i class="fa-solid fa-trash-can text-2xl text-brand-orange mb-2 block"></i>
                                <span class="font-bold text-sm block">Junk Removal</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Cleanouts & Debris</span>
                            </div>
                        </label>

                        <label class="cursor-pointer">
                            <input type="radio" name="service_type" value="Demolition" class="peer sr-only" onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-orange peer-checked:bg-brand-orange/10 peer-checked:text-white transition-all text-center">
                                <i class="fa-solid fa-hammer text-2xl text-brand-orange mb-2 block"></i>
                                <span class="font-bold text-sm block">Demolition</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Tear-Outs & Dismantling</span>
                            </div>
                        </label>

                        <label class="cursor-pointer">
                            <input type="radio" name="service_type" value="Site Support" class="peer sr-only" onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-orange peer-checked:bg-brand-orange/10 peer-checked:text-white transition-all text-center">
                                <i class="fa-solid fa-truck-ramp-box text-2xl text-brand-orange mb-2 block"></i>
                                <span class="font-bold text-sm block">Site Support</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Contractor Labor & Hauling</span>
                            </div>
                        </label>
                    </div>
                </div>

                <!-- STEP 2: PROJECT SCALE -->
                <div>
                    <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-3">
                        2. Select Project Scale
                    </label>
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                        <label class="cursor-pointer">
                            <input type="radio" name="project_scale" value="Small / Single Area" class="peer sr-only" checked onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-orange peer-checked:bg-brand-orange/10 peer-checked:text-white transition-all text-center">
                                <span class="font-bold text-sm block">Small / Single Load</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Single room, shed, or pickup load</span>
                            </div>
                        </label>

                        <label class="cursor-pointer">
                            <input type="radio" name="project_scale" value="Medium / Partial Unit" class="peer sr-only" onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-orange peer-checked:bg-brand-orange/10 peer-checked:text-white transition-all text-center">
                                <span class="font-bold text-sm block">Medium / Partial Job</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Full garage, apartment unit, multi-item</span>
                            </div>
                        </label>

                        <label class="cursor-pointer">
                            <input type="radio" name="project_scale" value="Large / Full Property" class="peer sr-only" onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-orange peer-checked:bg-brand-orange/10 peer-checked:text-white transition-all text-center">
                                <span class="font-bold text-sm block">Large / Full Property</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Whole house cleanout, full gut demo</span>
                            </div>
                        </label>
                    </div>
                </div>

                <!-- STEP 3: LOCATION & DETAILS -->
                <div class="grid sm:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-2">Location / City</label>
                        <select id="location-select" required class="w-full bg-brand-dark border border-brand-light rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-orange">
                            <option value="Leamington">Leamington, ON</option>
                            <option value="Kingsville">Kingsville, ON</option>
                            <option value="Wheatley">Wheatley, ON</option>
                            <option value="Essex">Essex, ON</option>
                            <option value="Harrow / Amherstburg">Harrow / Amherstburg</option>
                            <option value="Windsor / Other">Windsor / Greater Essex County</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-2">Target Timeline</label>
                        <select id="timeline-select" class="w-full bg-brand-dark border border-brand-light rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-orange">
                            <option value="ASAP (24-48 Hours)">ASAP (Same Day / 24-48 Hours)</option>
                            <option value="Within 1 Week">Within 1 Week</option>
                            <option value="Flexible / Planning">Flexible / Future Project</option>
                        </select>
                    </div>
                </div>

                <!-- CONTACT FIELDS -->
                <div class="grid sm:grid-cols-2 gap-4 pt-2">
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-2">Your Name</label>
                        <input type="text" required placeholder="John Doe" class="w-full bg-brand-dark border border-brand-light rounded-xl px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-brand-orange">
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-2">Phone Number (For Text / Call)</label>
                        <input type="tel" required placeholder="(519) 555-0123" class="w-full bg-brand-dark border border-brand-light rounded-xl px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-brand-orange">
                    </div>
                </div>

                <!-- DYNAMIC ESTIMATE DISPLAY CARD -->
                <div class="bg-brand-dark p-6 rounded-2xl border border-brand-orange/30 flex flex-col sm:flex-row items-center justify-between gap-4">
                    <div>
                        <div class="text-xs uppercase font-bold text-slate-400">Estimated Price Range:</div>
                        <div id="price-display" class="text-2xl sm:text-3xl font-heading font-black text-brand-orange">
                            $150 - $350 CAD
                        </div>
                        <div class="text-[11px] text-slate-400 mt-0.5">*Final price confirmed on-site or via direct job photos. No hidden fees.</div>
                    </div>
                    <button type="submit" class="w-full sm:w-auto bg-brand-orange hover:bg-brand-orangeHover text-slate-950 font-extrabold text-base px-8 py-4 rounded-xl shadow-lg glow-orange transition-all whitespace-nowrap">
                        SUBMIT FOR CALLBACK
                    </button>
                </div>
            </form>
        </div>
    </section>

    <!-- SERVICE AREA & WHY NEXTPHASE -->
    <section id="coverage" class="py-20 bg-brand-card/30 border-t border-brand-light/30">
        <div class="max-w-7xl mx-auto px-4 sm:px-8">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                
                <div class="lg:col-span-6 space-y-6">
                    <span class="text-xs font-bold text-brand-orange uppercase tracking-widest">LOCAL LEAMINGTON OPERATOR</span>
                    <h2 class="font-heading text-3xl sm:text-4xl font-black text-white">WHY CONTRACTORS & LANDLORDS CHOOSE NEXTPHASE</h2>
                    
                    <div class="space-y-4 pt-2">
                        <div class="flex items-start gap-4">
                            <div class="w-8 h-8 rounded-lg bg-brand-orange/20 text-brand-orange flex items-center justify-center shrink-0 font-bold">1</div>
                            <div>
                                <h4 class="font-bold text-white text-base">Direct & Scrappy Resourcefulness</h4>
                                <p class="text-slate-400 text-sm">We keep overhead low and operations lean. You get honest, competitive cash pricing without paying for corporate marketing fluff.</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4">
                            <div class="w-8 h-8 rounded-lg bg-brand-orange/20 text-brand-orange flex items-center justify-center shrink-0 font-bold">2</div>
                            <div>
                                <h4 class="font-bold text-white text-base">Obsessive Site Cleanliness</h4>
                                <p class="text-slate-400 text-sm">We don't leave until the driveway is swept and nails are picked up with magnetic sweepers. We leave your job site ready for trades or tenants.</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4">
                            <div class="w-8 h-8 rounded-lg bg-brand-orange/20 text-brand-orange flex items-center justify-center shrink-0 font-bold">3</div>
                            <div>
                                <h4 class="font-bold text-white text-base">Multi-Trade Growth Mindset</h4>
                                <p class="text-slate-400 text-sm">NextPhase is built to scale alongside your project needs—from simple junk removal to full-scale structural site prep.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Service Region Box -->
                <div class="lg:col-span-6 bg-brand-card border border-brand-light p-8 rounded-3xl space-y-6">
                    <h3 class="font-heading text-xl font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot text-brand-orange"></i>
                        <span>Primary Service Coverage</span>
                    </h3>
                    <p class="text-slate-300 text-sm">Based directly in Leamington, ON, providing rapid dispatch across Essex County:</p>
                    
                    <div class="grid grid-cols-2 gap-3 text-sm font-semibold text-white">
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-orange text-xs"></i>
                            <span>Leamington</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-orange text-xs"></i>
                            <span>Kingsville</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-orange text-xs"></i>
                            <span>Wheatley</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-orange text-xs"></i>
                            <span>Essex</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-orange text-xs"></i>
                            <span>Harrow</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-orange text-xs"></i>
                            <span>Windsor-Essex</span>
                        </div>
                    </div>

                    <div class="p-4 bg-brand-dark/80 rounded-xl border border-brand-orange/30 text-center">
                        <p class="text-xs text-slate-300 font-medium">Have a job outside these areas?</p>
                        <a href="tel:5195550199" class="text-brand-orange font-bold text-sm hover:underline mt-1 inline-block">
                            Call us to check fleet dispatch availability →
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-slate-950 border-t border-brand-light/40 py-12 px-4 sm:px-8 text-slate-400 text-xs sm:text-sm">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-8 mb-12">
            <!-- Col 1: Brand -->
            <div class="space-y-4">
                <div class="flex items-center gap-3">
                    <div class="w-8 h-8 bg-brand-orange rounded-lg flex items-center justify-center text-slate-950 font-heading font-black text-base">
                        NP
                    </div>
                    <span class="font-heading font-bold text-white text-base">NEXTPHASE COMPANIES</span>
                </div>
                <p class="text-xs text-slate-400 leading-relaxed">
                    Leamington & Essex County's premier multi-service contractor. Specializing in Junk Removal, Selective Demolition, and Site Support.
                </p>
            </div>

            <!-- Col 2: Services -->
            <div>
                <h4 class="font-bold text-white text-sm mb-3">Divisions</h4>
                <ul class="space-y-2 text-xs">
                    <li><a href="#services" onclick="switchTab('junk')" class="hover:text-brand-orange">NextPhase Junk Removal</a></li>
                    <li><a href="#services" onclick="switchTab('demo')" class="hover:text-brand-orange">NextPhase Demolition</a></li>
                    <li><a href="#services" onclick="switchTab('site')" class="hover:text-brand-orange">NextPhase Site & Contracting Support</a></li>
                </ul>
            </div>

            <!-- Col 3: Direct Contact -->
            <div>
                <h4 class="font-bold text-white text-sm mb-3">Dispatch Contact</h4>
                <p class="text-xs text-slate-300">Leamington, Ontario, Canada</p>
                <p class="text-xs text-brand-orange font-bold mt-2">Phone/Text: (519) 555-0199</p>
                <p class="text-xs text-slate-400 mt-1">Direct: info@nextphasecompanies.com</p>
            </div>

            <!-- Col 4: Hours -->
            <div>
                <h4 class="font-bold text-white text-sm mb-3">Hours of Operation</h4>
                <p class="text-xs">Monday – Saturday: 7:00 AM – 7:00 PM</p>
                <p class="text-xs">Sunday: On-Call Emergency Service</p>
                <p class="text-[11px] text-slate-500 mt-2">24/7 Response for Property Manager Turnovers.</p>
            </div>
        </div>

        <div class="max-w-7xl mx-auto border-t border-brand-light/20 pt-6 flex flex-col sm:flex-row items-center justify-between gap-4 text-xs">
            <p>&copy; 2026 NextPhase Companies. All Rights Reserved. Built for speed and reliability.</p>
            <div class="flex gap-4">
                <a href="#" class="hover:text-brand-orange">Privacy Policy</a>
                <a href="#" class="hover:text-brand-orange">Terms of Service</a>
            </div>
        </div>
    </footer>

    <!-- SUCCESS MODAL (Hidden by Default) -->
    <div id="success-modal" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-brand-card border border-brand-orange p-8 rounded-3xl max-w-md w-full text-center space-y-4 shadow-2xl relative">
            <div class="w-16 h-16 bg-brand-orange/20 text-brand-orange rounded-full flex items-center justify-center text-3xl mx-auto">
                <i class="fa-solid fa-circle-check"></i>
            </div>
            <h3 class="font-heading text-2xl font-black text-white">ESTIMATE REQUEST RECEIVED</h3>
            <p class="text-slate-300 text-sm">
                Your quote request has been dispatched. A NextPhase specialist will call or text you shortly to finalize details.
            </p>
            <div class="p-4 bg-brand-dark rounded-xl border border-brand-light text-left text-xs space-y-1">
                <div class="text-slate-400">Want immediate priority response?</div>
                <div class="text-brand-orange font-bold text-sm">Call/Text Dispatch: (519) 555-0199</div>
            </div>
            <button onclick="closeModal()" class="w-full bg-brand-orange text-slate-950 font-bold py-3 rounded-xl hover:bg-brand-orangeHover transition-all">
                CLOSE & RETURN TO SITE
            </button>
        </div>
    </div>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // Tab Switcher Logic
        function switchTab(tabKey) {
            // Hide all tab contents
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));
            
            // Reset tab button styling
            document.querySelectorAll('.tab-btn').forEach(btn => {
                btn.classList.remove('bg-brand-orange', 'text-slate-950');
                btn.classList.add('bg-brand-card', 'text-slate-300', 'border', 'border-brand-light');
            });

            // Show active content
            document.getElementById(`content-${tabKey}`).classList.remove('hidden');

            // Highlight active button
            const activeBtn = document.getElementById(`tab-${tabKey}`);
            activeBtn.classList.remove('bg-brand-card', 'text-slate-300', 'border', 'border-brand-light');
            activeBtn.classList.add('bg-brand-orange', 'text-slate-950');
        }

        // Price Calculator Logic
        function calculateEstimate() {
            const service = document.querySelector('input[name="service_type"]:checked').value;
            const scale = document.querySelector('input[name="project_scale"]:checked').value;
            const display = document.getElementById('price-display');

            let min = 150;
            let max = 350;

            if (service === 'Junk Removal') {
                if (scale.includes('Small')) { min = 120; max = 250; }
                else if (scale.includes('Medium')) { min = 280; max = 550; }
                else { min = 600; max = 1400; }
            } else if (service === 'Demolition') {
                if (scale.includes('Small')) { min = 250; max = 500; }
                else if (scale.includes('Medium')) { min = 600; max = 1500; }
                else { min = 1800; max = 4500; }
            } else if (service === 'Site Support') {
                if (scale.includes('Small')) { min = 200; max = 400; }
                else if (scale.includes('Medium')) { min = 450; max = 900; }
                else { min = 1000; max = 2500; }
            }

            display.textContent = `$${min} - $${max} CAD`;
        }

        // Form Submit Handler
        function handleQuoteSubmit(event) {
            event.preventDefault();
            document.getElementById('success-modal').classList.remove('hidden');
        }

        // Close Modal
        function closeModal() {
            document.getElementById('success-modal').classList.add('hidden');
        }
    </script>
</body>
</html>
