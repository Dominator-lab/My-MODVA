<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MODVA | Welcome</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/3.3.0/tailwind.min.css">
</head>
<body class="bg-gray-100">
    <header class="bg-blue-900 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">MODVA</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#" class="hover:text-blue-300">Home</a></li>
                    <li><a href="#about" class="hover:text-blue-300">About</a></li>
                    <li><a href="#services" class="hover:text-blue-300">Services</a></li>
                    <li><a href="#contact" class="hover:text-blue-300">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container mx-auto mt-8 p-4">
        <!-- Hero Section -->
        <section class="text-center bg-white shadow-lg rounded-lg p-8">
            <h2 class="text-4xl font-bold text-blue-900">Welcome to MODVA</h2>
            <p class="mt-4 text-gray-700">Empowering your financial success through innovation and excellence.</p>
            <a href="#services" class="mt-6 inline-block bg-blue-900 text-white py-2 px-4 rounded hover:bg-blue-700">Explore Our Services</a>
        </section>

        <!-- About Section -->
        <section id="about" class="mt-16">
            <h3 class="text-3xl font-bold text-blue-900">About Us</h3>
            <p class="mt-4 text-gray-700">MODVA is dedicated to providing exceptional financial solutions tailored to your unique needs. Our mission is to foster growth and innovation for businesses and individuals alike.</p>
        </section>

        <!-- Services Section -->
        <section id="services" class="mt-16">
            <h3 class="text-3xl font-bold text-blue-900">Our Services</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-6">
                <div class="bg-white shadow-lg rounded-lg p-6">
                    <h4 class="text-xl font-bold text-blue-900">Financial Consulting</h4>
                    <p class="mt-2 text-gray-700">Expert advice to optimize your financial strategies.</p>
                </div>
                <div class="bg-white shadow-lg rounded-lg p-6">
                    <h4 class="text-xl font-bold text-blue-900">Investment Planning</h4>
                    <p class="mt-2 text-gray-700">Maximize your returns with our tailored investment plans.</p>
                </div>
                <div class="bg-white shadow-lg rounded-lg p-6">
                    <h4 class="text-xl font-bold text-blue-900">Business Solutions</h4>
                    <p class="mt-2 text-gray-700">Innovative solutions to drive business growth and efficiency.</p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="mt-16">
            <h3 class="text-3xl font-bold text-blue-900">Contact Us</h3>
            <form class="bg-white shadow-lg rounded-lg p-6 mt-6">
                <div class="mb-4">
                    <label for="name" class="block text-gray-700 font-bold">Name</label>
                    <input type="text" id="name" name="name" class="w-full border rounded-lg p-2 mt-1" placeholder="Your Name">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-700 font-bold">Email</label>
                    <input type="email" id="email" name="email" class="w-full border rounded-lg p-2 mt-1" placeholder="Your Email">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-700 font-bold">Message</label>
                    <textarea id="message" name="message" class="w-full border rounded-lg p-2 mt-1" placeholder="Your Message"></textarea>
                </div>
                <button type="submit" class="bg-blue-900 text-white py-2 px-4 rounded hover:bg-blue-700">Send Message</button>
            </form>
        </section>
    </main>

    <footer class="bg-blue-900 text-white mt-16 p-4 text-center">
        <p>&copy; 2025 MODVA. All rights reserved.</p>
    </footer>
</body>
</html>
