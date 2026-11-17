<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NextPhase Solutions | Junk Removal, Demolition & Property Cleanouts Leamington</title>
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
                            blue: '#258cf4',       // Primary Card Blue
                            blueHover: '#1d7cd8', // Hover state
                            blueLight: '#eef6ff', // Light tint for backgrounds
                            dark: '#0f172a',      // Dark slate body background
                            card: '#1e293b',      // Slate card container
                            light: '#334155',     // Slate borders/accents
                            charcoal: '#2c3238',  // Deep charcoal from business card bevel
                            accent: '#38bdf8',    // Cyan highlight
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
        .glow-blue {
            box-shadow: 0 0 25px -5px rgba(37, 140, 244, 0.45);
        }
        .bg-grid-pattern {
            background-image: radial-gradient(rgba(255, 255, 255, 0.08) 1px, transparent 1px);
            background-size: 24px 24px;
        }
        /* Custom Hexagon Clip for logo badge */
        .hex-shape {
            clip-path: polygon(30% 0%, 70% 0%, 100% 30%, 100% 70%, 70% 100%, 30% 100%, 0% 70%, 0% 30%);
        }
    </style>
</head>
<body class="bg-brand-dark text-slate-100 font-sans antialiased selection:bg-brand-blue selection:text-white">

    <!-- TOP ANNOUNCEMENT BAR -->
    <div class="bg-brand-blue text-white font-bold text-xs sm:text-sm py-2.5 px-4 text-center tracking-wide flex flex-wrap items-center justify-center gap-2 shadow-md">
        <i class="fa-solid fa-shield-halved"></i>
        <span>LOCAL JUNK REMOVAL, DEMOLITION & PROPERTY CLEANOUTS IN LEAMINGTON & ESSEX COUNTY</span>
        <span class="phone-slot ml-1" data-btn="true" data-style="underline hover:text-slate-200 transition-colors font-extrabold inline-flex items-center gap-1 cursor-pointer"></span>
    </div>

    <!-- MAIN NAVIGATION -->
    <nav class="sticky top-0 z-50 bg-brand-dark/95 backdrop-blur-md border-b border-brand-light/40 py-3.5 px-4 sm:px-8">
        <div class="max-w-7xl mx-auto flex items-center justify-between">
            <!-- Brand Logo -->
            <a href="#" class="flex items-center gap-3.5 group">
                <!-- NP Hexagon Icon styled matching business card theme -->
                <div class="relative w-11 h-11 flex items-center justify-center group-hover:scale-105 transition-transform">
                    <div class="absolute inset-0 bg-brand-charcoal hex-shape transform rotate-6 scale-95 opacity-80"></div>
                    <div class="absolute inset-0 bg-brand-blue hex-shape flex items-center justify-center shadow-lg border border-white/20">
                        <span class="font-heading font-black text-xl text-white tracking-tighter">NP</span>
                    </div>
                </div>
                <div>
                    <div class="font-heading font-black text-xl tracking-tight text-white leading-none">
                        NEXTPHASE
                    </div>
                    <div class="text-[10px] uppercase font-bold text-brand-blue tracking-[0.25em] leading-tight mt-0.5">
                        SOLUTIONS
                    </div>
                </div>
            </a>

            <!-- Desktop Links -->
            <div class="hidden md:flex items-center gap-8 font-medium text-sm text-slate-300">
                <a href="#services" class="hover:text-brand-blue transition-colors">Services</a>
                <a href="#solutions" class="hover:text-brand-blue transition-colors">Who We Serve</a>
                <a href="#quote" class="hover:text-brand-blue transition-colors">Instant Estimate</a>
                <a href="#coverage" class="hover:text-brand-blue transition-colors">Service Area</a>
            </div>

            <!-- Header CTAs -->
            <div class="flex items-center gap-3">
                <span class="phone-slot hidden sm:inline-flex" data-btn="true" data-style="flex items-center gap-2 bg-brand-card hover:bg-brand-light text-white text-xs sm:text-sm font-semibold py-2.5 px-4 rounded-lg border border-brand-light transition-all cursor-pointer"></span>
                <a href="#quote" class="bg-brand-blue hover:bg-brand-blueHover text-white font-bold text-xs sm:text-sm py-2.5 px-5 rounded-lg shadow-md hover:shadow-brand-blue/30 transition-all transform active:scale-95">
                    Get Free Quote
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
                <div class="inline-flex items-center gap-2 bg-brand-blue/10 border border-brand-blue/30 rounded-full px-4 py-1.5 text-xs font-bold text-brand-blue">
                    <span class="w-2 h-2 rounded-full bg-brand-blue"></span>
                    Leamington & Essex County Residential, Rental & Contractor Support
                </div>

                <h1 class="font-heading text-4xl sm:text-5xl lg:text-6xl font-black text-white tracking-tight leading-[1.1]">
                    JUNK REMOVAL.<br/>
                    DEMOLITION.<br/>
                    <span class="text-transparent bg-clip-text bg-gradient-to-r from-brand-blue via-sky-400 to-brand-blue">
                        CLEANOUTS DONE RIGHT.
                    </span>
                </h1>

                <p class="text-slate-300 text-base sm:text-lg max-w-2xl mx-auto lg:mx-0 font-normal leading-relaxed">
                    NextPhase Solutions provides reliable junk removal, selective interior demolition, property cleanouts, and light hauling across Leamington and Essex County. Fast turnaround, fair pricing, and spotless cleanup on every job.
                </p>

                <!-- Core Capability Tags -->
                <div class="flex flex-wrap justify-center lg:justify-start gap-2 pt-1 text-xs font-semibold text-slate-300">
                    <span class="bg-brand-card border border-brand-light px-3.5 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-dumpster text-brand-blue"></i> Junk Removal & Hauling
                    </span>
                    <span class="bg-brand-card border border-brand-light px-3.5 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-person-digging text-brand-blue"></i> Interior & Selective Demo
                    </span>
                    <span class="bg-brand-card border border-brand-light px-3.5 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-house-circle-check text-brand-blue"></i> Property & Estate Cleanouts
                    </span>
                    <span class="bg-brand-card border border-brand-light px-3.5 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-truck-pickup text-brand-blue"></i> Contractor Debris Support
                    </span>
                </div>

                <!-- Action Buttons -->
                <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-4">
                    <a href="#quote" class="w-full sm:w-auto bg-brand-blue hover:bg-brand-blueHover text-white font-extrabold text-base px-8 py-4 rounded-xl shadow-lg glow-blue transition-all flex items-center justify-center gap-3 group">
                        <span>FREE ESTIMATE</span>
                        <i class="fa-solid fa-arrow-right group-hover:translate-x-1 transition-transform"></i>
                    </a>
                    <span class="phone-slot w-full sm:w-auto" data-btn="true" data-prefix="CALL " data-style="w-full sm:w-auto bg-brand-card hover:bg-brand-light text-white font-bold text-base px-8 py-4 rounded-xl border border-brand-light transition-all flex items-center justify-center gap-3 cursor-pointer"></span>
                </div>

                <h1 class="font-heading text-4xl sm:text-5xl lg:text-6xl font-black text-white tracking-tight leading-[1.1]">
                    JUNK REMOVAL.<br/>
                    DEMOLITION.<br/>
                    <span class="text-transparent bg-clip-text bg-gradient-to-r from-brand-blue via-sky-400 to-brand-blue">
                        CLEANOUTS DONE RIGHT.
                    </span>
                </h1>

                <p class="text-slate-300 text-base sm:text-lg max-w-2xl mx-auto lg:mx-0 font-normal leading-relaxed">
                    NextPhase Solutions provides reliable junk removal, selective interior demolition, property cleanouts, and light hauling across Leamington and Essex County. Fast turnaround, fair pricing, and spotless cleanup on every job.
                </p>

                <!-- Core Capability Tags -->
                <div class="flex flex-wrap justify-center lg:justify-start gap-2 pt-1 text-xs font-semibold text-slate-300">
                    <span class="bg-brand-card border border-brand-light px-3.5 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-dumpster text-brand-blue"></i> Junk Removal & Hauling
                    </span>
                    <span class="bg-brand-card border border-brand-light px-3.5 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-person-digging text-brand-blue"></i> Interior & Selective Demo
                    </span>
                    <span class="bg-brand-card border border-brand-light px-3.5 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-house-circle-check text-brand-blue"></i> Property & Estate Cleanouts
                    </span>
                    <span class="bg-brand-card border border-brand-light px-3.5 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-truck-pickup text-brand-blue"></i> Contractor Debris Support
                    </span>
                </div>

                <!-- Action Buttons -->
                <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-4">
                    <span class="phone-slot w-full sm:w-auto" data-btn="true" data-prefix="CALL FOR FREE ESTIMATE: " data-style="w-full sm:w-auto bg-brand-blue hover:bg-brand-blueHover text-white font-extrabold text-base px-8 py-4 rounded-xl shadow-lg glow-blue transition-all flex items-center justify-center gap-3 cursor-pointer"></span>
                    <a href="#pricing" class="w-full sm:w-auto bg-brand-card hover:bg-brand-light text-white font-bold text-base px-8 py-4 rounded-xl border border-brand-light transition-all flex items-center justify-center gap-3 group">
                    <a href="#quote" class="inline-block bg-brand-blue hover:bg-brand-blueHover text-white font-bold px-6 py-3 rounded-xl transition-all">
                        Request Junk Removal & Cleanout Quote
                    </a>
                </div>

                <!-- Trust Badges Grid -->
                <div class="pt-6 grid grid-cols-2 sm:grid-cols-4 gap-4 text-left border-t border-brand-light/40 text-xs text-slate-400 font-medium">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-blue"></i>
                        <span>Local & Reliable</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-blue"></i>
                        <span>Truck & Trailer Ready</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-blue"></i>
                        <span>Upfront Pricing</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-blue"></i>
                        <span>Spotless Cleanup</span>
                    </div>
                </div>
            </div>

            <!-- Right Quick Feature Card / Hero Display -->
            <div class="lg:col-span-5">
                <div class="bg-brand-card/90 backdrop-blur border border-brand-light p-6 sm:p-8 rounded-2xl shadow-2xl relative">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="w-12 h-12 bg-brand-blue/15 border border-brand-blue/30 rounded-xl flex items-center justify-center text-brand-blue text-2xl font-bold">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                        <div>
                            <h3 class="font-heading text-xl font-bold text-white">NextPhase Solutions</h3>
                            <p class="text-xs text-brand-blue font-semibold uppercase tracking-wider">Hauling, Demo & Cleanouts</p>
                        </div>
                    </div>

                    <p class="text-slate-400 text-sm mb-6">Practical, hands-on property clearance and tear-out services. We handle the heavy lifting, loading, and disposal so you can move straight to the next phase of your project.</p>

                    <div class="space-y-3.5">
                        <div class="flex items-start gap-3.5 p-3.5 rounded-lg bg-brand-dark/60 border border-brand-light/30">
                            <div class="w-9 h-9 rounded-lg bg-brand-blue/20 text-brand-blue flex items-center justify-center shrink-0 text-base">
                                <i class="fa-solid fa-dumpster"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Junk Removal & Debris Hauling</h4>
                                <p class="text-slate-400 text-xs">Garage cleanouts, unwanted furniture, appliances, yard waste, and renovation debris.</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-3.5 p-3.5 rounded-lg bg-brand-dark/60 border border-brand-light/30">
                            <div class="w-9 h-9 rounded-lg bg-brand-blue/20 text-brand-blue flex items-center justify-center shrink-0 text-base">
                                <i class="fa-solid fa-person-digging"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Interior & Selective Demolition</h4>
                                <p class="text-slate-400 text-xs">Kitchen & bath gutting, drywall/flooring tear-outs, shed & deck removal.</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-3.5 p-3.5 rounded-lg bg-brand-dark/60 border border-brand-light/30">
                            <div class="w-9 h-9 rounded-lg bg-brand-blue/20 text-brand-blue flex items-center justify-center shrink-0 text-base">
                                <i class="fa-solid fa-house-circle-check"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Property Cleanouts & Contracting</h4>
                                <p class="text-slate-400 text-xs">Tenant turnover clean-outs, estate clearances, and small tear-down prep.</p>
                            </div>
                        </div>
                    </div>

                    <div class="mt-6 pt-5 border-t border-brand-light/40 text-center">
                        <span class="phone-slot" data-btn="true" data-prefix="Call Direct: " data-suffix=" →" data-style="text-brand-blue hover:text-white font-bold text-sm transition-colors inline-flex items-center gap-1.5 cursor-pointer"></span>
                    </div>
                </div>
            </div>

        </div>
    </header>

    <!-- CORE SERVICES TABBED SECTION -->
    <section id="services" class="py-20 px-4 sm:px-8 max-w-7xl mx-auto">
        <div class="text-center max-w-3xl mx-auto mb-12">
            <h2 class="text-xs uppercase font-bold text-brand-blue tracking-widest mb-2">WHAT WE DO</h2>
            <p class="font-heading text-3xl sm:text-4xl font-black text-white">CORE SERVICES</p>
            <p class="text-slate-400 text-sm sm:text-base mt-3">Focused, dependable property clearing and demolition services built around showing up on time and working hard.</p>
        </div>

        <!-- Navigation Tabs -->
        <div class="flex flex-wrap justify-center gap-3 mb-10">
            <button onclick="switchTab('junk')" id="tab-junk" class="tab-btn bg-brand-blue text-white font-bold px-6 py-3.5 rounded-xl text-xs sm:text-sm transition-all shadow-md flex items-center gap-2">
                <i class="fa-solid fa-dumpster"></i>
                <span>Junk Removal & Cleanouts</span>
            </button>
            <button onclick="switchTab('demo')" id="tab-demo" class="tab-btn bg-brand-card hover:bg-brand-light text-slate-300 font-bold px-6 py-3.5 rounded-xl text-xs sm:text-sm transition-all border border-brand-light flex items-center gap-2">
                <i class="fa-solid fa-person-digging"></i>
                <span>Interior & Selective Demo</span>
            </button>
        </div>

        <!-- Tab Content Panels -->
        <!-- TAB 1: JUNK REMOVAL & CLEANOUTS -->
        <div id="content-junk" class="tab-content bg-brand-card border border-brand-light rounded-2xl p-6 sm:p-10">
            <div class="grid lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-block bg-brand-blue/10 text-brand-blue text-xs font-bold px-3 py-1 rounded-md uppercase tracking-wider border border-brand-blue/30">
                        Fast Loading, Clearances & Disposal
                    </div>
                    <h3 class="font-heading text-2xl sm:text-3xl font-bold text-white">Full-Service Junk Removal & Property Cleanouts</h3>
                    <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                        You point, we load and haul it away. Whether it's a single heavy appliance, a cluttered garage, a tenant turnover trash-out, or a full estate clearance, we handle all the lifting and sweep up before we leave.
                    </p>
                    <div class="grid sm:grid-cols-2 gap-3 text-sm text-slate-300">
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-blue"></i>
                            <span>Garage, Basement & Attic Cleanouts</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-blue"></i>
                            <span>Tenant Turnover & Estate Clearances</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-blue"></i>
                            <span>Furniture, Appliances & Scrap Metal</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-blue"></i>
                            <span>Renovation Debris & Yard Waste</span>
                        </div>
                    </div>
                    <a href="#quote" class="inline-block bg-brand-blue hover:bg-brand-blueHover text-white font-bold px-6 py-3 rounded-xl transition-all">
                        Request Demolition Quote
                    </a>
                </div>
                <div class="lg:col-span-5 bg-brand-dark p-6 rounded-xl border border-brand-light/40 space-y-4">
                    <h4 class="font-heading text-lg font-bold text-white border-b border-brand-light/40 pb-2">How It Works</h4>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Pricing:</span>
                        <span class="font-semibold text-brand-blue">Volume-Based & Upfront</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Setup:</span>
                        <span class="font-semibold text-white">Truck & Dump/Utility Trailer</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Updates:</span>
                        <span class="font-semibold text-white">Before & After Photos Sent</span>
                    </div>
                    <div class="bg-brand-blue/10 p-4 rounded-lg border border-brand-blue/20 text-xs text-brand-blue font-medium">
                        <i class="fa-solid fa-circle-info mr-1"></i>
                        Call us with details about your pile or property for a fast, no-obligation ballpark price.
                    </div>
                </div>
            </div>
        </div>

        <!-- TAB 2: DEMOLITION -->
        <div id="content-demo" class="tab-content hidden bg-brand-card border border-brand-light rounded-2xl p-6 sm:p-10">
            <div class="grid lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-block bg-brand-blue/10 text-brand-blue text-xs font-bold px-3 py-1 rounded-md uppercase tracking-wider border border-brand-blue/30">
                        Tear-Outs & Dismantling
                    </div>
                    <h3 class="font-heading text-2xl sm:text-3xl font-bold text-white">Interior & Selective Demolition</h3>
                    <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                        Clean, controlled tear-outs for homeowners and contractors prepping for a remodel. We strip rooms down to the studs, remove old outdoor structures, and haul every scrap away.
                    </p>
                    <div class="grid sm:grid-cols-2 gap-3 text-sm text-slate-300">
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-blue"></i>
                            <span>Kitchen & Bathroom Gutting</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-blue"></i>
                            <span>Drywall, Plaster & Flooring Removal</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-blue"></i>
                            <span>Shed, Deck & Fence Tear-Downs</span>
                        </div>
                        <div class="flex items-center gap-3 bg-brand-dark/50 p-3 rounded-lg border border-brand-light/30">
                            <i class="fa-solid fa-check text-brand-blue"></i>
                            <span>Non-Structural Interior Strip-Outs</span>
                        </div>
                    </div>
                    <a href="#pricing" class="inline-block bg-brand-blue hover:bg-brand-blueHover text-white font-bold px-6 py-3 rounded-xl transition-all">
                        View Demolition Rates
                    </a>
                </div>
                <div class="lg:col-span-5 bg-brand-dark p-6 rounded-xl border border-brand-light/40 space-y-4">
                    <h4 class="font-heading text-lg font-bold text-white border-b border-brand-light/40 pb-2">Demolition Standards</h4>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Care & Control:</span>
                        <span class="font-semibold text-brand-blue">Protects Surrounding Areas</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Cleanup:</span>
                        <span class="font-semibold text-white">Broom-Swept & Nail-Free</span>
                    </div>
                    <div class="flex justify-between text-xs sm:text-sm text-slate-300">
                        <span class="text-slate-400">Debris Disposal:</span>
                        <span class="font-semibold text-white">Hauled Away Same Visit</span>
                    </div>
                    <div class="bg-brand-blue/10 p-4 rounded-lg border border-brand-blue/20 text-xs text-brand-blue font-medium">
                        <i class="fa-solid fa-circle-info mr-1"></i>
                        Ideal for general contractors who want a clean shell before their trades arrive.
                    </div>
                </div>
            </div>
        </div>

        <!-- DIRECT HAULING CALLOUT BAR -->
        <div class="mt-6 bg-brand-card/70 border border-brand-light/60 rounded-2xl p-5 sm:px-8 flex flex-col sm:flex-row items-center justify-between gap-4">
            <div class="flex items-center gap-3.5 text-center sm:text-left">
                <div class="w-10 h-10 rounded-xl bg-brand-blue/15 border border-brand-blue/30 text-brand-blue flex items-center justify-center shrink-0 text-lg">
                    <i class="fa-solid fa-truck-pickup"></i>
                </div>
                <div>
                    <h4 class="font-bold text-white text-sm sm:text-base">Need Material, Equipment, or General Hauling?</h4>
                    <p class="text-slate-400 text-xs">Local pickup and trailer transport available across Leamington & Essex County.</p>
                </div>
            </div>
            <span class="phone-slot shrink-0" data-btn="true" data-prefix="CALL FOR QUOTE: " data-style="bg-brand-dark hover:bg-brand-light text-white text-xs sm:text-sm font-bold px-5 py-3 rounded-xl border border-brand-blue/40 transition-all flex items-center gap-2 cursor-pointer"></span>
        </div>

    </section>
    <!-- INTERACTIVE ESTIMATE CALCULATOR / QUOTE FORM -->
    <section id="quote" class="py-20 px-4 sm:px-8 max-w-5xl mx-auto">
        <div class="bg-brand-card border border-brand-light rounded-3xl p-6 sm:p-12 shadow-2xl relative overflow-hidden">
            <div class="absolute top-0 right-0 w-64 h-64 bg-brand-blue/10 rounded-full blur-3xl pointer-events-none"></div>

            <div class="text-center max-w-2xl mx-auto mb-10">
                <span class="bg-brand-blue/20 text-brand-blue text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider border border-brand-blue/30">
                    Ballpark Calculator
                </span>
                <h2 class="font-heading text-3xl sm:text-4xl font-black text-white mt-3">REQUEST A FREE ESTIMATE</h2>
                <p class="text-slate-400 text-sm mt-2">Select your service and load size below for an instant ballpark range and quick callback.</p>
            </div>

            <form id="quote-form" onsubmit="handleQuoteSubmit(event)" class="space-y-8">
                <!-- STEP 1: SERVICE TYPE -->
                <div>
                    <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-3">
                        1. Select Service Type
                    </label>
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
                        <label class="cursor-pointer">
                            <input type="radio" name="service_type" value="Junk Removal & Cleanouts" class="peer sr-only" checked onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-blue peer-checked:bg-brand-blue/10 peer-checked:text-white transition-all text-center">
                                <i class="fa-solid fa-dumpster text-xl text-brand-blue mb-2 block"></i>
                                <span class="font-bold text-xs sm:text-sm block">Junk Removal & Cleanouts</span>
                            </div>
                        </label>

                        <label class="cursor-pointer">
                            <input type="radio" name="service_type" value="Interior Demolition" class="peer sr-only" onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-blue peer-checked:bg-brand-blue/10 peer-checked:text-white transition-all text-center">
                                <i class="fa-solid fa-person-digging text-xl text-brand-blue mb-2 block"></i>
                                <span class="font-bold text-xs sm:text-sm block">Interior & Selective Demo</span>
                            </div>
                        </label>

                        <label class="cursor-pointer">
                            <input type="radio" name="service_type" value="Hauling" class="peer sr-only" onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-blue peer-checked:bg-brand-blue/10 peer-checked:text-white transition-all text-center">
                                <i class="fa-solid fa-truck-pickup text-xl text-brand-blue mb-2 block"></i>
                                <span class="font-bold text-xs sm:text-sm block">Hauling (Call for Quote)</span>
                            </div>
                        </label>
                    </div>
                </div>

                <!-- STEP 2: PROJECT SCALE -->
                <div>
                    <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-3">
                        2. Select Estimated Load or Job Size
                    </label>
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                        <label class="cursor-pointer">
                            <input type="radio" name="project_scale" value="Small / Partial" class="peer sr-only" checked onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-blue peer-checked:bg-brand-blue/10 peer-checked:text-white transition-all text-center">
                                <span class="font-bold text-sm block">Small / Partial Load</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Few bulky items, small closet / partial room, "pickup truck bed load"</span>
                            </div>
                        </label>

                        <label class="cursor-pointer">
                            <input type="radio" name="project_scale" value="Medium / Multi-Area" class="peer sr-only" onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-blue peer-checked:bg-brand-blue/10 peer-checked:text-white transition-all text-center">
                                <span class="font-bold text-sm block">Medium Load / Single Room</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Garage cleanout, Kitchen / bath / Bedroom tear-out, shed demo, Truck bed & trailer</span>
                            </div>
                        </label>

                        <label class="cursor-pointer">
                            <input type="radio" name="project_scale" value="Large / Full Site" class="peer sr-only" onchange="calculateEstimate()">
                            <div class="p-4 rounded-xl border border-brand-light bg-brand-dark/60 peer-checked:border-brand-blue peer-checked:bg-brand-blue/10 peer-checked:text-white transition-all text-center">
                                <span class="font-bold text-sm block">Large / Multi-Load Cleanout</span>
                                <span class="text-[11px] text-slate-400 block mt-1">Full house/estate cleanout, multi-room gut</span>
                            </div>
                        </label>
                    </div>
                </div>

                <!-- STEP 3: LOCATION & DETAILS -->
                <div class="grid sm:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-2">Location / Municipality</label>
                        <select id="location-select" required class="w-full bg-brand-dark border border-brand-light rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-blue">
                            <option value="Leamington">Leamington, ON</option>
                            <option value="Kingsville">Kingsville, ON</option>
                            <option value="Wheatley">Wheatley, ON</option>
                            <option value="Essex">Essex, ON</option>
                            <option value="Harrow / Amherstburg">Harrow / Amherstburg</option>
                            <option value="Windsor / Chatham">Windsor / Chatham-Kent / Surrounding Area</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-2">Target Schedule</label>
                        <select id="timeline-select" class="w-full bg-brand-dark border border-brand-light rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-blue">
                            <option value="Within a Few Days">Within the Next Few Days</option>
                            <option value="Within 1-2 Weeks">Within 1–2 Weeks</option>
                            <option value="Planning Phase">Just Getting a Price / Planning Ahead</option>
                        </select>
                    </div>
                </div>

                <!-- CONTACT FIELDS -->
                <div class="grid sm:grid-cols-2 gap-4 pt-2">
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-2">Your Name</label>
                        <input type="text" required placeholder="John Smith" class="w-full bg-brand-dark border border-brand-light rounded-xl px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-brand-blue">
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-300 tracking-wider mb-2">Your Phone Number</label>
                        <input type="tel" required placeholder="519-000-0000" class="w-full bg-brand-dark border border-brand-light rounded-xl px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-brand-blue">
                    </div>
                </div>

                <!-- DYNAMIC ESTIMATE DISPLAY CARD -->
                <div class="bg-brand-dark p-6 rounded-2xl border border-brand-blue/30 flex flex-col sm:flex-row items-center justify-between gap-4">
                    <div>
                        <div class="text-xs uppercase font-bold text-slate-400">Ballpark Price Range:</div>
                        <div id="price-display" class="text-2xl sm:text-3xl font-heading font-black text-brand-blue">
                            $125 - $275 CAD
                        </div>
                        <div class="text-[11px] text-slate-400 mt-0.5">*Includes loading & dump fees. Exact price confirmed before any work starts.</div>
                    </div>
                    <button type="submit" class="w-full sm:w-auto bg-brand-blue hover:bg-brand-blueHover text-white font-extrabold text-base px-8 py-4 rounded-xl shadow-lg glow-blue transition-all whitespace-nowrap">
                        REQUEST CALLBACK
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
                    <span class="text-xs font-bold text-brand-blue uppercase tracking-widest">LOCAL LEAMINGTON SERVICE</span>
                    <h2 class="font-heading text-3xl sm:text-4xl font-black text-white">WHY HIRE NEXTPHASE SOLUTIONS</h2>
                    
                    <div class="space-y-4 pt-2">
                        <div class="flex items-start gap-4">
                            <div class="w-8 h-8 rounded-lg bg-brand-blue/20 text-brand-blue flex items-center justify-center shrink-0 font-bold border border-brand-blue/30">1</div>
                            <div>
                                <h4 class="font-bold text-white text-base">Direct Owner-Operator Accountability</h4>
                                <p class="text-slate-400 text-sm">You deal directly with the person quoting and doing the work—no middlemen, no runaround, and clear communication from start to finish.</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4">
                            <div class="w-8 h-8 rounded-lg bg-brand-blue/20 text-brand-blue flex items-center justify-center shrink-0 font-bold border border-brand-blue/30">2</div>
                            <div>
                                <h4 class="font-bold text-white text-base">Lean & Fast Turnaround</h4>
                                <p class="text-slate-400 text-sm">Equipped with a heavy-duty pickup, trailer, and tear-out tools ready to fit into tight driveways and residential spaces without damaging property.</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4">
                            <div class="w-8 h-8 rounded-lg bg-brand-blue/20 text-brand-blue flex items-center justify-center shrink-0 font-bold border border-brand-blue/30">3</div>
                            <div>
                                <h4 class="font-bold text-white text-base">Broom-Swept Clean Every Time</h4>
                                <p class="text-slate-400 text-sm">We don't just haul away the big stuff—we sweep up dust, nails, and loose debris so your space is clean and ready for whatever comes next.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Service Region Box -->
                <div class="lg:col-span-6 bg-brand-card border border-brand-light p-8 rounded-3xl space-y-6">
                    <h3 class="font-heading text-xl font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot text-brand-blue"></i>
                        <span>Local Service Area</span>
                    </h3>
                    <p class="text-slate-300 text-sm">Based in Leamington, ON—serving homeowners, landlords, and contractors across Essex County:</p>
                    
                    <div class="grid grid-cols-2 gap-3 text-sm font-semibold text-white">
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-blue text-xs"></i>
                            <span>Leamington</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-blue text-xs"></i>
                            <span>Kingsville</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-blue text-xs"></i>
                            <span>Wheatley</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-blue text-xs"></i>
                            <span>Essex</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-blue text-xs"></i>
                            <span>Harrow & Cottam</span>
                        </div>
                        <div class="p-3 bg-brand-dark rounded-xl border border-brand-light/40 flex items-center gap-2">
                            <i class="fa-solid fa-location-dot text-brand-blue text-xs"></i>
                            <span>Amherstburg & Windsor</span>
                        </div>
                    </div>

                    <div class="p-4 bg-brand-dark/80 rounded-xl border border-brand-blue/30 text-center">
                        <p class="text-xs text-slate-300 font-medium">Have a load to haul or a room to tear out?</p>
                        <span class="phone-slot mt-1 inline-block" data-btn="true" data-prefix="Call: " data-suffix=" →" data-style="text-brand-blue font-bold text-sm hover:underline inline-flex items-center gap-1.5 cursor-pointer"></span>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-slate-950 border-t border-brand-light/40 py-12 px-4 sm:px-8 text-slate-400 text-xs sm:text-sm">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8 mb-12">
            <!-- Col 1: Brand -->
            <div class="space-y-4">
                <div class="flex items-center gap-3">
                    <div class="w-8 h-8 bg-brand-blue rounded-lg flex items-center justify-center text-white font-heading font-black text-sm">
                        NP
                    </div>
                    <div>
                        <div class="font-heading font-bold text-white text-base leading-none">NEXTPHASE</div>
                        <div class="text-[9px] text-brand-blue font-bold tracking-[0.2em]">SOLUTIONS</div>
                    </div>
                </div>
                <p class="text-xs text-slate-400 leading-relaxed">
                    Leamington & Essex County Junk Removal, Property Cleanouts, Interior & Selective Demolition, and Local Hauling.
                </p>
            </div>

            <!-- Col 2: Core Capabilities -->
            <div>
                <h4 class="font-bold text-white text-sm mb-3">Services</h4>
                <ul class="space-y-1.5 text-xs">
                    <li><a href="#services" onclick="switchTab('junk')" class="hover:text-brand-blue">Junk Removal & Cleanouts</a></li>
                    <li><a href="#services" onclick="switchTab('demo')" class="hover:text-brand-blue">Interior & Selective Demolition</a></li>
                    <li><a href="#quote" class="hover:text-brand-blue">Material & Equipment Hauling (Call for Quote)</a></li>
                </ul>
            </div>

            <!-- Col 3: Direct Contact -->
            <div>
                <h4 class="font-bold text-white text-sm mb-3">Direct Contact</h4>
                <p class="text-xs text-slate-300">Leamington, Ontario, Canada</p>
                <p class="text-xs mt-2"><span class="text-slate-400">Phone: </span><span class="phone-slot" data-btn="true" data-style="text-brand-blue font-bold hover:underline inline-flex items-center gap-1 cursor-pointer"></span></p>
                <p class="text-xs text-slate-400 mt-1">Web: nextphasecompanies.ca</p>
            </div>
        </div>

        <div class="max-w-7xl mx-auto border-t border-brand-light/20 pt-6 flex flex-col sm:flex-row items-center justify-between gap-4 text-xs">
            <p>&copy; 2026 NextPhase Solutions. All Rights Reserved.</p>
            <div class="flex gap-4">
                <a href="#" class="hover:text-brand-blue">Privacy Policy</a>
                <a href="#" class="hover:text-brand-blue">Terms of Service</a>
            </div>
        </div>
    </footer>

    <!-- SUCCESS MODAL (Hidden by Default) -->
    <div id="success-modal" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-brand-card border border-brand-blue p-8 rounded-3xl max-w-md w-full text-center space-y-4 shadow-2xl relative">
            <div class="w-16 h-16 bg-brand-blue/20 text-brand-blue rounded-full flex items-center justify-center text-3xl mx-auto border border-brand-blue/40">
                <i class="fa-solid fa-circle-check"></i>
            </div>
            <h3 class="font-heading text-2xl font-black text-white">ESTIMATE REQUEST RECEIVED</h3>
            <p class="text-slate-300 text-sm">
                Thanks for reaching out! Your project details are in, and we will call you shortly to confirm pricing and scheduling.
            </p>
            <div class="p-4 bg-brand-dark rounded-xl border border-brand-light text-left text-xs space-y-1">
                <div class="text-slate-400">Want to reach us right away?</div>
                <div><span class="phone-slot" data-btn="true" data-prefix="Call Direct: " data-style="text-brand-blue font-bold text-sm hover:underline inline-flex items-center gap-1.5 cursor-pointer"></span></div>
            </div>
            <button onclick="closeModal()" class="w-full bg-brand-blue text-white font-bold py-3 rounded-xl hover:bg-brand-blueHover transition-all">
                CLOSE & RETURN TO WEBSITE
            </button>
        </div>
    </div>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // Bot-Resistant Phone Obfuscation & Click-to-Reveal
        // Encodes digits so neither static HTML scrapers nor simple JS regex crawlers find a plain number.
        const _encodedP = [50, 50, 54, 52, 55, 55, 54, 51, 57, 56];
        function getPhoneRaw() {
            return String.fromCharCode(..._encodedP);
        }
        function getPhoneFormatted() {
            const raw = getPhoneRaw();
            return `${raw.slice(0, 3)}.${raw.slice(3, 6)}.NEXT (${raw.slice(0, 3)}-${raw.slice(3, 6)}-${raw.slice(6)})`;
        }

        function initProtectedPhones() {
            const slots = document.querySelectorAll('.phone-slot');
            slots.forEach(slot => {
                const prefix = slot.dataset.prefix || '';
                const suffix = slot.dataset.suffix || '';
                const styleClass = slot.dataset.style || '';

                // Enforce Click-to-Reveal on EVERY phone slot so zero numbers render automatically on load
                const btn = document.createElement('button');
                btn.type = 'button';
                btn.className = styleClass;
                btn.innerHTML = `<i class="fa-solid fa-phone"></i><span>${prefix}SHOW NUMBER</span>`;
                btn.addEventListener('click', function () {
                    const raw = getPhoneRaw();
                    const link = document.createElement('a');
                    link.href = 'tel:' + raw;
                    link.className = styleClass;
                    link.innerHTML = `<i class="fa-solid fa-phone"></i><span>${prefix}${getPhoneFormatted()}${suffix}</span>`;
                    slot.innerHTML = '';
                    slot.appendChild(link);
                    window.location.href = 'tel:' + raw;
                });
                slot.innerHTML = '';
                slot.appendChild(btn);
            });
        }

        // Tab Switcher Logic
        function switchTab(tabKey) {
            // Hide all tab contents
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));

            // Reset tab button styling
            document.querySelectorAll('.tab-btn').forEach(btn => {
                btn.classList.remove('bg-brand-blue', 'text-white');
                btn.classList.add('bg-brand-card', 'text-slate-300', 'border', 'border-brand-light');
            });

            // Show active content
            const contentEl = document.getElementById(`content-${tabKey}`);
            if (contentEl) {
                contentEl.classList.remove('hidden');
            }

            // Highlight active button
            const activeBtn = document.getElementById(`tab-${tabKey}`);
            if (activeBtn) {
                activeBtn.classList.remove('bg-brand-card', 'text-slate-300', 'border', 'border-brand-light');
                activeBtn.classList.add('bg-brand-blue', 'text-white');
            }
        }

        // Grounded Price Calculator Logic
        function calculateEstimate() {
            const serviceChecked = document.querySelector('input[name="service_type"]:checked');
            const scaleChecked = document.querySelector('input[name="project_scale"]:checked');

            if (!serviceChecked || !scaleChecked) return;

            const service = serviceChecked.value;
            const scale = scaleChecked.value;
            const display = document.getElementById('price-display');

            if (service === 'Hauling') {
                display.textContent = 'Call for Quote';
                return;
            }

            if (service === 'Junk Removal & Cleanouts') {
                if (scale.includes('Small')) {
                    display.textContent = '$125 - $275 CAD';
                } else if (scale.includes('Medium')) {
                    display.textContent = '$300 - $900+ CAD';
                } else {
                    display.textContent = 'Starting at $1,200+ (Custom Quote)';
                }
            } else if (service === 'Interior Demolition') {
                if (scale.includes('Small')) {
                    display.textContent = '$250 - $600 CAD';
                } else if (scale.includes('Medium')) {
                    display.textContent = '$650 - $1,800+ CAD';
                } else {
                    display.textContent = 'Starting at $1,800+ (Custom Quote)';
                }
            }
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

        // Initialize phone protection and price calculation on page load
        window.addEventListener('DOMContentLoaded', function() {
            initProtectedPhones();
            calculateEstimate();
        });
    </script>
</body>
</html>
