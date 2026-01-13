<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZENGO PLAY | Games On, Stress Gone</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        /* Full screen width */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
        }
        /* Fixed banner styling */
        .fixed-banner {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #0f172a 100%);
            z-index: 100;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
            transition: opacity 0.8s ease-out, visibility 0.8s ease-out;
        }
        .banner-content {
            text-align: center;
            max-width: 800px;
            padding: 20px;
        }
        /* Main content styling */
        .main-content {
            margin-top: 100vh; /* Start after banner */
            position: relative;
        }
        /* Form styling */
        .contact-form {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        /* Animation for banner hide */
        .banner-hidden {
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
        }
        /* Smooth transitions */
        .transition-all {
            transition: all 0.3s ease;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 10px;
        }
        ::-webkit-scrollbar-track {
            background: #0f172a;
        }
        ::-webkit-scrollbar-thumb {
            background: #3b82f6;
            border-radius: 5px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #2563eb;
        }
    </style>
</head>
<body class="bg-gray-900 text-white">
    <!-- Fixed Full Screen Banner -->
    <div id="mainBanner" class="fixed-banner">
        <div class="banner-content">
            <!-- Logo -->
            <h1 class="text-5xl md:text-6xl font-black uppercase mb-8 tracking-tight">
                <span class="text-blue-400">ZENGO</span> PLAY
            </h1>   
            <!-- Navigation -->
            <div class="flex flex-wrap justify-center gap-6 md:gap-8 mb-12 text-lg">
                <a href="#about" class="text-gray-300 hover:text-white transition-colors">What is Zengo?</a>
                <a href="#activities" class="text-gray-300 hover:text-white transition-colors">Activities</a>
                <a href="#benefits" class="text-gray-300 hover:text-white transition-colors">Benefits</a>
                <a href="#digital" class="text-gray-300 hover:text-white transition-colors">Digital</a>
            </div>
            <!-- Divider -->
            <div class="h-px bg-gradient-to-r from-transparent via-gray-600 to-transparent w-3/4 mx-auto my-12"></div>
            <!-- Main Heading -->
            <h2 class="text-6xl md:text-8xl font-black uppercase mb-6 leading-tight">
                <span class="block">GAMES ON,</span>
                <span class="text-blue-400">STRESS GONE</span>
            </h2>
            <!-- Subtitle -->
            <p class="text-xl md:text-2xl text-gray-300 mb-10 max-w-2xl mx-auto">
                Relaxation Meets Recreation. Find your "off switch" through the power of play.
            </p>
            <!-- Buttons -->
            <div class="flex flex-col sm:flex-row justify-center gap-4 mb-16">
                <button onclick="enterSite()" class="bg-white text-gray-900 px-8 py-4 rounded-full font-bold text-lg hover:bg-gray-100 transition-all transform hover:-translate-y-1">
                    Explore Games
                </button>
                <a href="#contact" onclick="enterSite()" class="border-2 border-white text-white px-8 py-4 rounded-full font-bold text-lg hover:bg-white hover:text-gray-900 transition-all transform hover:-translate-y-1 text-center">
                    Get Help Now
                </a>
            </div>
            <!-- Enter Site Button -->
            <div class="mt-12">
                <button onclick="enterSite()" class="text-gray-400 hover:text-white transition-colors flex items-center gap-2 mx-auto group">
                    <span>Enter Site</span>
                    <i class="fas fa-chevron-down group-hover:translate-y-1 transition-transform"></i>
                </button>
            </div>
        </div>
    </div>
    <!-- Main Content (hidden initially) -->
    <div id="mainContent" class="main-content opacity-0">
        <!-- Navigation Bar -->
        <nav class="fixed top-0 left-0 w-full bg-gray-900/90 backdrop-blur-sm z-50 py-4 px-6">
            <div class="max-w-7xl mx-auto flex justify-between items-center">
                <h1 class="text-2xl font-black tracking-tight uppercase">
                    <span class="text-blue-400">ZENGO</span> PLAY
                </h1>
                <div class="hidden md:flex space-x-8">
                    <a href="#about" class="text-gray-300 hover:text-white transition-colors">What is Zengo?</a>
                    <a href="#activities" class="text-gray-300 hover:text-white transition-colors">Activities</a>
                    <a href="#benefits" class="text-gray-300 hover:text-white transition-colors">Benefits</a>
                    <a href="#digital" class="text-gray-300 hover:text-white transition-colors">Digital</a>
                    <a href="#contact" class="text-blue-400 hover:text-blue-300 transition-colors">Contact</a>
                </div>
                <button onclick="showBanner()" class="text-gray-400 hover:text-white transition-colors">
                    <i class="fas fa-home"></i>
                </button>
            </div>
        </nav>
        <!-- About Section -->
        <section id="about" class="min-h-screen flex items-center px-6 py-20">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold mb-8">What is <span class="text-blue-400">Zengo Play</span>?</h2>
                <div class="space-y-6 text-lg text-gray-300">
                    <p>
                        In a world that never stops moving, Zengo Play provides a dedicated sanctuary for your mind. 
                    </p>
                    <p>
                        We believe gaming is a vital tool for mental restoration, helping to reduce cortisol levels and quiet daily anxiety.
                    </p>
                </div>
            </div>
        </section>
        <!-- Activities Section -->
        <section id="activities" class="min-h-screen bg-gray-800/50 px-6 py-20">
            <div class="max-w-6xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold mb-12 text-center">Active Recovery Modes</h2>
                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Balloon Pop -->
                    <div class="bg-gray-800/50 p-8 rounded-2xl hover:bg-gray-700/50 transition-all">
                        <div class="text-4xl mb-4 text-center">🎈</div>
                        <h3 class="text-2xl font-bold mb-4 text-center">Balloon Pop</h3>
                        <p class="text-gray-300 text-center">
                            Engage in rapid-response targeting to sharpen hand-eye coordination and release pent-up tension.
                        </p>
                    </div>
                    <!-- Ring Toss -->
                    <div class="bg-gray-800/50 p-8 rounded-2xl hover:bg-gray-700/50 transition-all">
                        <div class="text-4xl mb-4 text-center">⭕</div>
                        <h3 class="text-2xl font-bold mb-4 text-center">Ring Toss</h3>
                        <p class="text-gray-300 text-center">
                            Shift into a 'Flow State' by calibrating spatial awareness and focusing on trajectory and force.
                        </p>
                    </div>
                    <!-- Lucky Dice -->
                    <div class="bg-gray-800/50 p-8 rounded-2xl hover:bg-gray-700/50 transition-all">
                        <div class="text-4xl mb-4 text-center">🎲</div>
                        <h3 class="text-2xl font-bold mb-4 text-center">Lucky Dice</h3>
                        <p class="text-gray-300 text-center">
                            Stimulate the prefrontal cortex by analyzing risk and reward in a low-stakes environment.
                        </p>
                    </div>
                </div>
            </div>
        </section>
        <!-- Benefits Section -->
        <section id="benefits" class="min-h-screen px-6 py-20">
            <div class="max-w-6xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold mb-12">Benefits of <span class="text-blue-400">Zengo Play</span></h2>
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="space-y-6">
                        <div class="flex items-start gap-4">
                            <div class="text-blue-400 text-2xl">✓</div>
                            <div>
                                <h3 class="text-xl font-bold mb-2">Stress Reduction</h3>
                                <p class="text-gray-300">Lower cortisol levels through engaging gameplay</p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="text-blue-400 text-2xl">✓</div>
                            <div>
                                <h3 class="text-xl font-bold mb-2">Improved Focus</h3>
                                <p class="text-gray-300">Enhance concentration and attention span</p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="text-blue-400 text-2xl">✓</div>
                            <div>
                                <h3 class="text-xl font-bold mb-2">Mindfulness</h3>
                                <p class="text-gray-300">Stay present through immersive gaming experiences</p>
                            </div>
                        </div>
                    </div>
                    <div class="space-y-6">
                        <div class="flex items-start gap-4">
                            <div class="text-blue-400 text-2xl">✓</div>
                            <div>
                                <h3 class="text-xl font-bold mb-2">Community Support</h3>
                                <p class="text-gray-300">Connect with others on similar wellness journeys</p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="text-blue-400 text-2xl">✓</div>
                            <div>
                                <h3 class="text-xl font-bold mb-2">24/7 Access</h3>
                                <p class="text-gray-300">Mental wellness support anytime, anywhere</p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="text-blue-400 text-2xl">✓</div>
                            <div>
                                <h3 class="text-xl font-bold mb-2">Safe Space</h3>
                                <p class="text-gray-300">Anonymous and judgment-free environment</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Digital Section -->
        <section id="digital" class="min-h-screen bg-gray-800/50 px-6 py-20">
            <div class="max-w-6xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold mb-12">Digital <span class="text-blue-400">Sanctuary</span></h2>
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <p class="text-lg text-gray-300 mb-8">
                            Our online platform is available 24/7, fitting easily into your daily routine—whether you are in the library, your room, or commuting.
                        </p>
                        <ul class="space-y-4">
                            <li class="flex items-center gap-3">
                                <i class="fas fa-check text-blue-400"></i>
                                <span>Safe Space: Share thoughts anonymously</span>
                            </li>
                            <li class="flex items-center gap-3">
                                <i class="fas fa-check text-blue-400"></i>
                                <span>Guided Breathing: Visuals to calm the body</span>
                            </li>
                            <li class="flex items-center gap-3">
                                <i class="fas fa-check text-blue-400"></i>
                                <span>Progress Tracking: Monitor your wellness journey</span>
                            </li>
                        </ul>
                    </div>
                    <div class="bg-gray-900 p-8 rounded-2xl">
                        <div class="text-center">
                            <h3 class="text-2xl font-bold mb-4">Access Code</h3>
                            <div class="text-4xl font-mono bg-gray-800 p-6 rounded-xl mb-6">
                                ZENGO-2024
                            </div>
                            <p class="text-gray-400">Your personal access to the digital sanctuary</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Contact/Comment Section -->
        <section id="contact" class="min-h-screen px-6 py-20">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold mb-12">Contact <span class="text-blue-400">Us</span></h2>
                <!-- Contact Form -->
                <form id="contactForm" class="contact-form p-8 rounded-2xl space-y-6">
                    <div>
                        <label for="name" class="block text-gray-300 mb-2">Name</label>
                        <input type="text" id="name" name="name" 
                               class="w-full bg-gray-800 border border-gray-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-500"
                               required>
                    </div>
                    <div>
                        <label for="email" class="block text-gray-300 mb-2">Email</label>
                        <input type="email" id="email" name="email" 
                               class="w-full bg-gray-800 border border-gray-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-500"
                               required>
                    </div>
                    <div>
                        <label for="subject" class="block text-gray-300 mb-2">Subject</label>
                        <input type="text" id="subject" name="subject" 
                               class="w-full bg-gray-800 border border-gray-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-500"
                               required>
                    </div>
                    <div>
                        <label for="message" class="block text-gray-300 mb-2">Message</label>
                        <textarea id="message" name="message" rows="5"
                                  class="w-full bg-gray-800 border border-gray-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-500"
                                  required></textarea>
                    </div>
                    <button type="submit" 
                            class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg transition-colors flex items-center justify-center gap-2">
                        <i class="fas fa-paper-plane"></i>
                        Send Message to zengoplay@gmail.com
                    </button>
                </form>
                <!-- Form Status Messages -->
                <div id="formStatus" class="mt-6 text-center hidden">
                    <p class="text-green-400 font-bold" id="successMessage">Message sent successfully!</p>
                    <p class="text-red-400 font-bold" id="errorMessage">Failed to send message. Please try again.</p>
                </div> 
                <!-- Direct Email Option -->
                <div class="mt-12 text-center">
                    <p class="text-gray-400 mb-4">Or send directly to:</p>
                    <a href="mailto:zengoplay@gmail.com" 
                       class="inline-flex items-center gap-2 text-blue-400 hover:text-blue-300 text-lg">
                        <i class="fas fa-envelope"></i>
                        zengoplay@gmail.com
                    </a>
                </div>
            </div>
        </section>
        <!-- Footer -->
        <footer class="bg-gray-950 py-12 px-6">
            <div class="max-w-6xl mx-auto text-center">
                <div class="mb-8">
                    <h3 class="text-2xl font-bold mb-4">Emergency Help</h3>
                    <p class="text-gray-400 mb-4">
                        If games and breathing aren't enough, it's okay to reach out for support.
                    </p>
                    <div class="flex flex-wrap justify-center gap-6 text-blue-400">
                        <a href="tel:1-800-273-8255" class="hover:text-blue-300">Campus Counseling Hotline</a>
                        <a href="#" class="hover:text-blue-300">Student Union Support</a>
                    </div>
                </div>
                <div class="border-t border-gray-800 pt-8">
                    <p class="text-gray-500">
                        ©️ 2024 Zengo Play Lab. All rights reserved.
                    </p>
                </div>
            </div>
        </footer>
    </div>
    <script>
        // Banner visibility control
        function enterSite() {
            const banner = document.getElementById('mainBanner');
            const content = document.getElementById('mainContent');
            // Hide banner
            banner.classList.add('banner-hidden');
            // Show content with fade in
            setTimeout(() => {
                content.classList.remove('opacity-0');
                content.style.opacity = '1';
            }, 300);
            // Update URL without hash if it's just #
            if (window.location.hash === '#') {
                history.replaceState(null, null, ' ');
            }
        }
        function showBanner() {
            const banner = document.getElementById('mainBanner');
            const content = document.getElementById('mainContent'); 
            // Show banner
            banner.classList.remove('banner-hidden');
            // Hide content
            content.style.opacity = '0';
            // Scroll to top
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
        // Contact form handling
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault(); 
            const formData = new FormData(this);
            const data = Object.fromEntries(formData);  
            // Send email using Formspree (free service)
            fetch('https://formspree.io/f/mzbnnyjo', {
                method: 'POST',
                headers: {
                    'Content-Type': 'application/json',
                },
                body: JSON.stringify({
                    name: data.name,
                    email: data.email,
                    subject: data.subject,
                    message: data.message,
                    _replyto: 'zengoplay@gmail.com',
                    _subject: 'New Message from Zengo Play Website'
                })
            })
            .then(response => {
                const statusDiv = document.getElementById('formStatus');
                if (response.ok) {
                    // Show success message
                    document.getElementById('successMessage').classList.remove('hidden');
                    document.getElementById('errorMessage').classList.add('hidden');
                    statusDiv.classList.remove('hidden');
                    // Reset form
                    document.getElementById('contactForm').reset();
                    // Hide message after 5 seconds
                    setTimeout(() => {
                        statusDiv.classList.add('hidden');
                    }, 5000);
                } else {
                    throw new Error('Network response was not ok');
                }
            })
            .catch(error => {
                // Show error message
                document.getElementById('errorMessage').classList.remove('hidden');
                document.getElementById('successMessage').classList.add('hidden');
                document.getElementById('formStatus').classList.remove('hidden');
                console.error('Error:', error);
            });
        });
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                const href = this.getAttribute('href');
                // If it's not the contact link on banner, prevent default
                if (href !== '#contact' || !this.onclick) {
                    e.preventDefault();
                }
                const targetId = href;
                if (targetId === '#') return;
                // If clicking from main content, scroll smoothly
                if (!document.getElementById('mainBanner').classList.contains('banner-hidden')) {
                    enterSite();
                }
                setTimeout(() => {
                    const targetElement = document.querySelector(targetId);
                    if (targetElement) {
                        window.scrollTo({
                            top: targetElement.offsetTop - 80,
                            behavior: 'smooth'
                        });
                    }
                }, 500);
            });
        });
        // Handle direct contact link click from banner
        document.querySelector('a[href="#contact"][onclick]').addEventListener('click', function(e) {
            enterSite();
        });
        // Initialize
        document.addEventListener('DOMContentLoaded', function() {
            // Check if user has already visited
            const hasVisited = sessionStorage.getItem('zengoVisited');
            if (hasVisited) {
                // User has visited before, hide banner immediately
                enterSite();
            } else {
                // First visit, mark as visited
                sessionStorage.setItem('zengoVisited', 'true');
            }
            // Add scroll effect to navbar
            window.addEventListener('scroll', function() {
                const nav = document.querySelector('nav');
                if (window.scrollY > 100) {
                    nav.classList.add('bg-gray-900');
                    nav.classList.remove('bg-gray-900/90');
                } else {
                    nav.classList.remove('bg-gray-900');
                    nav.classList.add('bg-gray-900/90');
                }
            });
        });
    </script>
</body>
</html>
