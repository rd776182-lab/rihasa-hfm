<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RIHASA → HFM Market — Bergabung Bersama Saya</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#0F172A',
                        secondary: '#1E293B',
                        rihasaGold: '#F5C518',
                        rihasaGreen: '#10B981',
                        hfmBlue: '#0091DA',
                        whatsapp: '#25D366',
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow { text-shadow: 0 2px 4px rgba(0,0,0,0.3); }
            .card-glow { box-shadow: 0 8px 30px rgba(245, 197, 24, 0.15); }
            .logo-glow { filter: drop-shadow(0 0 12px rgba(245, 197, 24, 0.4)); }
        }
    </style>
</head>
<body class="bg-primary text-white font-sans min-h-screen">
    <!-- NAVBAR -->
    <nav class="bg-secondary/80 backdrop-blur-md fixed w-full z-50 border-b border-gray-700">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <!-- Logo RIHASA -->
                <span class="text-xl font-bold text-rihasaGold">RIHASA</span>
                <span class="text-gray-400 hidden sm:inline">→</span>
                <span class="font-semibold text-hfmBlue">HFM MARKET</span>
            </div>
            <div class="hidden md:flex gap-5 text-sm">
                <a href="#beranda" class="hover:text-rihasaGold transition">Beranda</a>
                <a href="#tentang" class="hover:text-rihasaGold transition">Tentang HFM</a>
                <a href="#gabung" class="hover:text-rihasaGold transition">Bergabung</a>
                <a href="#referral" class="hover:text-rihasaGold transition">Kode Referral</a>
                <a href="#kontak" class="hover:text-rihasaGold transition">Kontak</a>
            </div>
            <button class="md:hidden text-xl">
                <i class="fa fa-bars"></i>
            </button>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section id="beranda" class="pt-28 pb-16 px-4">
        <div class="container mx-auto text-center">
            <!-- Logo RIHASA + HFM Bersebelahan -->
            <div class="flex justify-center items-center gap-6 mb-8">
                <div class="text-center">
                    <div class="w-20 h-20 bg-rihasaGold/20 rounded-xl flex items-center justify-center mx-auto mb-2 logo-glow">
                        <span class="text-rihasaGold font-bold text-2xl">R</span>
                    </div>
                    <p class="font-bold text-rihasaGold">RIHASA</p>
                    <p class="text-xs text-gray-400">Perantara Saya</p>
                </div>
                <span class="text-2xl text-gray-500">+</span>
                <div class="text-center">
                    <div class="w-20 h-20 bg-hfmBlue/20 rounded-xl flex items-center justify-center mx-auto mb-2">
                        <span class="text-hfmBlue font-bold text-2xl">HFM</span>
                    </div>
                    <p class="font-bold text-hfmBlue">HFM MARKET</p>
                    <p class="text-xs text-gray-400">Broker Resmi</p>
                </div>
            </div>

            <h1 class="text-[clamp(1.8rem,5vw,3rem)] font-bold mb-4 leading-tight">
                Bergabung Bersama Saya di <br>
                <span class="text-hfmBlue">HFM Market</span>
            </h1>
            <p class="text-lg text-gray-300 max-w-xl mx-auto mb-6">
                Melalui <strong class="text-rihasaGold">RIHASA</strong> — akses pasar Forex, Emas, Indeks, Saham, Kripto & Minyak dengan kode referal saya:
            </p>

            <!-- KODE REFERRAL TAMPIL BESAR -->
            <div id="referral" class="bg-secondary/60 border-2 border-rihasaGold/50 rounded-xl p-5 max-w-sm mx-auto mb-8 card-glow">
                <p class="text-gray-400 text-sm mb-2">Kode Referral Saya</p>
                <p class="text-3xl font-bold text-rihasaGold tracking-wider">370238</p>
                <p class="text-xs text-gray-400 mt-2">Gunakan kode ini saat mendaftar</p>
            </div>

            <div class="flex flex-col sm:flex-row gap-4 justify-center mb-6">
                <a href="https://www.hfm.com/?ref=370238" target="_blank" 
                   class="inline-flex items-center justify-center gap-2 bg-hfmBlue hover:bg-blue-600 px-6 py-3 rounded-lg font-bold transition card-glow">
                    <i class="fa fa-user-plus"></i> Daftar dengan Kode 370238
                </a>
                <a href="https://wa.me/6285805108034?text=Saya%20mau%20bergabung%20HFM%20pakai%20kode%20referral%20370238%20melalui%20RIHASA" target="_blank" 
                   class="inline-flex items-center justify-center gap-2 bg-whatsapp hover:bg-green-600 px-6 py-3 rounded-lg font-bold transition">
                    <i class="fa fa-whatsapp"></i> Panduan via WhatsApp
                </a>
            </div>

            <p class="text-sm text-gray-400">
                <i class="fa fa-shield text-rihasaGold mr-1"></i> Teregulasi • 3,5 Juta+ Trader • Mitra Arsenal
            </p>
        </div>
    </section>

    <!-- TENTANG HFM -->
    <section id="tentang" class="py-16 px-4 bg-secondary/30">
        <div class="container mx-auto">
            <div class="text-center mb-10">
                <h2 class="text-2xl md:text-3xl font-bold mb-3">Tentang <span class="text-hfmBlue">HFM Market</span></h2>
                <p class="text-gray-400 max-w-xl mx-auto">Platform perdagangan global yang saya rekomendasikan</p>
            </div>

            <div class="grid md:grid-cols-3 gap-6">
                <div class="bg-secondary/50 p-5 rounded-xl border border-gray-700 hover:border-rihasaGold/40 transition">
                    <h4 class="font-bold text-rihasaGold mb-2">📊 Pasar Lengkap</h4>
                    <p class="text-gray-300 text-sm">Forex, Emas, Indeks, Saham, Kripto, Minyak — semua dalam satu akun.</p>
                </div>
                <div class="bg-secondary/50 p-5 rounded-xl border border-gray-700 hover:border-rihasaGold/40 transition">
                    <h4 class="font-bold text-rihasaGold mb-2">⚡ Cepat & Aman</h4>
                    <p class="text-gray-300 text-sm">Eksekusi instan, dana terpisah, deposit & tarik mudah.</p>
                </div>
                <div class="bg-secondary/50 p-5 rounded-xl border border-gray-700 hover:border-rihasaGold/40 transition">
                    <h4 class="font-bold text-rihasaGold mb-2">🎓 Bisa Latihan Dulu</h4>
                    <p class="text-gray-300 text-sm">Akun Demo — belajar tanpa risiko uang asli sebelum masuk pasar nyata.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CARA BERGABUNG -->
    <section id="gabung" class="py-16 px-4">
        <div class="container mx-auto">
            <div class="text-center mb-10">
                <h2 class="text-2xl md:text-3xl font-bold mb-3">Cara Bergabung Lewat <span class="text-rihasaGold">RIHASA</span></h2>
                <p class="text-gray-400">Gunakan kode referal saya: <strong class="text-rihasaGold">370238</strong></p>
            </div>

            <div class="grid md:grid-cols-4 gap-6 max-w-4xl mx-auto">
                <div class="text-center">
                    <div class="w-14 h-14 bg-rihasaGold/20 rounded-full flex items-center justify-center text-rihasaGold text-xl font-bold mx-auto mb-3">1</div>
                    <h5 class="font-bold mb-1">Klik Link Daftar</h5>
                    <p class="text-gray-400 text-sm">Buka: hfm.com/?ref=370238</p>
                </div>
                <div class="text-center">
                    <div class="w-14 h-14 bg-rihasaGold/20 rounded-full flex items-center justify-center text-rihasaGold text-xl font-bold mx-auto mb-3">2</div>
                    <h5 class="font-bold mb-1">Isi Data Diri</h5>
                    <p class="text-gray-400 text-sm">Nama, HP, email — pastikan benar</p>
                </div>
                <div class="text-center">
                    <div class="w-14 h-14 bg-rihasaGold/20 rounded-full flex items-center justify-center text-rihasaGold text-xl font-bold mx-auto mb-3">3</div>
                    <h5 class="font-bold mb-1">Kode Referral Otomatis</h5>
                    <p class="text-gray-400 text-sm">370238 sudah terpasang dari link saya</p>
                </div>
                <div class="text-center">
                    <div class="w-14 h-14 bg-rihasaGold/20 rounded-full flex items-center justify-center text-rihasaGold text-xl font-bold mx-auto mb-3">4</div>
                    <h5 class="font-bold mb-1">Mulai Trading</h5>
                    <p class="text-gray-400 text-sm">Verifikasi → deposit → buka posisi</p>
                </div>
            </div>

            <div class="text-center mt-10">
                <a href="https://www.hfm.com/?ref=370238" target="_blank" 
                   class="inline-block bg-rihasaGold hover:bg-yellow-500 text-black font-bold px-8 py-3 rounded-lg transition text-lg card-glow">
                    <i class="fa fa-external-link mr-2"></i> Buka HFM dengan Kode 370238
                </a>
            </div>
        </div>
    </section>

    <!-- KONTAK & BANTUAN -->
    <section id="kontak" class="py-16 px-4 bg-secondary/30">
        <div class="container mx-auto max-w-xl text-center">
            <h2 class="text-2xl font-bold mb-4">Butuh Bantuan?</h2>
            <p class="text-gray-400 mb-8">Panduan pendaftaran sampai siap trading — gratis dari saya</p>

            <div class="space-y-4">
                <a href="https://wa.me/6285805108034?text=Halo!%20Saya%20mau%20daftar%20HFM%20pakai%20kode%20referral%20370238%20melalui%20RIHASA" target="_blank" 
                   class="flex items-center justify-center gap-3 bg-whatsapp/20 hover:bg-whatsapp/30 text-whatsapp py-3 px-6 rounded-lg transition font-bold text-lg">
                    <i class="fa fa-whatsapp text-2xl"></i> WhatsApp: +62 858-0510-8034
                </a>
                
                <a href="mailto:rd776182@gmail.com" 
                   class="flex items-center justify-center gap-3 bg-red-600/20 hover:bg-red-600/30 text-red-400 py-3 px-6 rounded-lg transition">
                    <i class="fa fa-envelope text-xl"></i> rd776182@gmail.com
                </a>

                <a href="https://play.google.com/store/apps/details?id=com.hotforex.www.hotforex" target="_blank" 
                   class="flex items-center justify-center gap-3 bg-hfmBlue/20 hover:bg-hfmBlue/30 text-hfmBlue py-3 px-6 rounded-lg transition">
                    <i class="fa fa-android text-xl"></i> Unduh Aplikasi HFM di HP
                </a>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-secondary py-8 px-4 border-t border-gray-800">
        <div class="container mx-auto text-center">
            <p class="text-rihasaGold font-bold text-lg mb-1">RIHASA — Bergabung Bersama Saya di HFM Market</p>
            <p class="text-gray-400 text-sm mb-2">Kode Referral Saya: <strong class="text-rihasaGold">370238</strong></p>
            <p class="text-gray-500 text-xs mb-3">FROM IDEAS TO OPPORTUNITY</p>
            
            <p class="text-yellow-400/80 text-xs max-w-lg mx-auto">
                ⚠️ Peringatan Risiko: Trading berisiko tinggi terhadap modal. Pastikan Anda memahami risiko sebelum bertransaksi. Bukan jaminan keuntungan.
            </p>
        </div>
    </footer>
</body>
</html
