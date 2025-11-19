<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UBAYA Lost & Found - Premium System</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <style>
        body { font-family: 'Poppins', sans-serif; background-color: #f3f4f6; }
        
        /* Warna Ubaya */
        .bg-ubaya { background-color: #C8102E; }
        .text-ubaya { color: #C8102E; }
        .border-ubaya { border-color: #C8102E; }
        
        /* --- STYLE PREMIUM (BARU) --- */
        .bg-gold-light { background-color: #fffbeb; } /* Kuning sangat muda */
        .border-gold { border-color: #fbbf24; } /* Kuning Emas */
        .text-gold { color: #b45309; }
        .shadow-gold { box-shadow: 0 4px 20px rgba(251, 191, 36, 0.25); }
        
        /* Animasi berkedip halus untuk premium */
        @keyframes pulse-gold {
            0%, 100% { border-color: #fbbf24; }
            50% { border-color: #f59e0b; }
        }
        .premium-active { animation: pulse-gold 3s infinite; }

        /* Glass Effect Navbar */
        .glass-nav { background: rgba(255, 255, 255, 0.95); backdrop-filter: blur(10px); border-bottom: 1px solid rgba(0,0,0,0.05); }
        
        /* Hide Scrollbar */
        .no-scrollbar::-webkit-scrollbar { display: none; }
        .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        
        /* Kategori Button Active */
        .cat-btn.active { background-color: #C8102E; color: white; border-color: #C8102E; }
        
        /* File Upload Style */
        .file-drop-area { border: 2px dashed #cbd5e1; transition: all 0.3s; }
        .file-drop-area:hover { border-color: #C8102E; background-color: #fff5f5; }

        /* Checkbox Custom */
        .checkbox-premium:checked {
            accent-color: #d97706;
        }
    </style>
</head>
<body>

    <nav class="glass-nav fixed w-full z-40 top-0 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex-shrink-0 flex items-center cursor-pointer" onclick="window.location.reload()">
                    <div class="w-10 h-10 bg-ubaya rounded-lg flex items-center justify-center text-white text-xl mr-3 shadow-lg">
                        <i class="fa-solid fa-magnifying-glass-location"></i>
                    </div>
                    <div>
                        <h1 class="text-2xl font-bold text-gray-800 tracking-tight">UBAYA <span class="text-ubaya">L&F</span></h1>
                        <p class="text-xs text-gray-500 -mt-1">Lost & Found Center</p>
                    </div>
                </div>

                <div class="hidden md:flex space-x-4 items-center">
                    <a href="#" class="text-gray-700 hover:text-ubaya font-medium transition">Beranda</a>
                    <a href="#pencarian" class="text-gray-700 hover:text-ubaya font-medium transition">Cari Barang</a>
                    <button onclick="openModal()" class="bg-ubaya text-white px-5 py-2.5 rounded-full font-medium hover:bg-red-700 transition shadow-md hover:shadow-lg flex items-center gap-2 transform active:scale-95">
                        <i class="fa-solid fa-plus"></i> Lapor Barang
                    </button>
                    
                    <button onclick="toggleAdmin()" id="adminBtn" class="ml-2 w-10 h-10 rounded-full border border-gray-200 flex items-center justify-center text-gray-400 hover:text-ubaya hover:border-ubaya transition" title="Login Admin (Pemilik Database)">
                        <i class="fa-solid fa-lock"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <div class="pt-28 pb-8 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="bg-gradient-to-r from-gray-900 to-gray-800 rounded-3xl shadow-xl overflow-hidden relative p-8 md:p-10 text-center md:text-left flex flex-col md:flex-row items-center justify-between text-white">
            <div class="z-10">
                <h2 class="text-3xl md:text-4xl font-bold mb-2">Barang Hilang? Temukan Lebih Cepat!</h2>
                <p class="text-gray-300 mb-0">Gunakan fitur <span class="text-yellow-400 font-bold"><i class="fa-solid fa-crown"></i> Premium Highlight</span> agar laporanmu dilihat semua orang.</p>
            </div>
            <div class="mt-6 md:mt-0 z-10 bg-white/10 backdrop-blur-sm border border-white/20 p-4 rounded-xl flex items-center gap-4">
                <div class="bg-yellow-500 w-12 h-12 rounded-full flex items-center justify-center text-white text-2xl shadow-lg">
                    <i class="fa-solid fa-bell"></i>
                </div>
                <div class="text-left">
                    <p class="text-xs text-gray-300 uppercase tracking-wide">Fitur Berlangganan</p>
                    <p class="font-bold text-sm">Notifikasi & Prioritas Utama</p>
                    <p class="text-xs text-yellow-400 font-semibold">Rp 20.000 / post</p>
                </div>
            </div>
            <div class="absolute top-0 right-0 -mt-10 -mr-10 w-64 h-64 bg-ubaya opacity-20 rounded-full blur-3xl"></div>
        </div>
    </div>

    <section id="pencarian" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mb-8">
        
        <div class="flex flex-col md:flex-row justify-between items-center gap-4 mb-6">
            <div class="relative w-full md:w-1/2">
                <input type="text" id="searchInput" onkeyup="filterItems()" placeholder="Cari nama barang, lokasi, atau ciri-ciri..." class="w-full pl-12 pr-4 py-3 rounded-xl border border-gray-200 focus:outline-none focus:border-red-500 focus:ring-1 focus:ring-red-500 transition shadow-sm">
                <i class="fa-solid fa-search absolute left-4 top-4 text-gray-400"></i>
            </div>
            
            <div class="flex gap-3 w-full md:w-auto">
                <select id="statusFilter" onchange="filterItems()" class="w-full md:w-48 py-3 px-4 rounded-xl border border-gray-200 text-gray-600 focus:outline-none focus:border-red-500 cursor-pointer shadow-sm bg-white">
                    <option value="all">Semua Status</option>
                    <option value="Hilang">Barang Hilang</option>
                    <option value="Ditemukan">Barang Ditemukan</option>
                </select>
            </div>
        </div>

        <div class="mb-8">
            <div class="flex gap-3 overflow-x-auto no-scrollbar pb-2" id="categoryContainer">
                <button onclick="setCategory('all', this)" class="cat-btn active whitespace-nowrap px-5 py-2 rounded-full border border-gray-200 text-sm font-medium bg-white text-gray-600 hover:border-red-200 transition">Semua</button>
                <button onclick="setCategory('elektronik', this)" class="cat-btn whitespace-nowrap px-5 py-2 rounded-full border border-gray-200 text-sm font-medium bg-white text-gray-600 hover:border-red-200 transition">Elektronik</button>
                <button onclick="setCategory('botol', this)" class="cat-btn whitespace-nowrap px-5 py-2 rounded-full border border-gray-200 text-sm font-medium bg-white text-gray-600 hover:border-red-200 transition">Botol/Tumbler</button>
                <button onclick="setCategory('payung', this)" class="cat-btn whitespace-nowrap px-5 py-2 rounded-full border border-gray-200 text-sm font-medium bg-white text-gray-600 hover:border-red-200 transition">Payung</button>
                <button onclick="setCategory('kacamata', this)" class="cat-btn whitespace-nowrap px-5 py-2 rounded-full border border-gray-200 text-sm font-medium bg-white text-gray-600 hover:border-red-200 transition">Kacamata</button>
                <button onclick="setCategory('aksesoris', this)" class="cat-btn whitespace-nowrap px-5 py-2 rounded-full border border-gray-200 text-sm font-medium bg-white text-gray-600 hover:border-red-200 transition">Dompet & Kunci</button>
            </div>
        </div>
    </section>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pb-20">
        <div id="adminBanner" class="hidden mb-6 bg-red-50 border border-red-200 rounded-lg p-4 flex items-center justify-between">
            <div class="flex items-center">
                <i class="fa-solid fa-shield-halved text-ubaya text-xl mr-3"></i>
                <div>
                    <h4 class="font-bold text-gray-800">Mode Administrator Aktif</h4>
                    <p class="text-sm text-gray-600">Anda memiliki akses penuh untuk menghapus data.</p>
                </div>
            </div>
            <button onclick="toggleAdmin()" class="text-sm text-gray-500 hover:text-ubaya underline">Keluar</button>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6" id="item-container">
            </div>
        
        <div id="emptyState" class="hidden text-center py-20">
            <div class="bg-gray-100 w-24 h-24 rounded-full flex items-center justify-center mx-auto mb-4">
                <i class="fa-solid fa-box-open text-4xl text-gray-400"></i>
            </div>
            <h3 class="text-lg font-bold text-gray-700">Tidak ditemukan</h3>
            <p class="text-gray-500">Coba ganti kata kunci atau kategori lain.</p>
        </div>
    </main>

    <div id="reportModal" class="fixed inset-0 z-[60] hidden" aria-labelledby="modal-title" role="dialog" aria-modal="true">
        <div id="modal-overlay" class="fixed inset-0 bg-gray-900 bg-opacity-50 backdrop-blur-sm transition-opacity opacity-0"></div>

        <div class="fixed inset-0 z-10 overflow-y-auto">
            <div class="flex min-h-full items-center justify-center p-4 text-center sm:p-0">
                <div id="modal-content" class="relative transform overflow-hidden rounded-2xl bg-white text-left shadow-2xl transition-all sm:my-8 sm:w-full sm:max-w-2xl scale-95 opacity-0">
                    
                    <div class="bg-gray-50 px-6 py-4 border-b border-gray-100 flex justify-between items-center">
                        <h3 class="text-lg font-bold text-gray-900">
                            <i class="fa-solid fa-file-pen text-ubaya mr-2"></i> Form Lapor Barang
                        </h3>
                        <button onclick="closeModal()" class="text-gray-400 hover:text-gray-600 w-8 h-8 flex items-center justify-center rounded-full hover:bg-gray-200 transition">
                            <i class="fa-solid fa-xmark text-xl"></i>
                        </button>
                    </div>

                    <div class="px-6 py-6 max-h-[75vh] overflow-y-auto custom-scrollbar">
                        <form id="laporForm" onsubmit="submitForm(event)">
                            
                            <div class="mb-6">
                                <div class="file-drop-area rounded-xl p-6 text-center cursor-pointer relative bg-gray-50" onclick="document.getElementById('fileInput').click()">
                                    <input type="file" id="fileInput" class="hidden" accept="image/*" onchange="previewImage(this)">
                                    <div id="uploadPlaceholder">
                                        <i class="fa-solid fa-cloud-arrow-up text-3xl text-gray-400 mb-2"></i>
                                        <p class="text-sm text-gray-600 font-medium">Klik untuk upload foto (Wajib)</p>
                                    </div>
                                    <div id="previewContainer" class="hidden relative group">
                                        <img id="imgPreview" src="" class="mx-auto h-48 object-contain rounded-lg shadow-sm bg-white border">
                                        <div class="absolute inset-0 bg-black bg-opacity-40 hidden group-hover:flex items-center justify-center rounded-lg transition">
                                            <p class="text-white text-sm font-medium"><i class="fa-solid fa-pen"></i> Ganti Foto</p>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                                <div class="space-y-4">
                                    <h4 class="text-xs font-bold text-gray-400 uppercase tracking-wider border-b pb-1">Data Pelapor</h4>
                                    <input type="text" id="inputPelapor" required class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-red-200 outline-none text-sm" placeholder="Nama Lengkap">
                                    <input type="text" id="inputNrp" required class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-red-200 outline-none text-sm" placeholder="NRP / NPK">
                                    <input type="tel" id="inputWa" required class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-red-200 outline-none text-sm" placeholder="No. WhatsApp">
                                </div>

                                <div class="space-y-4">
                                    <h4 class="text-xs font-bold text-gray-400 uppercase tracking-wider border-b pb-1">Info Barang</h4>
                                    <select id="pilihStatus" class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-red-200 outline-none bg-white text-sm">
                                        <option value="hilang">Saya Kehilangan Barang</option>
                                        <option value="ditemukan">Saya Menemukan Barang</option>
                                    </select>
                                    <input type="text" id="inputNamaBarang" required class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-red-200 outline-none text-sm" placeholder="Nama Barang (Cth: Dompet)">
                                    <select id="pilihKategori" class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-red-200 outline-none bg-white text-sm">
                                        <option value="elektronik">Elektronik</option>
                                        <option value="botol">Botol/Tumbler</option>
                                        <option value="payung">Payung</option>
                                        <option value="kacamata">Kacamata</option>
                                        <option value="aksesoris">Dompet/Kunci</option>
                                        <option value="lainnya">Lainnya</option>
                                    </select>
                                </div>
                            </div>

                            <div class="mb-6">
                                <textarea id="inputDeskripsi" rows="2" class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-red-200 outline-none text-sm" placeholder="Deskripsi lokasi, warna, ciri-ciri khusus..."></textarea>
                            </div>

                            <div class="mb-6 bg-gradient-to-r from-yellow-50 to-orange-50 border border-yellow-200 rounded-xl p-4 flex items-start gap-3 relative overflow-hidden">
                                <div class="flex h-5 items-center z-10">
                                    <input id="checkPremium" type="checkbox" class="checkbox-premium h-5 w-5 rounded border-gray-300 text-yellow-600 focus:ring-yellow-500 cursor-pointer">
                                </div>
                                <div class="text-sm z-10">
                                    <label for="checkPremium" class="font-bold text-gray-900 cursor-pointer flex items-center gap-2">
                                        Aktifkan Fitur Berlangganan / Premium <span class="bg-yellow-400 text-xs px-2 py-0.5 rounded text-black shadow-sm">Rp 20.000</span>
                                    </label>
                                    <p class="text-gray-600 text-xs mt-1 leading-relaxed">
                                        <i class="fa-solid fa-crown text-yellow-600 mr-1"></i> Barang Tampil Paling Atas (Prioritas)<br>
                                        <i class="fa-solid fa-star text-yellow-600 mr-1"></i> Highlight Emas & Badge Mahkota<br>
                                        <i class="fa-solid fa-bell text-yellow-600 mr-1"></i> Notifikasi ke seluruh pengguna
                                    </p>
                                </div>
                                <i class="fa-solid fa-crown text-yellow-200 text-6xl absolute -bottom-2 -right-2 opacity-50 rotate-12"></i>
                            </div>

                            <div class="flex flex-row-reverse gap-3 pt-4 border-t border-gray-100">
                                <button type="submit" class="bg-ubaya text-white px-6 py-2.5 rounded-lg font-medium hover:bg-red-700 shadow-md transition flex items-center gap-2 text-sm">
                                    Kirim Laporan <i class="fa-solid fa-paper-plane"></i>
                                </button>
                                <button type="button" onclick="closeModal()" class="bg-white text-gray-700 px-6 py-2.5 rounded-lg font-medium border border-gray-300 hover:bg-gray-50 transition text-sm">
                                    Batal
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // --- 1. DATA PERSISTENCY (LOCAL STORAGE) ---
        // Data Default dengan contoh 1 Barang Premium
        const defaultItems = [
            { 
                id: 1,
                title: "AirPods Pro Case", 
                category: "elektronik",
                location: "Kantin Keluwih Meja 4", 
                date: "Baru Saja", 
                type: "Hilang", 
                isPremium: true, // Ini Data Premium
                img: "https://images.unsplash.com/photo-1606220588913-b3aacb4d2f46?auto=format&fit=crop&q=80&w=300&h=200", 
                desc: "Case warna putih polos, tertinggal saat makan siang." 
            },
            { 
                id: 2,
                title: "Tumbler Corkcicle", 
                category: "botol",
                location: "Perpustakaan Lt. 2", 
                date: "Hari ini", 
                type: "Hilang", 
                isPremium: false,
                img: "https://images.unsplash.com/photo-1602143407151-011141950038?auto=format&fit=crop&q=80&w=300&h=200", 
                desc: "Ada stiker himpunan mahasiswa." 
            },
            { 
                id: 3,
                title: "Payung Lipat", 
                category: "payung",
                location: "Gedung PF", 
                date: "17 Nov 2024", 
                type: "Ditemukan", 
                isPremium: false,
                img: "https://images.unsplash.com/photo-1508166785545-c2dd4c113c66?auto=format&fit=crop&q=80&w=300&h=200", 
                desc: "Ditemukan di dekat rak sepatu pintu masuk." 
            }
        ];

        // Cek Storage, kalau kosong pakai default
        let items = JSON.parse(localStorage.getItem('ubaya_items_premium')) || defaultItems;

        function saveToStorage() {
            localStorage.setItem('ubaya_items_premium', JSON.stringify(items));
        }

        // --- 2. LOGIKA ADMIN (KEAMANAN) ---
        let isAdmin = false;
        function toggleAdmin() {
            const btn = document.getElementById('adminBtn');
            const banner = document.getElementById('adminBanner');
            const icon = btn.querySelector('i');

            if (!isAdmin) {
                let password = prompt("Masukkan Password Admin:");
                if (password === "admin123") {
                    isAdmin = true;
                    icon.classList.remove('fa-lock');
                    icon.classList.add('fa-lock-open');
                    btn.classList.add('bg-ubaya', 'text-white', 'border-ubaya');
                    banner.classList.remove('hidden');
                    alert("Login Admin Berhasil!");
                } else if (password !== null) {
                    alert("Password Salah!");
                }
            } else {
                isAdmin = false;
                icon.classList.add('fa-lock');
                icon.classList.remove('fa-lock-open');
                btn.classList.remove('bg-ubaya', 'text-white', 'border-ubaya');
                banner.classList.add('hidden');
                alert("Logout Admin Berhasil.");
            }
            filterItems(); // Refresh tombol hapus
        }

        // --- 3. RENDER & LOGIKA TAMPILAN ---
        let currentCategory = 'all';

        function setCategory(cat, btnElement) {
            currentCategory = cat;
            document.querySelectorAll('.cat-btn').forEach(btn => {
                btn.classList.remove('active', 'bg-ubaya', 'text-white', 'border-ubaya');
                btn.classList.add('bg-white', 'text-gray-600', 'hover:border-red-200');
            });
            btnElement.classList.add('active', 'bg-ubaya', 'text-white', 'border-ubaya');
            filterItems();
        }

        function filterItems() {
            const searchText = document.getElementById('searchInput').value.toLowerCase();
            const statusValue = document.getElementById('statusFilter').value;
            const container = document.getElementById('item-container');
            const emptyState = document.getElementById('emptyState');
            
            container.innerHTML = ''; 
            let hasItems = false;

            // --- SORTING LOGIC: PREMIUM FIRST ---
            // Barang Premium ditaruh paling atas array sementara sebelum di-loop
            const sortedItems = [...items].sort((a, b) => {
                // Logic: true (1) > false (0), jadi b - a
                return (b.isPremium === true) - (a.isPremium === true);
            });

            sortedItems.forEach(item => {
                const matchSearch = item.title.toLowerCase().includes(searchText) || 
                                  item.location.toLowerCase().includes(searchText) || 
                                  item.desc.toLowerCase().includes(searchText);
                const matchCategory = currentCategory === 'all' || item.category === currentCategory;
                const matchStatus = statusValue === 'all' || item.type === statusValue;

                if (matchSearch && matchCategory && matchStatus) {
                    hasItems = true;
                    const badgeColor = item.type === 'Ditemukan' ? 'bg-green-100 text-green-700 border-green-200' : 'bg-red-100 text-red-700 border-red-200';
                    const icon = item.type === 'Ditemukan' ? 'fa-check-circle' : 'fa-circle-exclamation';
                    
                    // --- LOGIKA TAMPILAN PREMIUM ---
                    let cardClasses = "bg-white border-gray-100";
                    let crownBadge = "";
                    let premiumGlow = "";
                    
                    if(item.isPremium) {
                        // Style khusus barang berbayar
                        cardClasses = "bg-gold-light border-gold premium-active border-2 transform scale-[1.01]";
                        premiumGlow = "shadow-gold";
                        crownBadge = `
                            <div class="absolute top-3 left-3 px-3 py-1 rounded-full text-xs font-bold bg-gradient-to-r from-yellow-400 to-yellow-500 text-white shadow-md flex items-center gap-1 z-10 border border-white">
                                <i class="fa-solid fa-crown"></i> Premium
                            </div>
                        `;
                    }

                    // Tombol Delete Admin
                    let deleteButtonHtml = '';
                    if (isAdmin) {
                        deleteButtonHtml = `
                            <button onclick="deleteItem(${item.id})" class="text-gray-400 hover:text-red-600 transition p-1 ml-auto bg-white rounded border border-gray-200 shadow-sm px-2 text-xs" title="Hapus Data">
                                <i class="fa-solid fa-trash"></i> Hapus
                            </button>
                        `;
                    }

                    const html = `
                        <div class="${cardClasses} ${premiumGlow} rounded-2xl shadow-md hover:shadow-xl transition-all duration-300 overflow-hidden border group relative flex flex-col">
                            <div class="relative h-48 overflow-hidden flex-shrink-0">
                                ${crownBadge}
                                <img src="${item.img}" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                                <div class="absolute top-3 right-3 px-3 py-1 rounded-full text-xs font-bold border ${badgeColor} bg-white shadow-sm flex items-center gap-1">
                                    <i class="fa-solid ${icon}"></i> ${item.type}
                                </div>
                            </div>
                            <div class="p-5 flex flex-col flex-grow">
                                <div class="flex justify-between mb-2">
                                     <span class="text-[10px] uppercase font-bold text-gray-500 tracking-wider border border-gray-200 px-2 py-0.5 rounded bg-white">${item.category}</span>
                                     <span class="text-xs text-gray-400"><i class="fa-regular fa-calendar mr-1"></i>${item.date}</span>
                                </div>
                                <h4 class="text-lg font-bold text-gray-800 mb-1 line-clamp-1">${item.title}</h4>
                                <p class="text-sm text-gray-600 mb-4 line-clamp-2">${item.desc}</p>
                                
                                <div class="mt-auto pt-3 border-t border-gray-200/60 flex items-center">
                                    <div class="text-xs text-gray-500 flex items-center truncate mr-2">
                                        <i class="fa-solid fa-location-dot text-ubaya mr-1.5"></i> ${item.location}
                                    </div>
                                    ${deleteButtonHtml}
                                </div>
                            </div>
                        </div>
                    `;
                    container.innerHTML += html;
                }
            });

            if (!hasItems) {
                emptyState.classList.remove('hidden');
            } else {
                emptyState.classList.add('hidden');
            }
        }

        // Hapus Item (Hanya jika isAdmin = true)
        function deleteItem(id) {
            if(!isAdmin) return;
            if (confirm("PERINGATAN ADMIN: Apakah Anda yakin ingin menghapus data ini permanen?")) {
                items = items.filter(item => item.id !== id);
                saveToStorage(); // Update storage
                filterItems(); // Update tampilan
            }
        }

        // --- LOGIKA SUBMIT LAPORAN ---
        function submitForm(event) {
            event.preventDefault();
            const btn = event.submitter;
            const originalText = btn.innerHTML;
            
            // Ambil data form
            const isPremium = document.getElementById('checkPremium').checked;
            const waNumber = document.getElementById('inputWa').value;
            const namaBarang = document.getElementById('inputNamaBarang').value;

            // --- SIMULASI PEMBAYARAN ---
            if (isPremium) {
                // Pop up konfirmasi pembayaran
                const confirmPay = confirm(`
KONFIRMASI BERLANGGANAN PREMIUM
--------------------------------
Barang: ${namaBarang}
Biaya: Rp 20.000

Tekan OK untuk mensimulasikan pembayaran via QRIS/Transfer.
Tekan Cancel untuk membatalkan.
                `);
                
                if (!confirmPay) return; // Stop jika batal bayar
            }

            // Efek Loading
            btn.innerHTML = '<i class="fa-solid fa-circle-notch fa-spin"></i> Memproses...';
            btn.disabled = true;
            btn.classList.add('opacity-75');

            // Ambil sisa data
            const deskripsi = document.getElementById('inputDeskripsi').value;
            const kategoriVal = document.getElementById('pilihKategori').value;
            const statusVal = document.getElementById('pilihStatus').value;
            const uploadedImg = document.getElementById('imgPreview').src;
            const finalImg = (uploadedImg && uploadedImg !== window.location.href) ? uploadedImg : "https://via.placeholder.com/300x200?text=No+Image";
            const statusLabel = statusVal === 'hilang' ? 'Hilang' : 'Ditemukan';

            // Buat Objek Item
            const newItem = {
                id: Date.now(), 
                title: namaBarang,
                category: kategoriVal, 
                location: "Lihat Deskripsi",
                date: "Baru Saja",
                type: statusLabel,
                isPremium: isPremium, // Simpan status premium
                img: finalImg,
                desc: deskripsi
            };

            // Masukkan ke array & simpan
            items.unshift(newItem);
            saveToStorage();

            setTimeout(() => {
                // Reset filter agar item baru muncul
                document.getElementById('searchInput').value = ""; 
                document.getElementById('statusFilter').value = "all";
                setCategory('all', document.querySelector('#categoryContainer button:first-child'));
                
                // Pesan Sukses
                let msg = `Berhasil! Laporan "${namaBarang}" telah diterbitkan.`;
                if(isPremium) {
                    msg += `\n\n[PREMIUM AKTIF]\n- Highlight Emas Aktif\n- Posisi Paling Atas\n- Notifikasi terkirim ke user lain!`;
                }
                
                alert(msg);
                closeModal();
                
                // Reset Tombol
                btn.innerHTML = originalText;
                btn.disabled = false;
                btn.classList.remove('opacity-75');
                
                // Scroll ke atas
                window.scrollTo({ top: document.getElementById('pencarian').offsetTop, behavior: 'smooth' });

            }, 1200); // Delay sedikit lebih lama untuk efek dramatis
        }

        // --- MODAL UTILS ---
        const modal = document.getElementById('reportModal');
        const overlay = document.getElementById('modal-overlay');
        const content = document.getElementById('modal-content');

        function openModal() {
            modal.classList.remove('hidden');
            setTimeout(() => {
                overlay.classList.remove('opacity-0');
                content.classList.remove('scale-95', 'opacity-0');
                content.classList.add('scale-100', 'opacity-100');
            }, 10);
        }

        function closeModal() {
            overlay.classList.add('opacity-0');
            content.classList.remove('scale-100', 'opacity-100');
            content.classList.add('scale-95', 'opacity-0');
            setTimeout(() => {
                modal.classList.add('hidden');
                document.getElementById('laporForm').reset();
                resetPreview();
            }, 300);
        }

        function previewImage(input) {
            const previewContainer = document.getElementById('previewContainer');
            const uploadPlaceholder = document.getElementById('uploadPlaceholder');
            const imgPreview = document.getElementById('imgPreview');
            if (input.files && input.files[0]) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    imgPreview.src = e.target.result;
                    previewContainer.classList.remove('hidden');
                    uploadPlaceholder.classList.add('hidden');
                }
                reader.readAsDataURL(input.files[0]);
            }
        }

        function resetPreview() {
            document.getElementById('previewContainer').classList.add('hidden');
            document.getElementById('uploadPlaceholder').classList.remove('hidden');
            document.getElementById('fileInput').value = "";
            document.getElementById('imgPreview').src = "";
        }

        overlay.addEventListener('click', closeModal);

        // Init
        window.onload = function() {
            filterItems();
        };
    </script>
</body>
</html>
