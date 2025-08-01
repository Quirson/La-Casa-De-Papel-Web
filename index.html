<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Casa de Papel - Valrise Gaming</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Inter:wght@300;400;500;600;700;800&display=swap');

        :root {
            --red-primary: #DC2626;
            --red-dark: #991B1B;
            --red-darker: #7F1D1D;
            --red-light: #EF4444;
            --gold: #F59E0B;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: #0A0A0A;
            color: #FFFFFF;
            overflow-x: hidden;
            line-height: 1.6;
        }

        .logo-font {
            font-family: 'Orbitron', monospace;
        }

        /* Loading Screen */
        .loading-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, #000000 0%, #1F1F1F 50%, #000000 100%);
            z-index: 9999;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }

        .loading-logo {
            width: 200px;
            height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            animation: pulse 2s infinite;
        }

        .loading-logo img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Navigation */
        .navbar {
            background: rgba(0, 0, 0, 0.95);
            backdrop-filter: blur(20px);
            border-bottom: 1px solid rgba(220, 38, 38, 0.3);
        }

        .nav-item {
            position: relative;
            padding: 12px 20px;
            border-radius: 8px;
            transition: all 0.3s ease;
            font-weight: 500;
        }

        .nav-item:hover {
            background: linear-gradient(135deg, var(--red-primary), var(--red-dark));
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(220, 38, 38, 0.4);
        }

        /* Page Transitions */
        .page {
            display: none;
            min-height: 100vh;
        }

        .page.active {
            display: block;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Hero Section */
        .hero-section {
            background: linear-gradient(135deg, rgba(220, 38, 38, 0.1) 0%, rgba(0, 0, 0, 0.8) 100%);
            border-bottom: 2px solid var(--red-primary);
            position: relative;
            overflow: hidden;
            background-attachment: fixed;
            background-size: cover;
        }

        .hero-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse"><path d="M 10 0 L 0 0 0 10" fill="none" stroke="%23DC2626" stroke-width="0.5" opacity="0.1"/></pattern></defs><rect width="100" height="100" fill="url(%23grid)"/></svg>');
            opacity: 0.3;
        }

        /* Content Cards */
        .content-card {
            background: linear-gradient(135deg, rgba(31, 31, 31, 0.8) 0%, rgba(220, 38, 38, 0.05) 100%);
            border: 1px solid rgba(220, 38, 38, 0.2);
            border-radius: 16px;
            padding: 2rem;
            transition: all 0.3s ease;
            backdrop-filter: blur(10px);
        }

        .content-card:hover {
            transform: translateY(-8px);
            border-color: var(--red-primary);
            box-shadow: 0 20px 40px rgba(220, 38, 38, 0.2);
        }

        /* Buttons */
        .btn-primary {
            background: linear-gradient(135deg, var(--red-primary), var(--red-dark));
            color: white;
            padding: 12px 24px;
            border-radius: 10px;
            font-weight: 600;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            position: relative;
            overflow: hidden;
        }

        .btn-primary::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            transition: left 0.5s;
        }

        .btn-primary:hover::before {
            left: 100%;
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(220, 38, 38, 0.4);
        }

        /* Member Cards */
        .member-card {
            background: linear-gradient(135deg, rgba(31, 31, 31, 0.9) 0%, rgba(220, 38, 38, 0.1) 100%);
            border: 1px solid rgba(220, 38, 38, 0.3);
            border-radius: 20px;
            padding: 1.5rem;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .member-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, var(--red-primary), var(--gold), var(--red-primary));
        }

        .member-card:hover {
            transform: translateY(-10px) scale(1.02);
            border-color: var(--red-primary);
            box-shadow: 0 25px 50px rgba(220, 38, 38, 0.3);
        }

        .member-avatar {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--red-primary), var(--red-dark));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            margin: 0 auto 1rem;
            border: 3px solid var(--gold);
        }

        /* Rules */
        .rule-card {
            background: linear-gradient(135deg, rgba(31, 31, 31, 0.8) 0%, rgba(220, 38, 38, 0.05) 100%);
            border-left: 4px solid var(--red-primary);
            border-radius: 12px;
            padding: 1.5rem;
            margin-bottom: 1rem;
            transition: all 0.3s ease;
        }

        .rule-card:hover {
            transform: translateX(10px);
            background: linear-gradient(135deg, rgba(31, 31, 31, 0.9) 0%, rgba(220, 38, 38, 0.1) 100%);
            box-shadow: 0 10px 30px rgba(220, 38, 38, 0.2);
        }

        /* Media Grid */
        .media-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .media-item {
            background: rgba(31, 31, 31, 0.8);
            border: 1px solid rgba(220, 38, 38, 0.2);
            border-radius: 12px;
            overflow: hidden;
            transition: all 0.3s ease;
        }

        .media-item:hover {
            transform: scale(1.05);
            border-color: var(--red-primary);
        }

        /* Footer */
        .footer {
            background: linear-gradient(135deg, rgba(0, 0, 0, 0.95) 0%, rgba(31, 31, 31, 0.95) 100%);
            border-top: 2px solid var(--red-primary);
            padding: 2rem 0;
            margin-top: 4rem;
        }

        /* Background Animation */
        .background-animation {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.05;
        }

        .floating-element {
            position: absolute;
            font-size: 2rem;
            color: var(--red-primary);
            animation: float 8s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            25% { transform: translateY(-20px) rotate(5deg); }
            50% { transform: translateY(-10px) rotate(-5deg); }
            75% { transform: translateY(-30px) rotate(3deg); }
        }

        /* Audio Controls */
        .audio-controls {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 1000;
        }

        /* Custom Emojis */
        .custom-emoji {
            display: inline-block;
            width: 20px;
            height: 20px;
            background-size: contain;
            vertical-align: middle;
        }

        .discord-emoji {
            background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="%235865F2"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057a.082.082 0 0 0 .031.057 19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>');
        }

        .website-emoji {
            background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="%23DC2626"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.94-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/></svg>');
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero-section h1 {
                font-size: 3rem !important;
            }

            .content-card {
                padding: 1.5rem;
            }

            .media-grid {
                grid-template-columns: 1fr;
            }

            .member-card {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
<!-- Loading Screen -->
<div id="loadingScreen" class="loading-screen">
    <div class="loading-logo logo-font">
        <img src="Imagens/Logo.webp" alt="LCDP" class="w-32 h-32 object-contain">
    </div>
    <div class="mt-8 text-white text-xl font-light">Loading...</div>
    <div class="mt-4 w-64 h-2 bg-gray-800 rounded-full overflow-hidden">
        <div id="loadingBar" class="h-full bg-gradient-to-r from-red-600 to-red-400 rounded-full transition-all duration-300" style="width: 0%"></div>
    </div>
</div>

<!-- Background Animation -->
<div class="background-animation">
    <div class="floating-element" style="top: 10%; left: 10%; animation-delay: 0s;">🎭</div>
    <div class="floating-element" style="top: 20%; right: 15%; animation-delay: 2s;">💰</div>
    <div class="floating-element" style="bottom: 30%; left: 20%; animation-delay: 4s;">🔫</div>
    <div class="floating-element" style="bottom: 10%; right: 10%; animation-delay: 1s;">💎</div>
    <div class="floating-element" style="top: 50%; left: 5%; animation-delay: 3s;">🎯</div>
    <div class="floating-element" style="top: 70%; right: 5%; animation-delay: 5s;">⚡</div>
</div>

<!-- Navigation -->
<nav class="navbar fixed top-0 left-0 right-0 z-50">
    <div class="container mx-auto px-6 py-4">
        <div class="flex items-center justify-between">
            <div class="flex items-center gap-3">
                <img src="Imagens/Logo.webp" alt="LCDP" class="w-8 h-8 object-contain">
                <div class="logo-font text-2xl font-bold text-red-500">LA CASA DE PAPEL</div>
            </div>
            <div class="hidden md:flex space-x-2">
                <button onclick="showPage('home')" class="nav-item text-white">Home</button>
                <button onclick="showPage('rules')" class="nav-item text-white">Rules</button>
                <button onclick="showPage('gameplay')" class="nav-item text-white">Gameplay</button>
                <button onclick="showPage('about')" class="nav-item text-white">About</button>
                <button onclick="showPage('members')" class="nav-item text-white">Members</button>
                <button onclick="showPage('applications')" class="nav-item text-white">Applications</button>
                <button onclick="showPage('developer')" class="nav-item text-white">Developer</button>
            </div>
            <div class="md:hidden">
                <button onclick="toggleMobileMenu()" class="text-white p-2">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
        <div id="mobileMenu" class="hidden md:hidden mt-4 space-y-2">
            <button onclick="showPage('home')" class="block w-full text-left nav-item text-white">Home</button>
            <button onclick="showPage('rules')" class="block w-full text-left nav-item text-white">Rules</button>
            <button onclick="showPage('gameplay')" class="block w-full text-left nav-item text-white">Gameplay</button>
            <button onclick="showPage('about')" class="block w-full text-left nav-item text-white">About</button>
            <button onclick="showPage('members')" class="block w-full text-left nav-item text-white">Members</button>
            <button onclick="showPage('applications')" class="block w-full text-left nav-item text-white">Applications</button>
            <button onclick="showPage('developer')" class="block w-full text-left nav-item text-white">Developer</button>
        </div>
    </div>
</nav>

<!-- Audio Controls -->
<div class="audio-controls">
    <button id="audioToggle" onclick="toggleAudio()" class="btn-primary px-4 py-2 rounded-full text-white font-medium">
        🔊 Audio ON
    </button>
</div>

<!-- Home Page -->
<div id="home" class="page active">
    <!-- Hero Section -->
    <section class="hero-section pt-24 pb-16">
        <div class="container mx-auto px-6 text-center relative z-10">
            <div class="flex items-center justify-center gap-8 mb-6">
                <img src="Imagens/Logo.webp" alt="LCDP" class="w-16 h-16 md:w-24 md:h-24 object-contain">
                <h1 class="logo-font text-6xl md:text-8xl font-black text-red-500">LA CASA DE PAPEL</h1>
                <img src="Imagens/Logo.webp" alt="LCDP" class="w-16 h-16 md:w-24 md:h-24 object-contain">
            </div>
            <p class="text-3xl md:text-4xl text-white font-light mb-4">Valrise Gaming Family</p>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto mb-8">
                Experience the thrill of the legendary heist series in SA-MP roleplay. Strategic planning, epic missions, and unforgettable adventures await.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="https://discord.gg/cNq4xTfsTD" target="_blank" class="btn-primary px-8 py-4 text-lg font-bold inline-flex items-center gap-2">
                    <span class="discord-emoji custom-emoji"></span>
                    Join Our Discord
                </a>
                <button onclick="playIntroVideo()" class="btn-primary px-8 py-4 text-lg font-bold">
                    <i class="fas fa-play mr-2"></i>
                    Watch Introduction
                </button>
            </div>
        </div>
    </section>

    <!-- Content Sections -->
    <div class="container mx-auto px-6 py-16">
        <!-- About Section -->
        <section class="mb-20">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">Welcome to the Family</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
            </div>
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h3 class="text-2xl font-bold text-red-400 mb-6">🎭 Our Mission</h3>
                    <p class="text-gray-300 text-lg leading-relaxed mb-6">
                        We bring the excitement and strategy of the legendary TV series into the world of SA-MP roleplay. Every heist is planned with precision, every move calculated, and every member plays a crucial role in our success.
                    </p>
                    <p class="text-gray-300 text-lg leading-relaxed">
                        Join us for epic heists, strategic planning, and become part of a family that values loyalty, intelligence, and teamwork above all else.
                    </p>
                </div>
                <div class="content-card text-center">
                    <h4 class="text-2xl font-bold text-red-400 mb-6">The Complete Family</h4>
                    <div class="aspect-video bg-black rounded-lg overflow-hidden border-2 border-red-500 mb-4">
                        <img src="Imagens/sa-mp-052.png" alt="LCDP Family Members" class="w-full h-full object-cover">
                    </div>
                    <p class="text-gray-400 italic">"Together we are unstoppable, divided we fall"</p>
                </div>
            </div>
        </section>

        <!-- Servers Section -->
        <section class="mb-20">
            <hr class="border-red-500 border-2 mb-12 opacity-50">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">La Casa de Papel Roleplay Servers</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="content-card">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 mr-4 bg-black rounded-lg border border-red-500 flex items-center justify-center">
                            <img src="Imagens/Valrise.jpg" alt="Valrise Gaming" class="w-12 h-12 object-contain">
                        </div>
                        <div>
                            <h3 class="text-2xl font-bold text-red-400">Valrise Gaming</h3>
                            <p class="text-gray-400">Primary Operations Base</p>
                        </div>
                    </div>
                    <p class="text-gray-300 mb-6">Our main headquarters where the most ambitious heists are planned and executed. Join our elite team of professionals.</p>
                    <div class="flex gap-4">
                        <a href="https://discord.gg/2K5n8YjrRU" target="_blank" class="btn-primary px-4 py-2 text-sm inline-flex items-center gap-2">
                            <span class="discord-emoji custom-emoji"></span>
                            Discord
                        </a>
                        <a href="https://valrisegaming.com/" target="_blank" class="btn-primary px-4 py-2 text-sm inline-flex items-center gap-2">
                            <span class="website-emoji custom-emoji"></span>
                            Website
                        </a>
                    </div>
                </div>
                <div class="content-card">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 mr-4 bg-black rounded-lg border border-red-500 flex items-center justify-center">
                            <img src="Imagens/Europa.jpg" alt="Europa Roleplay" class="w-12 h-12 object-contain">
                        </div>
                        <div>
                            <h3 class="text-2xl font-bold text-red-400">Europa Roleplay</h3>
                            <p class="text-gray-400">Secondary Operations</p>
                        </div>
                    </div>
                    <p class="text-gray-300 mb-6">Our European branch expanding the family's influence across different territories and bringing new opportunities.</p>
                    <div class="flex gap-4">
                        <a href="https://discord.gg/jTcrybmUtT" target="_blank" class="btn-primary px-4 py-2 text-sm inline-flex items-center gap-2">
                            <span class="discord-emoji custom-emoji"></span>
                            Discord
                        </a>
                        <a href="https://europa-rp.com" target="_blank" class="btn-primary px-4 py-2 text-sm inline-flex items-center gap-2">
                            <span class="website-emoji custom-emoji"></span>
                            Website
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Video Section -->
        <section class="text-center">
            <hr class="border-red-500 border-2 mb-12 opacity-50">
            <div class="content-card max-w-8xl mx-auto">
                <h2 class="text-3xl font-bold text-red-400 mb-6">🎬 Family Introduction</h2>
                <div class="aspect-video bg-black rounded-lg overflow-hidden border border-red-500">
                    <video controls class="w-full h-full object-cover" poster="Videos/La%20Casa%20de%20Papel%20%20My%20Life%20Is%20Going%20On%20-%20-%20Cecilia%20Krull%20(Vídeo%20Oficial).mp4">
                        <source src="Videos/La%20Casa%20de%20Papel%20%20My%20Life%20Is%20Going%20On%20-%20-%20Cecilia%20Krull%20(Vídeo%20Oficial).mp4" type="video/mp4">
                        <source src="Videos/La%20Casa%20de%20Papel%20%20My%20Life%20Is%20Going%20On%20-%20-%20Cecilia%20Krull%20(Vídeo%20Oficial).mp4" type="video/webm">
                        Your browser does not support the video tag.
                    </video>
                </div>
                <p class="text-gray-400 mt-4">
                    <i class="fas fa-info-circle mr-2"></i>
                    Background audio will pause automatically when video starts
                </p>
            </div>
        </section>
    </div>
</div>

<!-- Rules Page -->
<div id="rules" class="page">
    <div class="hero-section pt-24 pb-16">
        <div class="container mx-auto px-6 text-center relative z-10">
            <h1 class="logo-font text-5xl md:text-6xl font-black text-red-500 mb-6">FAMILY RULES</h1>
            <p class="text-xl text-gray-300 mb-4">The Code We Live By</p>
            <p class="text-lg text-gray-400 max-w-2xl mx-auto">
                These rules ensure our family operates with precision, loyalty, and respect. Follow them to remain part of our elite organization.
            </p>
        </div>
    </div>

    <div class="container mx-auto px-6 py-16">
        <div class="max-w-5xl mx-auto">
            <div class="grid gap-6">
                <div class="rule-card">
                    <div class="flex items-start gap-6">
                        <div class="flex-shrink-0">
                            <div class="w-16 h-16 bg-gradient-to-br from-red-500 to-red-700 rounded-full flex items-center justify-center text-white font-bold text-xl">1</div>
                        </div>
                        <div class="flex-1">
                            <h3 class="text-2xl font-bold text-white mb-3 flex items-center gap-3">
                                <i class="fas fa-crown text-red-400"></i>
                                Follow Professor's Orders
                            </h3>
                            <p class="text-gray-300 text-lg mb-2">Absolute obedience to leadership is essential for our operations.</p>
                            <div class="bg-red-900 bg-opacity-30 p-3 rounded-lg border-l-4 border-red-500">
                                <p class="text-red-300 font-semibold">⚠️ Consequence: Immediate Kick</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="rule-card">
                    <div class="flex items-start gap-6">
                        <div class="flex-shrink-0">
                            <div class="w-16 h-16 bg-gradient-to-br from-red-500 to-red-700 rounded-full flex items-center justify-center text-white font-bold text-xl">2</div>
                        </div>
                        <div class="flex-1">
                            <h3 class="text-2xl font-bold text-white mb-3 flex items-center gap-3">
                                <i class="fas fa-shield-alt text-red-400"></i>
                                Protect High Ranks
                            </h3>
                            <p class="text-gray-300 text-lg mb-2">High-ranking members are off-limits. Their safety is paramount.</p>
                            <div class="bg-red-900 bg-opacity-30 p-3 rounded-lg border-l-4 border-red-500">
                                <p class="text-red-300 font-semibold">⚠️ Consequence: Blacklist or Kick</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="rule-card">
                    <div class="flex items-start gap-6">
                        <div class="flex-shrink-0">
                            <div class="w-16 h-16 bg-gradient-to-br from-red-500 to-red-700 rounded-full flex items-center justify-center text-white font-bold text-xl">3</div>
                        </div>
                        <div class="flex-1">
                            <h3 class="text-2xl font-bold text-white mb-3 flex items-center gap-3">
                                <i class="fas fa-users text-red-400"></i>
                                Family First
                            </h3>
                            <p class="text-gray-300 text-lg mb-2">Never harm a family member. Resolve conflicts through proper channels.</p>
                            <div class="bg-yellow-900 bg-opacity-30 p-3 rounded-lg border-l-4 border-yellow-500">
                                <p class="text-yellow-300 font-semibold">💡 Solution: Report to High Ranks</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="rule-card">
                    <div class="flex items-start gap-6">
                        <div class="flex-shrink-0">
                            <div class="w-16 h-16 bg-gradient-to-br from-red-500 to-red-700 rounded-full flex items-center justify-center text-white font-bold text-xl">4</div>
                        </div>
                        <div class="flex-1">
                            <h3 class="text-2xl font-bold text-white mb-3 flex items-center gap-3">
                                <i class="fas fa-car text-red-400"></i>
                                Respect Base Property
                            </h3>
                            <p class="text-gray-300 text-lg mb-2">Our vehicles and equipment are valuable assets. Handle with care.</p>
                            <div class="bg-orange-900 bg-opacity-30 p-3 rounded-lg border-l-4 border-orange-500">
                                <p class="text-orange-300 font-semibold">⚠️ Consequence: Family Warning (1/2)</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="rule-card">
                    <div class="flex items-start gap-6">
                        <div class="flex-shrink-0">
                            <div class="w-16 h-16 bg-gradient-to-br from-red-500 to-red-700 rounded-full flex items-center justify-center text-white font-bold text-xl">5</div>
                        </div>
                        <div class="flex-1">
                            <h3 class="text-2xl font-bold text-white mb-3 flex items-center gap-3">
                                <i class="fas fa-handshake text-red-400"></i>
                                Maintain Respect
                            </h3>
                            <p class="text-gray-300 text-lg mb-2">Treat all family members with dignity and respect at all times.</p>
                            <div class="bg-gray-800 p-3 rounded-lg border-l-4 border-gray-500 mb-3">
                                <p class="text-gray-300"><strong>Definition:</strong> Disrespect includes insults, bullying, and mocking</p>
                            </div>
                            <div class="bg-red-900 bg-opacity-30 p-3 rounded-lg border-l-4 border-red-500">
                                <p class="text-red-300 font-semibold">⚠️ Consequence: Immediate Kick</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Important Note -->
            <div class="content-card mt-12 text-center">
                <div class="text-4xl mb-4">📋</div>
                <h3 class="text-2xl font-bold text-red-400 mb-4">Important Notice</h3>
                <p class="text-gray-300 text-lg">
                    These are the <strong class="text-white">5 fundamental rules</strong> that govern our family.
                    Additional rules may be added by High Ranks as our organization evolves.
                </p>
                <div class="mt-6 p-4 bg-red-900 bg-opacity-20 rounded-lg border border-red-500">
                    <p class="text-red-300 font-semibold">
                        <i class="fas fa-exclamation-triangle mr-2"></i>
                        Ignorance of these rules is not an excuse. All members are expected to know and follow them.
                    </p>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Gameplay Page -->
<div id="gameplay" class="page">
    <div class="hero-section pt-24 pb-16">
        <div class="container mx-auto px-6 text-center relative z-10">
            <h1 class="logo-font text-5xl md:text-6xl font-black text-red-500 mb-6">GAMEPLAY</h1>
            <p class="text-xl text-gray-300 mb-4">Experience the Heist</p>
            <p class="text-lg text-gray-400 max-w-2xl mx-auto">
                Witness our legendary operations across different servers. Strategic planning meets explosive action.
            </p>
        </div>
    </div>

    <div class="container mx-auto px-6 py-16">
        <!-- Server Selection -->
        <div class="grid md:grid-cols-2 gap-8 mb-16">
            <div class="content-card text-center">
                <div class="w-20 h-20 mx-auto mb-6 bg-black rounded-lg border border-red-500 flex items-center justify-center">
                    <img src="Imagens/Valrise.jpg" alt="Valrise Gaming" class="w-16 h-16 object-contain">
                </div>
                <h2 class="text-3xl font-bold text-red-400 mb-4">Valrise Gaming</h2>
                <p class="text-gray-300 mb-6">Our primary operations base with the most ambitious heists and strategic missions.</p>
                <button onclick="showGameplayContent('valrise')" class="btn-primary px-8 py-4 text-lg font-bold w-full">
                    <i class="fas fa-play mr-2"></i>
                    View Valrise Content
                </button>
            </div>

            <div class="content-card text-center">
                <div class="w-20 h-20 mx-auto mb-6 bg-black rounded-lg border border-red-500 flex items-center justify-center">
                    <img src="Imagens/Europa.jpg" alt="Europa Roleplay" class="w-16 h-16 object-contain">
                </div>
                <h2 class="text-3xl font-bold text-red-400 mb-4">Europa Roleplay</h2>
                <p class="text-gray-300 mb-6">European operations showcasing international heist coordination and teamwork.</p>
                <button onclick="showGameplayContent('europa')" class="btn-primary px-8 py-4 text-lg font-bold w-full">
                    <i class="fas fa-play mr-2"></i>
                    View Europa Content
                </button>
            </div>
        </div>

        <!-- Gameplay Content -->
        <div id="gameplayContent" class="hidden">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">Gameplay Highlights</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
            </div>
            <!-- Dynamic Videos Section -->
            <section class="mb-16">
                <h3 class="text-2xl font-bold text-red-400 mb-8 flex items-center gap-3">
                    <i class="fas fa-video text-red-500"></i>
                    Mission Videos
                </h3>
                <div id="videosGrid" class="media-grid">
                    <!-- Conteúdo será inserido via JavaScript -->
                </div>
            </section>

            <!-- Dynamic Photos Section -->
            <section class="mb-16">
                <h3 class="text-2xl font-bold text-red-400 mb-8 flex items-center gap-3">
                    <i class="fas fa-camera text-red-500"></i>
                    Mission Screenshots
                </h3>
                <div id="photosGrid" class="media-grid">
                    <!-- Conteúdo será inserido via JavaScript -->
                </div>
            </section>
            <!-- Mission Description -->
            <div class="content-card text-center">
                <div class="text-5xl mb-6">🎭</div>
                <h3 class="text-3xl font-bold text-red-400 mb-6">Real Missions Inspired by the TV Show</h3>
                <p class="text-gray-300 text-lg leading-relaxed max-w-4xl mx-auto">
                    Experience authentic La Casa de Papel missions with strategic planning, teamwork, and epic heists that bring the series to life in SA-MP roleplay.
                    Every operation is meticulously planned, every detail matters, and every family member plays a crucial role in our success.
                </p>
                <div class="grid md:grid-cols-3 gap-6 mt-8">
                    <div class="bg-red-900 bg-opacity-20 p-4 rounded-lg border border-red-500">
                        <i class="fas fa-brain text-red-400 text-2xl mb-2"></i>
                        <h4 class="text-white font-bold mb-2">Strategic Planning</h4>
                        <p class="text-gray-400 text-sm">Every heist begins with meticulous planning</p>
                    </div>
                    <div class="bg-red-900 bg-opacity-20 p-4 rounded-lg border border-red-500">
                        <i class="fas fa-users text-red-400 text-2xl mb-2"></i>
                        <h4 class="text-white font-bold mb-2">Team Coordination</h4>
                        <p class="text-gray-400 text-sm">Perfect synchronization between all members</p>
                    </div>
                    <div class="bg-red-900 bg-opacity-20 p-4 rounded-lg border border-red-500">
                        <i class="fas fa-trophy text-red-400 text-2xl mb-2"></i>
                        <h4 class="text-white font-bold mb-2">Epic Execution</h4>
                        <p class="text-gray-400 text-sm">Flawless execution of complex operations</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- About Page -->
<div id="about" class="page">
    <div class="hero-section pt-24 pb-16">
        <div class="container mx-auto px-6 text-center relative z-10">
            <h1 class="logo-font text-5xl md:text-6xl font-black text-red-500 mb-6">ABOUT THE FAMILY</h1>
            <p class="text-xl text-gray-300 mb-4">Our Legacy & Operations</p>
            <p class="text-lg text-gray-400 max-w-2xl mx-auto">
                Discover the history, vision, and strategic locations of La Casa de Papel family across the gaming world.
            </p>
        </div>
    </div>

    <div class="container mx-auto px-6 py-16">
        <!-- Family History -->
        <section class="mb-20">
            <div class="text-center mb-12">
                <div class="flex items-center justify-center gap-4 mb-4">
                    <img src="Imagens/Logo.webp" alt="LCDP" class="w-12 h-12 object-contain">
                    <h2 class="text-4xl font-bold text-white">Our Foundation</h2>
                </div>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
            </div>
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="content-card">
                    <div class="text-5xl mb-6 text-center"></div>
                    <h3 class="text-2xl font-bold text-red-400 mb-6">Family History</h3>
                    <div class="space-y-6 mb-6">
                        <div class="flex items-center justify-between p-4 bg-red-900 bg-opacity-20 rounded-lg border-l-4 border-red-500">
                            <span class="text-gray-300 font-medium">Founded:</span>
                            <span class="text-white font-bold text-xl">2024</span>
                        </div>
                        <div class="flex items-center justify-between p-4 bg-red-900 bg-opacity-20 rounded-lg border-l-4 border-red-500">
                            <span class="text-gray-300 font-medium">Founder:</span>
                            <span class="text-white font-bold">Lord Jazavicar</span>
                        </div>
                        <div class="flex items-center justify-between p-4 bg-red-900 bg-opacity-20 rounded-lg border-l-4 border-red-500">
                            <span class="text-gray-300 font-medium">Real Name:</span>
                            <span class="text-white font-bold">Kenneth_Jazavicar</span>
                        </div>
                    </div>
                    <div class="bg-black bg-opacity-40 p-4 rounded-lg border border-red-500">
                        <h4 class="text-lg font-bold text-red-400 mb-3">The Great Heist</h4>
                        <p class="text-gray-300 text-sm leading-relaxed">
                            After 11 years of preparation, on July 17, 2025, the plan began. LCDP members entered the bank, taking 5 hostages and holding them in the hall. Police couldn't attack due to hostage safety. For 10 hours, they printed money while negotiations failed against the Professor's brilliant strategies. Tony's escape plan was genius - hostages wore robber clothes with fake guns while real robbers pretended to be hostages. Police arrested the wrong people, and the real crew escaped with 2 trucks of money. Later, Tony used his connections to free the innocent hostages. The perfect heist - cops never found the real masterminds.
                        </p>
                    </div>
                </div>

                <div class="content-card text-center">
                    <h3 class="text-2xl font-bold text-red-400 mb-6">Our Family Members</h3>
                    <div class="aspect-square bg-black rounded-lg overflow-hidden border-2 border-red-500 mb-4">
                        <img src="Imagens/sa-mp-046.png" alt="All LCDP Family Members" class="w-full h-full object-cover">
                    </div>
                    <p class="text-gray-400 italic mb-4">"United we stand, divided we fall"</p>
                    <div class="bg-red-900 bg-opacity-20 p-4 rounded-lg border-l-4 border-red-500">
                        <p class="text-red-300 font-semibold text-sm">
                            <i class="fas fa-crown mr-2"></i>
                            Every member plays a crucial role in our success
                        </p>
                    </div>
                </div>

            </div>
        </section>

        <!-- Contact Information -->
        <section class="mb-20">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">Connect With Us</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="content-card">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 mr-4 bg-black rounded-lg border border-red-500 flex items-center justify-center">
                            <img src="Imagens/Valrise.jpg" alt="Valrise Gaming" class="w-12 h-12 object-contain">
                        </div>
                        <div>
                            <h3 class="text-2xl font-bold text-red-400">Valrise Gaming</h3>
                            <p class="text-gray-400">Primary Operations Hub</p>
                        </div>
                    </div>
                    <div class="space-y-4">
                        <a href="https://discord.gg/2K5n8YjrRU" target="_blank" class="flex items-center gap-3 p-3 bg-red-900 bg-opacity-20 rounded-lg border border-red-500 hover:bg-red-900 hover:bg-opacity-30 transition-all">
                            <span class="discord-emoji custom-emoji"></span>
                            <span class="text-white font-medium">Discord Server</span>
                            <i class="fas fa-external-link-alt text-red-400 ml-auto"></i>
                        </a>
                        <a href="https://valrisegaming.com/" target="_blank" class="flex items-center gap-3 p-3 bg-red-900 bg-opacity-20 rounded-lg border border-red-500 hover:bg-red-900 hover:bg-opacity-30 transition-all">
                            <span class="website-emoji custom-emoji"></span>
                            <span class="text-white font-medium">Official Website</span>
                            <i class="fas fa-external-link-alt text-red-400 ml-auto"></i>
                        </a>
                    </div>
                </div>
                <div class="content-card">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 mr-4 bg-black rounded-lg border border-red-500 flex items-center justify-center">
                            <img src="Imagens/Europa.jpg" alt="Europa Roleplay" class="w-12 h-12 object-contain">
                        </div>
                        <div>
                            <h3 class="text-2xl font-bold text-red-400">Europa Roleplay</h3>
                            <p class="text-gray-400">European Operations</p>
                        </div>
                    </div>
                    <div class="space-y-4">
                        <a href="https://discord.gg/jTcrybmUtT" target="_blank" class="flex items-center gap-3 p-3 bg-red-900 bg-opacity-20 rounded-lg border border-red-500 hover:bg-red-900 hover:bg-opacity-30 transition-all">
                            <span class="discord-emoji custom-emoji"></span>
                            <span class="text-white font-medium">Discord Server</span>
                            <i class="fas fa-external-link-alt text-red-400 ml-auto"></i>
                        </a>
                        <a href="https://europa-rp.com" target="_blank" class="flex items-center gap-3 p-3 bg-red-900 bg-opacity-20 rounded-lg border border-red-500 hover:bg-red-900 hover:bg-opacity-30 transition-all">
                            <span class="website-emoji custom-emoji"></span>
                            <span class="text-white font-medium">Official Website</span>
                            <i class="fas fa-external-link-alt text-red-400 ml-auto"></i>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Headquarters -->
        <section>
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">Our Headquarters</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="content-card">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 mx-auto mb-4 bg-black rounded-lg border border-red-500 flex items-center justify-center">
                            <img src="Imagens/Valrise.jpg" alt="Valrise HQ" class="w-16 h-16 object-contain">
                        </div>
                        <h3 class="text-2xl font-bold text-red-400">Valrise HQ</h3>
                    </div>
                    <div class="bg-red-900 bg-opacity-20 p-4 rounded-lg border border-red-500 mb-6">
                        <div class="flex items-center justify-center gap-3">
                            <i class="fas fa-map-marker-alt text-red-400"></i>
                            <span class="text-white font-bold">Located in LV (GPS 1812)</span>
                        </div>
                    </div>
                    <div class="aspect-square bg-black rounded-lg overflow-hidden border-2 border-red-500">
                        <img src="Imagens/HQ1.jpg" alt="Valrise Gaming Headquarters" class="w-full h-full object-cover">
                    </div>
                </div>
                <div class="content-card">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 mx-auto mb-4 bg-black rounded-lg border border-red-500 flex items-center justify-center">
                            <img src="Imagens/Europa.jpg" alt="Europa HQ" class="w-16 h-16 object-contain">
                        </div>
                        <h3 class="text-2xl font-bold text-red-400">Europa HQ</h3>
                    </div>
                    <div class="bg-red-900 bg-opacity-20 p-4 rounded-lg border border-red-500 mb-6">
                        <div class="flex items-center justify-center gap-3">
                            <i class="fas fa-eye-slash text-red-400"></i>
                            <span class="text-white font-bold">Secret Location</span>
                        </div>
                    </div>
                    <div class="aspect-square bg-black rounded-lg overflow-hidden border-2 border-red-500">
                        <img src="Imagens/HQ2.png" alt="Europa Roleplay Headquarters" class="w-full h-full object-cover">
                    </div>
                </div>
            </div>
        </section>
    </div>
</div>

<!-- Members Page -->
<div id="members" class="page">
    <div class="hero-section pt-24 pb-16">
        <div class="container mx-auto px-6 text-center relative z-10">
            <h1 class="logo-font text-5xl md:text-6xl font-black text-red-500 mb-6">FAMILY MEMBERS</h1>
            <p class="text-xl text-gray-300 mb-4">Meet the Elite Crew</p>
            <p class="text-lg text-gray-400 max-w-2xl mx-auto">
                Each member brings unique skills and expertise to our operations. Together, we form an unstoppable force.
            </p>
        </div>
    </div>

    <div class="container mx-auto px-6 py-16">
        <!-- Leadership -->
        <section class="mb-20">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">Leadership</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
            </div>
            <div class="max-w-2xl mx-auto">
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <img src="Imagens/PROFESSOR.jpg" alt="Kenneth Jazavicar" class="w-20 h-20 rounded-full object-cover">
                    </div>
                    <h3 class="text-2xl font-bold text-red-400 mb-2">The Professor</h3>
                    <p class="text-gray-300 font-medium mb-2">Kenneth Jazavicar</p>
                    <p class="text-yellow-400 font-bold mb-4">Rank 100</p>
                    <p class="text-gray-300 mb-4 leading-relaxed">
                        The mastermind behind all operations. Strategic genius who plans every detail with mathematical precision.
                        His vision transforms impossible heists into flawless executions.
                    </p>
                    <div class="bg-red-900 bg-opacity-20 p-4 rounded-lg border-l-4 border-red-500">
                        <p class="text-red-300 font-semibold italic text-lg">"Money is everything 💸"</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- High Command -->
        <section class="mb-20">
            <hr class="border-red-500 border-2 mb-12 opacity-50">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">High Command</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <img src="Imagens/Tony.png" alt="Tony Jazavicar" class="w-20 h-20 rounded-full object-cover">
                    </div>
                    <h3 class="text-xl font-bold text-red-400 mb-2">Mastermind</h3>
                    <p class="text-gray-300 font-medium mb-2">Tony Jazavicar</p>
                    <p class="text-yellow-400 font-bold mb-4">Rank 90</p>
                    <p class="text-gray-300 mb-4">
                        The Professor's cousin and most trusted ally. Acts as the visible leader while Kenneth remains in the shadows.
                    </p>
                    <div class="bg-red-900 bg-opacity-20 p-3 rounded-lg">
                        <p class="text-red-300 font-semibold italic">"Family first, always"</p>
                    </div>
                </div>
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <img src="Imagens/Pika.png" alt="Pika Kurn" class="w-20 h-20 rounded-full object-cover">
                    </div>
                    <h3 class="text-xl font-bold text-red-400 mb-2">The Right Hand</h3>
                    <p class="text-gray-300 font-medium mb-2">Pika Kurn</p>
                    <p class="text-yellow-400 font-bold mb-4">Rank 70</p>
                    <p class="text-gray-300 mb-4">
                        Trusted lieutenant ensuring all operations run smoothly and maintaining family discipline.
                    </p>
                    <div class="bg-red-900 bg-opacity-20 p-3 rounded-lg">
                        <p class="text-red-300 font-semibold italic">"Loyalty above all"</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Strategic Council -->
        <section class="mb-20">
            <hr class="border-red-500 border-2 mb-12 opacity-50">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">Strategic Council</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
                <p class="text-gray-400 mt-4">Elite strategists planning and coordinating all family operations</p>
            </div>
            <div class="grid md:grid-cols-3 gap-6">
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <img src="Imagens/Blaze.png" alt="Blaze Jazavicar" class="w-20 h-20 rounded-full object-cover">
                    </div>
                    <h3 class="text-lg font-bold text-red-400 mb-2">Strategic Alpha</h3>
                    <p class="text-gray-300 font-medium mb-2">Blaze Jazavicar</p>
                    <p class="text-yellow-400 font-bold mb-3">Rank 80</p>
                    <p class="text-gray-300 text-sm mb-3">Primary strategic planner specializing in complex heist operations and tactical coordination.</p>
                    <div class="bg-red-900 bg-opacity-20 p-2 rounded">
                        <p class="text-red-300 font-semibold italic text-sm">"Strategy wins wars"</p>
                    </div>
                </div>
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <img src="Imagens/Saki.png" alt="Saki Magic" class="w-20 h-20 rounded-full object-cover">
                    </div>
                    <h3 class="text-lg font-bold text-red-400 mb-2">Strategic Beta</h3>
                    <p class="text-gray-300 font-medium mb-2">Saki Magic</p>
                    <p class="text-yellow-400 font-bold mb-3">Rank 80</p>
                    <p class="text-gray-300 text-sm mb-3">Intelligence operations specialist ensuring perfect information flow and security.</p>
                    <div class="bg-red-900 bg-opacity-20 p-2 rounded">
                        <p class="text-red-300 font-semibold italic text-sm">"Knowledge is power"</p>
                    </div>
                </div>
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <img src="Imagens/Kaos.png" alt="Kaos Jazavicar" class="w-20 h-20 rounded-full object-cover">
                    </div>
                    <h3 class="text-lg font-bold text-red-400 mb-2">Strategic Gamma</h3>
                    <p class="text-gray-300 font-medium mb-2">Kaos Jazavicar</p>
                    <p class="text-yellow-400 font-bold mb-3">Rank 80</p>
                    <p class="text-gray-300 text-sm mb-3">Tactical operations expert handling field coordination and emergency protocols.</p>
                    <div class="bg-red-900 bg-opacity-20 p-2 rounded">
                        <p class="text-red-300 font-semibold italic text-sm">"Chaos controlled"</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Right Hand Operations -->
        <section class="mb-20">
            <hr class="border-red-500 border-2 mb-12 opacity-50">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">Right Hand Operations</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
                <p class="text-gray-400 mt-4">Trusted lieutenants ensuring operational excellence</p>
            </div>
            <div class="max-w-2xl mx-auto">
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <img src="Imagens/Kisaki.png" alt="Kisaki Tetta" class="w-20 h-20 rounded-full object-cover">
                    </div>
                    <h3 class="text-xl font-bold text-red-400 mb-2">The Right Hand</h3>
                    <p class="text-gray-300 font-medium mb-2">Kisaki Tetta</p>
                    <p class="text-yellow-400 font-bold mb-4">Rank 70</p>
                    <p class="text-gray-300 mb-4 leading-relaxed">
                        Secondary right hand ensuring backup leadership and maintaining operational continuity during critical missions.
                    </p>
                    <div class="bg-red-900 bg-opacity-20 p-4 rounded-lg border-l-4 border-red-500">
                        <p class="text-red-300 font-semibold italic text-lg">"Backup is everything"</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Prime Members -->
        <section>
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">Prime Operatives</h2>
                <div class="w-24 h-1 bg-red-500 mx-auto"></div>
                <p class="text-gray-400 mt-4">Elite members with prime responsibilities and specialized skills</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <i class="fas fa-diamond text-white"></i>
                    </div>
                    <h3 class="text-lg font-bold text-red-400 mb-2">Prime Alpha</h3>
                    <p class="text-gray-300 font-medium mb-3">Member Name</p>
                    <p class="text-gray-300 text-sm mb-3">Advanced reconnaissance and surveillance operations.</p>
                    <div class="bg-red-900 bg-opacity-20 p-2 rounded">
                        <p class="text-red-300 font-semibold italic text-sm">"Eyes everywhere"</p>
                    </div>
                </div>
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <i class="fas fa-bolt text-white"></i>
                    </div>
                    <h3 class="text-lg font-bold text-red-400 mb-2">Prime Beta</h3>
                    <p class="text-gray-300 font-medium mb-3">Member Name</p>
                    <p class="text-gray-300 text-sm mb-3">Rapid response and emergency operations specialist.</p>
                    <div class="bg-red-900 bg-opacity-20 p-2 rounded">
                        <p class="text-red-300 font-semibold italic text-sm">"Speed is life"</p>
                    </div>
                </div>
                <div class="member-card text-center">
                    <div class="member-avatar">
                        <i class="fas fa-cog text-white"></i>
                    </div>
                    <h3 class="text-lg font-bold text-red-400 mb-2">Prime Gamma (0) Actually</h3>
                    <p class="text-gray-300 font-medium mb-3">Member Name</p>
                    <p class="text-gray-300 text-sm mb-3">Technical operations and equipment management expert. Actually 0 Primes </p>
                    <div class="bg-red-900 bg-opacity-20 p-2 rounded">
                        <p class="text-red-300 font-semibold italic text-sm">"Technology wins"</p>
                    </div>
                </div>
            </div>
        </section>
    </div>
</div>

<!-- Applications Page -->
<div id="applications" class="page">
    <div class="hero-section pt-24 pb-16">
        <div class="container mx-auto px-6 text-center relative z-10">
            <h1 class="logo-font text-5xl md:text-6xl font-black text-red-500 mb-6">JOIN THE FAMILY</h1>
            <p class="text-2xl text-gray-300 mb-4">Ready for the Ultimate Heist?</p>
            <p class="text-lg text-gray-400 max-w-2xl mx-auto">
                Do you have what it takes to join the most elite heist crew? Prove your worth and become part of La Casa de Papel family.
            </p>
        </div>
    </div>

    <div class="container mx-auto px-6 py-16">
        <div class="max-w-4xl mx-auto">
            <!-- Requirements Section -->
            <section class="mb-16">
                <div class="text-center mb-12">
                    <h2 class="text-4xl font-bold text-white mb-4">Requirements</h2>
                    <div class="w-24 h-1 bg-red-500 mx-auto"></div>
                    <p class="text-gray-400 mt-4">Meet these criteria to be considered for our elite operations</p>
                </div>

                <div class="grid md:grid-cols-2 gap-6">
                    <div class="content-card">
                        <div class="flex items-center mb-4">
                            <div class="text-4xl mr-4">🧠</div>
                            <div>
                                <h3 class="text-xl font-bold text-red-400">Strategic Planner</h3>
                                <p class="text-gray-400">Master of tactical thinking</p>
                            </div>
                        </div>
                        <p class="text-gray-300">
                            Demonstrate exceptional strategic thinking and planning abilities. Every heist requires meticulous preparation and foresight.
                        </p>
                    </div>

                    <div class="content-card">
                        <div class="flex items-center mb-4">
                            <div class="text-4xl mr-4">🤝</div>
                            <div>
                                <h3 class="text-xl font-bold text-red-400">Team Player</h3>
                                <p class="text-gray-400">Respect the hierarchy</p>
                            </div>
                        </div>
                        <p class="text-gray-300">
                            Show absolute loyalty and respect for leadership. Follow orders without question and maintain family unity at all times.
                        </p>
                    </div>

                    <div class="content-card">
                        <div class="flex items-center mb-4">
                            <div class="text-4xl mr-4">🎯</div>
                            <div>
                                <h3 class="text-xl font-bold text-red-400">Combat Ready</h3>
                                <p class="text-gray-400">Weapon proficiency required</p>
                            </div>
                        </div>
                        <p class="text-gray-300">
                            Possess excellent marksmanship and combat skills. Be prepared to defend the family and execute operations with precision.
                        </p>
                    </div>

                    <div class="content-card">
                        <div class="flex items-center mb-4">
                            <div class="text-4xl mr-4">🚁</div>
                            <div>
                                <h3 class="text-xl font-bold text-red-400">Vehicle Expert</h3>
                                <p class="text-gray-400">Multi-vehicle proficiency</p>
                            </div>
                        </div>
                        <p class="text-gray-300">
                            Master various vehicles including cars, motorcycles, helicopters, and planes. Mobility is crucial for successful operations.
                        </p>
                    </div>
                </div>
            </section>

            <!-- Application Process -->
            <section class="text-center">
                <div class="content-card max-w-2xl mx-auto">
                    <div class="text-5xl mb-6">🎭</div>
                    <h2 class="text-3xl font-bold text-red-400 mb-6">Ready to Apply?</h2>
                    <p class="text-gray-300 text-lg mb-8 leading-relaxed">
                        Join our Discord server to begin your application process. Our recruitment team will evaluate your skills and determine if you have what it takes to join our legendary crew.
                    </p>
                    <a href="https://discord.gg/cNq4xTfsTD" target="_blank" class="btn-primary px-12 py-6 text-2xl font-bold inline-flex items-center gap-3">
                        <span class="discord-emoji custom-emoji"></span>
                        Join Us
                    </a>
                    <p class="text-gray-400 mt-6">
                        <i class="fas fa-info-circle mr-2"></i>
                        Click to join our Discord and start your journey to becoming a family member
                    </p>
                </div>
            </section>
        </div>
    </div>
</div>

<!-- Developer Page -->
<div id="developer" class="page">
    <div class="hero-section pt-24 pb-16">
        <div class="container mx-auto px-6 text-center relative z-10">
            <h1 class="logo-font text-5xl md:text-6xl font-black text-red-500 mb-6">DEVELOPER</h1>
            <p class="text-xl text-gray-300 mb-4">The Architect Behind the Code</p>
            <p class="text-lg text-gray-400 max-w-2xl mx-auto">
                Meet the mastermind who brought this digital experience to life with precision and creativity.
            </p>
        </div>
    </div>

    <div class="container mx-auto px-6 py-16">
        <div class="max-w-3xl mx-auto">
            <div class="content-card text-center">
                <div class="mb-8">
                    <div class="w-40 h-40 bg-gradient-to-br from-red-500 via-red-600 to-red-700 rounded-full mx-auto flex items-center justify-center border-4 border-gold shadow-2xl overflow-hidden cursor-pointer transform transition-all duration-300 hover:scale-105" onclick="animateDeveloperCard()">
                        <img src="Imagens/Walter.png" alt="Walter White" class="w-full h-full object-cover">
                    </div>
                </div>

                <h2 class="text-5xl font-bold text-red-400 mb-4">Walter White</h2>
                <p class="text-2xl text-gray-300 mb-8">Full Stack Developer & Digital Architect</p>

                <div class="flex justify-center gap-4 mb-8">
                    <a href="https://discord.com/users/quirson_ngale" target="_blank" class="bg-red-900 bg-opacity-20 px-6 py-3 rounded-lg border border-red-500 hover:bg-red-900 hover:bg-opacity-40 transition-all cursor-pointer transform hover:scale-105 flex items-center gap-2">
                        <span class="discord-emoji custom-emoji"></span>
                        <span class="text-white font-semibold">Discord</span>
                    </a>

                    <a href="https://quirson.github.io/Portfolio/#" target="_blank" class="bg-red-900 bg-opacity-20 px-6 py-3 rounded-lg border border-red-500 hover:bg-red-900 hover:bg-opacity-40 transition-all cursor-pointer transform hover:scale-105 flex items-center gap-2">
                        <span class="website-emoji custom-emoji"></span>
                        <span class="text-white font-semibold">Portfolio</span>
                    </a>
                </div>

                <div class="bg-red-900 bg-opacity-10 p-8 rounded-lg border-l-4 border-red-500">
                    <p class="text-gray-300 text-xl italic leading-relaxed">
                        "Simplicity is the soul of efficiency"
                    </p>
                    <p class="text-gray-400 mt-4">
                        Crafting digital experiences with precision, passion, and a touch of genius. Every line of code tells a story, every design choice serves a purpose.
                    </p>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Footer -->
<footer class="footer">
    <div class="container mx-auto px-6">
        <div class="text-center">
            <div class="mb-6">
                <div class="logo-font text-2xl font-bold text-red-500 mb-2">LA CASA DE PAPEL</div>
                <p class="text-gray-400">Valrise Gaming Family</p>
            </div>
            <div class="border-t border-red-800 pt-6">
                <p class="text-gray-300 mb-2">
                    © 2024 La Casa de Papel – All rights reserved.
                </p>
                <p class="text-gray-400">
                    Developed with much ♥ by
                    <a href="https://quirson.github.io/Portfolio/#" target="_blank" class="text-red-400 hover:text-red-300 font-semibold">
                        Walter White
                    </a>
                    – "Simplicity is the soul of efficiency"
                </p>
            </div>
        </div>
    </div>
</footer>

<!-- Audio Element -->
<audio id="backgroundAudio" loop>
    <source src="Musicas/La%20Casa%20de%20Papel%20_%20My%20Life%20Is%20Going%20On%20-%20-%20Cecilia%20Krull%20(Vídeo%20Oficial)%20%5BF1oHBcTdKL4%5D.mp3" type="audio/mpeg">
</audio>

<script>
    let currentPage = 'home';
    let audioPlaying = false;
    let backgroundAudio = document.getElementById('backgroundAudio');

    // AutoPlay
    // Set audio volume and prepare for autoplay
    backgroundAudio.volume = 0.7; // Ajuste o volume se quiser (0.0 a 1.0)
    backgroundAudio.preload = 'auto';

    // Try to enable autoplay on page load
    document.addEventListener('DOMContentLoaded', function() {
        // Enable autoplay policy bypass attempts
        backgroundAudio.muted = false;

        // Try immediate play
        setTimeout(() => {
            if (!audioPlaying) {
                backgroundAudio.play().then(() => {
                    audioPlaying = true;
                    updateAudioButton();
                }).catch(e => {
                    console.log('Immediate autoplay blocked, waiting for user interaction');
                });
            }
        }, 1000);
    });

    // Loading Screen Animation
    window.addEventListener('load', function() {
        let progress = 0;
        const loadingBar = document.getElementById('loadingBar');
        const loadingScreen = document.getElementById('loadingScreen');

        const loadingInterval = setInterval(() => {
            progress += Math.random() * 15;
            if (progress >= 100) {
                progress = 100;
                clearInterval(loadingInterval);

                setTimeout(() => {
                    gsap.to(loadingScreen, {
                        opacity: 0,
                        duration: 1,
                        onComplete: () => {
                            loadingScreen.style.display = 'none';
                            startBackgroundAudio();
                            initializeAnimations();
                        }
                    });
                }, 500);
            }
            loadingBar.style.width = progress + '%';
        }, 100);
    });

    // Audio Functions
    function startBackgroundAudio() {
        backgroundAudio.play().then(() => {
            audioPlaying = true;
            updateAudioButton();
        }).catch(e => {
            console.log('Audio autoplay prevented');
            // Try to play on first user interaction
            document.addEventListener('click', function startOnClick() {
                backgroundAudio.play().then(() => {
                    audioPlaying = true;
                    updateAudioButton();
                    document.removeEventListener('click', startOnClick);
                }).catch(err => console.log('Audio play failed'));
            }, { once: true });

            document.addEventListener('keydown', function startOnKey() {
                backgroundAudio.play().then(() => {
                    audioPlaying = true;
                    updateAudioButton();
                    document.removeEventListener('keydown', startOnKey);
                }).catch(err => console.log('Audio play failed'));
            }, { once: true });
        });
    }

    function toggleAudio() {
        if (audioPlaying) {
            backgroundAudio.pause();
            audioPlaying = false;
        } else {
            if (currentPage !== 'gameplay') {
                backgroundAudio.play().catch(e => console.log('Audio play failed'));
                audioPlaying = true;
            }
        }
        updateAudioButton();
    }

    function updateAudioButton() {
        const button = document.getElementById('audioToggle');
        button.innerHTML = audioPlaying ? '<i class="fas fa-volume-up mr-2"></i>Audio ON' : '<i class="fas fa-volume-mute mr-2"></i>Audio OFF';
    }

    // Page Navigation
    function showPage(pageId) {
        // Hide all pages with fade out
        document.querySelectorAll('.page').forEach(page => {
            if (page.classList.contains('active')) {
                gsap.to(page, {
                    opacity: 0,
                    duration: 0.3,
                    onComplete: () => {
                        page.classList.remove('active');
                    }
                });
            }
        });

        // Show selected page with fade in
        setTimeout(() => {
            const targetPage = document.getElementById(pageId);
            targetPage.classList.add('active');
            gsap.fromTo(targetPage,
                { opacity: 0 },
                { opacity: 1, duration: 0.5 }
            );
            currentPage = pageId;

            // Handle audio based on page
            // Handle audio based on page
            if (pageId === 'gameplay') {
                backgroundAudio.pause();
                audioPlaying = false;
            } else {
                if (!audioPlaying) {
                    backgroundAudio.play().catch(e => console.log('Audio play failed'));
                    audioPlaying = true;
                }
            }
            updateAudioButton();

            // Close mobile menu
            document.getElementById('mobileMenu').classList.add('hidden');

            // Scroll to top
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }, 300);
    }

    // Mobile Menu Toggle
    function toggleMobileMenu() {
        const mobileMenu = document.getElementById('mobileMenu');
        mobileMenu.classList.toggle('hidden');

        if (!mobileMenu.classList.contains('hidden')) {
            gsap.fromTo(mobileMenu,
                { opacity: 0, y: -20 },
                { opacity: 1, y: 0, duration: 0.3 }
            );
        }
    }

    // Gameplay Content
    function showGameplayContent(server) {
        const content = document.getElementById('gameplayContent');
        content.classList.remove('hidden');

        // Videos por servidor
        const videosData = {
            valrise: [
                { src: 'Videos/EUVAL.mp4', title: 'Valrise Bank Heist', desc: 'Epic Valrise bank robbery operation' },
                { src: 'Videos/VAL1.mp4', title: 'Valrise Teamwork', desc: 'Perfect Valrise family coordination' },
                { src: 'Videos/VAL2.mp4', title: 'Valrise Great Escape', desc: 'Valrise thrilling escape sequences' }
            ],
            europa: [
                { src: 'Videos/EUVAL.mp4', title: 'Europa Bank Heist', desc: 'Strategic Europa bank operation' },
                { src: 'Videos/LC1.mp4', title: 'Europa Teamwork', desc: 'Europa family perfect sync' },
                { src: 'Videos/LC2.mp4', title: 'Europa Great Escape', desc: 'Europa epic getaway scenes' }
            ]
        };

        // Imagens por servidor
        const photosData = {
            valrise: [
                { src: 'Imagens/LC1.png', title: 'Valrise Strategic Meeting', desc: 'Planning at Valrise HQ' },
                { src: 'Imagens/LC2.png', title: 'Valrise Mission Progress', desc: 'Active Valrise operation' },
                { src: 'Imagens/LC3.png', title: 'Valrise Success', desc: 'Celebrating Valrise victory' },
                { src: 'Imagens/LC4.png', title: 'Valrise Headquarters', desc: 'Valrise secure base' }
            ],
            europa: [
                { src: 'Imagens/EU1.jpg', title: 'Europa Strategic Meeting', desc: 'Planning at Europa HQ' },
                { src: 'Imagens/EU2.jpg', title: 'Europa Mission Progress', desc: 'Active Europa operation' },
                { src: 'Imagens/EU3.png', title: 'Europa Success', desc: 'Celebrating Europa victory' },
                { src: 'Imagens/EU4.jpg', title: 'Europa Headquarters', desc: 'Europa secure base' }
            ]
        };

        // Inserir vídeos
        const videosGrid = document.getElementById('videosGrid');
        videosGrid.innerHTML = videosData[server].map(video => `
        <div class="media-item">
            <div class="aspect-video bg-black overflow-hidden border-b border-red-500">
                <video controls class="w-full h-full object-cover">
                    <source src="${video.src}" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
            <div class="p-4">
                <h4 class="text-lg font-bold text-white mb-2">${video.title}</h4>
                <p class="text-gray-400 text-sm">${video.desc}</p>
            </div>
        </div>
    `).join('');

        // Inserir fotos
        const photosGrid = document.getElementById('photosGrid');
        photosGrid.innerHTML = photosData[server].map(photo => `
        <div class="media-item">
            <div class="aspect-video bg-black overflow-hidden border-b border-red-500">
                <img src="${photo.src}" alt="${photo.title}" class="w-full h-full object-cover">
            </div>
            <div class="p-4">
                <h4 class="text-lg font-bold text-white mb-2">${photo.title}</h4>
                <p class="text-gray-400 text-sm">${photo.desc}</p>
            </div>
        </div>
    `).join('');

        // Update title
        const title = content.querySelector('h2');
        title.textContent = `${server === 'valrise' ? 'Valrise Gaming' : 'Europa Roleplay'} Highlights`;

        // Animações
        gsap.fromTo(content, { opacity: 0, y: 30 }, { opacity: 1, y: 0, duration: 0.6 });
        gsap.fromTo('.media-item', { opacity: 0, scale: 0.9 }, { opacity: 1, scale: 1, duration: 0.4, stagger: 0.1, delay: 0.3 });
    }

    // Initialize Animations
    function initializeAnimations() {
        // Animate floating elements
        gsap.to('.floating-element', {
            y: -30,
            rotation: 10,
            duration: 4,
            ease: 'power2.inOut',
            yoyo: true,
            repeat: -1,
            stagger: 0.5
        });

        // Animate content cards on scroll
        gsap.utils.toArray('.content-card').forEach(card => {
            gsap.fromTo(card,
                { opacity: 0, y: 50 },
                {
                    opacity: 1,
                    y: 0,
                    duration: 0.8,
                    scrollTrigger: {
                        trigger: card,
                        start: 'top 85%',
                        end: 'bottom 15%',
                        toggleActions: 'play none none reverse'
                    }
                }
            );
        });

        // Animate member cards
        gsap.utils.toArray('.member-card').forEach((card, index) => {
            gsap.fromTo(card,
                { opacity: 0, scale: 0.9 },
                {
                    opacity: 1,
                    scale: 1,
                    duration: 0.6,
                    delay: index * 0.1,
                    scrollTrigger: {
                        trigger: card,
                        start: 'top 85%',
                        toggleActions: 'play none none reverse'
                    }
                }
            );
        });

        // Animate rule cards
        gsap.utils.toArray('.rule-card').forEach((card, index) => {
            gsap.fromTo(card,
                { opacity: 0, x: -50 },
                {
                    opacity: 1,
                    x: 0,
                    duration: 0.6,
                    delay: index * 0.1,
                    scrollTrigger: {
                        trigger: card,
                        start: 'top 85%',
                        toggleActions: 'play none none reverse'
                    }
                }
            );
        });
    }

    // Close mobile menu when clicking outside
    document.addEventListener('click', function(event) {
        const mobileMenu = document.getElementById('mobileMenu');
        const menuButton = event.target.closest('button[onclick="toggleMobileMenu()"]');

        if (!mobileMenu.contains(event.target) && !menuButton && !mobileMenu.classList.contains('hidden')) {
            mobileMenu.classList.add('hidden');
        }
    });

    // Smooth scroll for internal links
    document.addEventListener('DOMContentLoaded', function() {
        // Add hover effects to buttons
        document.querySelectorAll('.btn-primary').forEach(button => {
            button.addEventListener('mouseenter', function() {
                gsap.to(this, { scale: 1.05, duration: 0.2 });
            });

            button.addEventListener('mouseleave', function() {
                gsap.to(this, { scale: 1, duration: 0.2 });
            });
        });

        // Add click effects to nav items
        document.querySelectorAll('.nav-item').forEach(item => {
            item.addEventListener('click', function() {
                gsap.fromTo(this,
                    { scale: 0.95 },
                    { scale: 1, duration: 0.2 }
                );
            });
        });
    });

    // Developer Card Animation
    function animateDeveloperCard() {
        const card = document.querySelector('.w-40.h-40');
        gsap.to(card, {
            rotation: 360,
            scale: 1.1,
            duration: 0.8,
            ease: 'power2.out',
            onComplete: () => {
                gsap.to(card, {
                    rotation: 0,
                    scale: 1,
                    duration: 0.3
                });
            }
        });
    }

    // Keyboard navigation
    document.addEventListener('keydown', function(event) {
        if (event.key === 'Escape') {
            // Close mobile menu
            document.getElementById('mobileMenu').classList.add('hidden');

            // Close video modal
            const modal = document.querySelector('.fixed.inset-0');
            if (modal) {
                closeVideoModal();
            }
        }
    });
    // Auto pause/resume audio when videos play/pause
    document.addEventListener('DOMContentLoaded', function() {
        // Function to handle video events
        function handleVideoEvents() {
            const videos = document.querySelectorAll('video');

            videos.forEach(video => {
                video.addEventListener('play', function() {
                    if (audioPlaying) {
                        backgroundAudio.pause();
                    }
                });

                video.addEventListener('pause', function() {
                    if (audioPlaying && currentPage !== 'gameplay') {
                        backgroundAudio.play().catch(e => console.log('Audio resume failed'));
                    }
                });

                video.addEventListener('ended', function() {
                    if (audioPlaying && currentPage !== 'gameplay') {
                        backgroundAudio.play().catch(e => console.log('Audio resume failed'));
                    }
                });
            });
        }

        // Initial setup
        handleVideoEvents();

        // Re-setup when gameplay content is loaded
        const originalShowGameplayContent = window.showGameplayContent;
        window.showGameplayContent = function(server) {
            originalShowGameplayContent(server);
            setTimeout(handleVideoEvents, 100); // Small delay to ensure content is loaded
        };
    });
</script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9680a8dae0b4dd69',t:'MTc1NDAwMjI3OC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
