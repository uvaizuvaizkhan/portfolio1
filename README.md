<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kingsly Mohan | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- GSAP for smooth animations -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #0a0a0a;
            color: #ffffff;
            overflow-x: hidden;
        }
        .reveal { opacity: 0; transform: translateY(30px); }
        .line-grow { width: 0; height: 1px; background: #3b82f6; }
        .expertise-card:hover { background: #111; }
        .nav-blur { backdrop-filter: blur(10px); background: rgba(10, 10, 10, 0.8); }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav class="fixed w-full z-50 px-8 py-6 flex justify-between items-center nav-blur border-b border-white/5">
        <span class="text-lg font-bold tracking-tighter uppercase">KM / 24</span>
        <div class="flex gap-8 text-xs font-medium uppercase tracking-widest text-zinc-400">
            <a href="#work" class="hover:text-white transition">Experience</a>
            <a href="#expertise" class="hover:text-white transition">Expertise</a>
            <a href="mailto:Kingslymohan2017@gmail.com" class="hover:text-white transition">Contact</a>
        </div>
    </nav>

    <!-- Section 1: Hero -->
    <section class="min-h-screen flex flex-col justify-center px-8 lg:px-24">
        <div class="max-w-6xl">
            <h2 class="text-blue-500 font-medium mb-4 reveal uppercase tracking-[0.3em] text-sm italic">Based in Abu Dhabi, UAE</h2>
            <h1 class="text-6xl md:text-8xl font-bold tracking-tighter reveal mb-8 leading-none">
                KINGSLY <br> <span class="text-zinc-500">MOHAN.</span>
            </h1>
            <div class="flex flex-col md:flex-row md:items-center gap-8 reveal">
                <p class="text-lg text-zinc-400 max-w-xl leading-relaxed">
                    Senior Pipeline Rehabilitation Engineer specializing in CIPP technology. Delivering high-precision trenchless infrastructure solutions across the Middle East.
                </p>
                <div class="h-px w-24 bg-zinc-800 hidden md:block"></div>
                <div class="flex gap-4">
                    <div class="p-3 border border-white/10 rounded-full hover:bg-white hover:text-black transition cursor-pointer">
                        <i data-lucide="linkedin" class="w-5 h-5"></i>
                    </div>
                    <div class="p-3 border border-white/10 rounded-full hover:bg-white hover:text-black transition cursor-pointer">
                        <i data-lucide="mail" class="w-5 h-5"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section 2: Big Stats -->
    <section class="py-32 px-8 lg:px-24 border-y border-white/5 bg-zinc-950">
        <div class="grid md:grid-cols-3 gap-16">
            <div class="reveal">
                <span class="text-sm text-zinc-500 uppercase tracking-widest mb-4 block">Proven Track Record</span>
                <h3 class="text-6xl font-bold">300<span class="text-blue-500">+</span></h3>
                <p class="text-zinc-400 mt-2">Kilometers of pipeline rehabilitated using advanced CIPP systems.</p>
            </div>
            <div class="reveal" style="transition-delay: 0.1s;">
                <span class="text-sm text-zinc-500 uppercase tracking-widest mb-4 block">Industry Tenure</span>
                <h3 class="text-6xl font-bold">08<span class="text-blue-500">+</span></h3>
                <p class="text-zinc-400 mt-2">Years of progressive experience in UAE and Qatar environments.</p>
            </div>
            <div class="reveal" style="transition-delay: 0.2s;">
                <span class="text-sm text-zinc-500 uppercase tracking-widest mb-4 block">Core Focus</span>
                <h3 class="text-6xl font-bold">CIPP</h3>
                <p class="text-zinc-400 mt-2">Specialist in UV curing, robotic cutting, and trenchless maintenance.</p>
            </div>
        </div>
    </section>

    <!-- Section 3: Experience (The "Work" Section) -->
    <section id="work" class="py-32 px-8 lg:px-24">
        <h2 class="text-xs uppercase tracking-[0.5em] text-zinc-500 mb-16 reveal">Selected Experience</h2>
        
        <!-- Job 1 -->
        <div class="group py-12 border-b border-white/5 flex flex-col md:flex-row justify-between items-start md:items-center reveal">
            <div class="mb-4 md:mb-0">
                <span class="text-blue-500 text-sm font-mono mb-2 block">2026 — Present</span>
                <h3 class="text-3xl font-bold group-hover:translate-x-4 transition-transform duration-500 uppercase tracking-tighter">Veolia Middle East</h3>
            </div>
            <div class="text-left md:text-right">
                <p class="text-xl text-zinc-300">Pipeline Rehabilitation Engineer</p>
                <p class="text-sm text-zinc-500 mt-1 uppercase">Abu Dhabi, UAE</p>
            </div>
        </div>

        <!-- Job 2 -->
        <div class="group py-12 border-b border-white/5 flex flex-col md:flex-row justify-between items-start md:items-center reveal">
            <div class="mb-4 md:mb-0">
                <span class="text-zinc-500 text-sm font-mono mb-2 block">2023 — 2026</span>
                <h3 class="text-3xl font-bold group-hover:translate-x-4 transition-transform duration-500 uppercase tracking-tighter tracking-tighter">International Foundation Group</h3>
            </div>
            <div class="text-left md:text-right">
                <p class="text-xl text-zinc-300">Operations Engineer</p>
                <p class="text-sm text-zinc-500 mt-1 uppercase">United Arab Emirates</p>
            </div>
        </div>

        <!-- Job 3 -->
        <div class="group py-12 border-b border-white/5 flex flex-col md:flex-row justify-between items-start md:items-center reveal">
            <div class="mb-4 md:mb-0">
                <span class="text-zinc-500 text-sm font-mono mb-2 block">2018 — 2022</span>
                <h3 class="text-3xl font-bold group-hover:translate-x-4 transition-transform duration-500 uppercase tracking-tighter">Applus+ Velosi LLC</h3>
            </div>
            <div class="text-left md:text-right">
                <p class="text-xl text-zinc-300">Rehabilitation Specialist</p>
                <p class="text-sm text-zinc-500 mt-1 uppercase">Qatar</p>
            </div>
        </div>
    </section>

    <!-- Section 4: Expertise -->
    <section id="expertise" class="py-32 px-8 lg:px-24 bg-white text-black">
        <div class="grid lg:grid-cols-2 gap-16">
            <div>
                <h2 class="text-6xl font-bold tracking-tighter leading-none mb-8 reveal">Technical <br> Ecosystem.</h2>
                <p class="text-zinc-600 max-w-md reveal">A comprehensive suite of capabilities ranging from robotic intervention to complex condition assessment.</p>
            </div>
            <div class="space-y-12 reveal">
                <div>
                    <h4 class="text-sm uppercase tracking-widest font-bold border-b border-black/10 pb-4 mb-6">Machinery & Systems</h4>
                    <div class="flex flex-wrap gap-3">
                        <span class="px-4 py-2 border border-black/10 rounded-full text-sm">ProKASRO Robotics</span>
                        <span class="px-4 py-2 border border-black/10 rounded-full text-sm">Reline Europe</span>
                        <span class="px-4 py-2 border border-black/10 rounded-full text-sm">UV Curing Units</span>
                        <span class="px-4 py-2 border border-black/10 rounded-full text-sm">Inversion Drums</span>
                    </div>
                </div>
                <div>
                    <h4 class="text-sm uppercase tracking-widest font-bold border-b border-black/10 pb-4 mb-6">Inspection & QA</h4>
                    <div class="flex flex-wrap gap-3">
                        <span class="px-4 py-2 border border-black/10 rounded-full text-sm">IBAK IKAS Evolution</span>
                        <span class="px-4 py-2 border border-black/10 rounded-full text-sm">IPEK Systems</span>
                        <span class="px-4 py-2 border border-black/10 rounded-full text-sm">Defect Coding</span>
                        <span class="px-4 py-2 border border-black/10 rounded-full text-sm">HSE Compliance</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-20 px-8 lg:px-24 border-t border-white/5">
        <div class="flex flex-col md:flex-row justify-between items-end gap-12">
            <div>
                <h2 class="text-5xl md:text-7xl font-bold tracking-tighter reveal mb-10">LET'S CONNECT.</h2>
                <div class="flex flex-col gap-4 text-zinc-400 font-medium">
                    <a href="mailto:Kingslymohan2017@gmail.com" class="hover:text-white transition text-2xl">Kingslymohan2017@gmail.com</a>
                    <a href="tel:+971562483266" class="hover:text-white transition text-xl">+971 56 248 3266</a>
                </div>
            </div>
            <div class="text-zinc-500 text-xs uppercase tracking-widest">
                Designed for Kingsly Mohan — 2024
            </div>
        </div>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // GSAP Animations
        gsap.registerPlugin(ScrollTrigger);

        // Entrance Reveal Animation
        const reveals = document.querySelectorAll('.reveal');
        reveals.forEach((el) => {
            gsap.to(el, {
                scrollTrigger: {
                    trigger: el,
                    start: "top 85%",
                    toggleActions: "play none none none"
                },
                opacity: 1,
                y: 0,
                duration: 1.2,
                ease: "power4.out"
            });
        });

        // Job Row Hover Effect (Subtle)
        const jobRows = document.querySelectorAll('.group');
        jobRows.forEach((row) => {
            row.addEventListener('mouseenter', () => {
                gsap.to(row, { backgroundColor: "rgba(255,255,255,0.02)", duration: 0.3 });
            });
            row.addEventListener('mouseleave', () => {
                gsap.to(row, { backgroundColor: "transparent", duration: 0.3 });
            });
        });
    </script>
</body>
</html>
