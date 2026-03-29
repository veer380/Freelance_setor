<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Freelancer Mails | Layanan Penyetoran Gmail Profesional</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        :root {
            --primary-blue: #2563eb;
            --secondary-blue: #1e40af;
        }

        body { 
            font-family: 'Inter', sans-serif; 
            scroll-behavior: smooth; 
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(229, 231, 235, 0.5);
        }

        .gradient-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
        }

        .price-tag {
            background: #dcfce7;
            color: #166534;
            padding: 4px 12px;
            border-radius: 999px;
            font-weight: 700;
            font-size: 0.875rem;
            display: inline-block;
        }

        .rules-list li {
            position: relative;
            padding-left: 1.5rem;
            margin-bottom: 0.5rem;
        }

        .rules-list li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: var(--primary-blue);
            font-weight: bold;
        }

        .info-card {
            border-left: 4px solid var(--primary-blue);
            transition: transform 0.2s;
        }

        .info-card:hover {
            transform: translateY(-5px);
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 10px;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <nav class="sticky top-0 z-50 bg-white shadow-sm border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex items-center gap-2">
                    <div class="bg-blue-600 p-2 rounded-lg">
                        <i class="fas fa-user-tie text-white text-xl"></i>
                    </div>
                    <span class="font-bold text-xl tracking-tight text-gray-900">Freelancer <span class="text-blue-600">Mails</span></span>
                </div>
                <div class="hidden md:flex space-x-8 font-medium text-sm">
                    <a href="#kategori" class="hover:text-blue-600 transition">Kategori</a>
                    <a href="#info" class="hover:text-blue-600 transition">Info Operasional</a>
                    <a href="#setor" class="hover:text-blue-600 transition text-blue-600 font-bold">Mulai Setor</a>
                </div>
                <button onclick="window.location.href='#setor'" class="bg-blue-600 text-white px-5 py-2 rounded-full font-semibold hover:bg-blue-700 transition shadow-md text-sm">
                    Admin CS
                </button>
            </div>
        </div>
    </nav>

    <header class="gradient-bg py-16 text-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 text-center relative z-10">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 leading-tight">Pusat Penyetoran Gmail</h1>
            <p class="text-lg md:text-xl opacity-90 mb-10 max-w-2xl mx-auto">
                Kirim data setoran Anda langsung ke sistem Telegram Admin Freelancer Mails. Cepat, Aman, dan Terbayar Tepat Waktu.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4 text-center">
                <a href="#setor" class="bg-white text-blue-700 px-8 py-3 rounded-full font-bold hover:bg-gray-100 transition shadow-lg">Mulai Setor Sekarang</a>
            </div>
        </div>
    </header>

    <section id="info" class="py-12 bg-white border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="info-card p-6 bg-blue-50 rounded-r-2xl shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <i class="fas fa-search-dollar text-blue-600 text-2xl"></i>
                        <h3 class="font-bold text-gray-900 text-lg">Sistem Sortir</h3>
                    </div>
                    <p class="text-sm text-gray-600 leading-relaxed">
                        Proses melalui tahap <b>Cek - Lolos</b> secara teliti. Akun yang valid akan segera dipindahkan ke sistem pembayaran.
                    </p>
                </div>
                <div class="info-card p-6 bg-green-50 rounded-r-2xl border-l-green-600 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <i class="fas fa-wallet text-green-600 text-2xl"></i>
                        <h3 class="font-bold text-gray-900 text-lg">Estimasi Payment</h3>
                    </div>
                    <p class="text-sm text-gray-600 leading-relaxed">
                        <b>Proses Payment 2x24 Jam</b> kerja setelah akun dinyatakan lolos sortir. Transaksi amanah 100%.
                    </p>
                </div>
                <div class="info-card p-6 bg-purple-50 rounded-r-2xl border-l-purple-600 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <i class="fas fa-headset text-purple-600 text-2xl"></i>
                        <h3 class="font-bold text-gray-900 text-lg">Dukungan Admin</h3>
                    </div>
                    <p class="text-sm text-gray-600 leading-relaxed">
                        Kami menjamin <b>Respon Cepat</b> dari tim kami untuk memastikan setiap kendala penyetoran teratasi.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="kategori" class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mt-2">Kriteria & Harga Terbaru</h2>
                <div class="h-1 w-20 bg-blue-600 mx-auto mt-4 rounded-full"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="p-6 rounded-3xl border-2 bg-white shadow-md border-pink-500 hover:shadow-lg transition">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="font-bold text-lg text-pink-700">Kategori: AYA</h3>
                        <span class="price-tag">Rp 3.000</span>
                    </div>
                    <ul class="text-xs text-gray-700 rules-list space-y-2">
                        <li>Wajib ada kata <b>"aya"</b> dalam email.</li>
                        <li>Password wajib: <b>aass1122</b>.</li>
                        <li>Tahun lahir wajib: <b>2000</b>.</li>
                        <li>No Verifikasi & No Tap.</li>
                    </ul>
                </div>

                <div class="p-6 rounded-3xl border-2 bg-white shadow-md border-green-500 hover:shadow-lg transition">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="font-bold text-lg text-green-700">Kategori: Bebas</h3>
                        <span class="price-tag">Rp 1.000</span>
                    </div>
                    <ul class="text-xs text-gray-700 rules-list space-y-2">
                        <li><b>No Verifikasi</b> (Clean).</li>
                        <li>Format dan pola <b>tidak boleh serupa</b>.</li>
                        <li>Tahun lahir <b>2000</b>.</li>
                        <li>Kualitas akun terjaga baik.</li>
                    </ul>
                </div>

                <div class="p-6 rounded-3xl border-2 bg-white shadow-md border-blue-400 hover:shadow-lg transition">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="font-bold text-lg text-blue-700">Kategori: YASE</h3>
                        <span class="price-tag">Rp 3.200</span>
                    </div>
                    <ul class="text-xs text-gray-700 rules-list space-y-2">
                        <li><b>Wajib tambah kata "yase"</b> di akhir email.</li>
                        <li>Password: <b>aass1122</b>.</li>
                        <li>Lahir: <b>1990 - 2000</b>.</li>
                        <li><b>No Verifikasi</b>.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="setor" class="py-16 bg-white">
        <div class="max-w-4xl mx-auto px-4">
            <div class="glass-card p-8 md:p-12 rounded-[2rem] shadow-2xl border border-gray-100">
                <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-10 gap-6">
                    <h2 class="text-2xl font-extrabold flex items-center gap-3">
                        <i class="fab fa-telegram-plane text-blue-600 text-3xl"></i> Formulir Penyetoran
                    </h2>
                    <div class="flex items-center gap-3 bg-amber-50 text-amber-700 px-4 py-2 rounded-2xl border border-amber-200">
                        <span class="text-xs font-bold uppercase">Estimasi 2x24 Jam</span>
                    </div>
                </div>

                <form id="depositForm" class="space-y-6">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="space-y-2">
                            <label class="block text-xs font-bold uppercase tracking-wider text-gray-500 text-left">Nama Penyetor</label>
                            <input type="text" id="namaPenyetor" required class="w-full p-4 rounded-xl border border-gray-200 outline-none text-sm bg-gray-50">
                        </div>
                        <div class="space-y-2">
                            <label class="block text-xs font-bold uppercase tracking-wider text-gray-500 text-left">No WhatsApp</label>
                            <input type="number" id="noWhatsapp" required placeholder="08..." class="w-full p-4 rounded-xl border border-gray-200 outline-none text-sm bg-gray-50">
                        </div>
                    </div>

                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="space-y-2">
                            <label class="block text-xs font-bold uppercase tracking-wider text-gray-500 text-left">Kategori</label>
                            <select id="kategoriSelect" required class="w-full p-4 rounded-xl border border-gray-200 outline-none text-sm bg-gray-50">
                                <option value="">Pilih Kategori</option>
                                <option value="AYA (Rp 3.000)">AYA - Rp 3.000</option>
                                <option value="BEBAS (Rp 1.000)">Bebas - Rp 1.000</option>
                                <option value="YASE (Rp 3.200)">YASE - Rp 3.200</option>
                                <option value="AWALAN ADMIN (Rp 3.300)">Awalan Admin - Rp 3.300</option>
                                </select>
                        </div>
                        <div class="space-y-2">
                            <label class="block text-xs font-bold uppercase tracking-wider text-gray-500 text-left" id="accountLabel">Nomor DANA</label>
                            <input type="text" id="nomorRekening" required class="w-full p-4 rounded-xl border border-gray-200 outline-none text-sm bg-gray-50">
                        </div>
                    </div>

                    <div class="space-y-2 text-left">
                        <label class="block text-xs font-bold uppercase tracking-wider text-gray-500">List Akun (Email | Pass)</label>
                        <textarea id="dataAkun" rows="6" required placeholder="email@gmail.com | pass123" class="w-full p-4 rounded-xl border border-gray-200 outline-none font-mono text-xs bg-gray-50"></textarea>
                    </div>

                    <button type="button" onclick="sendToTelegram()" class="w-full bg-blue-600 text-white py-5 rounded-2xl font-extrabold hover:bg-blue-700 transition shadow-xl flex items-center justify-center gap-3">
                        <i class="fab fa-telegram-plane"></i> Kirim Setoran
                    </button>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-gray-900 text-white py-12 text-center">
        <span class="font-bold text-2xl">Freelancer <span class="text-blue-600">Mails</span></span>
        <p class="text-gray-500 mt-4 text-xs">© 2024 Freelancer Mails | Amanah & Profesional</p>
    </footer>

    <div id="loadingModal" class="fixed inset-0 bg-black/60 hidden flex items-center justify-center z-[100]">
        <div class="bg-white p-8 rounded-3xl text-center shadow-2xl">
            <div class="animate-spin rounded-full h-10 w-10 border-b-2 border-blue-600 mx-auto mb-4"></div>
            <p class="font-bold">Mengirim Data...</p>
        </div>
    </div>

    <div id="successModal" class="fixed inset-0 bg-black/60 hidden flex items-center justify-center z-[100]">
        <div class="bg-white p-10 rounded-[2rem] max-w-sm w-full text-center shadow-2xl">
            <i class="fas fa-check-circle text-green-500 text-5xl mb-4"></i>
            <h3 class="font-bold text-xl mb-6">Setoran Berhasil Dikirim!</h3>
            <button onclick="location.reload()" class="w-full bg-blue-600 text-white py-4 rounded-xl font-bold">Oke</button>
        </div>
    </div>

    <script>
        const BOT_TOKEN = "8516355515:AAG9VHpoDBKeBePVUYDq3Y7gvQFXUDPghzs";
        const CHAT_ID = "1358848961"; 

        async function sendToTelegram() {
            const form = {
                nama: document.getElementById('namaPenyetor').value,
                wa: document.getElementById('noWhatsapp').value,
                kategori: document.getElementById('kategoriSelect').value,
                nomor: document.getElementById('nomorRekening').value,
                akun: document.getElementById('dataAkun').value
            };

            if (!form.nama  !form.wa  !form.kategori  !form.nomor  !form.akun) {
                alert("Mohon lengkapi semua data!");
                return;
            }

            document.getElementById('loadingModal').classList.remove('hidden');

            const message = 🚀 *SETORAN BARU (Freelancer Mails)*\n +
                            ━━━━━━━━━━━━━━━━━━━━\n +
                            👤 *Nama:* ${form.nama}\n +
                            📱 *WhatsApp:* ${form.wa}\n +
                            📂 *Kategori:* ${form.kategori}\n +
                            💳 *No. DANA/Rek:* \${form.nomor}\\n\n +
                            📄 *Data Akun:*\n\\\\n${form.akun}\n\\\\n +
                            ━━━━━━━━━━━━━━━━━━━━\n +
                            ⏰ ${new Date().toLocaleString('id-ID')};
                            try {
                const response = await fetch(https://api.telegram.org/bot${BOT_TOKEN}/sendMessage, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify({
                        chat_id: CHAT_ID,
                        text: message,
                        parse_mode: 'Markdown'
                    })
                });

                if (response.ok) {
                    document.getElementById('loadingModal').classList.add('hidden');
                    document.getElementById('successModal').classList.remove('hidden');
                } else {
                    throw new Error();
                }
            } catch (error) {
                document.getElementById('loadingModal').classList.add('hidden');
                alert("Gagal mengirim. Periksa koneksi atau bot token Anda.");
            }
        }
    </script>
</body>
</html>
