<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Zengo Play | Games On, Stress Gone</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        /* Full screen optimization */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
          html, body {
            min-height: 100vh;
            width: 100%;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }
        body { 
            background-color: #F5F1E9; 
            color: #1E3A8A; 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
        }
        .hero-gradient { 
            background: linear-gradient(135deg, #1E3A8A 0%, #3B82F6 100%);
            min-height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .accent-beige { 
            background-color: #E7E0D2; 
        }
        .card-shadow { 
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card-shadow:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .fullscreen-section {
            min-height: 100vh;
            padding: 4rem 1.5rem;
        }
        /* Mobile menu */
        .mobile-menu {
            display: none;
        }
        @media (max-width: 768px) {
            .mobile-menu {
                display: block;
            }  
            .desktop-menu {
                display: none;
            }
            .hero-gradient h2 {
                font-size: 2.5rem;
            }
        }
        /* Full screen button styles */
        #fullscreen-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 1000;
            background: #1E3A8A;
            color: white;
            border: none;
            border-radius: 50%;
            width: 50px;
            height: 50px;
            cursor: pointer;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
        #fullscreen-btn:hover {
            background: #3B82F6;
            transform: scale(1.1);
        }
    </style>
</head>
<body class="antialiased">
    <!-- Mobile Menu Button -->
    <button id="mobile-menu-btn" class="mobile-menu fixed top-6 right-6 z-50 md:hidden bg-blue-600 text-white p-3 rounded-lg">
        <i class="fas fa-bars"></i>
    </button>
    <!-- Mobile Menu Overlay -->
    <div id="mobile-menu-overlay" class="mobile-menu fixed inset-0 bg-white z-40 hidden flex-col justify-center items-center space-y-8">
        <button id="close-menu" class="absolute top-6 right-6 text-2xl">
            <i class="fas fa-times"></i>
        </button>
        <a href="#about" class="text-2xl font-bold hover:text-blue-600">What is Zengo?</a>
        <a href="#games" class="text-2xl font-bold hover:text-blue-600">Activities</a>
        <a href="#benefits" class="text-2xl font-bold hover:text-blue-600">Benefits</a>
        <a href="#digital" class="text-2xl font-bold hover:text-blue-600">Digital Sanctuary</a>
        <button class="bg-blue-600 text-white px-8 py-3 rounded-full font-bold hover:bg-blue-700 transition mt-4">Enter Lab</button>
    </div>
    <nav class="p-6 flex justify-between items-center bg-white shadow-sm fixed w-full z-30">
        <h1 class="text-2xl font-bold tracking-tighter uppercase">Zengo <span class="text-blue-600">Play</span></h1>
        <div class="desktop-menu hidden md:flex space-x-8 font-medium">
            <a href="#about" class="hover:text-blue-600 transition-colors">What is Zengo?</a>
            <a href="#games" class="hover:text-blue-600 transition-colors">Activities</a>
            <a href="#benefits" class="hover:text-blue-600 transition-colors">Benefits</a>
            <a href="#digital" class="hover:text-blue-600 transition-colors">Digital Sanctuary</a>
        </div>
        <button class="hidden md:block bg-blue-600 text-white px-6 py-2 rounded-full font-bold hover:bg-blue-700 transition">Enter Lab</button>
    </nav>
    <!-- Add spacing for fixed nav -->
    <div class="pt-20"></div>
    <header class="hero-gradient text-white px-6 text-center fullscreen-section">
        <h2 class="text-5xl md:text-7xl font-extrabold mb-4 uppercase tracking-tight">Games On, Stress Gone</h2>
        <p class="text-xl md:text-2xl mb-8 opacity-90 max-w-2xl mx-auto">Relaxation Meets Recreation. Find your "off switch" through the power of play.</p>
        <div class="flex flex-col sm:flex-row justify-center gap-4">
            <a href="#games" class="bg-white text-blue-900 px-8 py-3 rounded-lg font-bold hover:bg-opacity-90 transition">Explore Games</a>
            <a href="#help" class="border-2 border-white px-8 py-3 rounded-lg font-bold hover:bg-white hover:text-blue-900 transition">Get Help Now</a>
        </div>
    </header>
    <section id="about" class="fullscreen-section px-6 max-w-5xl mx-auto text-center flex flex-col justify-center">
        <h3 class="text-3xl font-bold mb-6">What is Zengo Play?</h3>
        <p class="text-lg leading-relaxed text-gray-700 mb-6">
            In a world that never stops moving, Zengo Play provides a dedicated sanctuary for your mind. 
            We believe gaming is a vital tool for mental restoration, helping to reduce cortisol levels and quiet daily anxiety.
        </p>
        <div class="italic font-bold text-blue-600 text-xl uppercase tracking-widest">Stress • Play • Repeat</div>
    </section>
    <section id="games" class="accent-beige fullscreen-section px-6">
        <div class="max-w-6xl mx-auto text-center flex flex-col justify-center">
            <h3 class="text-4xl font-bold mb-12">Active Recovery Modes</h3>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-2xl card-shadow">
                    <div class="text-4xl mb-4">🎈</div>
                    <h4 class="text-xl font-bold mb-4">1. Balloon Pop</h4>
                    <p class="text-sm text-gray-600">Engage in rapid-response targeting to sharpen hand-eye coordination and release pent-up tension.</p>
                </div>
                <div class="bg-white p-8 rounded-2xl card-shadow">
                    <div class="text-4xl mb-4">⭕</div>
                    <h4 class="text-xl font-bold mb-4">2. Ring Toss</h4>
                    <p class="text-sm text-gray-600">Shift into a 'Flow State' by calibrating spatial awareness and focusing on trajectory and force.</p>
                </div>
                <div class="bg-white p-8 rounded-2xl card-shadow">
                    <div class="text-4xl mb-4">🎲</div>
                    <h4 class="text-xl font-bold mb-4">3. Lucky Dice</h4>
                    <p class="text-sm text-gray-600">Stimulate the prefrontal cortex by analyzing risk and reward in a low-stakes environment.</p>
                </div>
            </div>
        </div>
    </section>
    <section id="digital" class="fullscreen-section px-6 max-w-6xl mx-auto flex items-center">
        <div class="flex flex-col md:flex-row items-center gap-12">
            <div class="md:w-1/2">
                <h3 class="text-4xl font-bold mb-6">The Digital Sanctuary</h3>
                <p class="text-lg text-gray-700 mb-6">
                    Our online platform is available 24/7, fitting easily into your daily routine—whether you are in the library, your room, or commuting.
                </p>
                <ul class="space-y-4">
                <li class="flex items-center gap-3">
                        <i class="fas fa-check-circle text-blue-600"></i>
                        <span><strong>Safe Space:</strong> Share thoughts anonymously.</span>
                    </li>
                    <li class="flex items-center gap-3">
                        <i class="fas fa-check-circle text-blue-600"></i>
                        <span><strong>Guided Breathing:</strong> Visuals to calm the body.</span>
                    </li>
                    <li class="flex items-center gap-3">
                        <i class="fas fa-check-circle text-blue-600"></i>
                        <span><strong>Progress Tracking:</strong> Monitor your mental wellness journey.</span>
                    </li>
                </ul>
            </div>
            <div class="md:w-1/2 bg-blue-100 p-10 rounded-3xl border-4 border-dashed border-blue-300">
                <div class="text-center font-mono text-blue-800">
                    <p class="mb-4 font-bold">ACCESS CODE REQUIRED</p>
                    <div class="bg-white p-4 rounded text-2xl tracking-widest border border-blue-400">ONE-TIME PASSWORD</div>
                    <p class="mt-6 text-sm opacity-75">Scan QR code for instant access</p>
                    <div class="mt-4 inline-block bg-white p-4">
                        <!-- QR code placeholder -->
                        <div class="w-32 h-32 bg-gray-300 flex items-center justify-center">
                            <span class="text-xs">QR Code</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <footer id="help" class="bg-gray-900 text-white py-16 px-6">
        <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12">
            <div>
                <h4 class="text-2xl font-bold mb-4">Emergency Help</h4>
                <p class="opacity-80 mb-6">If games and breathing aren't enough, it's okay to reach out for support.</p>
                <div class="space-y-4">
                    <div class="bg-gray-800 p-4 rounded-lg">
                        <p class="font-bold text-blue-400">Campus Counseling Hotline</p>
                        <p class="text-sm opacity-75">24/7 Confidential Support</p>
                    </div>
                    <div class="bg-gray-800 p-4 rounded-lg">
                        <p class="font-bold text-blue-400">Student Union Support</p>
                        <p class="text-sm opacity-75">Peer-to-peer counseling</p>
                    </div>
                </div>
            </div>
            <div>
                <h4 class="text-2xl font-bold mb-4">Contact Lab</h4>
                <p class="opacity-70 mb-4">Pantheon Museum • Borghese Gallery • Sistine Chapel</p>
                <div class="mt-8 flex gap-6 text-2xl">
                    <a href="#" class="hover:text-blue-400 transition-colors"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="hover:text-blue-400 transition-colors"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="hover:text-blue-400 transition-colors"><i class="fas fa-envelope"></i></a>
                    <a href="#" class="hover:text-blue-400 transition-colors"><i class="fab fa-discord"></i></a>
                </div>
                <div class="mt-8 p-4 bg-gray-800 rounded-lg">
                    <p class="text-sm opacity-75">Subscribe to our newsletter</p>
                    <div class="flex mt-2">
                        <input type="email" placeholder="Your email" class="flex-grow p-2 rounded-l text-gray-900">
                        <button class="bg-blue-600 px-4 py-2 rounded-r hover:bg-blue-700">Join</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="text-center mt-12 pt-8 border-t border-gray-800 opacity-50 text-sm">
            ©️ 2026 Zengo Play Lab. All rights reserved. | Mental Wellness Through Play
        </div>
    </footer>
    <!-- Full Screen Button -->
    <button id="fullscreen-btn" title="Toggle Fullscreen">
        <i class="fas fa-expand"></i>
    </button>
    <script>
        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenuOverlay = document.getElementById('mobile-menu-overlay');
        const closeMenuBtn = document.getElementById('close-menu');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenuOverlay.classList.remove('hidden');
            mobileMenuOverlay.classList.add('flex');
        });
        closeMenuBtn.addEventListener('click', () => {
            mobileMenuOverlay.classList.add('hidden');
            mobileMenuOverlay.classList.remove('flex');
        });
        // Close menu when clicking links
        mobileMenuOverlay.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenuOverlay.classList.add('hidden');
                mobileMenuOverlay.classList.remove('flex');
            });
        });
        // Full Screen Toggle
        const fullscreenBtn = document.getElementById('fullscreen-btn');
        fullscreenBtn.addEventListener('click', toggleFullScreen);
        function toggleFullScreen() {
            if (!document.fullscreenElement) {
                document.documentElement.requestFullscreen().catch(err => {
                    console.log(`Fullscreen error: ${err.message}`);
                });
                fullscreenBtn.innerHTML = '<i class="fas fa-compress"></i>';
            } else {
                if (document.exitFullscreen) {
                    document.exitFullscreen();
                    fullscreenBtn.innerHTML = '<i class="fas fa-expand"></i>';
                }
            }
        }
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;       
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        // Update fullscreen button icon when exiting fullscreen via other methods
        document.addEventListener('fullscreenchange', () => {
            if (!document.fullscreenElement) {
                fullscreenBtn.innerHTML = '<i class="fas fa-expand"></i>';
            }
        });
    </script>
</body>
</html>
