<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Community Science Museum</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary: #1a3a5f;
            --secondary: #4da8da;
            --accent: #e63946;
            --light: #f5f7fa;
            --dark: #333;
            --gray: #6c757d;
            --transition: all 0.3s ease;
        }

        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Header Styles */
        .top-header {
            background-color: var(--primary);
            color: white;
            padding: 0.8rem 0;
        }

        .top-header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .logo h1 {
            font-size: 1.8rem;
            font-weight: 700;
        }

        .logo span {
            color: var(--secondary);
        }

        .search-bar {
            display: flex;
            align-items: center;
            background: white;
            border-radius: 4px;
            overflow: hidden;
            width: 300px;
        }

        .search-bar input {
            flex-grow: 1;
            padding: 0.5rem 1rem;
            border: none;
            outline: none;
        }

        .search-bar button {
            background: var(--secondary);
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
        }

        .auth-buttons {
            display: flex;
            gap: 1rem;
        }

        .auth-buttons a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: var(--transition);
        }

        .auth-buttons a:hover {
            color: var(--secondary);
        }

        /* Main Navigation */
        .main-nav {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .main-nav ul {
            display: flex;
            list-style: none;
            justify-content: center;
        }

        .main-nav li {
            position: relative;
        }

        .main-nav a {
            display: block;
            padding: 1.2rem 1.5rem;
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            transition: var(--transition);
        }

        .main-nav a:hover,
        .main-nav a.active {
            color: var(--primary);
            background-color: rgba(77, 168, 218, 0.1);
        }

        .main-nav a.active::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: var(--primary);
        }

        /* Hero Section */
        .hero {
            background:linear-gradient(rgba(233, 235, 238, 0.8), rgba(230, 234, 240, 0.103)), 
                        url("C:/Users/HAFFY/Desktop/WEB DESIGN/Lecture 3/html/homeimagetop.jpg") no-repeat center center/cover;
            color: white;
            padding: 5rem 0;
            text-align: center;
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }

        .btn {
            display: inline-block;
            background-color: var(--accent);
            color: white;
            padding: 0.8rem 1.5rem;
            border: none;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            transition: var(--transition);
            cursor: pointer;
        }

        .btn:hover {
            background-color: #c1121f;
            transform: translateY(-2px);
        }

        /* Content Section */
        .content-section {
            padding: 4rem 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            color: var(--primary);
            font-size: 2.2rem;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background-color: var(--secondary);
            margin: 1rem auto;
        }

        .content-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            align-items: center;
        }

        .content-text h3 {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            color: var(--primary);
        }

        .content-text p {
            margin-bottom: 1.5rem;
            color: var(--gray);
        }

        .content-image {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .content-image img {
            width: 100%;
            height: auto;
            display: block;
            transition: var(--transition);
        }

        .content-image:hover img {
            transform: scale(1.05);
        }

        /* Exhibitions Section */
        .exhibitions {
            background-color: #eef2f7;
            padding: 4rem 0;
        }

        .exhibitions-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .exhibition-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: var(--transition);
        }

        .exhibition-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
        }

        .exhibition-img {
            height: 200px;
            background-size: cover;
            background-position: center;
        }

        .exhibition-content {
            padding: 1.5rem;
        }

        .exhibition-content h3 {
            margin-bottom: 0.5rem;
            color: var(--primary);
        }

        .exhibition-content p {
            margin-bottom: 1rem;
            color: var(--gray);
        }

        /* Footer */
        .main-footer {
            background-color: #1a1a1a;
            color: white;
            padding: 3rem 0 1.5rem;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .footer-section h3 {
            margin-bottom: 1rem;
            font-size: 1.2rem;
            color: var(--secondary);
        }

        .footer-section ul {
            list-style: none;
        }

        .footer-section ul li {
            margin-bottom: 0.5rem;
        }

        .footer-section a {
            color: #ccc;
            text-decoration: none;
            transition: var(--transition);
        }

        .footer-section a:hover {
            color: white;
        }

        .social-icons {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }

        .social-icons a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            text-decoration: none;
            color: white;
            transition: var(--transition);
        }

        .social-icons a:hover {
            background-color: var(--secondary);
        }

        .payment-methods {
            margin-top: 1rem;
        }

        .payment-methods img {
            height: 30px;
            margin-right: 0.5rem;
        }

        .footer-bottom {
            text-align: center;
            padding-top: 1.5rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #999;
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 992px) {
            .content-grid {
                grid-template-columns: 1fr;
                gap: 2rem;
            }
            
            .content-image {
                order: -1;
            }
        }

        @media (max-width: 768px) {
            .top-header .container {
                flex-direction: column;
                gap: 1rem;
            }
            
            .search-bar {
                width: 100%;
                max-width: 400px;
            }
            
            .main-nav ul {
                flex-wrap: wrap;
            }
            
            .main-nav a {
                padding: 1rem;
            }
            
            .hero h2 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
        }

        @media (max-width: 480px) {
            .logo h1 {
                font-size: 1.5rem;
            }
            
            .section-title {
                font-size: 1.8rem;
            }
            
            .exhibitions-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Top Header -->
    <header class="top-header">
        <div class="container">
            <div class="logo">
                <h1>Community <span>Science Museum</span></h1>
            </div>
            <div class="search-bar">
                <input type="text" placeholder="Search...">
                <button><i class="fas fa-search"></i></button>
            </div>
            <div class="auth-buttons">
                <a href="#">Login</a>
                <a href="#">Register</a>
            </div>
        </div>
    </header>

    <!-- Main Navigation -->
    <nav class="main-nav">
        <div class="container">
            <ul>
                <li><a href="#" class="active">HOME</a></li>
                <li><a href="#">MUSEUM PROGRAMS</a></li>
                <li><a href="#">EXPLORE</a></li>
                <li><a href="#">EVENTS</a></li>
                <li><a href="#">EXHIBITIONS</a></li>
                <li><a href="#">VISIT US</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <h2>Discover the Wonders of Science</h2>
                <p>Explore our interactive exhibits, fascinating collections, and engaging events for all ages.</p>
                <a href="#" class="btn">Plan Your Visit</a>
            </div>
        </div>
    </section>

    <!-- Content Section -->
    <section class="content-section">
        <div class="container">
            <h2 class="section-title">Explore Our Universe</h2>
            <div class="content-grid">
                <div class="content-text">
                    <h3>Cosmology</h3>
                    <p>Over the course of human history, science has developed from our early understanding of fire, wind, water and earth to exploring every thing from galaxies far away to the very building blocks of life itself.</p>
                    <p>Explore the wonders of our cosmos. Our fantastic exhibition, ‘The Sky Above Us’, explores the night sky and what we can see and know about the universe around us. We'll locate the various constellations and galaxies that can be seen and learn a bit about the early navigators who used the stars to travel by.</p>
                    <a href="#" class="btn">Learn More</a>
                </div>
                <div class="content-image">
                    <img src="C:\Users\HAFFY\Desktop\WEB DESIGN\Lecture 3\html\kid-touches-robot.jpg" alt="Cosmology exhibition">
                </div>
            </div>
        </div>
    </section>

    <!-- Exhibitions Section -->
    <section class="exhibitions">
        <div class="container">
            <h2 class="section-title">Current Exhibitions</h2>
            <div class="exhibitions-grid">
                <div class="exhibition-card">
                    <div class="exhibition-img" style="background-image: url('https://images.unsplash.com/photo-1532187863486-abf9dbad1b69?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
                    <div class="exhibition-content">
                        <h3>Space Exploration</h3>
                        <p>Journey through the cosmos with our interactive space exhibit featuring real meteorites and a planetarium.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
                <div class="exhibition-card">
                    <div class="exhibition-img" style="background-image: url('https://images.unsplash.com/photo-1559757148-5c350d0d3c56?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
                    <div class="exhibition-content">
                        <h3>Ancient Civilizations</h3>
                        <p>Discover the scientific achievements of ancient cultures from Egypt to Mesopotamia.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
                <div class="exhibition-card">
                    <div class="exhibition-img" style="background-image: url('https://images.unsplash.com/photo-1554475900-0a0350e3fc7b?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
                    <div class="exhibition-content">
                        <h3>Future Technologies</h3>
                        <p>Explore cutting-edge innovations in robotics, AI, and sustainable energy solutions.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="main-footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Navigation</h3>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Events</a></li>
                        <li><a href="#">Programs</a></li>
                        <li><a href="#">Exhibitions</a></li>
                        <li><a href="#">Explore</a></li>
                        <li><a href="#">Visit Us</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Follow Us</h3>
                    <div class="social-icons">
                        <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
                        <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                        <a href="#" aria-label="YouTube"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                <div class="footer-section">
                    <h3>Contact Information</h3>
                    <p>Community Science Museum</p>
                    <p>Tel. +256 757 886 712</p>
                    <div class="payment-methods">
                        <h4>Pay With</h4>
                        <div>
                            <i class="fab fa-cc-visa" style="font-size: 2rem; margin-right: 10px;"></i>
                            <i class="fab fa-cc-mastercard" style="font-size: 2rem; margin-right: 10px;"></i>
                            <i class="fab fa-cc-paypal" style="font-size: 2rem;"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Community Science Museum. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Simple search functionality
        document.querySelector('.search-bar button').addEventListener('click', function() {
            const searchTerm = document.querySelector('.search-bar input').value;
            if (searchTerm.trim() !== '') {
                alert(`Searching for: ${searchTerm}`);
            }
        });

        // Add active class to navigation items on click
        document.querySelectorAll('.main-nav a').forEach(link => {
            link.addEventListener('click', function(e) {
                document.querySelectorAll('.main-nav a').forEach(item => {
                    item.classList.remove('active');
                });
                this.classList.add('active');
            });
        });
    </script>
</body>
</html>
