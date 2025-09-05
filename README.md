<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ankesh Rathore | Tech Student Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        @keyframes colorPulse {
            0% { border-color: #4f46e5; }
            50% { border-color: #7c3aed; }
            100% { border-color: #4f46e5; }
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        @keyframes slideInLeft {
            from { transform: translateX(-50px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
        
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .animate-entry {
            animation: fadeIn 0.8s ease-out forwards;
        }
        
        .animate-pulse-hover:hover {
            animation: pulse 1.5s infinite ease-in-out;
        }
        
        .animate-slide-left {
            animation: slideInLeft 0.8s ease-out forwards;
        }
        
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(79, 70, 229, 0.3);
            animation: pulse 1.5s infinite ease-in-out;
        }
        
        .profile-border {
            animation: colorPulse 6s infinite;
        }
        
        .social-icon:hover {
            animation: rotate 0.6s ease-in-out;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-100 font-sans leading-relaxed">
    <!-- Navigation Menu -->
    <nav class="bg-gray-800/80 backdrop-blur-md fixed w-full z-50 shadow-xl">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between items-center py-4">
                <div class="text-2xl font-bold text-purple-400">Ankesh<span class="text-white">Rathore</span></div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="hover:text-purple-400 transition duration-300">Home</a>
                    <a href="#about" class="hover:text-purple-400 transition duration-300">About</a>
                    <a href="#skills" class="hover:text-purple-400 transition duration-300">Skills</a>
                    <a href="Profilee.html" class="hover:text-purple-400 transition duration-300">Contact</a>
                </div>
                <div class="md:hidden">
                    <button id="menu-toggle" class="text-white focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-gray-800/95 px-4 pb-4">
            <a href="#home" class="block py-2 hover:text-purple-400 transition duration-300">Home</a>
            <a href="#about" class="block py-2 hover:text-purple-400 transition duration-300">About</a>
            <a href="#skills" class="block py-2 hover:text-purple-400 transition duration-300">Skills</a>
            <title>"E:\My_code\C++\Profilee.html"</title>
            <a href="Profilee.html" class="block py-2 hover:text-purple-400 transition duration-300">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center justify-center pt-20 px-4">
        <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
            <div class="animate-entry" style="animation-delay: 0.2s;">
                <h1 class="text-4xl md:text-6xl font-bold mb-6">
                    Hi, I'm <span class="text-purple-400">Ankesh</span>
                </h1>
                <h2 class="text-2xl md:text-3xl mb-6 text-purple-200">Computer Science Student & Game Developer</h2>
                <p class="text-lg mb-8 text-gray-300">
                    Passionate about programming, game development, and artificial intelligence. 
                    Currently pursuing my degree while building innovative digital experiences.
                </p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-purple-600 hover:bg-purple-700 text-white px-6 py-3 rounded-lg transition duration-300 animate-pulse-hover">
                        Contact Me
                    </a>
                    <a href="#skills" class="border border-purple-400 text-purple-400 hover:bg-purple-400/10 px-6 py-3 rounded-lg transition duration-300 animate-pulse-hover">
                        View Skills
                    </a>
                </div>
            </div>
            <div class="animate-entry flex justify-center" style="animation-delay: 0.4s;">
                <div class="profile-border relative rounded-full p-1 bg-gradient-to-r from-purple-600 to-indigo-600 w-64 h-64 md:w-80 md:h-80">
                    <div class="w-full h-full rounded-full overflow-hidden bg-gray-800 animate-pulse-hover">
                        <img src="https://raw.githubusercontent.com/Ankesh21-Rathore/portfolio.ankesh.rathore/d53901e37732e83747c27bf96d06294c0899b509/WhatsApp%20Image%202025-09-05%20at%2022.18.56_a6388844.jpg" 
                             alt="Professional profile photo of Ankesh Rathore, computer science student and game developer"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="absolute -bottom-4 left-1/2 transform -translate-x-1/2 bg-purple-600 px-4 py-2 rounded-full text-sm font-semibold whitespace-nowrap">
                        AI & Game Dev Expert
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 px-4 bg-gray-800/50">
        <div class="max-w-4xl mx-auto animate-entry">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 text-center">
                About <span class="text-purple-400">Me</span>
            </h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="md:col-span-2">
                    <p class="text-lg mb-6 text-gray-300">
                        I'm Ankesh Rathore, a passionate computer science student specializing in game development and artificial intelligence. 
                        Currently pursuing my degree, I'm deeply fascinated by the intersection of programming and creative technologies.
                    </p>
                    <p class="text-lg mb-6 text-gray-300">
                        My technical journey began with learning C and C++, which developed into a love for game engines like Unity and Unreal. 
                        I enjoy creating immersive digital experiences that combine technical precision with creative vision.
                    </p>
                    <p class="text-lg text-gray-300">
                        Outside of coding, I'm an avid learner who enjoys staying updated with the latest in technology, 
                        particularly in the fields of AI and interactive media. I believe in continuous improvement 
                        and pushing boundaries in digital creation.
                    </p>
                </div>
                <div class="flex items-center justify-center animate-slide-left" style="animation-delay: 0.3s;">
                    <div class="bg-gray-700/50 p-6 rounded-xl border border-gray-600 w-full">
                        <div class="flex items-center mb-4">
                            <div class="bg-purple-600/20 p-2 rounded-lg mr-4">
                                <i class="fas fa-user-graduate text-purple-400 text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold">Education</h3>
                                <p class="text-sm text-gray-400">Bachelor of Technology (CSE)</p>
                            </div>
                        </div>
                        <div class="flex items-center mb-4">
                            <div class="bg-purple-600/20 p-2 rounded-lg mr-4">
                                <i class="fas fa-laptop-code text-purple-400 text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold">Specialization</h3>
                                <p class="text-sm text-gray-400">Game Development & AI</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-purple-600/20 p-2 rounded-lg mr-4">
                                <i class="fas fa-envelope text-purple-400 text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold">Contact</h3>
                                <p class="text-sm text-gray-400">as9921645@gmail.com</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 px-4">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold mb-16 text-center animate-entry">
                Technical <span class="text-purple-400">Skills</span>
            </h2>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Programming Languages -->
                <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 hover:border-purple-500 transition duration-300 skill-card animate-entry" style="animation-delay: 0.2s;">
                    <div class="flex items-center mb-4">
                        <div class="bg-purple-600/20 p-3 rounded-lg mr-4">
                            <i class="fas fa-code text-purple-400 text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold">Programming</h3>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>C/C++ (Advanced)</span>
                        </li>
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>Java (Advanced)</span>
                        </li>
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>C# (Proficient)</span>
                        </li>
                    </ul>
                </div>
                
                <!-- Game Development -->
                <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 hover:border-purple-500 transition duration-300 skill-card animate-entry" style="animation-delay: 0.4s;">
                    <div class="flex items-center mb-4">
                        <div class="bg-purple-600/20 p-3 rounded-lg mr-4">
                            <i class="fas fa-gamepad text-purple-400 text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold">Game Development</h3>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>Unity Engine</span>
                        </li>
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>Unreal Engine</span>
                        </li>
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>3D Modeling Basics</span>
                        </li>
                    </ul>
                </div>
                
                <!-- AI Expertise -->
                <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 hover:border-purple-500 transition duration-300 skill-card animate-entry" style="animation-delay: 0.6s;">
                    <div class="flex items-center mb-4">
                        <div class="bg-purple-600/20 p-3 rounded-lg mr-4">
                            <i class="fas fa-brain text-purple-400 text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold">AI Expertise</h3>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>Machine Learning</span>
                        </li>
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>AI in 3D Modeling</span>
                        </li>
                        <li class="flex items-center">
                            <span class="bg-gray-700 rounded-full w-2 h-2 mr-2"></span>
                            <span>AI in Game Dev</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-4 bg-gray-800/50">
        <div class="max-w-4xl mx-auto animate-entry">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 text-center">
                Get In <span class="text-purple-400">Touch</span>
            </h2>
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-xl font-semibold mb-6">Contact Information</h3>
                    <ul class="space-y-6">
                        <li class="flex items-start">
                            <div class="bg-purple-600/20 p-3 rounded-lg mr-4">
                                <i class="fas fa-envelope text-purple-400"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Email</h4>
                                <p class="text-gray-400">as9921645@gmail.com</p>
                            </div>
                        </li>
                        <li class="flex items-start">
                            <div class="bg-purple-600/20 p-3 rounded-lg mr-4">
                                <i class="fas fa-map-marker-alt text-purple-400"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Location</h4>
                                <p class="text-gray-400">ITM Gwalior - 474001</p>
                            </div>
                        </li>
                    </ul>
                </div>
                <div>
                    <form class="space-y-6">
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800/80 py-8 px-4 border-t border-gray-700">
        <div class="max-w-6xl mx-auto">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0 text-xl font-bold text-purple-400">Ankesh<span class="text-white">Rathore</span></div>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-purple-400 transition duration-300">
                        <i class="fab fa-github text-2xl social-icon"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-purple-400 transition duration-300">
                        <i class="fab fa-linkedin text-2xl social-icon"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-purple-400 transition duration-300">
                        <i class="fab fa-twitter text-2xl social-icon"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-purple-400 transition duration-300">
                        <i class="fab fa-instagram text-2xl social-icon"></i>
                    </a
                </div>
            </div>
            <div class="mt-6 pt-6 border-t border-gray-700 text-center text-gray-400 text-sm">
                <p>© 2025 Ankesh Rathore. Second_Year.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('menu-toggle').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                const mobileMenu = document.getElementById('mobile-menu');
                
                if (targetElement) {
                    // Close mobile menu if open
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                    
                    // Smooth scroll to target
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Scroll animation for elements
        document.addEventListener('DOMContentLoaded', function() {
            const animateElements = document.querySelectorAll('.animate-entry');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = 1;
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, { threshold: 0.1 });
            
            animateElements.forEach(element => {
                element.style.opacity = 0;
                observer.observe(element);
            });
        });
    </script>
</body>
</html>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete Contact Page</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.emailjs.com/sdk/3.2.0/email.min.js"></script>
    <script>
        (function(){
            emailjs.init("service_p01px5m"); // Replace with your EmailJS user ID after signing up
        })();
    </script>
    <style>
        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            font-family: 'Arial', sans-serif;
            color: white;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        .contact-form {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 12px;
            padding: 30px;
            max-width: 500px;
            width: 100%;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
        }
        .contact-form h1 {
            text-align: center;
            margin-bottom: 24px;
        }
        .form-group {
            margin-bottom: 16px;
        }
        .form-group label {
            display: block;
            margin-bottom: 6px;
            font-weight: bold;
        }
        .form-group input, .form-group textarea {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 8px;
            background: rgba(255, 255, 255, 0.2);
            color: white;
            font-size: 1rem;
            box-sizing: border-box;
        }
        .form-group input:focus, .form-group textarea:focus {
            outline: none;
            background: rgba(255, 255, 255, 0.3);
            box-shadow: 0 0 8px 2px rgba(102, 126, 234, 0.7);
        }
        .form-group textarea {
            resize: vertical;
            min-height: 100px;
        }
        button {
            width: 100%;
            padding: 14px;
            background: #667eea;
            border: none;
            border-radius: 8px;
            color: white;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        button:hover {
            background: #5a67d8;
        }
        .message {
            text-align: center;
            margin-top: 16px;
            font-weight: bold;
        }
        .success { color: #34d399; }
        .error { color: #f87171; }
    </style>
</head>
<body>
    <div class="contact-form">
        <h1>Contact Us</h1>
        <form id="contactForm" novalidate>
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required placeholder="Your name">
                <p class="error" id="nameError" style="display: none;">Please enter your name.</p>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required placeholder="you@example.com">
                <p class="error" id="emailError" style="display: none;">Please enter a valid email.</p>
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea id="message" name="message" required placeholder="Your message"></textarea>
                <p class="error" id="messageError" style="display: none;">Please enter a message.</p>
            </div>
            <button type="submit">Send Message</button>
        </form>
        <p id="formMessage" class="message"></p>
    </div>

    <script>
        const form = document.getElementById('contactForm');
        const nameInput = document.getElementById('name');
        const emailInput = document.getElementById('email');
        const messageInput = document.getElementById('message');
        const formMessage = document.getElementById('formMessage');
        const nameError = document.getElementById('nameError');
        const emailError = document.getElementById('emailError');
        const messageError = document.getElementById('messageError');

        function validateEmail(email) {
            return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email);
        }

        form.addEventListener('submit', function (e) {
            e.preventDefault();

            // Hide errors
            nameError.style.display = 'none';
            emailError.style.display = 'none';
            messageError.style.display = 'none';
            formMessage.textContent = '';
            formMessage.className = 'message';

            let valid = true;
            if (!nameInput.value.trim()) {
                nameError.style.display = 'block';
                valid = false;
            }
            if (!validateEmail(emailInput.value.trim())) {
                emailError.style.display = 'block';
                valid = false;
            }
            if (!messageInput.value.trim()) {
                messageError.style.display = 'block';
                valid = false;
            }
            if (!valid) return;

            formMessage.textContent = 'Sending message...';
            formMessage.className = 'message';

            // Replace with your EmailJS service and template IDs
            emailjs.send("service_p01px5m", "template_lakns5d", {
                from_name: nameInput.value,
                from_email: emailInput.value,
                message: messageInput.value,
            })
            .then(() => {
                formMessage.textContent = 'Thank you! Your message has been sent.';
                formMessage.className = 'message success';
                form.reset();
            }, (error) => {
                formMessage.textContent = 'Oops! Something went wrong. Please try again.';
                formMessage.className = 'message error';
                console.error('EmailJS error:', error);
            });
        });
    </script>
</body>
</html>
</content>
</create_file>
</tools_action>
