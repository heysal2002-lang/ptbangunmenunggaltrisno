<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PT Bangun Manunggal Trisno - Solusi Konstruksi & Perdagangan Umum</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Montserrat & Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            800: '#152542',
                            900: '#0b1325',
                            DEFAULT: '#1e3a8a'
                        },
                        gold: {
                            400: '#fbbf24',
                            500: '#d97706',
                            DEFAULT: '#f59e0b'
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
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased">

    <!-- Header / Navbar -->
    <header class="fixed top-0 left-0 w-full bg-navy-900/95 backdrop-blur-md text-white z-50 shadow-lg border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo / Name -->
            <a href="#" class="flex items-center gap-3 group">
                <img src="logo.jpg" alt="Logo PT Bangun Manunggal Trisno" class="w-10 h-10 object-cover rounded-lg shadow-md group-hover:scale-105 transition-transform bg-white">
                <div class="flex flex-col">
                    <span class="font-heading font-bold text-lg tracking-wide leading-tight text-white group-hover:text-gold transition-colors">PT BANGUN MANUNGGAL TRISNO</span>
                    <span class="text-[10px] text-slate-400 tracking-wider uppercase">General Contractor & Supplier</span>
                </div>
            </a>

            <!-- Desktop Navigation -->
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium">
                <a href="#home" class="hover:text-gold transition-colors">Beranda</a>
                <a href="#about" class="hover:text-gold transition-colors">Tentang Kami</a>
                <a href="#services" class="hover:text-gold transition-colors">Layanan</a>
                <a href="#portfolio" class="hover:text-gold transition-colors">Portofolio</a>
                <a href="#why-us" class="hover:text-gold transition-colors">Keunggulan</a>
                <a href="#contact" class="hover:text-gold transition-colors">Kontak</a>
            </nav>

            <!-- CTA Button Desktop -->
            <div class="hidden lg:flex items-center">
                <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20mengenai%20proyek%20konstruksi." 
                   target="_blank" 
                   class="bg-gradient-to-r from-gold to-yellow-500 hover:from-yellow-500 hover:to-gold text-navy-900 font-semibold px-5 py-2.5 rounded-full shadow-lg shadow-gold/20 hover:shadow-gold/40 transition-all flex items-center gap-2 text-sm">
                    <i class="fa-brands fa-whatsapp text-lg"></i>
                    <span>Konsultasi WA</span>
                </a>
            </div>

            <!-- Mobile Menu Button -->
            <button id="menu-btn" class="md:hidden text-slate-300 hover:text-white focus:outline-none p-2">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile Navigation Drawer -->
        <div id="mobile-menu" class="hidden md:hidden bg-navy-900 border-t border-slate-800 px-4 pt-4 pb-6 space-y-3">
            <a href="#home" class="block py-2 text-slate-200 hover:text-gold font-medium border-b border-slate-800/50">Beranda</a>
            <a href="#about" class="block py-2 text-slate-200 hover:text-gold font-medium border-b border-slate-800/50">Tentang Kami</a>
            <a href="#services" class="block py-2 text-slate-200 hover:text-gold font-medium border-b border-slate-800/50">Layanan</a>
            <a href="#portfolio" class="block py-2 text-slate-200 hover:text-gold font-medium border-b border-slate-800/50">Portofolio</a>
            <a href="#why-us" class="block py-2 text-slate-200 hover:text-gold font-medium border-b border-slate-800/50">Keunggulan</a>
            <a href="#contact" class="block py-2 text-slate-200 hover:text-gold font-medium">Kontak</a>
            <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20mengenai%20proyek%20konstruksi." 
               target="_blank" 
               class="mt-4 w-full bg-gold text-navy-900 font-bold py-3 rounded-lg flex items-center justify-center gap-2 shadow-md">
                <i class="fa-brands fa-whatsapp text-xl"></i>
                <span>Konsultasi WhatsApp</span>
            </a>
        </div>
    </header>

    <!-- 1. Bagian Utama / Hero Section -->
    <section id="home" class="relative min-h-screen pt-20 flex items-center justify-center bg-navy-900 overflow-hidden">
        <!-- Background Overlay -->
        <div class="absolute inset-0 z-0 opacity-20 bg-cover bg-center" style="background-image: url('sakura-java.jpg');"></div>
        <div class="absolute inset-0 bg-gradient-to-t from-navy-900 via-navy-900/80 to-transparent z-0"></div>

        <div class="relative z-10 max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center py-24">
            <span class="inline-block px-4 py-1.5 bg-gold/10 border border-gold/30 text-gold text-xs sm:text-sm font-semibold rounded-full mb-6 tracking-wide uppercase">
                General Contractor & Supplier Terpercaya
            </span>
            <h1 class="text-3xl sm:text-5xl lg:text-6xl font-heading font-extrabold text-white tracking-tight leading-tight mb-6">
                PT Bangun Manunggal Trisno
            </h1>
            <p class="text-lg sm:text-xl text-slate-300 max-w-3xl mx-auto font-light leading-relaxed mb-10">
                Mitra Terpercaya Solusi Konstruksi dan Perdagangan Umum
            </p>
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20mengenai%20proyek%20konstruksi." 
                   target="_blank" 
                   class="w-full sm:w-auto bg-gradient-to-r from-gold to-yellow-500 hover:from-yellow-500 hover:to-gold text-navy-900 font-bold px-8 py-4 rounded-xl shadow-xl shadow-gold/20 hover:scale-105 transition-all flex items-center justify-center gap-3 text-base">
                    <i class="fa-brands fa-whatsapp text-2xl"></i>
                    <span>Konsultasi Proyek (WhatsApp)</span>
                </a>
                <a href="#services" class="w-full sm:w-auto bg-slate-800/80 hover:bg-slate-700 text-white font-semibold px-8 py-4 rounded-xl border border-slate-700 transition-all flex items-center justify-center text-base">
                    Lihat Layanan Kami
                </a>
            </div>
        </div>
    </section>

    <!-- 2. Tentang Kami (About Us) -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <div class="inline-flex items-center gap-2 text-gold font-bold text-sm uppercase tracking-wider">
                        <span class="w-8 h-0.5 bg-gold"></span>
                        <span>Tentang Kami</span>
                    </div>
                    <h2 class="text-3xl sm:text-4xl font-heading font-bold text-navy-900 leading-tight">
                        Komitmen Mutu & Kekuatan Konstruksi Terintegrasi
                    </h2>
                    <p class="text-slate-600 leading-relaxed text-base sm:text-lg">
                        <strong>PT Bangun Manunggal Trisno</strong> adalah perusahaan yang bergerak di bidang jasa konstruksi terintegrasi. Kami berkomitmen memberikan hasil pembangunan yang kokoh, aman, tepat waktu, dan berstandar mutu tinggi.
                    </p>
                    <p class="text-slate-600 leading-relaxed text-base">
                        Dengan didukung oleh tenaga ahli profesional dan berpengalaman di bidangnya, kami siap melayani berbagai kebutuhan proyek konstruksi skala kecil, menengah, hingga besar di seluruh Indonesia.
                    </p>
                    <div class="grid grid-cols-2 gap-6 pt-4 border-t border-slate-100">
                        <div>
                            <span class="block text-3xl font-heading font-extrabold text-gold mb-1">100%</span>
                            <span class="text-sm text-slate-500 font-medium">Standar Mutu & Keamanan</span>
                        </div>
                        <div>
                            <span class="block text-3xl font-heading font-extrabold text-gold mb-1">Berbadan Hukum</span>
                            <span class="text-sm text-slate-500 font-medium">Resmi & Legalitas Lengkap</span>
                        </div>
                    </div>
                </div>

                <div class="relative">
                    <div class="rounded-2xl overflow-hidden shadow-2xl bg-navy-900 text-white p-8 sm:p-10 relative">
                        <div class="absolute top-0 right-0 p-8 opacity-10">
                            <i class="fa-solid fa-building-shield text-9xl"></i>
                        </div>
                        <h3 class="text-2xl font-heading font-bold text-gold mb-4">Visi & Misi Perusahaan</h3>
                        <p class="text-slate-300 text-sm leading-relaxed mb-6">
                            Menjadi mitra utama konstruksi terpercaya yang mengedepankan efisiensi, inovasi teknis, serta standar K3 ketat dalam setiap penyelesaian proyek.
                        </p>
                        <ul class="space-y-3 text-sm text-slate-200">
                            <li class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-gold"></i>
                                <span>Manajemen proyek transparan & akuntabel</span>
                            </li>
                            <li class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-gold"></i>
                                <span>Kemitraan jangka panjang berbasis kepercayaan</span>
                            </li>
                            <li class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-gold"></i>
                                <span>Hasil pengerjaan tepat waktu sesuai RAB</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. Layanan Kami (Services) -->
    <section id="services" class="py-20 bg-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-gold font-bold text-sm uppercase tracking-wider block mb-2">Layanan Profesional</span>
                <h2 class="text-3xl sm:text-4xl font-heading font-bold text-navy-900">Solusi Konstruksi Terlengkap</h2>
                <p class="text-slate-600 mt-4">Kami menyediakan pengerjaan konstruksi end-to-end dari perencanaan hingga pengerjaan akhir.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white rounded-xl p-8 shadow-md hover:shadow-xl transition-all border border-slate-200/60 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-navy-900/5 text-gold rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-gold group-hover:text-navy-900 transition-colors">
                            <i class="fa-solid fa-city"></i>
                        </div>
                        <h3 class="text-xl font-heading font-bold text-navy-900 mb-3">Konstruksi Bangunan & Gedung</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Pembangunan rumah tinggal, ruko, gedung perkantoran, dan fasilitas umum dari perencanaan hingga selesai.
                        </p>
                    </div>
                </div>

                <!-- Service 2 -->
                <div class="bg-white rounded-xl p-8 shadow-md hover:shadow-xl transition-all border border-slate-200/60 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-navy-900/5 text-gold rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-gold group-hover:text-navy-900 transition-colors">
                            <i class="fa-solid fa-screwdriver-wrench"></i>
                        </div>
                        <h3 class="text-xl font-heading font-bold text-navy-900 mb-3">Renovasi & Restorasi</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Perbaikan, perluasan, dan pembaruan struktur maupun interior bangunan sesuai kebutuhan spesifik Anda.
                        </p>
                    </div>
                </div>

                <!-- Service 3 -->
                <div class="bg-white rounded-xl p-8 shadow-md hover:shadow-xl transition-all border border-slate-200/60 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-navy-900/5 text-gold rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-gold group-hover:text-navy-900 transition-colors">
                            <i class="fa-solid fa-road"></i>
                        </div>
                        <h3 class="text-xl font-heading font-bold text-navy-900 mb-3">Pekerjaan Infrastruktur & Sipil</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Pengerjaan jalan, saluran air/drainase, turap penahan tanah, serta pengerjaan sipil pendukung lainnya.
                        </p>
                    </div>
                </div>

                <!-- Service 4 -->
                <div class="bg-white rounded-xl p-8 shadow-md hover:shadow-xl transition-all border border-slate-200/60 flex flex-col justify-between group">
                    <div>
                        <div class="w-14 h-14 bg-navy-900/5 text-gold rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-gold group-hover:text-navy-900 transition-colors">
                            <i class="fa-solid fa-clipboard-check"></i>
                        </div>
                        <h3 class="text-xl font-heading font-bold text-navy-900 mb-3">Manajemen & Konsultasi Proyek</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Pengawasan teknis, perencanaan anggaran (RAB), dan pengelolaan tata kelola proyek secara efektif & efisien.
                        </p>
                    </div>
                </div>

                <!-- Service 5 -->
                <div class="bg-white rounded-xl p-8 shadow-md hover:shadow-xl transition-all border border-slate-200/60 flex flex-col justify-between group md:col-span-2 lg:col-span-1">
                    <div>
                        <div class="w-14 h-14 bg-navy-900/5 text-gold rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-gold group-hover:text-navy-900 transition-colors">
                            <i class="fa-solid fa-trowel-bricks"></i>
                        </div>
                        <h3 class="text-xl font-heading font-bold text-navy-900 mb-3">Pematangan Lahan</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Layanan lengkap mencakup <em>land clearing</em>, <em>cut and fill</em>, pemadatan tanah (<em>compaction</em>), serta pembangunan sistem drainase.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Portofolio Proyek (Project Portfolio) -->
    <section id="portfolio" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-gold font-bold text-sm uppercase tracking-wider block mb-2">Pengalaman Kerja</span>
                <h2 class="text-3xl sm:text-4xl font-heading font-bold text-navy-900">Portofolio Proyek Unggulan</h2>
                <p class="text-slate-600 mt-4">Rekam jejak pengerjaan proyek konstruksi PT Bangun Manunggal Trisno di berbagai sektor industri dan instansi.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Portfolio Item 1 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all">
                    <div class="h-56 bg-slate-800 relative overflow-hidden">
                        <img src="sakura-java.jpg" alt="Revitalisasi PT Sakura Java Indonesia" class="w-full h-full object-cover">
                        <span class="absolute top-4 left-4 bg-navy-900/90 text-gold text-xs px-3 py-1 rounded-full font-semibold">Cikarang, EJIP</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-heading font-bold text-lg text-navy-900 mb-2">Revitalisasi Infrastruktur Jalan</h3>
                        <p class="text-xs text-gold font-semibold uppercase tracking-wider mb-3">PT. Sakura Java Indonesia</p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Pengerjaan revitalisasi jalan kawasan industri, perbaikan beton, dan pengecoran area pabrik.
                        </p>
                    </div>
                </div>

                <!-- Portfolio Item 2 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all">
                    <div class="h-56 bg-slate-800 relative overflow-hidden">
                        <img src="brin-serpong.jpg" alt="Project BRIN Serpong" class="w-full h-full object-cover">
                        <span class="absolute top-4 left-4 bg-navy-900/90 text-gold text-xs px-3 py-1 rounded-full font-semibold">Serpong, Tangerang</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-heading font-bold text-lg text-navy-900 mb-2">Pematangan Lahan & Bunker</h3>
                        <p class="text-xs text-gold font-semibold uppercase tracking-wider mb-3">BRIN Serpong</p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Pekerjaan Cut and Fill, pondasi penahan tanah, serta pengerjaan pembuatan bunker khusus.
                        </p>
                    </div>
                </div>

                <!-- Portfolio Item 3 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all">
                    <div class="h-56 bg-slate-800 relative overflow-hidden">
                        <img src="smkn-12.jpg" alt="SMKN 12 Legok" class="w-full h-full object-cover">
                        <span class="absolute top-4 left-4 bg-navy-900/90 text-gold text-xs px-3 py-1 rounded-full font-semibold">Legok, Kab. Tangerang</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-heading font-bold text-lg text-navy-900 mb-2">Revitalisasi Gedung Praktik</h3>
                        <p class="text-xs text-gold font-semibold uppercase tracking-wider mb-3">SMKN 12 Kab. Tangerang</p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Design & Building Ruang Praktik Siswa dan fasilitas toilet pendukung.
                        </p>
                    </div>
                </div>

                <!-- Portfolio Item 4 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all">
                    <div class="h-56 bg-slate-800 relative overflow-hidden">
                        <img src="ajinomoto.jpg" alt="Ajinomoto Karawang" class="w-full h-full object-cover">
                        <span class="absolute top-4 left-4 bg-navy-900/90 text-gold text-xs px-3 py-1 rounded-full font-semibold">Karawang Barat</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-heading font-bold text-lg text-navy-900 mb-2">Konstruksi STP & Infrastruktur</h3>
                        <p class="text-xs text-gold font-semibold uppercase tracking-wider mb-3">PT. Ajinomoto Indonesia</p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Pengerjaan struktur penampungan STP (Sewage Treatment Plant) dan fasilitas infrastruktur pabrik.
                        </p>
                    </div>
                </div>

                <!-- Portfolio Item 5 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all">
                    <div class="h-56 bg-slate-800 relative overflow-hidden">
                        <img src="mandom.jpg" alt="PT Mandom MM2100" class="w-full h-full object-cover">
                        <span class="absolute top-4 left-4 bg-navy-900/90 text-gold text-xs px-3 py-1 rounded-full font-semibold">Cibitung, MM2100</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-heading font-bold text-lg text-navy-900 mb-2">Pekerjaan Jalan & Pile Cap</h3>
                        <p class="text-xs text-gold font-semibold uppercase tracking-wider mb-3">PT. Mandom Indonesia</p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Konstruksi fondasi pile cap gedung pabrik baru, pekerjaan pematangan jalan, dan saluran.
                        </p>
                    </div>
                </div>

                <!-- Portfolio Item 6 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-lg transition-all">
                    <div class="h-56 bg-slate-800 relative overflow-hidden">
                        <img src="<img width="1195" height="896" alt="krakatau" src="https://github.com/user-attachments/assets/442b4a3c-9d49-4f3d-839f-753abb69445c" />
" alt="Dermaga Cigading" class="w-full h-full object-cover">
                        <span class="absolute top-4 left-4 bg-navy-900/90 text-gold text-xs px-3 py-1 rounded-full font-semibold">Serang, Banten</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-heading font-bold text-lg text-navy-900 mb-2">Struktur Sipil Dermaga</h3>
                        <p class="text-xs text-gold font-semibold uppercase tracking-wider mb-3">Dermaga Cigading (PT Krakatau Eng.)</p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Pengerjaan struktur beton, fasilitas dermaga, serta pekerjaan konstruksi lapangan pendukung.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. Keunggulan Kami (Why Choose Us) -->
    <section id="why-us" class="py-20 bg-navy-900 text-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-gold font-bold text-sm uppercase tracking-wider block mb-2">Nilai Tambah Kami</span>
                <h2 class="text-3xl sm:text-4xl font-heading font-bold">Mengapa Memilih Kami?</h2>
                <p class="text-slate-300 mt-4">Prinsip utama yang menjadikan kami mitra terpercaya di bidang jasa konstruksi nasional.</p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Reason 1 -->
                <div class="bg-slate-800/60 p-6 rounded-xl border border-slate-700/60 hover:border-gold/50 transition-all text-center">
                    <div class="w-16 h-16 bg-gold/10 text-gold rounded-full flex items-center justify-center text-2xl mx-auto mb-6">
                        <i class="fa-solid fa-user-gear"></i>
                    </div>
                    <h3 class="font-heading font-bold text-lg mb-3">Tenaga Ahli Berpengalaman</h3>
                    <p class="text-slate-300 text-sm leading-relaxed">
                        Dikerjakan oleh tim profesional, ahli teknik terakreditasi, dan pekerja lapangan terlatih.
                    </p>
                </div>

                <!-- Reason 2 -->
                <div class="bg-slate-800/60 p-6 rounded-xl border border-slate-700/60 hover:border-gold/50 transition-all text-center">
                    <div class="w-16 h-16 bg-gold/10 text-gold rounded-full flex items-center justify-center text-2xl mx-auto mb-6">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="font-heading font-bold text-lg mb-3">Mutu & Kualitas Terjamin</h3>
                    <p class="text-slate-300 text-sm leading-relaxed">
                        Menggunakan material berkualitas sesuai standar keamanan teknis dan konstruksi bangunan.
                    </p>
                </div>

                <!-- Reason 3 -->
                <div class="bg-slate-800/60 p-6 rounded-xl border border-slate-700/60 hover:border-gold/50 transition-all text-center">
                    <div class="w-16 h-16 bg-gold/10 text-gold rounded-full flex items-center justify-center text-2xl mx-auto mb-6">
                        <i class="fa-solid fa-clock font-bold"></i>
                    </div>
                    <h3 class="font-heading font-bold text-lg mb-3">Tepat Waktu & Transparan</h3>
                    <p class="text-slate-300 text-sm leading-relaxed">
                        Perencanaan pengerjaan yang terstruktur serta estimasi Rencana Anggaran Biaya (RAB) yang jelas.
                    </p>
                </div>

                <!-- Reason 4 -->
                <div class="bg-slate-800/60 p-6 rounded-xl border border-slate-700/60 hover:border-gold/50 transition-all text-center">
                    <div class="w-16 h-16 bg-gold/10 text-gold rounded-full flex items-center justify-center text-2xl mx-auto mb-6">
                        <i class="fa-solid fa-file-contract"></i>
                    </div>
                    <h3 class="font-heading font-bold text-lg mb-3">Legalitas Perusahaan Lengkap</h3>
                    <p class="text-slate-300 text-sm leading-relaxed">
                        Perusahaan resmi berbadan hukum (PT) dengan sertifikasi NIB, SBU, dan standar ISO terverifikasi.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. Kontak & Lokasi (Contact Us & Interactive Map) -->
    <section id="contact" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-gold font-bold text-sm uppercase tracking-wider block mb-2">Hubungi Kami</span>
                <h2 class="text-3xl sm:text-4xl font-heading font-bold text-navy-900">Kontak & Lokasi Kantor</h2>
                <p class="text-slate-600 mt-4">Silakan hubungi kami untuk informasi lebih lanjut atau konsultasi kebutuhan proyek Anda.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                <!-- Contact Info Details -->
                <div class="lg:col-span-5 bg-white p-8 rounded-2xl shadow-md border border-slate-200/80 space-y-6">
                    <h3 class="text-xl font-heading font-bold text-navy-900 border-b border-slate-100 pb-4">Informasi Operasional</h3>
                    
                    <div class="flex items-start gap-4">
                        <div class="w-10 h-10 bg-navy-900/5 text-gold rounded-lg flex items-center justify-center shrink-0 text-lg mt-1">
                            <i class="fa-solid fa-location-dot"></i>
                        </div>
                        <div>
                            <span class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Alamat Kantor</span>
                            <p class="text-slate-700 text-sm leading-relaxed">
                                Jl. Green Lake City Boulevard Jl. West Europe VIII No.69, RT.001/RW.001, Ketapang, Kec. Cipondoh, Kota Tangerang, Banten 15147
                            </p>
                        </div>
                    </div>

                    <div class="flex items-start gap-4">
                        <div class="w-10 h-10 bg-navy-900/5 text-gold rounded-lg flex items-center justify-center shrink-0 text-lg mt-1">
                            <i class="fa-solid fa-phone"></i>
                        </div>
                        <div>
                            <span class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Telepon Kantor</span>
                            <a href="tel:02123096007" class="text-slate-700 hover:text-navy-900 text-sm font-medium">02123096007</a>
                        </div>
                    </div>

                    <div class="flex items-start gap-4">
                        <div class="w-10 h-10 bg-emerald-500/10 text-emerald-600 rounded-lg flex items-center justify-center shrink-0 text-lg mt-1">
                            <i class="fa-brands fa-whatsapp"></i>
                        </div>
                        <div>
                            <span class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">WhatsApp Fast Response</span>
                            <a href="https://wa.me/6281284186229" target="_blank" class="text-emerald-600 hover:underline font-bold text-sm">0812-8418-6229</a>
                        </div>
                    </div>

                    <div class="flex items-start gap-4">
                        <div class="w-10 h-10 bg-navy-900/5 text-gold rounded-lg flex items-center justify-center shrink-0 text-lg mt-1">
                            <i class="fa-solid fa-envelope"></i>
                        </div>
                        <div>
                            <span class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Email Resmi</span>
                            <a href="mailto:sutrisno.bmt@gmail.com" class="text-slate-700 hover:text-navy-900 text-sm font-medium">sutrisno.bmt@gmail.com</a>
                        </div>
                    </div>

                    <div class="flex items-start gap-4">
                        <div class="w-10 h-10 bg-navy-900/5 text-gold rounded-lg flex items-center justify-center shrink-0 text-lg mt-1">
                            <i class="fa-solid fa-clock"></i>
                        </div>
                        <div>
                            <span class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Jam Operasional</span>
                            <p class="text-slate-700 text-sm font-medium">Senin – Sabtu (08.00 - 17.00 WIB)</p>
                        </div>
                    </div>

                    <div class="pt-4">
                        <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20mengenai%20proyek%20konstruksi." 
                           target="_blank" 
                           class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-3.5 px-6 rounded-xl flex items-center justify-center gap-3 shadow-lg shadow-emerald-600/20 transition-all text-sm">
                            <i class="fa-brands fa-whatsapp text-xl"></i>
                            <span>Hubungi Langsung via WhatsApp</span>
                        </a>
                    </div>
                </div>

                <!-- Interactive Google Maps -->
                <div class="lg:col-span-7 bg-white p-2 rounded-2xl shadow-md border border-slate-200/80 h-full min-h-[400px]">
                    <iframe 
                        title="Lokasi Kantor PT Bangun Manunggal Trisno"
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.386047713809!2d106.69085887499026!3d-6.212711693775211!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f982937748db%3A0x88f2f254b0fa0e7!2sGreen%20Lake%20City!5e0!3m2!1sid!2sid!4v1700000000000!5m2!1sid!2sid" 
                        class="w-full h-full min-h-[420px] rounded-xl border-0" 
                        allowfullscreen="" 
                        loading="lazy" 
                        referrerpolicy="no-referrer-when-downgrade">
                    </iframe>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-navy-900 text-slate-400 py-12 border-t border-slate-800 text-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-6">
            <div class="flex items-center gap-3">
                <img src="logo.jpg" alt="Logo BMT" class="w-8 h-8 object-cover rounded bg-white">
                <span class="text-white font-heading font-bold tracking-wide">PT BANGUN MANUNGGAL TRISNO</span>
            </div>
            <p class="text-center sm:text-right text-xs text-slate-500">
                &copy; 2026 PT Bangun Manunggal Trisno. All rights reserved.
            </p>
        </div>
    </footer>

    <!-- Fixed Floating WhatsApp Button -->
    <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20mengenai%20proyek%20konstruksi." 
       target="_blank" 
       class="fixed bottom-6 right-6 bg-emerald-500 text-white w-14 h-14 rounded-full flex items-center justify-center shadow-2xl hover:bg-emerald-600 hover:scale-110 transition-all z-50 group">
        <i class="fa-brands fa-whatsapp text-3xl"></i>
        <span class="absolute right-16 bg-navy-900 text-white text-xs font-semibold px-3 py-1.5 rounded-lg shadow-lg opacity-0 group-hover:opacity-100 transition-opacity whitespace-nowrap pointer-events-none">
            Konsultasi WhatsApp
        </span>
    </a>

    <!-- Vanilla JavaScript for Mobile Menu Toggle -->
    <script>
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
