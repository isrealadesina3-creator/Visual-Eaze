<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VISUAL EAZE STUDIOS | Graphics & Photography Portfolio</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font and base styles */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        :root {
            --primary-color: #0d1117; /* Dark background */
            --secondary-color: #161b22; /* Slightly lighter dark for cards */
            --accent-color: #00bcd4; /* Cyan/Electric Blue for accents */
            --text-color: #c9d1d9; /* Light gray text */
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--primary-color);
            color: var(--text-color);
            line-height: 1.6;
        }
        /* Ensures smooth scroll to anchor links */
        html {
            scroll-behavior: smooth;
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#0d1117',
                        secondary: '#161b22',
                        accent: '#00bcd4',
                    }
                }
            }
        }
    </script>
</head>
<body>

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-primary/95 backdrop-blur-sm shadow-lg">
        <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- Logo & Company Name -->
            <a href="#" class="flex items-center space-x-2">
                <!-- Inline SVG Logo: Stylized Camera/Aperture -->
                <svg class="w-8 h-8 text-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.19 4h3.633a2 2 0 011.664.89l.812 1.22a2 2 0 001.664.89H21a2 2 0 012 2v10a2 2 0 01-2 2H3a2 2 0 01-2-2V9z"></path>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 13a3 3 0 11-6 0 3 3 0 016 0z"></path>
                </svg>
                <span class="text-xl font-extrabold text-white tracking-wider">VISUAL EAZE STUDIOS</span>
            </a>
            
            <!-- Mobile Menu Toggler (Hidden on larger screens) -->
            <button id="menu-toggle" class="md:hidden p-2 rounded-lg hover:bg-secondary transition duration-300">
                <svg class="w-6 h-6 text-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                </svg>
            </button>
            
            <!-- Desktop Links -->
            <div class="hidden md:flex space-x-6">
                <a href="#services" class="text-text-color hover:text-accent transition duration-300 font-medium">Services</a>
                <a href="#portfolio" class="text-text-color hover:text-accent transition duration-300 font-medium">Portfolio</a>
                <a href="#contact" class="text-text-color hover:text-accent transition duration-300 font-medium">Contact</a>
            </div>
        </nav>

        <!-- Mobile Menu (Initially Hidden) -->
        <div id="mobile-menu" class="hidden md:hidden bg-secondary w-full transition-all duration-300 ease-in-out">
            <div class="px-4 pt-2 pb-3 space-y-1">
                <a href="#services" class="block px-3 py-2 rounded-md text-base font-medium text-text-color hover:bg-primary hover:text-accent">Services</a>
                <a href="#portfolio" class="block px-3 py-2 rounded-md text-base font-medium text-text-color hover:bg-primary hover:text-accent">Portfolio</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium text-text-color hover:bg-primary hover:text-accent">Contact</a>
            </div>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="relative overflow-hidden pt-20 pb-16 md:pt-32 md:pb-24">
            <div class="container mx-auto px-4 text-center">
                <h1 class="text-4xl sm:text-6xl font-extrabold leading-tight mb-4 text-white">
                    Your <span class="text-accent">Vision</span>, Our <span class="text-accent">Eaze</span>.
                </h1>
                <p class="text-lg sm:text-xl max-w-3xl mx-auto mb-8 text-gray-400">
                    VISUAL EAZE STUDIOS is your dedicated partner in Lagos, Nigeria, for stunning graphics, professional photography, and immersive visual content creation.
                </p>
                <a href="#portfolio" class="inline-block px-8 py-3 text-lg font-semibold text-primary bg-accent rounded-full hover:bg-cyan-500 transition duration-300 shadow-xl transform hover:scale-105">
                    View Our Work
                </a>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-16 md:py-24 bg-secondary">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl sm:text-4xl font-bold text-center mb-12 text-white">Our Expertise</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Service Card 1: Graphics Content -->
                    <div class="p-6 bg-primary rounded-xl shadow-2xl hover:shadow-accent/30 transition duration-500 transform hover:-translate-y-1">
                        <div class="text-accent mb-4">
                            <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 17h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-3 text-white">Graphics Content Creation</h3>
                        <p class="text-gray-400">From concept to execution, we craft compelling digital and print graphics, ensuring your brand message is sharp, memorable, and visually dynamic.</p>
                    </div>

                    <!-- Service Card 2: Photo Shoots -->
                    <div class="p-6 bg-primary rounded-xl shadow-2xl hover:shadow-accent/30 transition duration-500 transform hover:-translate-y-1">
                        <div class="text-accent mb-4">
                            <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-3 text-white">Professional Photo Shoots</h3>
                        <p class="text-gray-400">High-end shoots for fashion, products, portraits, and events. We capture the essence of the moment with professional lighting and direction.</p>
                    </div>

                    <!-- Service Card 3: Live Camera/Videography -->
                    <div class="p-6 bg-primary rounded-xl shadow-2xl hover:shadow-accent/30 transition duration-500 transform hover:-translate-y-1">
                        <div class="text-accent mb-4">
                            <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 10l4.55 4.55a2 2 0 010 2.83l-4.55 4.55-4.55-4.55a2 2 0 010-2.83L15 10zm-4 4h.01M3 8v6a4 4 0 004 4h6a4 4 0 004-4v-6a4 4 0 00-4-4H7a4 4 0 00-4 4z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-3 text-white">Live Camera & Videography</h3>
                        <p class="text-gray-400">Covering live events, interviews, and corporate videos. We provide top-tier live-action capture for dynamic storytelling.</p>
                    </div>

                    <!-- Service Card 4: All Photography -->
                    <div class="p-6 bg-primary rounded-xl shadow-2xl hover:shadow-accent/30 transition duration-500 transform hover:-translate-y-1">
                        <div class="text-accent mb-4">
                            <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.19 4h3.633a2 2 0 011.664.89l.812 1.22a2 2 0 001.664.89H21a2 2 0 012 2v10a2 2 0 01-2 2H3a2 2 0 01-2-2V9z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 13a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-3 text-white">Comprehensive Photography</h3>
                        <p class="text-gray-400">Covering all facets of still photography, ensuring every image meets the highest standard of clarity, composition, and artistic value.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Portfolio Section (Shooting Events Showcase) -->
        <section id="portfolio" class="py-16 md:py-24">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl sm:text-4xl font-bold text-center mb-12 text-white">Our Impressive Portfolio</h2>
                <p class="text-center text-lg max-w-2xl mx-auto mb-10 text-gray-400">A glimpse into our past shooting events—capturing high-stakes moments and delivering powerful visuals.</p>

                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 sm:gap-6">
                    <!-- Placeholder Images (Impressive Shooting Events) -->

                    <!-- Image 1: High-Fashion Shoot -->
                    <div class="overflow-hidden rounded-xl shadow-xl group cursor-pointer transform hover:scale-[1.02] transition duration-500">
                        <img src="https://placehold.co/600x400/00bcd4/161b22?text=High-Fashion+Shoot" alt="High-Fashion Photography Event" class="w-full h-48 object-cover transition-opacity duration-500 group-hover:opacity-80" loading="lazy">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent p-4 flex items-end">
                            <p class="text-sm font-semibold text-white">Fashion Event</p>
                        </div>
                    </div>

                    <!-- Image 2: Corporate Brand Graphics -->
                    <div class="overflow-hidden rounded-xl shadow-xl group cursor-pointer transform hover:scale-[1.02] transition duration-500">
                        <img src="https://placehold.co/600x400/1e293b/00bcd4?text=Corporate+Brand+Graphics" alt="Corporate Branding Design" class="w-full h-48 object-cover transition-opacity duration-500 group-hover:opacity-80" loading="lazy">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent p-4 flex items-end">
                            <p class="text-sm font-semibold text-white">Branding & Identity</p>
                        </div>
                    </div>
                    
                    <!-- Image 3: Product Photography Session -->
                    <div class="overflow-hidden rounded-xl shadow-xl group cursor-pointer transform hover:scale-[1.02] transition duration-500">
                        <img src="https://placehold.co/600x400/0d1117/00bcd4?text=Product+Photography" alt="Product Photography Session" class="w-full h-48 object-cover transition-opacity duration-500 group-hover:opacity-80" loading="lazy">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent p-4 flex items-end">
                            <p class="text-sm font-semibold text-white">Product Showcase</p>
                        </div>
                    </div>

                    <!-- Image 4: Live Event Videography -->
                    <div class="overflow-hidden rounded-xl shadow-xl group cursor-pointer transform hover:scale-[1.02] transition duration-500">
                        <img src="https://placehold.co/600x400/334155/00bcd4?text=Live+Event+Videography" alt="Live Event Videography Capture" class="w-full h-48 object-cover transition-opacity duration-500 group-hover:opacity-80" loading="lazy">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent p-4 flex items-end">
                            <p class="text-sm font-semibold text-white">Live Event Coverage</p>
                        </div>
                    </div>

                    <!-- Image 5: Logo Design Mockup -->
                    <div class="overflow-hidden rounded-xl shadow-xl group cursor-pointer transform hover:scale-[1.02] transition duration-500">
                        <img src="https://placehold.co/600x400/00bcd4/161b22?text=Unique+Logo+Design" alt="Unique Logo Design" class="w-full h-48 object-cover transition-opacity duration-500 group-hover:opacity-80" loading="lazy">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent p-4 flex items-end">
                            <p class="text-sm font-semibold text-white">Creative Logo Concepts</p>
                        </div>
                    </div>

                    <!-- Image 6: Portrait Photography -->
                    <div class="overflow-hidden rounded-xl shadow-xl group cursor-pointer transform hover:scale-[1.02] transition duration-500">
                        <img src="https://placehold.co/600x400/1e293b/00bcd4?text=Studio+Portrait+Session" alt="Studio Portrait Session" class="w-full h-48 object-cover transition-opacity duration-500 group-hover:opacity-80" loading="lazy">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent p-4 flex items-end">
                            <p class="text-sm font-semibold text-white">Studio Portraits</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer / Contact Section -->
    <footer id="contact" class="bg-primary pt-16 pb-8 border-t border-secondary">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl sm:text-4xl font-bold text-center mb-10 text-accent">Get in Touch</h2>
            
            <div class="flex flex-col md:flex-row justify-around items-start md:items-center space-y-8 md:space-y-0 text-center md:text-left">
                
                <!-- Contact Details -->
                <div class="w-full md:w-auto">
                    <h3 class="text-xl font-semibold mb-4 text-white">Contact Information</h3>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-center justify-center md:justify-start">
                            <svg class="w-5 h-5 mr-3 text-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                            <a href="mailto:visualeazestudios@gmail.com" class="hover:text-white transition duration-300">visualeazestudios@gmail.com</a>
                        </li>
                        <li class="flex items-center justify-center md:justify-start">
                            <svg class="w-5 h-5 mr-3 text-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                            <a href="tel:+2349042021352" class="hover:text-white transition duration-300">09042021352 (WhatsApp)</a>
                        </li>
                    </ul>
                </div>

                <!-- Location -->
                <div class="w-full md:w-auto">
                    <h3 class="text-xl font-semibold mb-4 text-white">Find Us</h3>
                    <p class="flex items-center justify-center md:justify-start text-gray-400">
                        <svg class="w-5 h-5 mr-3 text-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                        Lagos, Nigeria
                    </p>
                </div>
            </div>

            <div class="mt-12 text-center text-sm text-gray-600 border-t border-gray-700 pt-6">
                &copy; <span id="current-year"></span> VISUAL EAZE STUDIOS. All rights reserved.
            </div>
        </div>
    </footer>

    <script>
        // Set current year dynamically in the footer
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Mobile Menu Toggle Logic
        const menuToggle = document.getElementById('menu-toggle');
        const mobileMenu = document.getElementById('mobile-menu');

        menuToggle.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            // Change button icon (Hamburger to X and vice-versa)
            const icon = menuToggle.querySelector('svg path');
            if (mobileMenu.classList.contains('hidden')) {
                // Show Hamburger
                icon.setAttribute('d', 'M4 6h16M4 12h16m-7 6h7');
            } else {
                // Show X
                icon.setAttribute('d', 'M6 18L18 6M6 6l12 12');
            }
        });

        // Hide mobile menu when a link is clicked
        mobileMenu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                // Reset icon to hamburger
                menuToggle.querySelector('svg path').setAttribute('d', 'M4 6h16M4 12h16m-7 6h7');
            });
        });
    </script>
</body>
</html>


