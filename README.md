<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>ZENGO PLAY | Games On, Stress Gone</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        /* Full width and full screen optimization */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }   
        html, body {
            width: 100vw;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }
        body {
            background-color: #0A192F;
            color: #E6F1FF;
            font-family: 'Inter', sans-serif;
        }
        /* Full width sections */
        section, header, footer {
            width: 100vw;
            max-width: 100%;
        }
        /* Modern gradient */
        .hero-gradient {
            background: linear-gradient(135deg, 
                #0A192F 0%, 
                #112240 25%, 
                #1E3A8A 50%, 
                #3B82F6 75%, 
                #60A5FA 100%);
            background-size: 400% 400%;
            animation: gradientShift 15s ease infinite;
        }
        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        /* Glass morphism effect */
        .glass-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .nav-glass {
            background: rgba(10, 25, 47, 0.9);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        /* Neon glow */
        .neon-glow {
            text-shadow: 0 0 10px rgba(59, 130, 246, 0.5),
                         0 0 20px rgba(59, 130, 246, 0.3),
                         0 0 30px rgba(59, 130, 246, 0.1);
        }
        /* Full screen sections */
        .full-screen-section {
            min-height: 100vh;
            padding: 80px 5%;
        }
        /* Responsive adjustments */
        @media (max-width: 768px) {
            .full-screen-section {
                padding: 100px 5% 60px;
            }
            .hero-title {
                font-size: 3rem !important;
            }
        }
    </style>
</head>
<body class="antialiased">
    <!-- Navigation -->
    <nav class="nav-glass fixed w-full z-50 py-4 px-5% flex justify-between items-center">
        <h1 class="text-2xl font-black tracking-tight uppercase text-white">
            <span class="text-blue-400">ZENGO</span> PLAY
        </h1>
        <div class="hidden md:flex space-x-8">
            <a href="#about" class="text-gray-300 hover:text-white transition-colors font-medium">What is Zengo?</a>
            <a href="#activities" class="text-gray-300 hover:text-white transition-colors font-medium">Activities</a>
            <a href="#benefits" class="text-gray-300 hover:text-white transition-colors font-medium">Benefits</a>
            <a href="#digital" class="text-gray-300 hover:text-white transition-colors font-medium">Digital</a>
        </div>
        <button class="bg-gradient-to-r from-blue-500 to-blue-600 text-white px-6 py-2 rounded-full font-bold hover:from-blue-600 hover:to-blue-700 transition-all shadow-lg">
            Enter Lab
        </button>
    </nav>
    <!-- Hero Section -->
    <header class="hero-gradient full-screen-section flex items-center justify-center text-center px-5%">
        <div class="max-w-5xl mx-auto">
            <h2 class="hero-title text-6xl md:text-8xl font-black mb-6 uppercase tracking-tighter neon-glow">
                GAMES ON,<br><span class="text-blue-400">STRESS GONE</span>
            </h2>
            <p class="text-xl md:text-2xl mb-10 text-gray-300 max-w-3xl mx-auto">
                Relaxation Meets Recreation. Find your "off switch" through the power of play.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-5">
                <a href="#activities" class="bg-white text-blue-900 px-8 py-4 rounded-full font-bold text-lg hover:bg-opacity-90 transition-all transform hover:-translate-y-1 shadow-xl">
                    Explore Games
                </a>
                <a href="#help" class="border-2 border-white text-white px-8 py-4 rounded-full font-bold text-lg hover:bg-white hover:text-blue-900 transition-all transform hover:-translate-y-1">
                    Get Help Now
                </a>
            </div>
        </div>
    </header>
    <!-- What is Zengo Section -->
    <section id="about" class="full-screen-section bg-gray-900 px-5%">
        <div class="max-w-6xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-12">
            <div class="lg:w-1/2">
                <h3 class="text-4xl md:text-5xl font-bold mb-8">What is <span class="text-blue-400">Zengo Play</span>?</h3>
                <p class="text-lg text-gray-300 mb-6 leading-relaxed">
                    In a world that never stops moving, Zengo Play provides a dedicated sanctuary for your mind. 
                    We believe gaming is a vital tool for mental restoration, helping to reduce cortisol levels 
                    and quiet daily anxiety through scientifically-designed play experiences.
                </p>
                <div class="grid grid-cols-2 gap-6 mt-8">
                    <div class="glass-card p-6 rounded-2xl">
                        <div class="text-blue-400 text-3xl mb-4">🧠</div>
                        <h4 class="font-bold text-lg mb-2">Mindful Gaming</h4>
                        <p class="text-sm text-gray-400">Purposeful play for mental clarity</p>
                    </div>
                    <div class="glass-card p-6 rounded-2xl">
                        <div class="text-blue-400 text-3xl mb-4">⚡</div>
                        <h4 class="font-bold text-lg mb-2">Instant Relief</h4>
                        <p class="text-sm text-gray-400">Quick stress reduction techniques</p>
                    </div>
                </div>
            </div>
            <div class="lg:w-1/2">
                <div class="bg-gradient-to-br from-blue-900 to-gray-900 p-1 rounded-3xl">
                    <div class="bg-gray-900 rounded-3xl p-8">
                        <div class="aspect-video bg-gradient-to-br from-blue-500/20 to-blue-900/20 rounded-2xl flex items-center justify-center">
                            <div class="text-center">
                                <div class="text-6xl mb-4">🎮</div>
                                <p class="text-xl font-bold">Interactive Mental Wellness</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Activities Section -->
    <section id="activities" class="full-screen-section bg-gray-800 px-5%">
        <div class="max-w-7xl mx-auto">
            <h3 class="text-4xl md:text-5xl font-bold mb-16 text-center">Active Recovery Modes</h3>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Balloon Pop -->
                <div class="glass-card p-8 rounded-3xl hover:transform hover:-translate-y-2 transition-all duration-300">
                    <div class="text-5xl mb-6 text-center">🎈</div>
                    <h4 class="text-2xl font-bold mb-4 text-center">Balloon Pop</h4>
                    <p class="text-gray-300 mb-6 text-center">
                        Engage in rapid-response targeting to sharpen hand-eye coordination and release pent-up tension.
                    </p>
                    <div class="text-center">
                        <a href="#balloon-pop" class="text-blue-400 hover:text-blue-300 font-medium">Try Now →</a>
                    </div>
                </div>  
                <!-- Ring Toss -->
                <div class="glass-card p-8 rounded-3xl hover:transform hover:-translate-y-2 transition-all duration-300">
                    <div class="text-5xl mb-6 text-center">⭕</div>
                    <h4 class="text-2xl font-bold mb-4 text-center">Ring Toss</h4>
                    <p class="text-gray-300 mb-6 text-center">
                        Shift into a 'Flow State' by calibrating spatial awareness and focusing on trajectory and force.
                    </p>
                    <div class="text-center">
                        <a href="#ring-toss" class="text-blue-400 hover:text-blue-300 font-medium">Try Now →</a>
                    </div>
                </div>
                <!-- Lucky Dice -->
                <div class="glass-card p-8 rounded-3xl hover:transform hover:-translate-y-2 transition-all duration-300">
                    <div class="text-5xl mb-6 text-center">🎲</div>
                    <h4 class="text-2xl font-bold mb-4 text-center">Lucky Dice</h4>
                    <p class="text-gray-300 mb-6 text-center">
                        Stimulate the prefrontal cortex by analyzing risk and reward in a low-stakes environment.
                    </p>
                    <div class="text-center">
                        <a href="#lucky-dice" class="text-blue-400 hover:text-blue-300 font-medium">Try Now →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- NEW: Benefits Section -->
    <section id="benefits" class="full-screen-section bg-gradient-to-b from-gray-900 to-blue-900/30 px-5%">
        <div class="max-w-7xl mx-auto">
            <h3 class="text-4xl md:text-5xl font-bold mb-16 text-center">
                The <span class="text-blue-400">Benefits</span> of Play
            </h3>
            <div class="grid lg:grid-cols-2 gap-12 mb-16">
                <div class="space-y-8">
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-500/20 p-4 rounded-2xl">
                            <span class="text-2xl">🧘</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3">Stress Reduction</h4>
                            <p class="text-gray-300">
                                Gaming triggers dopamine release, reducing cortisol levels by up to 68% after just 20 minutes of play.
                            </p>
                        </div>
                    </div>   
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-500/20 p-4 rounded-2xl">
                            <span class="text-2xl">💡</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3">Enhanced Focus</h4>
                            <p class="text-gray-300">
                                Improves attention span and cognitive flexibility through engaging, goal-oriented activities.
                            </p>
                        </div>
                    </div>
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-500/20 p-4 rounded-2xl">
                            <span class="text-2xl">😌</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3">Emotional Regulation</h4>
                            <p class="text-gray-300">
                                Provides safe emotional outlets and teaches healthy coping mechanisms through gameplay.
                            </p>
                        </div>
                    </div>
                </div>
                <div class="space-y-8">
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-500/20 p-4 rounded-2xl">
                            <span class="text-2xl">👥</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3">Social Connection</h4>
                            <p class="text-gray-300">
                                Multiplayer modes foster community support and reduce feelings of isolation.
                            </p>
                        </div>
                    </div>
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-500/20 p-4 rounded-2xl">
                            <span class="text-2xl">⏰</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3">Mindfulness Practice</h4>
                            <p class="text-gray-300">
                                Games designed to anchor you in the present moment, reducing anxiety about past or future.
                            </p>
                        </div>
                    </div>
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-500/20 p-4 rounded-2xl">
                            <span class="text-2xl">📈</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3">Cognitive Growth</h4>
                            <p class="text-gray-300">
                                Stimulates neural pathways for problem-solving, memory, and creative thinking.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Stats Section -->
            <div class="glass-card rounded-3xl p-8 mt-12">
                <h4 class="text-2xl font-bold mb-8 text-center">Proven Results</h4>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                    <div class="text-center">
                        <div class="text-3xl font-bold text-blue-400 mb-2">89%</div>
                        <p class="text-sm text-gray-400">Report reduced anxiety</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold text-blue-400 mb-2">92%</div>
                        <p class="text-sm text-gray-400">Better sleep quality</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold text-blue-400 mb-2">76%</div>
                        <p class="text-sm text-gray-400">Improved focus</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold text-blue-400 mb-2">30 min</div>
                        <p class="text-sm text-gray-400">Average daily play</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Digital Sanctuary Section -->
    <section id="digital" class="full-screen-section bg-gray-900 px-5%">
        <div class="max-w-6xl mx-auto">
            <h3 class="text-4xl md:text-5xl font-bold mb-12">The Digital <span class="text-blue-400">Sanctuary</span></h3>
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <p class="text-lg text-gray-300 mb-8 leading-relaxed">
                        Our online platform is available 24/7, fitting easily into your daily routine—whether you are in the library, your room, or commuting.
                    </p>
                    <div class="space-y-6">
                        <div class="flex items-center gap-4">
                            <div class="w-12 h-12 bg-blue-500/20 rounded-xl flex items-center justify-center">
                                <i class="fas fa-shield-alt text-blue-400"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg">Safe Space</h4>
                                <p class="text-gray-400 text-sm">Anonymous sharing and encrypted conversations</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-4">
                            <div class="w-12 h-12 bg-blue-500/20 rounded-xl flex items-center justify-center">
                                <i class="fas fa-wind text-blue-400"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg">Guided Breathing</h4>
                                <p class="text-gray-400 text-sm">Visual and audio guides to calm your nervous system</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="relative">
                    <div class="glass-card p-8 rounded-3xl">
                        <div class="text-center">
                            <div class="text-sm uppercase tracking-widest text-blue-400 mb-4">Secure Access</div>
                            <div class="text-4xl font-mono bg-gray-800 p-6 rounded-2xl mb-6">ZENGO-2024</div>
                            <p class="text-gray-400 text-sm mb-8">Your one-time passcode for unlimited access</p>
                            <a href="#enter-lab" class="bg-gradient-to-r from-blue-500 to-blue-600 text-white px-8 py-3 rounded-full font-bold inline-block hover:from-blue-600 hover:to-blue-700 transition-all">
                                Generate New Code
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer id="help" class="bg-gray-950 py-16 px-5%">
        <div class="max-w-6xl mx-auto">
            <div class="grid md:grid-cols-3 gap-12 mb-12">
                <div>
                    <h4 class="text-2xl font-bold mb-6">Emergency Help</h4>
                    <p class="text-gray-400 mb-6">
                        If games and breathing aren't enough, it's okay to reach out for support.
                    </p>
                    <div class="space-y-4">
                        <a href="tel:1-800-273-8255" class="block text-blue-400 hover:text-blue-300 font-medium">
                            <i class="fas fa-phone mr-2"></i>1-800-273-8255
                        </a>
                        <a href="https://suicidepreventionlifeline.org" target="_blank" class="block text-blue-400 hover:text-blue-300 font-medium">
                            <i class="fas fa-globe mr-2"></i>Suicide Prevention Lifeline
                        </a>
                    </div>
                </div>
                <div>
                    <h4 class="text-2xl font-bold mb-6">Quick Links</h4>
                    <div class="space-y-3">
                        <a href="#about" class="block text-gray-400 hover:text-white transition-colors">About Zengo</a>
                        <a href="#activities" class="block text-gray-400 hover:text-white transition-colors">All Activities</a>
                        <a href="#benefits" class="block text-gray-400 hover:text-white transition-colors">Research & Benefits</a>
                        <a href="#digital" class="block text-gray-400 hover:text-white transition-colors">Digital Tools</a>
                    </div>
                </div>
                <div>
                    <h4 class="text-2xl font-bold mb-6">Connect With Us</h4>
                    <div class="flex gap-4 mb-6">
                        <a href="#" class="w-12 h-12 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition-colors">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="w-12 h-12 bg-gray-800 rounded-full flex items-center justify-center hover:bg-pink-600 transition-colors">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="w-12 h-12 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-800 transition-colors">
                            <i class="fab fa-discord"></i>
                        </a>
                    </div>
                    <p class="text-gray-400 text-sm">
                        Available 24/7 for mental wellness support
                    </p>
                </div>
            </div>
            <div class="border-t border-gray-800 pt-8 text-center text-gray-500 text-sm">
                © 2024 ZENGO PLAY. All rights reserved. | Games On, Stress Gone.
            </div>
        </div>
    </footer>
    <!-- Back to Top Button -->
    <a href="#" id="backToTop" class="fixed bottom-8 right-8 w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center text-white shadow-lg hover:bg-blue-700 transition-all opacity-0 invisible">
        <i class="fas fa-arrow-up"></i>
    </a>
    <script>
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
        // Back to top button
        const backToTop = document.getElementById('backToTop');
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTop.style.opacity = '1';
                backToTop.style.visibility = 'visible';
            } else {
                backToTop.style.opacity = '0';
                backToTop.style.visibility = 'hidden';
            }
        });
        // Add active state to navigation links
        const sections = document.querySelectorAll('section');
        const navLinks = document.querySelectorAll('nav a');
        window.addEventListener('scroll', () => {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (scrollY >= (sectionTop - 150)) {
                    current = section.getAttribute('id');
                }
            });
            navLinks.forEach(link => {
                link.classList.remove('text-white');
                link.classList.add('text-gray-300');
                if (link.getAttribute('href') === `#${current}`) {
                    link.classList.remove('text-gray-300');
                    link.classList.add('text-white');
                }
            });
        });
        // Mobile menu toggle (if you add mobile menu later)
        const mobileMenuBtn = document.createElement('button');
        mobileMenuBtn.innerHTML = '<i class="fas fa-bars"></i>';
        mobileMenuBtn.className = 'md:hidden fixed top-6 right-6 z-50 bg-blue-600 text-white p-3 rounded-lg';
        document.body.appendChild(mobileMenuBtn);
        // Add click effects to buttons
        document.querySelectorAll('button, a[href="#"]').forEach(btn => {
            btn.addEventListener('click', function(e) {
                if (this.getAttribute('href') === '#') return;
                // Add ripple effect
                const ripple = document.createElement('span');
                const rect = this.getBoundingClientRect();
                const size = Math.max(rect.width, rect.height);
                const x = e.clientX - rect.left - size / 2;
                const y = e.clientY - rect.top - size / 2; 
                ripple.style.cssText = `
                    position: absolute;
                    border-radius: 50%;
                    background: rgba(255, 255, 255, 0.7);
                    transform: scale(0);
                    animation: ripple 0.6s linear;
                    width: ${size}px;
                    height: ${size}px;
                    top: ${y}px;
                    left: ${x}px;
                    pointer-events: none;
                `;
                this.style.position = 'relative';
                this.style.overflow = 'hidden';
                this.appendChild(ripple);
                setTimeout(() => ripple.remove(), 600);
            });
        });       
        // Add CSS for ripple effect
        const style = document.createElement('style');
        style.textContent = `
            @keyframes ripple {
                to {
                    transform: scale(4);
                    opacity: 0;
                }
            }
        `;
        document.head.appendChild(style);
    </script>
</body>
</html>
