<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Satyadarshi Rout - Portfolio</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    
    <style>
        /* Dark Mode Styles */
        .dark-mode { background-color: #1a202c; color: #f7fafc; }
        .dark-mode section, .dark-mode header, .dark-mode footer, .dark-mode #mobile-menu { background-color: #1a202c; color: #f7fafc; }
        .dark-mode .bg-white { background-color: #2d3748; color: #f7fafc; }
        .dark-mode .bg-gray-100 { background-color: #4a5568; }
        .dark-mode .text-gray-600 { color: #cbd5e0; }
        .dark-mode .text-blue-900 { color: #90cdf4; }
        .dark-mode .shadow-md, .dark-mode .shadow-lg, .dark-mode .shadow-xl { box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.5), 0 4px 6px -2px rgba(0, 0, 0, 0.25); }
        /* Ensure form inputs are readable in dark mode */
        .dark-mode input, .dark-mode textarea { background-color: #4a5568; border-color: #718096; color: white; }
    </style>
</head>
<body id="body" class="bg-gray-50 text-gray-800 font-sans leading-relaxed transition-colors duration-300">

    <header class="bg-blue-900 text-white sticky top-0 z-50 shadow-lg">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center relative">
            <a href="#" class="text-2xl font-bold tracking-wider hover:text-blue-200 transition">S. ROUT</a>
            
            <nav class="hidden md:flex items-center space-x-6">
                <ul class="flex space-x-6">
                    <li><a href="#about" class="hover:text-blue-300 transition">About</a></li>
                    <li><a href="#skills" class="hover:text-blue-300 transition">Skills</a></li>
                    <li><a href="#projects" class="hover:text-blue-300 transition">Projects</a></li>
                    <li><a href="#contact" class="hover:text-blue-300 transition">Contact</a></li>
                </ul>
                <button id="theme-toggle-desktop" class="bg-blue-700 hover:bg-blue-600 px-3 py-2 rounded-full transition ml-4">
                    <i class="fas fa-moon"></i>
                </button>
            </nav>

            <div class="md:hidden flex items-center space-x-4">
                 <button id="theme-toggle-mobile" class="text-blue-200 hover:text-white focus:outline-none">
                    <i class="fas fa-moon text-xl"></i>
                </button>
                <button id="mobile-menu-button" class="text-blue-200 hover:text-white focus:outline-none">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </div>

        <div id="mobile-menu" class="hidden md:hidden absolute w-full bg-blue-900 shadow-lg z-40">
            <ul class="flex flex-col p-4 space-y-4 font-semibold">
                <li><a href="#about" class="block text-blue-200 hover:text-white transition">About</a></li>
                <li><a href="#skills" class="block text-blue-200 hover:text-white transition">Skills</a></li>
                <li><a href="#projects" class="block text-blue-200 hover:text-white transition">Projects</a></li>
                <li><a href="#contact" class="block text-blue-200 hover:text-white transition">Contact</a></li>
            </ul>
        </div>
    </header>

    <main>
        <section id="about" class="py-20 bg-white">
            <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 md:pr-10 mb-10 md:mb-0">
                    <h3 id="greeting-msg" class="text-blue-500 font-semibold mb-2">Hello!</h3>
                    <h1 class="text-4xl md:text-6xl font-bold text-blue-900 mb-4">I'm <span class="text-blue-600">Satyadarshi Rout</span></h1>
                    <h2 class="text-xl md:text-2xl text-gray-600 mb-6 font-medium">Mechanical Engineering Student | Data Science Enthusiast</h2>
                    <p class="text-gray-600 mb-6 text-lg leading-relaxed">
                        I am a B.Tech student at <strong>Odisha University of Technology and Research (OUTR)</strong>. I bridge the gap between mechanical engineering principles and digital innovation through data science and web development.
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <a href="#contact" class="bg-blue-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-700 transition shadow-md">Contact Me</a>
                        <a href="https://www.linkedin.com/in/satyadarshi-rout-606388309" target="_blank" class="border-2 border-blue-600 text-blue-600 px-6 py-3 rounded-lg font-semibold hover:bg-blue-50 transition">
                            <i class="fab fa-linkedin"></i> LinkedIn
                        </a>
                    </div>
                </div>
                
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative w-64 h-64 md:w-80 md:h-80 rounded-full shadow-xl border-4 border-white overflow-hidden">
                        <img src="https://via.placeholder.com/400x400?text=Your+Photo+Here" alt="Satyadarshi Rout" class="w-full h-full object-cover">
                    </div>
                </div>
            </div>
        </section>

        <section id="skills" class="py-16 bg-gray-100">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl font-bold text-center text-blue-900 mb-12">Technical Skills</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300 border-t-4 border-blue-500">
                        <div class="text-blue-500 text-4xl mb-4"><i class="fas fa-code"></i></div>
                        <h3 class="text-xl font-bold mb-4 text-gray-800">Languages</h3>
                        <ul class="space-y-2 text-gray-600 list-disc list-inside">
                            <li>Python</li>
                            <li>JavaScript</li>
                            <li>HTML & CSS</li>
                            <li>Go</li>
                        </ul>
                    </div>
                     <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300 border-t-4 border-green-500">
                        <div class="text-green-500 text-4xl mb-4"><i class="fas fa-layer-group"></i></div>
                        <h3 class="text-xl font-bold mb-4 text-gray-800">Frameworks</h3>
                        <ul class="space-y-2 text-gray-600 list-disc list-inside">
                            <li>React & Flutter</li>
                            <li>Streamlit</li>
                            <li>TensorFlow & Scikit-learn</li>
                        </ul>
                    </div>
                     <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300 border-t-4 border-purple-500">
                        <div class="text-purple-500 text-4xl mb-4"><i class="fas fa-tools"></i></div>
                        <h3 class="text-xl font-bold mb-4 text-gray-800">Tools & Platforms</h3>
                        <ul class="space-y-2 text-gray-600 list-disc list-inside">
                            <li>Git & GitHub</li>
                            <li>AWS S3</li>
                            <li>PowerBI & Figma</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="py-16 bg-blue-900 text-white">
            <div class="container mx-auto px-4">
                <div class="max-w-2xl mx-auto text-center mb-10">
                    <h2 class="text-3xl font-bold mb-4">Get In Touch</h2>
                    <p class="text-blue-200">Feel free to reach out for collaborations or just a friendly hello!</p>
                </div>
                <div class="max-w-xl mx-auto bg-white rounded-lg shadow-2xl p-8 text-gray-800">
                    <form id="contact-form">
                        <div class="mb-6">
                            <label for="name" class="block text-sm font-semibold mb-2">Name</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:outline-none transition" placeholder="Your Name">
                            <p id="name-error" class="text-red-500 text-xs mt-1 hidden">Name is required</p>
                        </div>
                        
                        <div class="mb-6">
                            <label for="email" class="block text-sm font-semibold mb-2">Email</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:outline-none transition" placeholder="your@email.com">
                            <p id="email-error" class="text-red-500 text-xs mt-1 hidden">Please enter a valid email</p>
                        </div>
                        
                        <div class="mb-6">
                            <label for="message" class="block text-sm font-semibold mb-2">Message</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:outline-none transition" placeholder="Write your message..."></textarea>
                            <p id="msg-error" class="text-red-500 text-xs mt-1 hidden">Message cannot be empty</p>
                        </div>

                        <button type="submit" class="w-full bg-blue-600 text-white font-bold py-3 rounded-md hover:bg-blue-700 transition duration-300 shadow-lg transform active:scale-95">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-gray-900 text-gray-400 py-8 text-center">
        <div class="container mx-auto px-4">
            <p>&copy; 2025 Satyadarshi Rout. All Rights Reserved.</p>
            <p class="text-sm mt-2">Built with HTML5, Tailwind CSS & JavaScript</p>
        </div>
    </footer>

    <script>
        // --- Global Variables ---
        const body = document.getElementById('body');
        const themeToggleBtnDesktop = document.getElementById('theme-toggle-desktop');
        const themeToggleBtnMobile = document.getElementById('theme-toggle-mobile');
        const mobileMenuBtn = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        const greetingElement = document.getElementById('greeting-msg');
        const contactForm = document.getElementById('contact-form');

        // --- 1. Dynamic Greeting Function ---
        function setGreeting() {
            const hour = new Date().getHours();
            let greetingText = hour < 12 ? "Good Morning!" : (hour < 18 ? "Good Afternoon!" : "Good Evening!");
            greetingElement.textContent = greetingText;
        }
        setGreeting(); // Run on page load

        // --- 2. Dark/Light Mode Toggle Function ---
        function toggleTheme() {
            body.classList.toggle('dark-mode');
            const isDark = body.classList.contains('dark-mode');
            const iconClassToRemove = isDark ? 'fa-moon' : 'fa-sun';
            const iconClassToAdd = isDark ? 'fa-sun' : 'fa-moon';

            // Update both desktop and mobile icons concurrently
            [themeToggleBtnDesktop, themeToggleBtnMobile].forEach(btn => {
                const icon = btn.querySelector('i');
                icon.classList.remove(iconClassToRemove);
                icon.classList.add(iconClassToAdd);
            });
        }
        // Attach event listeners to both theme buttons
        themeToggleBtnDesktop.addEventListener('click', toggleTheme);
        themeToggleBtnMobile.addEventListener('click', toggleTheme);

        // --- 3. Mobile Menu Toggle Function ---
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            // Toggle between hamburger (bars) and close (times) icon
            const icon = mobileMenuBtn.querySelector('i');
            if (mobileMenu.classList.contains('hidden')) {
               icon.classList.remove('fa-times');
               icon.classList.add('fa-bars');
            } else {
               icon.classList.remove('fa-bars');
               icon.classList.add('fa-times');
            }
        });

        // Close mobile menu automatically when a link is clicked
        mobileMenu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                mobileMenuBtn.querySelector('i').classList.remove('fa-times');
                mobileMenuBtn.querySelector('i').classList.add('fa-bars');
            });
        });

        // --- 4. Contact Form Validation ---
        contactForm.addEventListener('submit', function(event) {
            event.preventDefault(); // Stop form from submitting
            
            const name = document.getElementById('name').value.trim();
            const email = document.getElementById('email').value.trim();
            const message = document.getElementById('message').value.trim();
            let isValid = true;

            // Validation Logic
            if (name === "") {
                document.getElementById('name-error').classList.remove('hidden');
                isValid = false;
            } else { document.getElementById('name-error').classList.add('hidden'); }

            // Simple email regex pattern for validation
            const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (email === "" || !emailPattern.test(email)) {
                document.getElementById('email-error').classList.remove('hidden');
                isValid = false;
            } else { document.getElementById('email-error').classList.add('hidden'); }

            if (message === "") {
                document.getElementById('msg-error').classList.remove('hidden');
                isValid = false;
            } else { document.getElementById('msg-error').classList.add('hidden'); }

            if (isValid) {
                // In a real app, you would send this data to a backend server here.
                alert(`Thank you, ${name}! Your message has been validated. In a real application, it would be sent now.`);
                contactForm.reset(); // Clear form fields
            }
        });
    </script>
</body>
</html>
