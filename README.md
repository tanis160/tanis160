<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InnoLog - Innovative Logistics Solutions</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        /* Header styles */
        header {
            background-color: #1a237e;
            color: #fff;
            padding: 1rem 0;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        .nav-links {
            list-style: none;
            display: flex;
        }
        .nav-links li {
            margin-left: 20px;
        }
        .nav-links a {
            color: #fff;
            text-decoration: none;
        }
        /* Hero section styles */
        .hero {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 60vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: #fff;
        }
        .hero-content {
            width: 100%;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        .btn {
            display: inline-block;
            background-color: #ff4081;
            color: #fff;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .btn:hover {
            background-color: #e91e63;
        }
        /* Services section styles */
        .services {
            padding: 4rem 0;
            background-color: #f5f5f5;
        }
        .services h2 {
            text-align: center;
            margin-bottom: 2rem;
        }
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        .service-card {
            background-color: #fff;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .service-card h3 {
            margin-bottom: 1rem;
        }
        /* Innovation section styles */
        .innovation {
            padding: 4rem 0;
        }
        .innovation h2 {
            text-align: center;
            margin-bottom: 2rem;
        }
        .innovation-content {
            display: flex;
            align-items: center;
            gap: 2rem;
        }
        .innovation-text {
            flex: 1;
        }
        .innovation-image {
            flex: 1;
        }
        .innovation-image img {
            width: 100%;
            border-radius: 5px;
        }
        /* Footer styles */
        footer {
            background-color: #1a237e;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
        }
        /* Responsive styles */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            .hero h1 {
                font-size: 2rem;
            }
            .innovation-content {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav class="container">
            <div class="logo">InnoLog</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#innovation">Innovation</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="container hero-content">
                <h1>Innovative Logistics Solutions</h1>
                <p>Transforming supply chains with cutting-edge technology</p>
                <a href="#contact" class="btn">Get Started</a>
            </div>
        </section>

        <section id="services" class="services">
            <div class="container">
                <h2>Our Services</h2>
                <div class="services-grid">
                    <div class="service-card">
                        <h3>AI-Powered Route Optimization</h3>
                        <p>Maximize efficiency with our advanced AI algorithms for optimal route planning.</p>
                    </div>
                    <div class="service-card">
                        <h3>Blockchain Supply Chain</h3>
                        <p>Enhance transparency and traceability with our blockchain-based supply chain solutions.</p>
                    </div>
                    <div class="service-card">
                        <h3>IoT Fleet Management</h3>
                        <p>Real-time tracking and predictive maintenance using IoT devices for your fleet.</p>
                    </div>
                    <div class="service-card">
                        <h3>Automated Warehousing</h3>
                        <p>Increase accuracy and speed with our robotic warehouse automation systems.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="innovation" class="innovation">
            <div class="container">
                <h2>Driving Innovation in Logistics</h2>
                <div class="innovation-content">
                    <div class="innovation-text">
                        <p>At InnoLog, we're at the forefront of logistics innovation. Our team of experts constantly explores new technologies and methodologies to revolutionize the supply chain industry. From AI and machine learning to robotics and green technologies, we're committed to shaping the future of logistics.</p>
                        <p>Partner with us to stay ahead of the curve and transform your logistics operations for the digital age.</p>
                    </div>
                    <div class="innovation-image">
                        <img src="https://images.unsplash.com/photo-1581092921461-eab62e97a780?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Innovative logistics technology">
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer id="contact">
        <div class="container">
            <p>&copy; 2024 InnoLog. All rights reserved.</p>
            <p>Contact us: info@innolog.com | (123) 456-7890</p>
        </div>
    </footer>
</body>
</html>
