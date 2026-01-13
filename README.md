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
        {
        html, body {
            width: 100vw;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }
        body {
            background-color: #F5F1E9;
            color: #1E3A8A;
            font-family: 'Inter', sans-serif;
        }
        /* Full width sections */
        section, header, footer {
            width: 100vw;
            max-width: 100%;
        }
        /* Large Banner Styling - Matches IMG_7727.jpeg */
        .hero-banner {
            background: linear-gradient(135deg, #1E3A8A 0%, #3B82F6 50%, #1E40AF 100%);
            min-height: 90vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 80px 5%;
            position: relative;
            overflow: hidden;
        }
        .hero-banner::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: 
                radial-gradient(circle at 20% 80%, rgba(255,255,255,0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(255,255,255,0.1) 0%, transparent 50%);
        }
        /* Large Title Styling */
        .large-title {
            font-size: 5rem;
            line-height: 1;
            margin-bottom: 1rem;
        }
        @media (min-width: 768px) {
            .large-title {
                font-size: 7rem;
            }
        }
        @media (min-width: 1024px) {
            .large-title {
                font-size: 8rem;
            }
        } 
        /* Navigation */
        .main-nav {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            z-index: 50;
        }
        /* Color theme matching image */
        .accent-beige { 
            background-color: #E7E0D2; 
        }
        .card-shadow { 
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        /* Full screen sections */
        .full-screen-section {
            min-height: 100vh;
            padding: 100px 5%;
        }
        /* Contact form styling */
        .contact-form {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
        }
        /* Responsive adjustments */
        @media (max-width: 768px) {
            .full-screen-section {
                padding: 80px 5% 60px;
            }
            .large-title {
                font-size: 3.5rem !important;
            }
        }
        /* Custom blue colors matching image */
        .text-blue-900 {
            color: #1E3A8A;
        }
        .bg-blue-900 {
            background-color: #1E3A8A;
        }
        .border-blue-300 {
            border-color: #93C5FD;
        }
    </style>
</head>
<body class="antialiased">
    <!-- Navigation -->
    <nav class="main-nav py-6 px-5% flex justify-between items-center">
        <h1 class="text-2xl font-black tracking-tight uppercase text-white">
            <span class="text-blue-300">ZENGO</span> PLAY
        </h1>
        <div class="hidden md:flex space-x-8">
            <a href="#about" class="text-blue-100 hover:text-white transition-colors font-medium">What is Zengo?</a>
            <a href="#activities" class="text-blue-100 hover:text-white transition-colors font-medium">Activities</a>
            <a href="#benefits" class="text-blue-100 hover:text-white transition-colors font-medium">Benefits</a>
            <a href="#digital" class="text-blue-100 hover:text-white transition-colors font-medium">Digital</a>
            <a href="#contact" class="text-white font-medium border-b-2 border-white pb-1">Contact</a>
        </div>
        <button class="bg-white text-blue-900 px-6 py-3 rounded-full font-bold hover:bg-blue-50 transition-all shadow-lg">
            Enter Lab
        </button>
    </nav>
    <!-- Large Banner Hero Section - Matching IMG_7727.jpeg -->
    <header class="hero-banner">
        <div class="relative z-10 max-w-6xl mx-auto">
            <h2 class="large-title font-black mb-6 uppercase tracking-tighter text-white">
                <span class="block">GAMES ON,</span>
                <span class="block text-blue-200">STRESS GONE</span>
            </h2>
            <p class="text-xl md:text-2xl mb-10 text-blue-100 max-w-3xl mx-auto">
                Relaxation Meets Recreation. Find your "off switch" through the power of play.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-5">
                <a href="#activities" class="bg-white text-blue-900 px-8 py-4 rounded-full font-bold text-lg hover:bg-blue-50 transition-all transform hover:-translate-y-1 shadow-xl">
                    Explore Games
                </a>
                <a href="#contact" class="border-2 border-white text-white px-8 py-4 rounded-full font-bold text-lg hover:bg-white hover:text-blue-900 transition-all transform hover:-translate-y-1">
                    Get Help Now
                </a>
            </div>
        </div>
    </header>
    <!-- What is Zengo Section -->
    <section id="about" class="full-screen-section bg-white px-5%">
        <div class="max-w-6xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-12">
            <div class="lg:w-1/2">
                <h3 class="text-4xl md:text-5xl font-bold mb-8 text-blue-900">What is <span class="text-blue-600">Zengo Play</span>?</h3>
                <p class="text-lg text-gray-700 mb-6 leading-relaxed">
                    In a world that never stops moving, Zengo Play provides a dedicated sanctuary for your mind. 
                    We believe gaming is a vital tool for mental restoration, helping to reduce cortisol levels 
                    and quiet daily anxiety through scientifically-designed play experiences.
                </p>
                <div class="grid grid-cols-2 gap-6 mt-8">
                    <div class="glass-card p-6 rounded-2xl">
                        <div class="text-blue-600 text-3xl mb-4">🧠</div>
                        <h4 class="font-bold text-lg mb-2 text-blue-900">Mindful Gaming</h4>
                        <p class="text-sm text-gray-600">Purposeful play for mental clarity</p>
                    </div>
                    <div class="glass-card p-6 rounded-2xl">
                        <div class="text-blue-600 text-3xl mb-4">⚡</div>
                        <h4 class="font-bold text-lg mb-2 text-blue-900">Instant Relief</h4>
                        <p class="text-sm text-gray-600">Quick stress reduction techniques</p>
                    </div>
                </div>
            </div>
            <div class="lg:w-1/2">
                <div class="bg-gradient-to-br from-blue-100 to-blue-50 p-1 rounded-3xl">
                    <div class="bg-white rounded-3xl p-8">
                        <div class="aspect-video bg-gradient-to-br from-blue-200 to-blue-100 rounded-2xl flex items-center justify-center">
                            <div class="text-center">
                                <div class="text-6xl mb-4">🎮</div>
                                <p class="text-xl font-bold text-blue-900">Interactive Mental Wellness</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Activities Section -->
    <section id="activities" class="full-screen-section accent-beige px-5%">
        <div class="max-w-7xl mx-auto">
            <h3 class="text-4xl md:text-5xl font-bold mb-16 text-center text-blue-900">Active Recovery Modes</h3>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Balloon Pop -->
                <div class="bg-white p-8 rounded-3xl card-shadow hover:transform hover:-translate-y-2 transition-all duration-300">
                    <div class="text-5xl mb-6 text-center">🎈</div>
                    <h4 class="text-2xl font-bold mb-4 text-center text-blue-900">Balloon Pop</h4>
                    <p class="text-gray-700 mb-6 text-center">
                        Engage in rapid-response targeting to sharpen hand-eye coordination and release pent-up tension.
                    </p>
                    <div class="text-center">
                        <a href="#balloon-pop" class="text-blue-600 hover:text-blue-800 font-medium">Try Now →</a>
                    </div>
                </div>
                <!-- Ring Toss -->
                <div class="bg-white p-8 rounded-3xl card-shadow hover:transform hover:-translate-y-2 transition-all duration-300">
                    <div class="text-5xl mb-6 text-center">⭕</div>
                    <h4 class="text-2xl font-bold mb-4 text-center text-blue-900">Ring Toss</h4>
                    <p class="text-gray-700 mb-6 text-center">
                        Shift into a 'Flow State' by calibrating spatial awareness and focusing on trajectory and force.
                    </p>
                    <div class="text-center">
                        <a href="#ring-toss" class="text-blue-600 hover:text-blue-800 font-medium">Try Now →</a>
                    </div>
                </div>
                <!-- Lucky Dice -->
                <div class="bg-white p-8 rounded-3xl card-shadow hover:transform hover:-translate-y-2 transition-all duration-300">
                    <div class="text-5xl mb-6 text-center">🎲</div>
                    <h4 class="text-2xl font-bold mb-4 text-center text-blue-900">Lucky Dice</h4>
                    <p class="text-gray-700 mb-6 text-center">
                        Stimulate the prefrontal cortex by analyzing risk and reward in a low-stakes environment.
                    </p>
                    <div class="text-center">
                        <a href="#lucky-dice" class="text-blue-600 hover:text-blue-800 font-medium">Try Now →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Benefits Section -->
    <section id="benefits" class="full-screen-section bg-white px-5%">
        <div class="max-w-7xl mx-auto">
            <h3 class="text-4xl md:text-5xl font-bold mb-16 text-center text-blue-900">
                The <span class="text-blue-600">Benefits</span> of Play
            </h3>
            <div class="grid lg:grid-cols-2 gap-12 mb-16">
                <div class="space-y-8">
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-100 p-4 rounded-2xl">
                            <span class="text-2xl text-blue-600">🧘</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3 text-blue-900">Stress Reduction</h4>
                            <p class="text-gray-700">
                                Gaming triggers dopamine release, reducing cortisol levels by up to 68% after just 20 minutes of play.
                            </p>
                        </div>
                    </div>
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-100 p-4 rounded-2xl">
                            <span class="text-2xl text-blue-600">💡</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3 text-blue-900">Enhanced Focus</h4>
                            <p class="text-gray-700">
                                Improves attention span and cognitive flexibility through engaging, goal-oriented activities.
                            </p>
                        </div>
                    </div>
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-100 p-4 rounded-2xl">
                            <span class="text-2xl text-blue-600">😌</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3 text-blue-900">Emotional Regulation</h4>
                            <p class="text-gray-700">
                                Provides safe emotional outlets and teaches healthy coping mechanisms through gameplay.
                            </p>
                        </div>
                    </div>
                </div>
                <div class="space-y-8">
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-100 p-4 rounded-2xl">
                            <span class="text-2xl text-blue-600">👥</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3 text-blue-900">Social Connection</h4>
                            <p class="text-gray-700">
                                Multiplayer modes foster community support and reduce feelings of isolation.
                            </p>
                        </div>
                    </div>
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-100 p-4 rounded-2xl">
                            <span class="text-2xl text-blue-600">⏰</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3 text-blue-900">Mindfulness Practice</h4>
                            <p class="text-gray-700">
                                Games designed to anchor you in the present moment, reducing anxiety about past or future.
                            </p>
                        </div>
                    </div>
                    <div class="flex items-start gap-6">
                        <div class="bg-blue-100 p-4 rounded-2xl">
                            <span class="text-2xl text-blue-600">📈</span>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold mb-3 text-blue-900">Cognitive Growth</h4>
                            <p class="text-gray-700">
                                Stimulates neural pathways for problem-solving, memory, and creative thinking.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Stats Section -->
            <div class="bg-blue-50 rounded-3xl p-8 mt-12">
                <h4 class="text-2xl font-bold mb-8 text-center text-blue-900">Proven Results</h4>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                    <div class="text-center">
                        <div class="text-3xl font-bold text-blue-600 mb-2">89%</div>
                        <p class="text-sm text-gray-600">Report reduced anxiety</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold text-blue-600 mb-2">92%</div>
                        <p class="text-sm text-gray-600">Better sleep quality</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold text-blue-600 mb-2">76%</div>
                        <p class="text-sm text-gray-600">Improved focus</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold text-blue-600 mb-2">30 min</div>
                        <p class="text-sm text-gray-600">Average daily play</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Digital Sanctuary Section -->
    <section id="digital" class="full-screen-section accent-beige px-5%">
        <div class="max-w-6xl mx-auto">
            <h3 class="text-4xl md:text-5xl font-bold mb-12 text-blue-900">The Digital <span class="text-blue-600">Sanctuary</span></h3>
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <p class="text-lg text-gray-700 mb-8 leading-relaxed">
                        Our online platform is available 24/7, fitting easily into your daily routine—whether you are in the library, your room, or commuting.
                    </p>
                    <div class="space-y-6">
                        <div class="flex items-center gap-4">
                            <div class="w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center">
                                <i class="fas fa-shield-alt text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg text-blue-900">Safe Space</h4>
                                <p class="text-gray-600 text-sm">Anonymous sharing and encrypted conversations</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-4">
                            <div class="w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center">
                                <i class="fas fa-wind text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg text-blue-900">Guided Breathing</h4>
                                <p class="text-gray-600 text-sm">Visual and audio guides to calm your nervous system</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="relative">
                    <div class="bg-white p-8 rounded-3xl card-shadow">
                        <div class="text-center">
                            <div class="text-sm uppercase tracking-widest text-blue-600 mb-4">Secure Access</div>
                            <div class="text-4xl font-mono bg-blue-50 text-blue-900 p-6 rounded-2xl mb-6 border-2 border-dashed border-blue-300">
                                ZENGO-2024
                            </div>
                            <p class="text-gray-600 text-sm mb-8">Your one-time passcode for unlimited access</p>
                            <a href="#enter-lab" class="bg-blue-600 text-white px-8 py-3 rounded-full font-bold inline-block hover:bg-blue-700 transition-all">
                                Generate New Code
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer with Emergency Help and Contact Lab -->
    <footer id="help" class="bg-blue-900 text-white py-16 px-5%">
        <div class="max-w-6xl mx-auto">
            <div class="grid md:grid-cols-2 gap-12 mb-12">
                <div>
                    <h4 class="text-2xl font-bold mb-6">Emergency Help</h4>
                    <p class="text-blue-200 mb-6">
                        If games and breathing aren't enough, it's okay to reach out for support.
                    </p>
                    <div class="space-y-4 font-bold">
                        <p class="text-blue-300">Campus Counseling Hotline</p>
                        <p class="text-blue-300">Student Union Support</p>
                    </div>
                </div>
                <div class="text-right">
                    <h4 class="text-2xl font-bold mb-6">Contact Lab</h4>
                    <p class="text-blue-200 mb-6">
                        Pantheon Museum • Borghese Gallery • Sistine Chapel
                    </p>
                    <div class="mt-8 flex justify-end gap-6 text-2xl">
                        <a href="#" class="hover:text-blue-300 transition-colors"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="hover:text-blue-300 transition-colors"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="hover:text-blue-300 transition-colors"><i class="fas fa-envelope"></i></a>
                    </div>
                </div>
            </div>
            <!-- NEW: Comment Section -->
            <div id="contact" class="mt-16 pt-12 border-t border-blue-800">
                <h4 class="text-2xl font-bold mb-8 text-center">Send Us a Message</h4>
                <form id="commentForm" class="contact-form p-8 max-w-2xl mx-auto">
                    <div class="grid md:grid-cols-2 gap-6 mb-6">
                        <div>
                            <label for="name" class="block text-blue-200 mb-2">Name</label>
                            <input type="text" id="name" name="name" 
                                   class="w-full bg-blue-800 border border-blue-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-400"
                                   required>
                        </div>
                        <div>
                            <label for="email" class="block text-blue-200 mb-2">Email</label>
                            <input type="email" id="email" name="email" 
                                   class="w-full bg-blue-800 border border-blue-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-400"
                                   required>
                        </div>
                    </div>
                    <div class="mb-6">
                        <label for="subject" class="block text-blue-200 mb-2">Subject</label>
                        <input type="text" id="subject" name="subject" 
                               class="w-full bg-blue-800 border border-blue-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-400"
                               required>
                    </div>
                    <div class="mb-6">
                        <label for="message" class="block text-blue-200 mb-2">Message</label>
                        <textarea id="message" name="message" rows="5"
                                  class="w-full bg-blue-800 border border-blue-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-400"
                                  required></textarea>
                    </div>
                    <button type="submit" 
                            class="w-full bg-white text-blue-900 hover:bg-blue-50 font-bold py-4 px-6 rounded-lg transition-colors flex items-center justify-center gap-2">
                        <i class="fas fa-paper-plane"></i>
                        Send Message to zengoplay@gmail.com
                    </button>
                </form>
                <!-- Form Status Messages -->
                <div id="formStatus" class="mt-6 text-center hidden">
                    <p class="text-green-300 font-bold" id="successMessage">Message sent successfully to zengoplay@gmail.com!</p>
                    <p class="text-red-300 font-bold" id="errorMessage">Failed to send message. Please try again.</p>
                </div>
                <!-- Direct Email Link -->
                <div class="text-center mt-8">
                    <p class="text-blue-200 mb-4">Or email directly:</p>
                    <a href="mailto:zengoplay@gmail.com" 
                       class="inline-flex items-center gap-2 text-white hover:text-blue-300 text-lg bg-blue-800 hover:bg-blue-700 px-6 py-3 rounded-full transition-all">
                        <i class="fas fa-envelope"></i>
                        zengoplay@gmail.com
                    </a>
                </div>
            </div>
            <div class="text-center mt-16 pt-8 border-t border-blue-800 text-blue-300 text-sm">
                ©️ 2024 Zengo Play Lab. All rights reserved.
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
        // Contact form handling
        document.getElementById('commentForm').addEventListener('submit', function(e) {
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
                    document.getElementById('commentForm').reset();
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
                link.classList.remove('text-white', 'border-b-2', 'border-white');
                if (link.getAttribute('href') === `#${current}`) {
                    link.classList.add('text-white', 'border-b-2', 'border-white');
                }
            });
        });
        // Add animation to hero banner on load
        document.addEventListener('DOMContentLoaded', function() {
            const heroTitle = document.querySelector('.large-title');
            const heroSubtitle = document.querySelector('.hero-banner p');
            const heroButtons = document.querySelectorAll('.hero-banner a');
            // Animate elements sequentially
            setTimeout(() => {
                heroTitle.style.opacity = '1';
                heroTitle.style.transform = 'translateY(0)';
            }, 300);
            setTimeout(() => {
                heroSubtitle.style.opacity = '1';
                heroSubtitle.style.transform = 'translateY(0)';
            }, 600);
            setTimeout(() => {
                heroButtons.forEach((btn, index) => {
                    setTimeout(() => {
                        btn.style.opacity = '1';
                        btn.style.transform = 'translateY(0)';
                    }, index * 200);
                });
            }, 900);
            // Set initial styles for animation
            heroTitle.style.opacity = '0';
            heroTitle.style.transform = 'translateY(20px)';
            heroTitle.style.transition = 'opacity 0.8s ease, transform 0.8s ease';
            heroSubtitle.style.opacity = '0';
            heroSubtitle.style.transform = 'translateY(20px)';
            heroSubtitle.style.transition = 'opacity 0.8s ease, transform 0.8s ease';
            heroButtons.forEach(btn => {
                btn.style.opacity = '0';
                btn.style.transform = 'translateY(20px)';
                btn.style.transition = 'opacity 0.8s ease, transform 0.8s ease';
            });
        });
    </script>
</body>
</html>
