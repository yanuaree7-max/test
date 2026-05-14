<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Yanuar Reza Saputra</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f3f4f6;
            margin: 0;
            padding: 20px;
        }
        .vertical-text {
            writing-mode: vertical-rl;
            transform: rotate(180deg);
        }
        /* Custom Colors based on the reference */
        .bg-neon { background-color: #d1ff1a; }
        .text-neon { color: #d1ff1a; }
        .bg-dark { background-color: #222222; }
        .bg-purple-custom { background-color: #5c24ff; }
        .text-purple-custom { color: #5c24ff; }
        
        /* Smooth wavy background pattern */
        .bg-pattern {
            background-image: 
                radial-gradient(circle at 0% 0%, #d1ff1a 0%, transparent 30%),
                radial-gradient(circle at 100% 20%, #5c24ff 0%, transparent 25%);
            background-color: white;
        }

        /* Animasi Slide Down untuk Menu PR */
        @keyframes slideDown {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-slide-down {
            animation: slideDown 0.3s ease-out forwards;
        }

        /* Animasi Typing Dot untuk AI */
        .typing-dot {
            animation: typing 1.4s infinite ease-in-out;
            fill: currentColor;
        }
        .typing-dot:nth-child(1) { animation-delay: -0.32s; }
        .typing-dot:nth-child(2) { animation-delay: -0.16s; }
        @keyframes typing {
            0%, 80%, 100% { transform: scale(0); }
            40% { transform: scale(1); }
        }
    </style>
</head>
<body class="flex justify-center items-center min-h-screen">

    <!-- Main Container -->
    <div class="relative w-full max-w-4xl bg-pattern rounded-3xl shadow-2xl overflow-hidden flex flex-col md:flex-row">
        
        <!-- Left Vertical Bar -->
        <div class="hidden md:flex flex-col items-center justify-end bg-neon w-16 shrink-0 z-20 rounded-l-3xl rounded-br-[4rem]">
            <h2 class="vertical-text text-xl font-bold text-[#222222] tracking-widest pb-12">
                PORTFOLIO 2026
            </h2>
        </div>

        <!-- Main Content Area -->
        <div class="flex-1 w-full relative z-10">
            
            <!-- Mobile Vertical Bar Equivalent -->
            <div class="md:hidden bg-neon w-full p-2 text-center text-sm font-bold tracking-widest text-[#222222]">
                PORTFOLIO 2026
            </div>

            <!-- Header Section -->
            <div class="flex flex-col-reverse md:flex-row px-8 pt-8 pb-4">
                
                <!-- Profile Image -->
                <div class="w-full md:w-5/12 flex justify-center items-center mt-6 md:mt-0 relative">
                    <!-- FOTO PROFIL YANUAR -->
                    <img src="<a href="https://ibb.co.com/PzP5hJD0"><img src="https://i.ibb.co.com/FqyBwcHC/Desain-tanpa-judul.png" alt="Desain-tanpa-judul" border="0"></a>" class="w-full max-w-[260px] aspect-square object-cover object-center z-10 rounded-full border-4 border-neon shadow-lg">
                </div>

                <!-- Intro Text -->
                <div class="w-full md:w-7/12 flex flex-col justify-center text-left pl-0 md:pl-6">
                    <div class="mb-4">
                        <span class="bg-neon text-[#222] font-bold px-5 py-2 rounded-full text-lg inline-block shadow-sm italic">Hello!!</span>
                    </div>
                    <h1 class="text-4xl md:text-5xl font-extrabold text-[#222] leading-tight mb-2">
                        I'm <span class="text-purple-custom">Yanuar</span> Reza Saputra,
                    </h1>
                    <h2 class="text-lg md:text-xl font-bold text-[#444] leading-relaxed mb-4 tracking-wide">
                        Corporate Communication <span class="text-purple-400 font-normal">|</span> Investor Relations <span class="text-purple-400 font-normal">|</span> Graphic Designer <span class="text-purple-400 font-normal">|</span> Video Editor
                    </h2>
                    <div class="flex items-start gap-3 mt-2 bg-white/80 p-3.5 rounded-xl shadow-sm backdrop-blur-sm border border-white">
                        <img src="https://placehold.co/40x40/5c24ff/ffffff?text=PR" alt="icon" class="w-10 h-10 rounded-full shrink-0">
                        <p class="text-[13px] text-gray-700 font-medium leading-relaxed">
                            Profesional komunikasi tersertifikasi BNSP dengan dedikasi tinggi dalam membangun reputasi perusahaan melalui strategi korporat yang terintegrasi, perancangan identitas visual yang memukau, serta produksi konten digital yang berdampak dan terukur.
                        </p>
                    </div>
                </div>
            </div>

            <!-- Dark Section: About & Education -->
            <div class="bg-dark text-white rounded-t-[2.5rem] rounded-b-[2.5rem] p-8 md:p-10 relative z-20 shadow-xl mt-4">
                
                <!-- About Me -->
                <div class="flex flex-col md:flex-row gap-6 mb-10 border-b border-gray-700 pb-8">
                    <div class="w-full md:w-1/4">
                        <h3 class="text-2xl font-bold text-white italic">About Me</h3>
                    </div>
                    <div class="w-full md:w-3/4">
                        <p class="text-gray-300 text-sm md:text-base leading-relaxed text-justify">
                            Saya adalah <span class="text-neon font-semibold italic">Ahli Muda Investor Relations & Public Relations</span> di PT Wijaya Karya Realty dengan latar belakang pendidikan D3 Komunikasi Terapan di Universitas Sebelas Maret. Saya telah bersertifikasi <span class="text-neon font-semibold italic">PR Officer</span> (BNSP). Berpengalaman dalam komunikasi korporat, manajemen media sosial, dan produksi konten kreatif. Berkomitmen dalam memperkuat reputasi perusahaan melalui strategi komunikasi yang inovatif dan efektif.
                        </p>
                    </div>
                </div>

                <!-- Education -->
                <div class="flex flex-col md:flex-row gap-6">
                    <div class="w-full md:w-1/4">
                        <h3 class="text-2xl font-bold text-white italic">Education</h3>
                    </div>
                    <div class="w-full md:w-3/4 flex flex-col gap-5">
                        <!-- Education 1 -->
                        <div>
                            <div class="flex flex-col sm:flex-row sm:justify-between sm:items-start">
                                <h4 class="font-bold text-lg">Asia Cyber University</h4>
                                <span class="text-neon text-xs mt-1 sm:mt-0 font-semibold bg-gray-800 px-2 py-1 rounded">Apr 2026 - Apr 2028</span>
                            </div>
                            <p class="text-gray-400 text-sm font-medium italic">Co, Business/Corporate Communications</p>
                            <p class="text-gray-300 text-xs mt-1">IPK: 3.88/4.00</p>
                            <p class="text-gray-400 text-xs mt-2 leading-relaxed italic">Accelerating my degree through the Recognition of Prior Learning (RPL) program, utilizing Credit Transfer to bridge professional expertise with academic requirements.</p>
                        </div>
                        <div class="h-px bg-gray-700 w-full"></div>
                        <!-- Education 2 -->
                        <div>
                            <div class="flex flex-col sm:flex-row sm:justify-between sm:items-start">
                                <h4 class="font-bold text-lg">Universitas Sebelas Maret</h4>
                                <span class="text-neon text-xs mt-1 sm:mt-0 font-semibold bg-gray-800 px-2 py-1 rounded">Agu 2022 - Jul 2025</span>
                            </div>
                            <p class="text-gray-400 text-sm font-medium italic">Associate's degree Applied Communications</p>
                            <p class="text-gray-300 text-xs mt-1">IPK: 3.89 / <i class="italic">CUMLAUDE</i></p>
                            <p class="text-gray-400 text-xs mt-2">Keahlian: Produksi Video, <i class="italic">Social Media Communications</i>, dan +4 keahlian lainnya.</p>
                        </div>
                        <div class="h-px bg-gray-700 w-full"></div>
                        <!-- Education 3 -->
                        <div>
                            <div class="flex flex-col sm:flex-row sm:justify-between sm:items-start">
                                <h4 class="font-bold text-lg">SMK Negeri 1 Kebumen</h4>
                                <span class="text-neon text-xs mt-1 sm:mt-0 font-semibold bg-gray-800 px-2 py-1 rounded">Jul 2019 - Jun 2022</span>
                            </div>
                            <p class="text-gray-400 text-sm font-medium">Multimedia</p>
                            <p class="text-gray-300 text-xs mt-1">Nilai Akhir: 86.57 | Penghargaan Siswa Terbaik Program Studi Multimedia 2022</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Purple Section: Experience & Skills -->
            <div class="bg-purple-custom text-white rounded-[2.5rem] p-8 md:p-10 relative z-10 -mt-10 pt-16 shadow-lg rounded-b-none md:rounded-b-3xl">
                
                <!-- Work Experience -->
                <div class="flex flex-col md:flex-row gap-6 mb-10 border-b border-purple-400 pb-8">
                    <div class="w-full md:w-1/4">
                        <h3 class="text-2xl font-bold text-white italic">Work<br>Experience</h3>
                    </div>
                    <div class="w-full md:w-3/4">
                        
                        <!-- Timeline/Milestone Container -->
                        <div class="relative border-l-2 border-purple-400/40 ml-2 md:ml-4 space-y-8 pb-2">
                            
                            <!-- Experience 1 -->
                            <div class="relative pl-6 md:pl-8">
                                <div class="absolute -left-[11px] top-1.5 w-6 h-6 bg-purple-custom rounded-full border-[3px] border-neon flex items-center justify-center z-10 shadow-[0_0_10px_rgba(209,255,26,0.4)]">
                                    <div class="w-1.5 h-1.5 bg-neon rounded-full"></div>
                                </div>
                                
                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-center mb-1">
                                    <h4 class="font-bold text-xl text-neon leading-tight">PT Wijaya Karya Realty</h4>
                                    <span class="text-xs font-semibold bg-purple-800/80 px-3 py-1 rounded-full text-white mt-2 sm:mt-0 w-fit whitespace-nowrap">Des 2025 - Sekarang</span>
                                </div>
                                <p class="text-purple-200 font-medium mb-3 italic">Investor Relations & Public Relations Staff</p>
                                <ul class="list-disc list-outside ml-4 text-sm text-white/90 space-y-1.5">
                                    <li>Menyusun materi strategis <i class="italic">Annual Report</i>, RUPST, dan keterbukaan informasi untuk menjaga transparansi kepada investor melalui pengumpulan data lintas divisi.</li>
                                    <li>Mempublikasikan <i class="italic">press release</i> serta inisiatif CSR guna memperkuat citra positif perusahaan melalui eksekusi <i class="italic">media monitoring</i> yang komprehensif.</li>
                                    <li>Memproduksi aset visual korporat dan konten media sosial untuk meningkatkan interaksi audiens melalui implementasi desain berbasis panduan identitas merek.</li>
                                </ul>
                            </div>

                            <!-- Experience 2 -->
                            <div class="relative pl-6 md:pl-8">
                                <div class="absolute -left-[11px] top-1.5 w-6 h-6 bg-purple-custom rounded-full border-[3px] border-purple-400 flex items-center justify-center z-10">
                                    <div class="w-1.5 h-1.5 bg-purple-200 rounded-full"></div>
                                </div>

                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-center mb-1">
                                    <h4 class="font-bold text-xl text-neon leading-tight">PT Wijaya Karya Realty</h4>
                                    <span class="text-xs font-semibold bg-purple-800/80 px-3 py-1 rounded-full text-white mt-2 sm:mt-0 w-fit whitespace-nowrap">Jan 2025 - Mar 2025</span>
                                </div>
                                <p class="text-purple-200 font-medium mb-3 italic">Investor Relations & Public Relations Intern</p>
                                <ul class="list-disc list-outside ml-4 text-sm text-white/90 space-y-1.5">
                                    <li>Mendesain aset visual dan menyusun buletin korporat guna meningkatkan efektivitas komunikasi internal perusahaan melalui penyajian informasi yang interaktif.</li>
                                    <li>Mendokumentasikan kegiatan perusahaan secara audiovisual untuk menyediakan materi publikasi yang terstandarisasi melalui perancangan <i class="italic">content brief</i>.</li>
                                </ul>
                            </div>
                            
                            <!-- Experience 3 -->
                            <div class="relative pl-6 md:pl-8">
                                <div class="absolute -left-[11px] top-1.5 w-6 h-6 bg-purple-custom rounded-full border-[3px] border-purple-400 flex items-center justify-center z-10">
                                    <div class="w-1.5 h-1.5 bg-purple-200 rounded-full"></div>
                                </div>

                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-center mb-1">
                                    <h4 class="font-bold text-xl text-neon leading-tight">PT. Kalimaya Alunna Indonesia</h4>
                                    <span class="text-xs font-semibold bg-purple-800/80 px-3 py-1 rounded-full text-white mt-2 sm:mt-0 w-fit whitespace-nowrap">Sep 2024 - Des 2024</span>
                                </div>
                                <p class="text-purple-200 font-medium mb-3"><i class="italic">Content Creator Intern Brand</i> Lemonih (@lemonih.id)</p>
                                <ul class="list-disc list-outside ml-4 text-sm text-white/90 space-y-1.5">
                                    <li>Meningkatkan jangkauan konten akun Instagram baru hingga 229% guna memperluas <i class="italic">brand awareness</i> melalui riset tren audiens dan optimalisasi Meta Business Suite.</li>
                                    <li>Memproduksi konten media sosial termasuk 15+ <i class="italic">Reels</i> viral untuk memaksimalkan retensi audiens melalui penerapan naskah visual berbasis <i class="italic">storytelling</i>.</li>
                                </ul>
                            </div>

                            <!-- Experience 4 -->
                            <div class="relative pl-6 md:pl-8">
                                <div class="absolute -left-[11px] top-1.5 w-6 h-6 bg-purple-custom rounded-full border-[3px] border-purple-400 flex items-center justify-center z-10">
                                    <div class="w-1.5 h-1.5 bg-purple-200 rounded-full"></div>
                                </div>

                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-center mb-1">
                                    <h4 class="font-bold text-xl text-neon leading-tight">SOCMedia Group</h4>
                                    <span class="text-xs font-semibold bg-purple-800/80 px-3 py-1 rounded-full text-white mt-2 sm:mt-0 w-fit whitespace-nowrap">Feb 2024 - Jun 2024</span>
                                </div>
                                <p class="text-purple-200 font-medium mb-3 italic">Graphic Design Internship</p>
                                <ul class="list-disc list-outside ml-4 text-sm text-white/90 space-y-1.5">
                                    <li>Membuat 16 desain <i class="italic">feed</i> Instagram bulanan untuk klien guna menjaga konsistensi identitas merek melalui eksekusi <i class="italic">Editorial Plan</i> (EP) yang terstruktur.</li>
                                </ul>
                            </div>

                            <!-- Experience 5 -->
                            <div class="relative pl-6 md:pl-8">
                                <div class="absolute -left-[11px] top-1.5 w-6 h-6 bg-purple-custom rounded-full border-[3px] border-purple-400 flex items-center justify-center z-10">
                                    <div class="w-1.5 h-1.5 bg-purple-200 rounded-full"></div>
                                </div>

                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-center mb-1">
                                    <h4 class="font-bold text-xl text-neon leading-tight">SOCLyfe.com</h4>
                                    <span class="text-xs font-semibold bg-purple-800/80 px-3 py-1 rounded-full text-white mt-2 sm:mt-0 w-fit whitespace-nowrap">Feb 2024 - Jun 2024</span>
                                </div>
                                <p class="text-purple-200 font-medium mb-3 italic">Graphic Design & Video Journalist Internship</p>
                                <ul class="list-disc list-outside ml-4 text-sm text-white/90 space-y-1.5">
                                    <li>Memproduksi 90+ grafis <i class="italic">feed</i> berita bulanan untuk mendistribusikan informasi aktual secara cepat melalui alur kerja jurnalistik visual yang efisien.</li>
                                    <li>Memperbarui antarmuka desain media sosial platform guna meningkatkan daya tarik visual pembaca melalui penciptaan pedoman <i class="italic">rebranding</i> yang modern.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Skills & Software -->
                <div class="flex flex-col md:flex-row gap-6">
                    <div class="w-full md:w-1/4">
                        <h3 class="text-2xl font-bold text-white italic">Skills &<br>Software</h3>
                    </div>
                    <div class="w-full md:w-3/4">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4 grid-flow-dense">
                            <!-- Skill 1 -->
                            <div onclick="togglePR()" class="cursor-pointer flex items-center justify-between bg-white/10 p-3 rounded-xl hover:bg-white/20 transition group border border-transparent hover:border-neon/50">
                                <div class="flex items-center gap-3">
                                    <div class="w-10 h-10 rounded-full bg-neon flex items-center justify-center shrink-0 shadow-[0_0_10px_rgba(209,255,26,0.3)]">
                                        <svg class="w-5 h-5 text-[#222]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9.5a2 2 0 00-.586-1.414l-4.5-4.5A2 2 0 0012.586 3H12"></path></svg>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold text-sm group-hover:text-neon transition-colors italic">Public Relations</h4>
                                        <p class="text-[11px] text-purple-200 mt-0.5 leading-tight"><i class="italic">Press Release, Speech Director, Content Brief</i></p>
                                    </div>
                                </div>
                                <div class="pr-2 opacity-40 group-hover:opacity-100 group-hover:text-neon transition">
                                    <svg class="w-5 h-5 animate-bounce" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 13l-3 3m0 0l-3-3m3 3V8m0 13a9 9 0 110-18 9 9 0 010 18z"></path></svg>
                                </div>
                            </div>

                            <!-- PR Portfolio -->
                            <div id="pr-portfolio" class="hidden md:col-span-2 bg-purple-900/60 rounded-2xl border border-neon/50 overflow-hidden flex flex-col sm:flex-row group transition-all duration-300 relative">
                                <button onclick="togglePR()" class="absolute top-2 right-2 p-1.5 bg-black/40 hover:bg-red-500/80 rounded-full text-white/80 transition z-20">
                                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
                                </button>
                                <div class="w-full sm:w-2/5 bg-black/30 p-5 flex justify-center items-center">
                                    <img src="https://placehold.co/400x560/e2e8f0/64748b?text=Press+Release" class="w-full max-w-[160px] rounded shadow-2xl border-[5px] border-white/90">
                                </div>
                                <div class="w-full sm:w-3/5 p-5 sm:p-6 flex flex-col justify-center">
                                    <h5 class="text-[11px] font-bold text-white mb-2 border-b border-purple-500/30 pb-1 italic">PROJECT PRESS RELEASE</h5>
                                    <p class="text-xs text-white mb-4 italic">"Perkuat Daya Saing Global, Dua Hotel Naungan WIKA Realty Sabet Penghargaan Agoda Gold Circle Award 2025"</p>
                                    <div class="flex flex-wrap gap-2">
                                        <a href="https://m.merdekanews.co/read/40426/Perkuat-Daya-Saing-Global-Dua-Hotel-Naungan-WIKA-Realty-Sabet-Penghargaan-Agoda-Gold-Circle-Award-2025" target="_blank" class="text-[10px] bg-white/10 hover:bg-neon hover:text-[#222] px-3 py-1.5 rounded transition">Merdeka News</a>
                                        <a href="https://radarikn.id/ekonomi/read/12642/Perkuat-Daya-Saing-Global-Dua-Hotel-Naungan-WIKA-Realty-Sabet-Penghargaan-Agoda-Gold-Circle-Award-2025.html" target="_blank" class="text-[10px] bg-white/10 hover:bg-neon hover:text-[#222] px-3 py-1.5 rounded transition">Radar IKN</a>
                                    </div>
                                </div>
                            </div>

                            <!-- Skill 2 -->
                            <div onclick="toggleVE()" class="cursor-pointer flex items-center justify-between bg-white/10 p-3 rounded-xl hover:bg-white/20 transition group border border-transparent hover:border-neon/50">
                                <div class="flex items-center gap-3">
                                    <div class="w-10 h-10 rounded-full bg-neon flex items-center justify-center shrink-0">
                                        <svg class="w-5 h-5 text-[#222]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z"></path></svg>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold text-sm group-hover:text-neon italic">Video Editing</h4>
                                        <p class="text-xs text-purple-200">Premiere Pro, CapCut</p>
                                    </div>
                                </div>
                                <div class="pr-2 opacity-40 group-hover:opacity-100 transition">
                                    <svg class="w-5 h-5 animate-bounce" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M15 13l-3 3m0 0l-3-3m3 3V8m0 13a9 9 0 110-18 9 9 0 010 18z"></path></svg>
                                </div>
                            </div>

                            <!-- VE Portfolio -->
                            <div id="ve-portfolio" class="hidden md:col-span-2 bg-purple-900/60 rounded-2xl border border-neon/50 p-5 mt-2">
                                <h5 class="text-[11px] font-bold text-white mb-2 italic">VIDEO PROJECTS</h5>
                                <div class="flex flex-col gap-2">
                                    <a href="https://www.instagram.com/reel/DXX6hzqzArl/" target="_blank" class="text-xs bg-white/5 p-2 rounded hover:text-neon">1. Video Hari Kartini PT Wijaya Karya Realty</a>
                                    <a href="https://www.instagram.com/reel/DWH4ExwE0Cz/" target="_blank" class="text-xs bg-white/5 p-2 rounded hover:text-neon">2. Video Idul Fitri 1447 PT Wijaya Karya Realty</a>
                                </div>
                            </div>

                            <!-- Skill 3 -->
                            <div onclick="toggleGD()" class="cursor-pointer flex items-center justify-between bg-white/10 p-3 rounded-xl hover:bg-white/20 transition group border border-transparent hover:border-neon/50">
                                <div class="flex items-center gap-3">
                                    <div class="w-10 h-10 rounded-full bg-neon flex items-center justify-center shrink-0">
                                        <svg class="w-5 h-5 text-[#222]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v1m2 13a2 2 0 002-2V9.5a2 2 0 00-.586-1.414l-4.5-4.5A2 2 0 0012.586 3H12"></path></svg>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold text-sm italic">Graphic Design</h4>
                                        <p class="text-xs text-purple-200">Illustrator, Canva</p>
                                    </div>
                                </div>
                            </div>

                            <!-- Skill 4 -->
                            <div onclick="toggleSM()" class="cursor-pointer flex items-center justify-between bg-white/10 p-3 rounded-xl hover:bg-white/20 group border border-transparent hover:border-neon/50">
                                <div class="flex items-center gap-3">
                                    <div class="w-10 h-10 rounded-full bg-neon flex items-center justify-center shrink-0">
                                        <svg class="w-5 h-5 text-[#222]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"></path></svg>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold text-sm italic">Social Media</h4>
                                        <p class="text-xs text-purple-200">Planning, Meta Suite</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Certifications & Awards -->
                <div class="flex flex-col md:flex-row gap-6 mt-10 border-t border-purple-400 pt-8">
                    <div class="w-full md:w-1/4">
                        <h3 class="text-2xl font-bold text-white italic">Licenses &<br>Awards</h3>
                    </div>
                    <div class="w-full md:w-3/4">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div class="bg-purple-800/40 p-5 rounded-xl border border-purple-400/30">
                                <h4 class="font-bold text-neon text-sm mb-4">Sertifikasi</h4>
                                <ul class="flex flex-col gap-3 text-[13px]">
                                    <li>• Sertifikasi PR Officer - BNSP (2025)</li>
                                    <li>• Sertifikasi Microsoft Office</li>
                                    <li>• Perancang Grafis - BNSP (2022)</li>
                                </ul>
                            </div>
                            <div class="bg-purple-800/40 p-5 rounded-xl border border-purple-400/30">
                                <h4 class="font-bold text-neon text-sm mb-4">Penghargaan</h4>
                                <ul class="flex flex-col gap-3 text-[13px]">
                                    <li>• Juara 1 Poster VGCC HIMAKOMTER UNS</li>
                                    <li>• Siswa Terbaik Multimedia 2022</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Contacts -->
                <div class="flex flex-col md:flex-row gap-6 mt-10 border-t border-purple-400 pt-8">
                    <div class="w-full md:w-1/4">
                        <h3 class="text-2xl font-bold text-white italic">Get in Touch</h3>
                    </div>
                    <div class="w-full md:w-3/4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <a href="mailto:yanu.aree7@gmail.com" class="flex items-center gap-3 bg-purple-800/40 p-3 rounded-xl border border-purple-400/30 hover:border-neon transition">
                                <div class="w-10 h-10 rounded-full bg-red-500 flex items-center justify-center shrink-0">
                                    <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path></svg>
                                </div>
                                <div>
                                    <h4 class="font-bold text-white text-sm">Email</h4>
                                    <p class="text-xs text-purple-200">yanu.aree7@gmail.com</p>
                                </div>
                            </a>
                            <a href="https://www.linkedin.com/in/yanuar-reza-saputra" target="_blank" class="flex items-center gap-3 bg-purple-800/40 p-3 rounded-xl border border-purple-400/30 hover:border-neon transition">
                                <div class="w-10 h-10 rounded-full bg-[#0a66c2] flex items-center justify-center shrink-0">
                                    <svg class="w-5 h-5 text-white" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                                </div>
                                <div>
                                    <h4 class="font-bold text-white text-sm">LinkedIn</h4>
                                    <p class="text-xs text-purple-200">Yanuar Reza Saputra</p>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- AI Chat Widget -->
    <div class="fixed bottom-6 right-6 z-50">
        <button onclick="toggleAIChat()" id="ai-chat-btn" class="w-14 h-14 rounded-full bg-neon flex items-center justify-center shadow-lg hover:scale-110 transition-transform relative">
            <svg class="w-7 h-7 text-[#222]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z"></path></svg>
            <span class="absolute -top-1 -right-1 flex h-4 w-4">
              <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-purple-400 opacity-75"></span>
              <span class="relative inline-flex rounded-full h-4 w-4 bg-purple-500 border-2 border-white"></span>
            </span>
        </button>

        <div id="ai-chat-window" class="hidden absolute bottom-16 right-0 w-[320px] bg-white rounded-2xl shadow-2xl overflow-hidden flex flex-col border border-gray-200 h-[400px]">
            <div class="bg-gradient-to-r from-[#222] to-purple-custom p-3 flex justify-between items-center text-white">
                <span class="font-bold text-xs">Asisten Yanuar ✨</span>
                <button onclick="toggleAIChat()">×</button>
            </div>
            <div id="ai-chat-messages" class="flex-1 bg-gray-50 p-4 overflow-y-auto flex flex-col gap-3 text-[11px]">
                <div class="bg-white border p-2 rounded-lg">Halo! Saya AI Yanuar. Ada yang ingin ditanyakan tentang pengalaman PR atau desain saya?</div>
            </div>
            <div class="p-3 bg-white border-t flex gap-2">
                <input type="text" id="ai-chat-input" placeholder="Ketik pertanyaan..." class="flex-1 bg-gray-100 rounded-full px-3 text-xs outline-none" onkeypress="if(event.key==='Enter') sendChatMessage()">
                <button onclick="sendChatMessage()" class="w-8 h-8 rounded-full bg-purple-custom text-white flex items-center justify-center">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"></path></svg>
                </button>
            </div>
        </div>
    </div>

    <script>
        function toggleAIChat() {
            const win = document.getElementById('ai-chat-window');
            win.classList.toggle('hidden');
        }

        async function sendChatMessage() {
            const input = document.getElementById('ai-chat-input');
            const chat = document.getElementById('ai-chat-messages');
            const text = input.value.trim();
            if(!text) return;

            chat.innerHTML += `<div class="flex justify-end"><div class="bg-purple-100 p-2 rounded-lg">${text}</div></div>`;
            input.value = '';
            
            chat.innerHTML += `<div id="typing" class="bg-white border p-2 rounded-lg italic">Mengetik...</div>`;
            chat.scrollTop = chat.scrollHeight;

            setTimeout(() => {
                document.getElementById('typing').remove();
                chat.innerHTML += `<div class="bg-white border p-2 rounded-lg">Yanuar saat ini berkarir di PT WIKA Realty sebagai PR & Investor Relations. Beliau juga ahli di bidang desain grafis dan video editing.</div>`;
                chat.scrollTop = chat.scrollHeight;
            }, 1000);
        }

        function togglePR() { document.getElementById('pr-portfolio').classList.toggle('hidden'); }
        function toggleVE() { document.getElementById('ve-portfolio').classList.toggle('hidden'); }
        function toggleGD() {}
        function toggleSM() {}
        function toggleWA(e) { e.preventDefault(); }
    </script>
</body>
</html>
