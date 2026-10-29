<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Portofolio Saya</title>
    <!-- Tailwind CSS untuk styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 antialiased selection:bg-indigo-500 selection:text-white">

    <!-- Navigasi -->
    <nav class="fixed w-full z-50 bg-slate-900/80 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo -->
                <div class="flex-shrink-0 flex items-center">
                    <a href="#" class="text-2xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-indigo-400 to-cyan-400">
                        WebKu.
                    </a>
                </div>
                <!-- Menu Desktop -->
                <div class="hidden md:flex space-x-8">
                    <a href="#beranda" class="text-slate-300 hover:text-white transition">Beranda</a>
                    <a href="#layanan" class="text-slate-300 hover:text-white transition">Layanan</a>
                    <a href="#tentang" class="text-slate-300 hover:text-white transition">Tentang</a>
                </div>
                <!-- Tombol Kontak Desktop -->
                <div class="hidden md:flex">
                    <a href="#kontak" class="bg-indigo-600 hover:bg-indigo-700 text-white px-4 py-2 rounded-full font-medium transition shadow-lg shadow-indigo-600/30">
                        Hubungi Saya
                    </a>
                </div>
                <!-- Menu Mobile Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-300 hover:text-white focus:outline-none">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Menu Mobile Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-slate-800 border-b border-slate-700">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#beranda" class="block px-3 py-2 text-slate-300 hover:text-white hover:bg-slate-700 rounded-md">Beranda</a>
                <a href="#layanan" class="block px-3 py-2 text-slate-300 hover:text-white hover:bg-slate-700 rounded-md">Layanan</a>
                <a href="#tentang" class="block px-3 py-2 text-slate-300 hover:text-white hover:bg-slate-700 rounded-md">Tentang</a>
                <a href="#kontak" class="block px-3 py-2 text-indigo-400 font-bold hover:text-indigo-300">Hubungi Saya</a>
            </div>
        </div>
    </nav>

    <!-- Bagian Hero (Beranda) -->
    <section id="beranda" class="pt-32 pb-20 lg:pt-48 lg:pb-32 px-4 flex flex-col items-center justify-center text-center">
        <div class="inline-block mb-4 px-3 py-1 rounded-full bg-slate-800 border border-slate-700 text-sm text-cyan-400 font-medium">
            👋 Selamat datang di website saya
        </div>
        <h1 class="text-5xl md:text-7xl font-bold tracking-tight mb-6">
            Membangun <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-cyan-400">Masa Depan</span><br> Digital Anda
        </h1>
        <p class="max-w-2xl text-lg text-slate-400 mb-10">
            Saya adalah seorang desainer dan pengembang web yang bersemangat menciptakan pengalaman digital yang indah, fungsional, dan mudah digunakan.
        </p>
        <div class="flex flex-col sm:flex-row gap-4">
            <a href="#layanan" class="bg-indigo-600 hover:bg-indigo-700 text-white px-8 py-3 rounded-full font-semibold transition shadow-lg shadow-indigo-600/30">
                Mulai Proyek
            </a>
            <a href="#tentang" class="bg-slate-800 hover:bg-slate-700 text-white border border-slate-700 px-8 py-3 rounded-full font-semibold transition">
                Pelajari Lebih Lanjut
            </a>
        </div>
    </section>

    <!-- Bagian Layanan -->
    <section id="layanan" class="py-20 bg-slate-800/50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Layanan Terbaik Kami</h2>
                <p class="text-slate-400 max-w-2xl mx-auto">Solusi lengkap untuk kebutuhan digital Anda, dari desain hingga peluncuran.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Kartu Layanan 1 -->
                <div class="bg-slate-800 p-8 rounded-2xl border border-slate-700 hover:border-indigo-500 transition group">
                    <div class="w-14 h-14 bg-indigo-500/20 text-indigo-400 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Desain Website</h3>
                    <p class="text-slate-400 text-sm">Pembuatan antarmuka visual yang menarik, modern, dan sesuai dengan identitas merek Anda.</p>
                </div>

                <!-- Kartu Layanan 2 -->
                <div class="bg-slate-800 p-8 rounded-2xl border border-slate-700 hover:border-cyan-500 transition group">
                    <div class="w-14 h-14 bg-cyan-500/20 text-cyan-400 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Pengembangan Web</h3>
                    <p class="text-slate-400 text-sm">Menulis kode yang bersih, aman, dan responsif agar website berfungsi dengan sempurna di segala perangkat.</p>
                </div>

                <!-- Kartu Layanan 3 -->
                <div class="bg-slate-800 p-8 rounded-2xl border border-slate-700 hover:border-purple-500 transition group">
                    <div class="w-14 h-14 bg-purple-500/20 text-purple-400 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Optimasi Performa</h3>
                    <p class="text-slate-400 text-sm">Memastikan website Anda memuat dengan cepat dan dioptimalkan untuk mesin pencari (SEO).</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Bagian Tentang -->
    <section id="tentang" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="w-full md:w-1/2">
                    <img src="https://placehold.co/600x400/1e293b/a5b4fc?text=Gambar+Profil" alt="Profil" class="rounded-2xl shadow-2xl shadow-indigo-900/20 w-full object-cover">
                </div>
                <div class="w-full md:w-1/2">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6">Membantu bisnis tumbuh melalui desain yang hebat</h2>
                    <p class="text-slate-400 mb-6 text-lg">
                        Saya percaya bahwa website bukan hanya sekadar pajangan, melainkan alat komunikasi utama antara Anda dan pelanggan. Dengan pengalaman lebih dari 5 tahun, saya siap membantu mewujudkan visi Anda.
                    </p>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center text-slate-300">
                            <svg class="w-5 h-5 text-indigo-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                            Fokus pada Pengguna (User-Centric)
                        </li>
                        <li class="flex items-center text-slate-300">
                            <svg class="w-5 h-5 text-indigo-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                            Desain Responsif 100%
                        </li>
                        <li class="flex items-center text-slate-300">
                            <svg class="w-5 h-5 text-indigo-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                            Dukungan Jangka Panjang
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="kontak" class="bg-slate-950 py-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center">
            <div class="mb-4 md:mb-0">
                <span class="text-2xl font-bold text-white">WebKu.</span>
                <p class="text-slate-500 text-sm mt-2">© 2024 Hak Cipta Dilindungi.</p>
            </div>
            <div class="flex space-x-6">
                <!-- Icon Sosial Media Sederhana -->
                <a href="#" class="text-slate-400 hover:text-white transition">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/></svg>
                </a>
                <a href="#" class="text-slate-400 hover:text-white transition">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
                </a>
            </div>
        </div>
    </footer>

    <!-- Script untuk fungsi tombol menu mobile -->
    <script>
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
