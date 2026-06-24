<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>George Strait - Official Hub</title>
    <!-- Tailwind CSS for professional, modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: system-ui, -apple-system, sans-serif;
            background-color: #0f172a; /* Deep Slate Background */
            color: #f8fafc; /* Light Slate Text */
        }
        /* Custom background for the header area */
        .hero-bg {
            background: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 1)), 
                        url('https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80') center/cover;
        }
    </style>
</head>
<body class="antialiased selection:bg-amber-500 selection:text-slate-900">

    <!-- Header Section -->
    <header class="hero-bg py-24 px-6 text-center border-b border-slate-800">
        <div class="max-w-3xl mx-auto">
            <span class="text-amber-500 font-semibold tracking-widest uppercase text-xs mb-4 block">Official Fan Hub</span>
            <h1 class="text-5xl md:text-7xl font-bold mb-6 text-white tracking-tight">George Strait</h1>
            <p class="text-lg md:text-xl text-slate-400">The King of Country • Biography & Media Archive • Updated Daily</p>
        </div>
    </header>

    <main class="max-w-4xl mx-auto px-6 py-16 space-y-16">
        
        <!-- Stats Section -->
        <section class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
            <div class="bg-slate-800/40 p-6 rounded-2xl border border-slate-700/50 hover:border-slate-500 transition-colors">
                <p class="text-slate-400 text-sm uppercase tracking-wider mb-2">Born</p>
                <p class="text-xl font-semibold text-white">May 18, 1952</p>
            </div>
            <div class="bg-slate-800/40 p-6 rounded-2xl border border-slate-700/50 hover:border-slate-500 transition-colors">
                <p class="text-slate-400 text-sm uppercase tracking-wider mb-2">Origin</p>
                <p class="text-xl font-semibold text-white">Poteet, Texas</p>
            </div>
            <div class="bg-slate-800/40 p-6 rounded-2xl border border-slate-700/50 hover:border-slate-500 transition-colors">
                <p class="text-slate-400 text-sm uppercase tracking-wider mb-2">Legacy</p>
                <p class="text-xl font-semibold text-white">60 No. 1 Hits</p>
            </div>
        </section>

        <!-- Biography Section -->
        <section class="space-y-6">
            <h2 class="text-3xl font-bold text-white border-b border-slate-700 pb-4">The Career Journey</h2>
            <div class="text-slate-300 space-y-4 leading-relaxed text-lg">
                <p>George Strait is undeniably "The King of Country." With a career spanning over four decades, he has remained a cornerstone of traditional country music, refusing to compromise his authentic sound for fleeting pop trends.</p>
                <p>Holding the record for the most number-one hits in the history of music across all genres, his influence is immeasurable. From playing local honky-tonks in Texas to selling out massive stadium tours, his journey is a testament to the timeless appeal of a cowboy and his guitar.</p>
            </div>
        </section>

        <!-- Meet & Greet Section -->
        <section class="bg-gradient-to-br from-amber-900/30 to-slate-800/50 p-8 md:p-12 rounded-3xl border border-amber-700/30 relative overflow-hidden shadow-2xl">
            <div class="relative z-10">
                <span class="bg-amber-500 text-slate-900 text-xs font-bold px-4 py-1.5 rounded-full uppercase tracking-wider shadow-lg">Exclusive Opportunity</span>
                <h2 class="text-3xl md:text-4xl font-bold text-white mt-8 mb-4">Fan Meet & Greet</h2>
                <p class="text-slate-300 mb-8 max-w-2xl text-lg">An exclusive experience for dedicated supporters. Connect directly, share your favorite moments, and join an unforgettable session.</p>
                
                <div class="text-5xl font-light text-white mb-8 tracking-tight">$400.00</div>
                <ul class="text-slate-300 space-y-3 mb-10 text-lg">
                    <li class="flex items-center"><span class="text-amber-500 mr-3">✓</span> Professional meetup</li>
                    <li class="flex items-center"><span class="text-amber-500 mr-3">✓</span> Photo opportunity</li>
                    <li class="flex items-center"><span class="text-amber-500 mr-3">✓</span> Personalized interaction</li>
                </ul>
                
                <!-- Email Link configured with Subject and Body pre-fills -->
                <a href="mailto:personalgeorgestraitt@gmail.com?subject=Meet%20and%20Greet%20Inquiry&body=I%20would%20like%20to%20inquire%20about%20the%20Fan%20Meet%20%26%20Greet%20experience." 
                   class="inline-block bg-amber-500 hover:bg-amber-400 text-slate-900 font-bold py-4 px-10 rounded-xl transition duration-300 ease-in-out transform hover:-translate-y-1 shadow-[0_0_20px_rgba(245,158,11,0.3)]">
                    Inquire for Availability
                </a>
            </div>
        </section>

        <!-- Collaborate Section -->
        <section class="text-center bg-slate-800/20 p-12 rounded-3xl border border-slate-700/50">
            <h2 class="text-2xl font-bold text-white mb-4">Collaborate or Inquire</h2>
            <p class="text-slate-400 mb-6 text-lg">Interested in partnerships, interviews, or special projects? We'd love to hear from you.</p>
            <p class="text-slate-300 mb-8 text-lg"><strong>Managed by:</strong> <a href="mailto:personalgeorgestraitt@gmail.com" class="text-amber-500 hover:text-amber-400 underline decoration-amber-500/30 underline-offset-4">personalgeorgestraitt@gmail.com</a></p>
            <a href="mailto:personalgeorgestraitt@gmail.com?subject=Collaboration%20Inquiry" 
               class="inline-block border-2 border-slate-600 hover:border-amber-500 hover:text-amber-500 text-white font-semibold py-3 px-8 rounded-xl transition duration-300">
                Send Direct Message
            </a>
        </section>

    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-800 mt-8 py-10 text-center text-slate-500 text-sm">
        <div class="max-w-4xl mx-auto px-6 space-y-2">
            <p>© 2026 George Strait Official Hub. All rights reserved.</p>
            <p>This portal celebrates the legendary career of George Strait.</p>
        </div>
    </footer>

</body>
</html>
