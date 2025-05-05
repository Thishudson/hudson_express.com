# hudson_express.com
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HUDSON_EXPRESS - Delivering Excellence Worldwide</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 font-sans">
    <!-- Navbar -->
    <nav class="bg-blue-900 shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex">
                    <div class="flex-shrink-0 flex items-center">
                        <h1 class="text-2xl font-bold text-yellow-300">HUDSON_EXPRESS</h1>
                    </div>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="#home" class="text-yellow-100 hover:text-yellow-300 px-3 py-2 rounded-md text-sm font-medium">Home</a>
                    <a href="#about" class="text-yellow-100 hover:text-yellow-300 px-3 py-2 rounded-md text-sm font-medium">About</a>
                    <a href="#services" class="text-yellow-100 hover:text-yellow-300 px-3 py-2 rounded-md text-sm font-medium">Services</a>
                    <a href="#store" class="text-yellow-100 hover:text-yellow-300 px-3 py-2 rounded-md text-sm font-medium">Store</a>
                    <a href="#contact" class="text-yellow-100 hover:text-yellow-300 px-3 py-2 rounded-md text-sm font-medium">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="bg-gradient-to-r from-yellow-300 to-blue-700 text-white py-24">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-5xl font-extrabold sm:text-6xl">HUDSON_EXPRESS</h2>
            <p class="mt-4 text-xl max-w-2xl mx-auto">Delivering Excellence Worldwide with Reliable Logistics Solutions</p>
            <a href="#services" class="mt-6 inline-block bg-yellow-400 text-blue-900 font-semibold py-3 px-6 rounded-lg hover:bg-yellow-500 transition duration-300">Explore Our Services</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-blue-900 text-center">About Us</h2>
            <p class="mt-6 text-lg text-gray-600 text-center max-w-3xl mx-auto">HUDSON_EXPRESS is a global leader in logistics, dedicated to empowering businesses and individuals with innovative and reliable delivery solutions. Our mission is to ensure your goods reach their destination safely, on time, and with unparalleled service.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-blue-900 text-center">Our Services</h2>
            <div class="mt-12 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl transition duration-300">
                    <i class="fas fa-globe-americas text-4xl text-yellow-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold text-blue-900">International Logistics</h3>
                    <p class="mt-4 text-gray-600">Seamless global shipping with real-time tracking, customs clearance, and efficient delivery timelines.</p>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl transition duration-300">
                    <i class="fas fa-truck text-4xl text-yellow-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold text-blue-900">Reliable Delivery</h3>
                    <p class="mt-4 text-gray-600">Guaranteed on-time delivery with advanced tracking solutions for complete peace of mind.</p>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl transition duration-300">
                    <i class="fas fa-cogs text-4xl text-yellow-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold text-blue-900">Custom Solutions</h3>
                    <p class="mt-4 text-gray-600">Tailored logistics services to meet the unique needs of your business or personal shipments.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- E-commerce Store Section -->
    <section id="store" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-blue-900 text-center">Our Store</h2>
            <div class="mt-12 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold text-blue-900">Shipping Kit</h3>
                    <p class="mt-2 text-gray-600">Essential tools for safe packaging.</p>
                    <p class="mt-2 text-lg font-bold text-blue-900">$19.99</p>
                    <button onclick="addToCart('Shipping Kit', 19.99)" class="mt-4 bg-blue-900 text-yellow-300 font-semibold py-2 px-4 rounded-lg hover:bg-blue-800 transition duration-300">Add to Cart</button>
                </div>
                <div class="bg-gray-50 p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold text-blue-900">Tracking Subscription</h3>
                    <p class="mt-2 text-gray-600">Premium tracking for your shipments.</p>
                    <p class="mt-2 text-lg font-bold text-blue-900">$9.99/month</p>
                    <button onclick="addToCart('Tracking Subscription', 9.99)" class="mt-4 bg-blue-900 text-yellow-300 font-semibold py-2 px-4 rounded-lg hover:bg-blue-800 transition duration-300">Add to Cart</button>
                </div>
            </div>
            <div class="mt-12 text-center">
                <h3 class="text-2xl font-semibold text-blue-900">Cart Summary</h3>
                <p id="cart-total" class="mt-4 text-lg text-gray-600">Total: $0.00</p>
                <button onclick="checkout()" class="mt-4 bg-yellow-400 text-blue-900 font-semibold py-2 px-6 rounded-lg hover:bg-yellow-500 transition duration-300">Checkout</button>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-blue-900 py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-yellow-300 text-center">Contact Us</h2>
            <div class="mt-12 max-w-lg mx-auto">
                <div>
                    <label for="name" class="block text-sm font-medium text-yellow-100">Name</label>
                    <input type="text" id="name" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-yellow-400 focus:border-yellow-400 sm:text-sm p-3" placeholder="Your Name">
                </div>
                <div class="mt-6">
                    <label for="email" class="block text-sm font-medium text-yellow-100">Email</label>
                    <input type="email" id="email" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-yellow-400 focus:border-yellow-400 sm:text-sm p-3" placeholder="Your Email">
                </div>
                <div class="mt-6">
                    <label for="message" class="block text-sm font-medium text-yellow-100">Message</label>
                    <textarea id="message" rows="4" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-yellow-400 focus:border-yellow-400 sm:text-sm p-3" placeholder="Your Message"></textarea>
                </div>
                <div class="mt-8">
                    <button onclick="submitForm()" class="w-full bg-yellow-400 text-blue-900 font-semibold py-3 px-4 rounded-lg hover:bg-yellow-500 transition duration-300">Send Message</button>
                </div>
            </div>
            <p class="mt-8 text-center text-yellow-100">Call us at +234 808 340 8364</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-yellow-100 py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p>© 2025 HUDSON_EXPRESS. All rights reserved.</p>
            <p class="mt-2">Contact: +234 808 340 8364 | Email: support@hudsonexpress.com</p>
        </div>
    </footer>

    <script>
        let cart = [];
        
        function addToCart(itemName, price) {
            cart.push({ name: itemName, price: price });
            updateCartTotal();
        }

        function updateCartTotal() {
            const total = cart.reduce((sum, item) => sum + item.price, 0).toFixed(2);
            document.getElementById('cart-total').textContent = `Total: $${total}`;
        }

        function checkout() {
            if (cart.length > 0) {
                alert('Thank you for your purchase! We will contact you for payment and delivery details.');
                cart = [];
                updateCartTotal();
            } else {
                alert('Your cart is empty.');
            }
        }

        function submitForm() {
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            if (name && email && message) {
                alert('Thank you for your message! We will get back to you soon.');
                document.getElementById('name').value = '';
                document.getElementById('email').value = '';
                document.getElementById('message').value = '';
            } else {
                alert('Please fill out all fields.');
            }
        }
    </script>
</body>
</html>
