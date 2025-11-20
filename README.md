# Personal-Portfolio-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Satyadarshi Rout - Portfolio</title>
    
    <!-- Tailwind CSS for styling (Makes the HTML look professional) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Icons for social media and contact info -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    
    <style>
        /* Smooth scrolling for navigation links */
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans leading-relaxed">

    <!-- HEADER & NAVIGATION (HTML5 Semantic Element) -->
    <header class="bg-blue-900 text-white sticky top-0 z-50 shadow-lg">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <!-- Logo / Name -->
            <a href="#" class="text-2xl font-bold tracking-wider hover:text-blue-200 transition">S. ROUT</a>
            
            <!-- Nav Bar -->
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#about" class="hover:text-blue-300 transition">About</a></li>
                    <li><a href="#skills" class="hover:text-blue-300 transition">Skills</a></li>
                    <li><a href="#projects" class="hover:text-blue-300 transition">Projects</a></li>
                    <li><a href="#contact" class="hover:text-blue-300 transition">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <!-- HERO / INTRO SECTION -->
        <section id="about" class="py-20 bg-white">
            <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
                <!-- Text Content -->
                <div class="md:w-1/2 md:pr-10">
                    <h1 class="text-4xl md:text-6xl font-bold text-blue-900 mb-4">Hi, I'm <span class="text-blue-600">Satyadarshi Rout</span></h1>
                    <h2 class="text-xl md:text-2xl text-gray-600 mb-6 font-medium">Mechanical Engineering Student | Data Science Enthusiast | Web Developer</h2>
                    <p class="text-gray-600 mb-6 text-lg">
                        I am a B.Tech student at <strong>Odisha University of Technology and Research (OUTR)</strong>. 
                        I bridge the gap between mechanical engineering and digital innovation. I have experience as a 
                        <strong>Data Scientist Intern</strong> at Compute Avenue and active involvement in the 
                        <strong>Google Developer Group</strong> and <strong>Zairza Technical Club</strong>.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#contact" class="bg-blue-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-700 transition shadow-md">Contact Me</a>
                        <a href="https://www.linkedin.com/in/satyadarshi-rout-606388309" target="_blank" class="border-2 border-blue-600 text-blue-600 px-6 py-3 rounded-lg font-semibold hover:bg-blue-50 transition">
                            <i class="fab fa-linkedin"></i> LinkedIn
                        </a>
                    </div>
                </div>
                
                <!-- Profile Image Placeholder (SVG) -->
                <div class="md:w-1/2 mt-10 md:mt-0 flex justify-center">
                    <div class="relative w-64 h-64 md:w-80 md:h-80 bg-blue-100 rounded-full flex items-center justify-center shadow-xl border-4 border-white overflow-hidden">
                        <!-- Using an SVG as a placeholder for your photo -->
                        <svg class="w-40 h-40 text-blue-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" clip-rule="evenodd"></path></svg>
                    </div>
                </div>
            </div>
        </section>

        <!-- SKILLS SECTION -->
        <section id="skills" class="py-16 bg-gray-100">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl font-bold text-center text-blue-900 mb-12">Technical Skills</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Language Category -->
                    <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300 border-t-4 border-blue-500">
                        <div class="text-blue-500 text-4xl mb-4"><i class="fas fa-code"></i></div>
                        <h3 class="text-xl font-bold mb-4">Languages</h3>
                        <ul class="space-y-2 text-gray-600 list-disc list-inside">
                            <li>Python</li>
                            <li>JavaScript</li>
                            <li>HTML & CSS</li>
                            <li>Go</li>
                        </ul>
                    </div>

                    <!-- Frameworks Category -->
                    <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300 border-t-4 border-green-500">
                        <div class="text-green-500 text-4xl mb-4"><i class="fas fa-layer-group"></i></div>
                        <h3 class="text-xl font-bold mb-4">Frameworks</h3>
                        <ul class="space-y-2 text-gray-600 list-disc list-inside">
                            <li>React & Flutter</li>
                            <li>Streamlit</li>
                            <li>TensorFlow & Scikit-Learn</li>
                            <li>Flask</li>
                        </ul>
                    </div>

                    <!-- Tools Category -->
                    <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300 border-t-4 border-purple-500">
                        <div class="text-purple-500 text-4xl mb-4"><i class="fas fa-tools"></i></div>
                        <h3 class="text-xl font-bold mb-4">Tools & Platforms</h3>
                        <ul class="space-y-2 text-gray-600 list-disc list-inside">
                            <li>Git & GitHub</li>
                            <li>AWS S3 & Firebase</li>
                            <li>Figma & PowerBI</li>
                            <li>VS Studio</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- PROJECTS SECTION -->
        <section id="projects" class="py-16 bg-white">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl font-bold text-center text-blue-900 mb-12">Key Projects</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Project 1 -->
                    <article class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 flex flex-col">
                        <div class="p-6 flex-grow">
                            <div class="flex justify-between items-start mb-4">
                                <h3 class="text-xl font-bold text-gray-800">E-commerce Dashboard</h3>
                                <span class="bg-blue-100 text-blue-800 text-xs px-2 py-1 rounded-full">Streamlit</span>
                            </div>
                            <p class="text-gray-600 text-sm mb-4">
                                Built an interactive dashboard to help businesses visualize sales, customer, and product data. 
                                Features dynamic filters and integrated CSV uploads.
                            </p>
                            <div class="text-xs text-gray-500 mb-4 font-semibold">
                                Tech: Python, Pandas, Plotly, PowerBI
                            </div>
                        </div>
                        <div class="bg-gray-100 p-4 border-t border-gray-200 text-center">
                            <a href="#" class="text-blue-600 hover:text-blue-800 font-medium text-sm">View Repository <i class="fas fa-arrow-right ml-1"></i></a>
                        </div>
                    </article>

                    <!-- Project 2 -->
                    <article class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 flex flex-col">
                        <div class="p-6 flex-grow">
                            <div class="flex justify-between items-start mb-4">
                                <h3 class="text-xl font-bold text-gray-800">AI Chatbot for College</h3>
                                <span class="bg-green-100 text-green-800 text-xs px-2 py-1 rounded-full">NLP</span>
                            </div>
                            <p class="text-gray-600 text-sm mb-4">
                                Developed an AI-powered chatbot using NLP models to handle student queries instantly, 
                                reducing response time by 70%.
                            </p>
                            <div class="text-xs text-gray-500 mb-4 font-semibold">
                                Tech: Python, Flask, TensorFlow
                            </div>
                        </div>
                        <div class="bg-gray-100 p-4 border-t border-gray-200 text-center">
                            <a href="#" class="text-blue-600 hover:text-blue-800 font-medium text-sm">View Repository <i class="fas fa-arrow-right ml-1"></i></a>
                        </div>
                    </article>

                    <!-- Project 3 -->
                    <article class="bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-xl transition duration-300 flex flex-col">
                        <div class="p-6 flex-grow">
                            <div class="flex justify-between items-start mb-4">
                                <h3 class="text-xl font-bold text-gray-800">Sales Prediction ML</h3>
                                <span class="bg-purple-100 text-purple-800 text-xs px-2 py-1 rounded-full">Machine Learning</span>
                            </div>
                            <p class="text-gray-600 text-sm mb-4">
                                Implemented ML models to predict sales based on historical data, helping businesses optimize 
                                inventory and reduce stockouts.
                            </p>
                            <div class="text-xs text-gray-500 mb-4 font-semibold">
                                Tech: Scikit-learn, Pandas, Seaborn
                            </div>
                        </div>
                        <div class="bg-gray-100 p-4 border-t border-gray-200 text-center">
                            <a href="#" class="text-blue-600 hover:text-blue-800 font-medium text-sm">View Repository <i class="fas fa-arrow-right ml-1"></i></a>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- CONTACT FORM SECTION -->
        <section id="contact" class="py-16 bg-blue-900 text-white">
            <div class="container mx-auto px-4">
                <div class="max-w-2xl mx-auto text-center mb-10">
                    <h2 class="text-3xl font-bold mb-4">Get In Touch</h2>
                    <p class="text-blue-200">Feel free to reach out for collaborations or just a friendly hello!</p>
                </div>

                <div class="max-w-xl mx-auto bg-white rounded-lg shadow-2xl p-8 text-gray-800">
                    <!-- HTML5 Form -->
                    <form action="#" method="POST">
                        <div class="mb-6">
                            <label for="name" class="block text-sm font-semibold mb-2">Name</label>
                            <input type="text" id="name" name="name" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:outline-none" placeholder="Your Name" required>
                        </div>
                        
                        <div class="mb-6">
                            <label for="email" class="block text-sm font-semibold mb-2">Email</label>
                            <input type="email" id="email" name="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:outline-none" placeholder="your.email@example.com" required>
                        </div>
                        
                        <div class="mb-6">
                            <label for="message" class="block text-sm font-semibold mb-2">Message</label>
                            <textarea id="message" name="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:outline-none" placeholder="Write your message here..." required></textarea>
                        </div>

                        <button type="submit" class="w-full bg-blue-600 text-white font-bold py-3 rounded-md hover:bg-blue-700 transition duration-300 shadow-lg">
                            Send Message
                        </button>
                    </form>

                    <div class="mt-8 text-center border-t pt-6">
                        <p class="text-gray-600 mb-4">Or connect via</p>
                        <div class="flex justify-center space-x-6">
                            <a href="https://www.linkedin.com/in/satyadarshi-rout-606388309" target="_blank" class="text-2xl text-blue-600 hover:text-blue-800 transition"><i class="fab fa-linkedin"></i></a>
                            <a href="mailto:satyadarshirout2005@gmail.com" class="text-2xl text-red-500 hover:text-red-700 transition"><i class="fas fa-envelope"></i></a>
                            <a href="#" class="text-2xl text-gray-800 hover:text-black transition"><i class="fab fa-github"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- FOOTER -->
    <footer class="bg-gray-900 text-gray-400 py-8 text-center">
        <div class="container mx-auto px-4">
            <p>&copy; 2025 Satyadarshi Rout. All Rights Reserved.</p>
            <p class="text-sm mt-2">Built with HTML5 & Tailwind CSS</p>
        </div>
    </footer>

</body>
</html>
