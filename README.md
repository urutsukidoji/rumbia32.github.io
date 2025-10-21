# rumbia32.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rumbia32 - Authentic Johor Cuisine</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
        }
        .hero-pattern {
            background-image: url('http://static.photos/food/1200x630/42');
            background-size: cover;
            background-position: center;
        }
        .menu-item:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-amber-600 text-white shadow-lg">
        <div class="container mx-auto px-6 py-3">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-4">
                    <i data-feather="coffee" class="w-8 h-8"></i>
                    <span class="text-xl font-bold">Rumbia32</span>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#" class="hover:text-amber-200">Home</a>
                    <a href="#" class="hover:text-amber-200">Menu</a>
                    <a href="#" class="hover:text-amber-200">About</a>
                    <a href="#" class="hover:text-amber-200">Contact</a>
                </div>
                <button class="md:hidden focus:outline-none">
                    <i data-feather="menu" class="w-6 h-6"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-pattern relative py-32 text-white">
        <div class="absolute inset-0 bg-black bg-opacity-50"></div>
        <div class="container mx-auto px-6 relative z-10">
            <div class="md:w-3/5">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Authentic Johor Cuisine</h1>
                <p class="text-xl mb-8">Experience the rich flavors of Malaysia's southern culinary heritage</p>
                <button class="bg-amber-600 hover:bg-amber-700 text-white px-6 py-3 rounded-full font-semibold transition duration-300">
                    Explore Our Menu
                </button>
            </div>
        </div>
    </section>

    <!-- Signature Dishes -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Our Signature Dishes</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Dish 1 -->
                <div class="menu-item bg-gray-50 rounded-xl overflow-hidden shadow-lg">
                    <img src="http://static.photos/food/640x360/101" alt="Laksa Johor" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Laksa Johor</h3>
                        <p class="text-gray-600 mb-4">A unique noodle dish with rich fish-based broth and spaghetti-like noodles.</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-amber-600">RM 12.90</span>
                            <button class="text-amber-600 hover:text-amber-700">
                                <i data-feather="plus-circle" class="w-5 h-5"></i>
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Dish 2 -->
                <div class="menu-item bg-gray-50 rounded-xl overflow-hidden shadow-lg">
                    <img src="http://static.photos/food/640x360/102" alt="Mee Bandung" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Mee Bandung</h3>
                        <p class="text-gray-600 mb-4">Spicy noodle dish with prawn broth, chili paste, and fresh seafood.</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-amber-600">RM 10.90</span>
                            <button class="text-amber-600 hover:text-amber-700">
                                <i data-feather="plus-circle" class="w-5 h-5"></i>
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Dish 3 -->
                <div class="menu-item bg-gray-50 rounded-xl overflow-hidden shadow-lg">
                    <img src="http://static.photos/food/640x360/103" alt="Nasi Briyani Gam" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Nasi Briyani Gam</h3>
                        <p class="text-gray-600 mb-4">Fragrant rice cooked with spices, served with mutton curry and acar.</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-amber-600">RM 15.90</span>
                            <button class="text-amber-600 hover:text-amber-700">
                                <i data-feather="plus-circle" class="w-5 h-5"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <img src="http://static.photos/people/640x360/201" alt="Chef preparing food" class="rounded-xl shadow-lg">
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-3xl font-bold mb-6">Our Story</h2>
                    <p class="text-gray-700 mb-4">Rumbia32 was founded in 2010 with a passion for preserving the authentic flavors of Johor cuisine. Our chefs bring generations of family recipes to your table.</p>
                    <p class="text-gray-700 mb-6">We source only the freshest ingredients and prepare each dish with the same care as we would for our own family.</p>
                    <button class="bg-amber-600 hover:bg-amber-700 text-white px-6 py-3 rounded-full font-semibold transition duration-300">
                        Learn More About Us
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">What Our Customers Say</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-gray-50 p-6 rounded-xl shadow">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4">
                            <img src="http://static.photos/people/200x200/301" alt="Customer" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-semibold">Ahmad Faris</h4>
                            <div class="flex text-amber-400">
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"The Laksa Johor here reminds me of my grandmother's cooking. Absolutely authentic!"</p>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-gray-50 p-6 rounded-xl shadow">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4">
                            <img src="http://static.photos/people/200x200/302" alt="Customer" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-semibold">Sarah Lim</h4>
                            <div class="flex text-amber-400">
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"I come here every weekend for their Mee Bandung. The portion is generous and full of flavor."</p>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-gray-50 p-6 rounded-xl shadow">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4">
                            <img src="http://static.photos/people/200x200/303" alt="Customer" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-semibold">David Wong</h4>
                            <div class="flex text-amber-400">
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <i data-feather="star" class="w-4 h-4"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"The Nasi Briyani Gam is to die for! Tender mutton and perfectly cooked rice."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="py-16 bg-amber-600 text-white text-center">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-6">Ready to Taste Johor?</h2>
            <p class="text-xl mb-8 max-w-2xl mx-auto">Visit us today or order online to experience authentic Johor cuisine delivered to your doorstep.</p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <button class="bg-white text-amber-600 hover:bg-gray-100 px-8 py-3 rounded-full font-semibold transition duration-300">
                    Order Now
                </button>
                <button class="border-2 border-white text-white hover:bg-white hover:text-amber-600 px-8 py-3 rounded-full font-semibold transition duration-300">
                    Call Us
                </button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center mb-4">
                        <i data-feather="coffee" class="w-8 h-8 mr-2"></i>
                        <span class="text-xl font-bold">Rumbia32</span>
                    </div>
                    <p class="text-gray-400">Bringing authentic Johor flavors to your table since 2010.</p>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Home</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Menu</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">About Us</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Contact</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Contact Us</h4>
                    <ul class="space-y-2">
                        <li class="flex items-center text-gray-400">
                            <i data-feather="map-pin" class="w-4 h-4 mr-2"></i>
                            <span>32, Jalan Rumbia, 83000 Batu Pahat</span>
                        </li>
                        <li class="flex items-center text-gray-400">
                            <i data-feather="phone" class="w-4 h-4 mr-2"></i>
                            <span>+60 12-345 6789</span>
                        </li>
                        <li class="flex items-center text-gray-400">
                            <i data-feather="mail" class="w-4 h-4 mr-2"></i>
                            <span>info@rumbia32.com</span>
                        </li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Opening Hours</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex justify-between">
                            <span>Monday - Friday</span>
                            <span>10am - 10pm</span>
                        </li>
                        <li class="flex justify-between">
                            <span>Saturday - Sunday</span>
                            <span>9am - 11pm</span>
                        </li>
                    </ul>
                    <div class="flex space-x-4 mt-4">
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i data-feather="facebook" class="w-5 h-5"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i data-feather="instagram" class="w-5 h-5"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i data-feather="twitter" class="w-5 h-5"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-500">
                <p>&copy; 2023 Rumbia32. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Floating Order Button (Mobile) -->
    <div class="fixed bottom-6 right-6 md:hidden">
        <button class="bg-amber-600 hover:bg-amber-700 text-white p-4 rounded-full shadow-lg floating">
            <i data-feather="shopping-cart" class="w-6 h-6"></i>
        </button>
    </div>

    <script>
        feather.replace();
        
        // Simple animation for menu items
        document.querySelectorAll('.menu-item').forEach((item, index) => {
            item.style.transitionDelay = ${index * 0.1}s;
        });
    </script>
</body>
</html>
