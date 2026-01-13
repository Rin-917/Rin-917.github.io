<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <!-- Add this meta tag for proper full-screen display -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Zengo Play | Games On, Stress Gone</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        /* Full width and height styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        html, body {
            width: 100vw;
            max-width: 100vw;
            overflow-x: hidden;
            min-height: 100vh;
        }
        body { 
            background-color: #F5F1E9; 
            color: #1E3A8A; 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
        }
        /* Full width hero section - FIXED */
        .hero-gradient { 
            background: linear-gradient(135deg, #1E3A8A 0%, #3B82F6 100%);
            width: 100vw;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 0;
            margin: 0;
        }
        .accent-beige { 
            background-color: #E7E0D2; 
        }
        .card-shadow { 
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            transition: transform 0.3s ease;
        }
        .card-shadow:hover {
            transform: translateY(-5px);
        }
        /* Make ALL sections full width */
        section, header, footer, nav {
            width: 100vw;
            max-width: 100vw;
            padding-left: 0;
            padding-right: 0;
        }
        /* Full width containers */
        .full-width-container {
            width: 100vw;
            max-width: 100vw;
            padding-left: 5%;
            padding-right: 5%;
        }
        /* Form styling */
        .contact-form {
            background: white;
            border-radius: 10px;
            padding: 2rem;
        }
        /* Emergency link styling */
        .emergency-link {
            transition: all 0.3s ease;
        }
        .emergency-link:hover {
            transform: translateX(5px);
            background-color: rgba(59, 130, 246, 0.1);
        }
        /* Remove any max-width constraints */
        .remove-max-width {
            max-width: none !important;
        }
        /* Full screen hero content */
        .hero-content {
            width: 100%;
            padding: 0 5%;
        }
        /* Responsive adjustments */
        @media (max-width: 768px) {
            .hero-gradient {
                padding: 0;
            } 
            .full-width-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }
    </style>
</head>
<body class="antialiased">
    <!-- Navigation - Fixed full width -->
    <nav class="w-screen p-6 flex justify-between items-center bg-white shadow-sm">
        <h1 class="text-2xl font-bold tracking-tighter uppercase">Zengo <span class="text-blue-600">Play</span></h1>
        <div class="hidden md:flex space-x-8 font-medium">
            <a href="#about" class="hover:text-blue-600">What is Zengo?</a>
            <a href="#games" class="hover:text-blue-600">Activities</a>
            <a href="#benefits" class="hover:text-blue-600">Benefits</a>
            <a href="#digital" class="hover:text-blue-600">Digital Sanctuary</a>
        </div>
        <button class="bg-blue-600 text-white px-6 py-2 rounded-full font-bold hover:bg-blue-700 transition">Enter Lab</button>
    </nav>
    <!-- Hero Section - Full screen -->
    <header class="hero-gradient text-white text-center">
        <div class="hero-content max-w-6xl mx-auto">
            <h2 class="text-5xl md:text-8xl font-extrabold mb-4 uppercase tracking-tight">Games On, Stress Gone</h2>
            <p class="text-xl md:text-2xl mb-8 opacity-90 max-w-2xl mx-auto">Relaxation Meets Recreation. Find your "off switch" through the power of play.</p>
            <div class="flex justify-center gap-4">
                <a href="#games" class="bg-white text-blue-900 px-8 py-3 rounded-lg font-bold hover:bg-opacity-90 transition">Explore Games</a>
                <a href="#contact" class="border-2 border-white px-8 py-3 rounded-lg font-bold hover:bg-white hover:text-blue-900 transition">Get Help Now</a>
            </div>
        </div>
    </header>
    <section id="about" class="py-20 full-width-container">
        <div class="max-w-5xl mx-auto text-center">
            <h3 class="text-3xl font-bold mb-6">What is Zengo Play?</h3>
            <p class="text-lg leading-relaxed text-gray-700 mb-6">
                In a world that never stops moving, Zengo Play provides a dedicated sanctuary for your mind. 
                We believe gaming is a vital tool for mental restoration, helping to reduce cortisol levels and quiet daily anxiety.
            </p>
            <div class="italic font-bold text-blue-600 text-xl uppercase tracking-widest">Stress • Play • Repeat</div>
        </div>
    </section>
    <section id="games" class="py-20 accent-beige full-width-container">
        <div class="max-w-6xl mx-auto text-center">
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
    <!-- Benefits Section -->
    <section id="benefits" class="py-20 full-width-container bg-white">
        <div class="max-w-6xl mx-auto">
            <h3 class="text-4xl font-bold mb-12 text-center">Benefits of Zengo Play</h3>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="space-y-6">
                    <div class="flex items-start gap-4">
                        <div class="text-blue-600 text-xl mt-1">✓</div>
                        <div>
                            <h4 class="text-xl font-bold mb-2 text-blue-900">Stress Reduction</h4>
                            <p class="text-gray-700">Lower cortisol levels through engaging gameplay and relaxation techniques.</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-4">
                        <div class="text-blue-600 text-xl mt-1">✓</div>
                        <div>
                            <h4 class="text-xl font-bold mb-2 text-blue-900">Improved Focus</h4>
                            <p class="text-gray-700">Enhance concentration and attention span through targeted gaming activities.</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-4">
                        <div class="text-blue-600 text-xl mt-1">✓</div>
                        <div>
                            <h4 class="text-xl font-bold mb-2 text-blue-900">Mindfulness Practice</h4>
                            <p class="text-gray-700">Learn to stay present and reduce anxiety through guided gaming experiences.</p>
                        </div>
                    </div>
                </div>
                <div class="space-y-6">
                    <div class="flex items-start gap-4">
                        <div class="text-blue-600 text-xl mt-1">✓</div>
                        <div>
                            <h4 class="text-xl font-bold mb-2 text-blue-900">Emotional Regulation</h4>
                            <p class="text-gray-700">Develop healthy coping mechanisms and emotional resilience.</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-4">
                        <div class="text-blue-600 text-xl mt-1">✓</div>
                        <div>
                            <h4 class="text-xl font-bold mb-2 text-blue-900">Community Support</h4>
                            <p class="text-gray-700">Connect with others in a safe, supportive environment for mental wellness.</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-4">
                        <div class="text-blue-600 text-xl mt-1">✓</div>
                        <div>
                            <h4 class="text-xl font-bold mb-2 text-blue-900">Cognitive Enhancement</h4>
                            <p class="text-gray-700">Improve problem-solving skills, memory, and creative thinking abilities.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="digital" class="py-20 full-width-container">
        <div class="max-w-6xl mx-auto">
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
                            <div class="w-32 h-32 bg-gray-300 flex items-center justify-center">
                                <span class="text-xs">QR Code</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Comment Section -->
    <section id="contact" class="py-20 full-width-container bg-gray-50">
        <div class="max-w-4xl mx-auto">
            <h3 class="text-3xl font-bold mb-8 text-center">Send Us a Message</h3>
            <form id="commentForm" class="contact-form card-shadow">
                <div class="grid md:grid-cols-2 gap-6 mb-6">
                    <div>
                        <label for="name" class="block text-gray-700 mb-2">Name</label>
                        <input type="text" id="name" name="name" 
                               class="w-full border border-gray-300 rounded-lg px-4 py-3 focus:outline-none focus:border-blue-500"
                               required>
                    </div>                    
                    <div>
                        <label for="email" class="block text-gray-700 mb-2">Email</label>
                        <input type="email" id="email" name="email" 
                               class="w-full border border-gray-300 rounded-lg px-4 py-3 focus:outline-none focus:border-blue-500"
                               required>
                    </div>
                </div>
                <div class="mb-6">
                    <label for="subject" class="block text-gray-700 mb-2">Subject</label>
                    <input type="text" id="subject" name="subject" 
                           class="w-full border border-gray-300 rounded-lg px-4 py-3 focus:outline-none focus:border-blue-500"
                           required>
                </div>                
                <div class="mb-6">
                    <label for="message" class="block text-gray-700 mb-2">Message</label>
                    <textarea id="message" name="message" rows="5"
                              class="w-full border border-gray-300 rounded-lg px-4 py-3 focus:outline-none focus:border-blue-500"
                              required></textarea>
                </div>                
                <button type="submit" 
                        class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg transition-colors flex items-center justify-center gap-2">
                    <i class="fas fa-paper-plane"></i>
                    Send Message to zengoplay@gmail.com
                </button>
            </form>            
            <div id="formStatus" class="mt-6 text-center hidden">
                <p class="text-green-600 font-bold" id="successMessage">Message sent successfully!</p>
                <p class="text-red-600 font-bold" id="errorMessage">Failed to send message. Please try again.</p>
            </div>            
            <div class="text-center mt-8">
                <p class="text-gray-600 mb-4">Or email directly:</p>
                <a href="mailto:zengoplay@gmail.com" 
                   class="inline-flex items-center gap-2 text-blue-600 hover:text-blue-800 text-lg">
                    <i class="fas fa-envelope"></i>
                    zengoplay@gmail.com
                </a>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer id="help" class="bg-gray-900 text-white py-16 full-width-container">
        <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12">
            <div>
                <h4 class="text-2xl font-bold mb-4">Emergency Help</h4>
                <p class="opacity-80 mb-6">If games and breathing aren't enough, it's okay to reach out for support.</p>
                <div class="space-y-4">
                    <a href="tel:1-800-273-8255" class="emergency-link bg-gray-800 p-4 rounded-lg block hover:bg-gray-700">
                        <p class="font-bold text-blue-400 hover:text-blue-300">Campus Counseling Hotline</p>
                        <p class="text-sm opacity-75 mt-1">24/7 Confidential Support • Click to call: 1-800-273-8255</p>
                    </a>
                    <a href="https://suicidepreventionlifeline.org" target="_blank" class="emergency-link bg-gray-800 p-4 rounded-lg block hover:bg-gray-700">
                        <p class="font-bold text-blue-400 hover:text-blue-300">Student Union Support</p>
                        <p class="text-sm opacity-75 mt-1">Peer-to-peer counseling • Click for online resources</p>
                    </a>
                    <a href="https://www.crisistextline.org" target="_blank" class="emergency-link bg-gray-800 p-4 rounded-lg block hover:bg-gray-700">
                        <p class="font-bold text-blue-400 hover:text-blue-300">Crisis Text Line</p>
                        <p class="text-sm opacity-75 mt-1">Text HOME to 741741 • Free 24/7 support</p>
                    </a>
                </div>
            </div>
            <div>
                <h4 class="text-2xl font-bold mb-4">Contact Lab</h4>
                <p class="opacity-70 mb-4">Pantheon Museum • Borghese Gallery • Sistine Chapel</p>
                <div class="mt-8 flex gap-6 text-2xl">
                    <a href="https://www.instagram.com/playzengo_official/" target="_blank" class="hover:text-blue-400 transition-colors">
                        <i class="fab fa-instagram"></i>
                    </a>
                    <a href="https://x.com/ZengoPlay1" target="_blank" class="hover:text-blue-400 transition-colors">
                        <i class="fab fa-twitter"></i>
                    </a>
                    <a href="mailto:zengoplay@gmail.com" class="hover:text-blue-400 transition-colors">
                        <i class="fas fa-envelope"></i>
                    </a>
                </div>
                <div class="mt-8 p-4 bg-gray-800 rounded-lg">
                    <p class="text-sm opacity-75">Subscribe to our newsletter</p>
                    <div class="flex mt-2">
                        <input type="email" id="newsletterEmail" placeholder="Your email" class="flex-grow p-2 rounded-l text-gray-900">
                        <button onclick="subscribeNewsletter()" class="bg-blue-600 px-4 py-2 rounded-r hover:bg-blue-700">Join</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="text-center mt-12 pt-8 border-t border-gray-800 opacity-50 text-sm">
            ©️ 2026 Zengo Play Lab. All rights reserved. | Mental Wellness Through Play
        </div>
    </footer>
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
        // Contact form handling
        document.getElementById('commentForm').addEventListener('submit', function(e) {
            e.preventDefault();      
            const formData = new FormData(this);
            const data = Object.fromEntries(formData);       
            // Send email using your Formspree URL
            fetch('https://formspree.io/f/xeeeqrbr', {
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
                    document.getElementById('successMessage').classList.remove('hidden');
                    document.getElementById('errorMessage').classList.add('hidden');
                    statusDiv.classList.remove('hidden');     
                    document.getElementById('commentForm').reset();
                    setTimeout(() => {
                        statusDiv.classList.add('hidden');
                    }, 5000);
                } else {
                    throw new Error('Network response was not ok');
                }
            })
            .catch(error => {
                document.getElementById('errorMessage').classList.remove('hidden');
                document.getElementById('successMessage').classList.add('hidden');
                document.getElementById('formStatus').classList.remove('hidden');
                console.error('Error:', error);
            });
        });
        function subscribeNewsletter() {
            const emailInput = document.getElementById('newsletterEmail');
            const email = emailInput.value.trim();            
            if (!email) {
                alert('Please enter your email address.');
                return;
            }        
            if (!validateEmail(email)) {
                alert('Please enter a valid email address.');
                return;
            }     
            alert('Thank you for subscribing to the Zengo Play newsletter!');
            emailInput.value = '';
        }
        function validateEmail(email) {
            const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            return re.test(email);
        }
        // Make the Enter Lab button functional
        document.querySelector('nav button').addEventListener('click', function() {
            alert('Welcome to Zengo Play Lab! Accessing the interactive gaming space...');
        });
    </script>
</body>
</html>
