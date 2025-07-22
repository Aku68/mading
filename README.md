<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mading Digital - MTsN 4 Bandung Barat</title>
    
    <!-- Menggunakan Tailwind CSS untuk styling modern -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Menggunakan Google Fonts untuk tipografi yang lebih baik -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    
    <style>
        /* Menetapkan font default */
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f0f4f8; /* Latar belakang abu-abu muda */
        }
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Inter', sans-serif;
        }
        /* Efek gradien untuk judul */
        .gradient-text {
            background: linear-gradient(to right, #1e40af, #3b82f6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-fill-color: transparent;
        }
        .card-hover {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }
        .card-hover:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }
    </style>
</head>
<body class="bg-slate-100 text-slate-800">

    <!-- Header dan Navigasi -->
    <header class="bg-white/80 backdrop-blur-lg shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <!-- Placeholder Logo -->
                <div class="w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center">
                    <span class="text-white font-bold text-xl">M4</span>
                </div>
                <div>
                    <h1 class="font-bold text-lg text-blue-800">Mading Digital</h1>
                    <p class="text-sm text-slate-600">MTs Negeri 4 Bandung Barat</p>
                </div>
            </div>
            <nav class="hidden md:flex space-x-6 items-center">
                <a href="#info" class="text-slate-600 hover:text-blue-600 font-semibold transition-colors">Info Sekolah</a>
                <a href="#kreasi" class="text-slate-600 hover:text-blue-600 font-semibold transition-colors">Karya Siswa</a>
                <a href="#galeri" class="text-slate-600 hover:text-blue-600 font-semibold transition-colors">Galeri</a>
                <a href="#redaksi" class="text-slate-600 hover:text-blue-600 font-semibold transition-colors">Tim Redaksi</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden p-2 rounded-md text-slate-600 hover:bg-slate-200">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4">
            <a href="#info" class="block py-2 text-slate-600 hover:text-blue-600 font-semibold">Info Sekolah</a>
            <a href="#kreasi" class="block py-2 text-slate-600 hover:text-blue-600 font-semibold">Karya Siswa</a>
            <a href="#galeri" class="block py-2 text-slate-600 hover:text-blue-600 font-semibold">Galeri</a>
            <a href="#redaksi" class="block py-2 text-slate-600 hover:text-blue-600 font-semibold">Tim Redaksi</a>
        </div>
    </header>

    <!-- Konten Utama -->
    <main class="container mx-auto px-6 py-8 md:py-12">

        <!-- Salam Redaksi -->
        <section id="salam" class="text-center mb-16">
            <h2 class="text-4xl md:text-6xl font-extrabold mb-4 gradient-text">Kreasi Siswa Opat Bandung Barat</h2>
            <p class="text-lg text-slate-600 max-w-3xl mx-auto">Edisi Juli 2025 - Menjadi wadah informasi, kreativitas, dan inspirasi bagi seluruh warga MTs Negeri 4 Bandung Barat. Selamat membaca!</p>
        </section>

        <!-- Info Sekolah -->
        <section id="info" class="mb-16">
            <h3 class="text-3xl font-bold mb-8 text-center text-blue-800">Gema Patbara: Info Terkini</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Kartu Info 1 -->
                <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                    <div class="flex items-center space-x-4 mb-4">
                        <div class="bg-blue-100 p-3 rounded-full"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-blue-600"><path d="M8 2v4"/><path d="M16 2v4"/><rect width="18" height="18" x="3" y="4" rx="2"/><path d="M3 10h18"/></svg></div>
                        <h4 class="text-xl font-bold text-slate-800">Jadwal PAS</h4>
                    </div>
                    <p class="text-slate-600">Penilaian Akhir Semester (PAS) Ganjil akan dilaksanakan mulai tanggal 1-8 Desember 2025. Persiapkan diri kalian dengan belajar yang tekun,memnggunakan waktu sebaik-baiknya untuk belajar!</p>
                </div>
                <!-- Kartu Info 2 -->
                <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                    <div class="flex items-center space-x-4 mb-4">
                        <div class="bg-green-100 p-3 rounded-full"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-600"><path d="M12.22 2h-4.44a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h8.88a2 2 0 0 0 2-2v-8.88z"/><path d="M18 2h-2.12a2 2 0 0 0-1.77 1.03L12 6H8"/><path d="M22 12h-4.12a2 2 0 0 0-1.77 1.03L14 18H10"/></svg></div>
                        <h4 class="text-xl font-bold text-slate-800">Lomba Class Meeting</h4>
                    </div>
                    <p class="text-slate-600">Segera daftarkan kelasmu untuk lomba futsal, tarik tambang, dan cerdas cermat. Pendaftaran ditutup 10 Desember.</p>
                </div>
                <!-- Kartu Info 3 -->
                <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                    <div class="flex items-center space-x-4 mb-4">
                        <div class="bg-purple-100 p-3 rounded-full"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-purple-600"><path d="M4 19.5v-15A2.5 2.5 0 0 1 6.5 2H20v20H6.5a2.5 2.5 0 0 1 0-5H20"/></svg></div>
                        <h4 class="text-xl font-bold text-slate-800">Literasi Digital</h4>
                    </div>
                    <p class="text-slate-600">Ayo ikuti seminar "Cerdas di Dunia Maya" pada hari Sabtu, 29 November 2025 di Aula Sekolah. Tempat terbatas!</p>
                </div>
            </div>
        </section>

        <!-- Karya Siswa -->
        <section id="kreasi" class="mb-16">
            <h3 class="text-3xl font-bold mb-8 text-center text-blue-800">Jendela Kreasi Siswa</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Puisi -->
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover">
                    <h4 class="text-2xl font-bold mb-2 text-slate-800">Senja di Bandung Barat</h4>
                    <p class="text-sm text-slate-500 mb-4">Oleh: Anisa Putri - Kelas IX A</p>
                    <p class="text-slate-600 italic leading-relaxed">Di ufuk barat, jingga memeluk mesra,<br>Menyapa gunung yang diam membisu.<br>Angin sepoi membawa kabar senja,<br>Tentang hari yang kan segera berlalu...</p>
                </div>
                <!-- Cerpen -->
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover">
                    <h4 class="text-2xl font-bold mb-2 text-slate-800">Sepatu Baru</h4>
                    <p class="text-sm text-slate-500 mb-4">Oleh: Budi Santoso - Kelas VIII B</p>
                    <p class="text-slate-600 leading-relaxed">Rian menatap sepatu barunya dengan binar di mata. Bukan sekadar alas kaki, itu adalah janji pada dirinya sendiri untuk berlari lebih kencang mengejar mimpi. Hari pertama ia memakainya ke sekolah terasa berbeda...</p>
                </div>
            </div>
        </section>

        <!-- Galeri -->
        <section id="galeri" class="mb-16">
            <h3 class="text-3xl font-bold mb-8 text-center text-blue-800">Galeri Prestasi & Kegiatan</h3>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <div class="grid gap-4">
                    <div><img class="h-auto max-w-full rounded-lg shadow-md" src="https://placehold.co/500x700/3b82f6/ffffff?text=Juara+1+Lomba+Pramuka" alt="Juara 1 Lomba Pramuka"></div>
                    <div><img class="h-auto max-w-full rounded-lg shadow-md" src="https://placehold.co/500x400/16a34a/ffffff?text=Kegiatan+Jumat+Bersih" alt="Kegiatan Jumat Bersih"></div>
                </div>
                <div class="grid gap-4">
                    <div><img class="h-auto max-w-full rounded-lg shadow-md" src="https://placehold.co/500x400/c026d3/ffffff?text=Pentas+Seni+Sekolah" alt="Pentas Seni Sekolah"></div>
                    <div><img class="h-auto max-w-full rounded-lg shadow-md" src="https://placehold.co/500x700/f97316/ffffff?text=Upacara+Bendera" alt="Upacara Bendera"></div>
                </div>
                <div class="grid gap-4">
                    <div><img class="h-auto max-w-full rounded-lg shadow-md" src="https://placehold.co/500x700/f59e0b/ffffff?text=Tim+Futsal+Patbara" alt="Tim Futsal Patbara"></div>
                    <div><img class="h-auto max-w-full rounded-lg shadow-md" src="https://placehold.co/500x400/0891b2/ffffff?text=Studi+Tur+ke+Museum" alt="Studi Tur ke Museum"></div>
                </div>
                <div class="grid gap-4">
                    <div><img class="h-auto max-w-full rounded-lg shadow-md" src="https://placehold.co/500x400/be185d/ffffff?text=Perpustakaan+Sekolah" alt="Perpustakaan Sekolah"></div>
                    <div><img class="h-auto max-w-full rounded-lg shadow-md" src="https://placehold.co/500x700/65a30d/ffffff?text=Lomba+Adzan" alt="Lomba Adzan"></div>
                </div>
            </div>
        </section>

        <!-- Tim Redaksi -->
        <section id="redaksi" class="mb-16">
            <h3 class="text-3xl font-bold mb-8 text-center text-blue-800">Tim Redaksi</h3>
            <div class="max-w-4xl mx-auto text-center bg-white p-8 rounded-xl shadow-lg">
                <h4 class="text-2xl font-bold mb-2">Pembina</h4>
                <p class="text-slate-600 mb-6">H. Ahmad Ridwan, S.PdI.</p>
                <h4 class="text-2xl font-bold mb-2">Ketua Redaksi</h4>
                <p class="text-slate-600 mb-6">Edward Azmy Efendi (Ketua OSIS)</p>
                <h4 class="text-2xl font-bold mb-2">Anggota Tim</h4>
                <p class="text-slate-600">Vida Ilma Nafis, Nazla, Daffa (VIII A), Gita (VIII B)</p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-blue-800 text-white">
        <div class="container mx-auto px-6 py-8 text-center">
            <p>&copy; 2025 Mading Digital MTs Negeri 4 Bandung Barat. All rights reserved.</p>
            <p class="text-sm text-blue-200 mt-2">Dibuat dengan semangat kreativitas.</p>
        </div>
    </footer>

    <!-- Tombol Kembali ke Atas -->
    <button id="back-to-top" class="hidden fixed bottom-8 right-8 bg-blue-600 text-white p-3 rounded-full shadow-lg hover:bg-blue-700 transition-all">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 15l7-7 7 7" />
        </svg>
    </button>

    <script>
        // Script untuk menu mobile
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Script untuk menutup menu mobile saat link di-klik
        const mobileNavLinks = document.querySelectorAll('#mobile-menu a');
        mobileNavLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Script untuk tombol "Kembali ke Atas"
        const backToTopButton = document.getElementById('back-to-top');
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('hidden');
            } else {
                backToTopButton.classList.add('hidden');
            }
        });
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
    </script>

</body>
</html>

