<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Penilaian Kebersihan SMKS HEPWETI - Oktober 2025</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            box-sizing: border-box;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .fade-in {
            animation: fadeIn 0.6s ease-out forwards;
        }
        
        .score-card {
            transition: all 0.3s ease;
        }
        
        .score-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
        }
        
        .progress-bar {
            transition: width 1s ease-out;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-blue-50 to-green-50 min-h-full">
    <div class="container mx-auto px-4 py-8">
        <!-- Header -->
        <header class="text-center mb-12 fade-in">
            <div class="bg-white rounded-2xl shadow-lg p-8 mb-6">
                <h1 class="text-4xl font-bold text-blue-900 mb-3">SMKS HEPWETI</h1>
                <h2 class="text-2xl font-semibold text-green-700 mb-2">Laporan Penilaian Kebersihan</h2>
                <p class="text-gray-600 text-lg">Bulan Oktober 2025</p>
                <div class="mt-4 inline-block bg-blue-100 px-6 py-2 rounded-full">
                    <p class="text-sm font-medium text-blue-800">📅 Tanggal Penilaian: 26 Oktober 2025</p>
                </div>
            </div>
        </header>

        <!-- Latar Belakang dan Tujuan -->
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 mb-8">
            <!-- Latar Belakang -->
            <div class="bg-white rounded-xl shadow-lg p-8 fade-in">
                <div class="flex items-start mb-4">
                    <span class="text-3xl mr-4">📋</span>
                    <h3 class="text-2xl font-bold text-blue-900">Latar Belakang</h3>
                </div>
                <p class="text-gray-700 leading-relaxed text-justify">
                    Kebersihan lingkungan sekolah merupakan faktor penting dalam menciptakan suasana belajar yang kondusif dan sehat. 
                    SMKS HEPWETI berkomitmen untuk menjaga standar kebersihan yang tinggi di seluruh area sekolah, baik di ruang kelas 
                    maupun laboratorium. Penilaian kebersihan ini dilakukan secara berkala untuk memastikan setiap unit memenuhi 
                    standar kebersihan yang telah ditetapkan dan mendorong budaya hidup bersih di lingkungan sekolah.
                </p>
            </div>

            <!-- Tujuan -->
            <div class="bg-white rounded-xl shadow-lg p-8 fade-in">
                <div class="flex items-start mb-4">
                    <span class="text-3xl mr-4">🎯</span>
                    <h3 class="text-2xl font-bold text-green-900">Tujuan Penilaian</h3>
                </div>
                <ul class="text-gray-700 leading-relaxed space-y-3">
                    <li class="flex items-start">
                        <span class="text-green-600 mr-2">•</span>
                        Mengukur tingkat kebersihan setiap kelas dan laboratorium
                    </li>
                    <li class="flex items-start">
                        <span class="text-green-600 mr-2">•</span>
                        Mendorong kompetisi sehat antar kelas dalam menjaga kebersihan
                    </li>
                    <li class="flex items-start">
                        <span class="text-green-600 mr-2">•</span>
                        Mengidentifikasi area yang perlu perbaikan
                    </li>
                    <li class="flex items-start">
                        <span class="text-green-600 mr-2">•</span>
                        Mewujudkan prinsip PANCA WALUYA di lingkungan sekolah
                    </li>
                </ul>
            </div>
        </div>

        <!-- Catatan Penting -->
        <div class="bg-gradient-to-r from-yellow-100 to-orange-100 border-l-4 border-orange-500 rounded-lg p-6 mb-8 shadow-md fade-in">
            <div class="flex items-start">
                <span class="text-3xl mr-4">⚠️</span>
                <div>
                    <h3 class="font-bold text-orange-900 text-xl mb-2">Catatan Penting</h3>
                    <p class="text-orange-800 text-lg leading-relaxed">
                        Kebersihan adalah tanggung jawab bersama agar terciptanya prinsip <strong>PANCA WALUYA</strong>
                    </p>
                </div>
            </div>
        </div>

        <!-- Kriteria Penilaian -->
        <div class="bg-white rounded-xl shadow-lg p-8 mb-8 fade-in">
            <div class="flex items-start mb-6">
                <span class="text-3xl mr-4">📝</span>
                <h3 class="text-2xl font-bold text-purple-900">Kriteria Penilaian Kebersihan</h3>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4">
                <div class="bg-purple-50 rounded-lg p-4 border-l-4 border-purple-500">
                    <div class="flex items-center mb-2">
                        <span class="text-lg mr-2">🧽</span>
                        <h4 class="font-semibold text-purple-800">Kebersihan Lantai</h4>
                    </div>
                    <p class="text-sm text-purple-700">Kondisi lantai bersih, tidak berdebu dan tidak ada sampah</p>
                </div>
                
                <div class="bg-blue-50 rounded-lg p-4 border-l-4 border-blue-500">
                    <div class="flex items-center mb-2">
                        <span class="text-lg mr-2">📋</span>
                        <h4 class="font-semibold text-blue-800">Kebersihan Papan Tulis</h4>
                    </div>
                    <p class="text-sm text-blue-700">Papan tulis bersih, tidak ada coretan yang mengganggu</p>
                </div>
                
                <div class="bg-green-50 rounded-lg p-4 border-l-4 border-green-500">
                    <div class="flex items-center mb-2">
                        <span class="text-lg mr-2">🪑</span>
                        <h4 class="font-semibold text-green-800">Kerapian Meja & Kursi</h4>
                    </div>
                    <p class="text-sm text-green-700">Meja dan kursi tertata rapi, bersih dari debu</p>
                </div>
                
                <div class="bg-yellow-50 rounded-lg p-4 border-l-4 border-yellow-500">
                    <div class="flex items-center mb-2">
                        <span class="text-lg mr-2">🪟</span>
                        <h4 class="font-semibold text-yellow-800">Kebersihan Jendela</h4>
                    </div>
                    <p class="text-sm text-yellow-700">Jendela dan ventilasi bersih, tidak berdebu</p>
                </div>
                
                <div class="bg-pink-50 rounded-lg p-4 border-l-4 border-pink-500">
                    <div class="flex items-center mb-2">
                        <span class="text-lg mr-2">🎨</span>
                        <h4 class="font-semibold text-pink-800">Dekorasi Dinding</h4>
                    </div>
                    <p class="text-sm text-pink-700">Adanya dekorasi yang rapi dan terawat di dinding kelas</p>
                </div>
                
                <div class="bg-red-50 rounded-lg p-4 border-l-4 border-red-500">
                    <div class="flex items-center mb-2">
                        <span class="text-lg mr-2">🗑️</span>
                        <h4 class="font-semibold text-red-800">Tong Sampah</h4>
                    </div>
                    <p class="text-sm text-red-700">Tersedia tong sampah yang bersih dan tidak penuh</p>
                </div>
                
                <div class="bg-emerald-50 rounded-lg p-4 border-l-4 border-emerald-500">
                    <div class="flex items-center mb-2">
                        <span class="text-lg mr-2">🌱</span>
                        <h4 class="font-semibold text-emerald-800">Perawatan Tanaman</h4>
                    </div>
                    <p class="text-sm text-emerald-700">Tanaman yang disediakan terawat dengan baik</p>
                </div>
                
                <div class="bg-indigo-50 rounded-lg p-4 border-l-4 border-indigo-500">
                    <div class="flex items-center mb-2">
                        <span class="text-lg mr-2">🏫</span>
                        <h4 class="font-semibold text-indigo-800">Lingkungan Kelas</h4>
                    </div>
                    <p class="text-sm text-indigo-700">Kebersihan area sekitar kelas dan koridor</p>
                </div>
            </div>
        </div>

        <!-- Filter Tabs -->
        <div class="flex justify-center mb-8 fade-in">
            <div class="bg-white rounded-xl shadow-md p-2 inline-flex gap-2">
                <button onclick="showSection('all')" id="btn-all" class="px-6 py-3 rounded-lg font-semibold transition-all bg-blue-600 text-white">
                    Semua
                </button>
                <button onclick="showSection('kelas')" id="btn-kelas" class="px-6 py-3 rounded-lg font-semibold transition-all text-gray-600 hover:bg-gray-100">
                    Kelas
                </button>
                <button onclick="showSection('lab')" id="btn-lab" class="px-6 py-3 rounded-lg font-semibold transition-all text-gray-600 hover:bg-gray-100">
                    Laboratorium
                </button>
            </div>
        </div>

        <!-- Penilaian Kelas -->
        <div id="section-kelas" class="mb-12">
            <h3 class="text-3xl font-bold text-blue-900 mb-6 text-center">🏫 Penilaian Kebersihan Kelas</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Kelas X -->
                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-blue-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">X TKJ</h4>
                        <span class="text-3xl font-bold text-blue-600">7.0</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-blue-500 h-3 rounded-full" style="width: 70%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">70%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-blue-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">X AKL</h4>
                        <span class="text-3xl font-bold text-blue-600">7.0</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-blue-500 h-3 rounded-full" style="width: 70%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">70%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-blue-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">X BDP</h4>
                        <span class="text-3xl font-bold text-blue-600">7.0</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-blue-500 h-3 rounded-full" style="width: 70%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">70%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-green-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">X DPB</h4>
                        <span class="text-3xl font-bold text-green-600">9.5</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-green-500 h-3 rounded-full" style="width: 95%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">95%</p>
                </div>

                <!-- Kelas XI -->
                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-yellow-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">XI TKJ</h4>
                        <span class="text-3xl font-bold text-yellow-600">8.0</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-yellow-500 h-3 rounded-full" style="width: 80%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">80%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-yellow-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">XI AKL</h4>
                        <span class="text-3xl font-bold text-yellow-600">8.0</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-yellow-500 h-3 rounded-full" style="width: 80%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">80%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-yellow-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">XI BDP</h4>
                        <span class="text-3xl font-bold text-yellow-600">8.0</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-yellow-500 h-3 rounded-full" style="width: 80%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">80%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-green-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">XI DPB</h4>
                        <span class="text-3xl font-bold text-green-600">9.6</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-green-500 h-3 rounded-full" style="width: 96%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">96%</p>
                </div>

                <!-- Kelas XII -->
                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-yellow-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">XII TKJ</h4>
                        <span class="text-3xl font-bold text-yellow-600">9</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-yellow-500 h-3 rounded-full" style="width: 85%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">85%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-green-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">XII AKL</h4>
                        <span class="text-3xl font-bold text-green-600">9.6</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-green-500 h-3 rounded-full" style="width: 96%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">96%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-green-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">XII BD</h4>
                        <span class="text-3xl font-bold text-green-600">9.6</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-green-500 h-3 rounded-full" style="width: 97%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">97%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-green-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">XII TB</h4>
                        <span class="text-3xl font-bold text-green-600">9.7</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-green-500 h-3 rounded-full" style="width: 96%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">96%</p>
                </div>
            </div>
        </div>

        <!-- Penilaian Lab -->
        <div id="section-lab" class="mb-12">
            <h3 class="text-3xl font-bold text-green-900 mb-6 text-center">🔬 Penilaian Kebersihan Laboratorium</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-yellow-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">LAB TKJ</h4>
                        <span class="text-3xl font-bold text-yellow-600">8.0</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-yellow-500 h-3 rounded-full" style="width: 80%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">80%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-yellow-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">LAB AKL</h4>
                        <span class="text-3xl font-bold text-yellow-600">8.8</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-yellow-500 h-3 rounded-full" style="width: 88%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">88%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-yellow-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">LAB BDP</h4>
                        <span class="text-3xl font-bold text-yellow-600">8.9</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-yellow-500 h-3 rounded-full" style="width: 89%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">89%</p>
                </div>

                <div class="score-card bg-white rounded-xl shadow-lg p-6 border-t-4 border-green-500">
                    <div class="flex justify-between items-center mb-4">
                        <h4 class="text-xl font-bold text-gray-800">LAB DPB</h4>
                        <span class="text-3xl font-bold text-green-600">9.5</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-3 mb-2">
                        <div class="progress-bar bg-green-500 h-3 rounded-full" style="width: 95%"></div>
                    </div>
                    <p class="text-sm text-gray-600 text-right">95%</p>
                </div>
            </div>
        </div>

        <!-- Rekomendasi -->
        <div class="bg-white rounded-xl shadow-lg p-8 mb-8 fade-in">
            <div class="flex items-start mb-6">
                <span class="text-3xl mr-4">💡</span>
                <h3 class="text-2xl font-bold text-blue-900">Rekomendasi Perbaikan</h3>
            </div>
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                <div class="bg-red-50 rounded-lg p-6 border-l-4 border-red-500">
                    <h4 class="font-bold text-red-800 mb-3">🚨 Perlu Perhatian Khusus (Skor < 8.0)</h4>
                    <ul class="space-y-2 text-red-700">
                        <li class="flex items-start">
                            <span class="mr-2">•</span>
                            <span><strong>X TKJ, X AKL, X BDP:</strong> Tingkatkan kebersihan lantai dan kerapian meja kursi serta membuang sampah ke tempat sampah</span>
                        </li>
                        <li class="flex items-start">
                            <span class="mr-2">•</span>
                            <span><strong>LAB TKJ:</strong> Perlu perawatan lebih intensif pada peralatan dan lingkungan lab</span>
                        </li>
                    </ul>
                </div>
                
                <div class="bg-yellow-50 rounded-lg p-6 border-l-4 border-yellow-500">
                    <h4 class="font-bold text-yellow-800 mb-3">⚠️ Perlu Perbaikan (Skor 8.0 - 8.9)</h4>
                    <ul class="space-y-2 text-yellow-700">
                        <li class="flex items-start">
                            <span class="mr-2">•</span>
                            <span><strong>Kelas XI & XII TKJ:</strong> Fokus pada kebersihan di kelas dan perawatan tanaman</span>
                        </li>
                        <li class="flex items-start">
                            <span class="mr-2">•</span>
                            <span><strong>LAB AKL & BDP:</strong> Tingkatkan kebersihan jendela dan ventilasi</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="mt-6 bg-green-50 rounded-lg p-6 border-l-4 border-green-500">
                <h4 class="font-bold text-green-800 mb-3">🏆 Prestasi Terbaik (Skor ≥ 9.5)</h4>
                <p class="text-green-700 mb-3">Selamat kepada kelas dan laboratorium dengan pencapaian luar biasa:</p>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-2">
                    <span class="bg-green-100 px-3 py-1 rounded-full text-sm font-medium text-green-800">X DPB (9.5)</span>
                    <span class="bg-green-100 px-3 py-1 rounded-full text-sm font-medium text-green-800">XI DPB (9.6)</span>
                    <span class="bg-green-100 px-3 py-1 rounded-full text-sm font-medium text-green-800">XII AKL (9.6)</span>
                    <span class="bg-green-100 px-3 py-1 rounded-full text-sm font-medium text-green-800">XII BD (9.6)</span>
                    <span class="bg-green-100 px-3 py-1 rounded-full text-sm font-medium text-green-800">XII TB (9.7)</span>
                    <span class="bg-green-100 px-3 py-1 rounded-full text-sm font-medium text-green-800">LAB DPB (9.5)</span>
                </div>
            </div>
        </div>

        <!-- Penutup -->
        <div class="bg-gradient-to-r from-blue-100 to-green-100 rounded-xl shadow-lg p-8 mb-8 fade-in">
            <div class="text-center">
                <span class="text-4xl mb-4 block">🤝</span>
                <h3 class="text-2xl font-bold text-gray-800 mb-4">Penutup</h3>
                <p class="text-gray-700 leading-relaxed mb-6 max-w-4xl mx-auto">
                    Penilaian kebersihan ini merupakan bagian dari upaya bersama untuk menciptakan lingkungan belajar yang sehat, 
                    nyaman, dan kondusif bagi seluruh warga sekolah SMKS HEPWETI. Kebersihan bukan hanya tanggung jawab petugas 
                    kebersihan, tetapi merupakan tanggung jawab bersama seluruh siswa, guru, dan staf sekolah.
                </p>
                <p class="text-gray-700 leading-relaxed mb-6 max-w-4xl mx-auto">
                    Mari kita terus bersama-sama menjaga dan meningkatkan kebersihan lingkungan sekolah untuk mewujudkan 
                    <strong>PANCA WALUYA</strong> - lingkungan yang bersih, sehat, indah, tertib, dan aman untuk mendukung 
                    proses pembelajaran yang optimal.
                </p>
                <div class="bg-white rounded-lg p-4 inline-block shadow-md">
                    <p class="text-sm font-medium text-gray-600">
                        "Kebersihan adalah sebagian dari iman, dan lingkungan bersih adalah investasi untuk masa depan yang lebih baik"
                    </p>
                </div>
            </div>
        </div>

        <!-- Footer -->
        <footer class="text-center mt-12 bg-white rounded-xl shadow-lg p-6">
            <p class="text-gray-600 mb-2">Tim Penilai Kebersihan Sekolah</p>
            <p class="text-sm text-gray-500">SMKS HEPWETI © 2025</p>
        </footer>
    </div>

    <script>
        function showSection(section) {
            const kelasSection = document.getElementById('section-kelas');
            const labSection = document.getElementById('section-lab');
            const btnAll = document.getElementById('btn-all');
            const btnKelas = document.getElementById('btn-kelas');
            const btnLab = document.getElementById('btn-lab');
            
            btnAll.className = 'px-6 py-3 rounded-lg font-semibold transition-all text-gray-600 hover:bg-gray-100';
            btnKelas.className = 'px-6 py-3 rounded-lg font-semibold transition-all text-gray-600 hover:bg-gray-100';
            btnLab.className = 'px-6 py-3 rounded-lg font-semibold transition-all text-gray-600 hover:bg-gray-100';
            
            if (section === 'all') {
                kelasSection.style.display = 'block';
                labSection.style.display = 'block';
                btnAll.className = 'px-6 py-3 rounded-lg font-semibold transition-all bg-blue-600 text-white';
            } else if (section === 'kelas') {
                kelasSection.style.display = 'block';
                labSection.style.display = 'none';
                btnKelas.className = 'px-6 py-3 rounded-lg font-semibold transition-all bg-blue-600 text-white';
            } else if (section === 'lab') {
                kelasSection.style.display = 'none';
                labSection.style.display = 'block';
                btnLab.className = 'px-6 py-3 rounded-lg font-semibold transition-all bg-blue-600 text-white';
            }
        }
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9942c0a185635615',t:'MTc2MTQwNjE5OC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>using UnityEngine;

public class HeroMovement : MonoBehaviour
{
    public float moveSpeed = 5f;
    Vector2 input;
    Rigidbody rb;

    void Awake() => rb = GetComponent<Rigidbody>();

    // Panggil dari UI joystick: SetInput(x,y)
    public void SetInput(Vector2 v) => input = v;

    void FixedUpdate()
    {
        Vector3 move = new Vector3(input.x, 0, input.y) * moveSpeed * Time.fixedDeltaTime;
        rb.MovePosition(transform.position + move);

        if (move.sqrMagnitude > 0.001f)
        {
            transform.forward = Vector3.Slerp(transform.forward, move.normalized, 0.2f);
        }
    }
}


