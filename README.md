<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Combat Solutions</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background: #003366; color: white; padding: 20px; text-align: center; }
        nav { display: flex; justify-content: center; background: #00509e; padding: 10px; }
        nav a { color: white; text-decoration: none; padding: 15px 20px; font-weight: bold; }
        section { padding: 40px; max-width: 1100px; margin: auto; background: white; box-shadow: 0px 4px 8px rgba(0,0,0,0.1); border-radius: 10px; }
        .services { display: flex; flex-wrap: wrap; justify-content: space-around; }
        .service-item { width: 45%; margin-bottom: 20px; }
        .service-item img { width: 100%; border-radius: 10px; }
        footer { text-align: center; padding: 20px; background: #003366; color: white; margin-top: 20px; }
        form { display: flex; flex-direction: column; max-width: 500px; margin: auto; }
        input, textarea { padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; }
        button { padding: 10px; background: #00509e; color: white; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>Combat Solutions</h1>
        <p>Empowering Schools with Smart Solutions</p>
    </header>
    
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-item">
                <img src="admin-support.jpg" alt="Administrative Support">
                <h3>Administrative Support</h3>
                <p>We offer a comprehensive school management system that automates attendance tracking, grade management, staff coordination, and parent communication, making school administration seamless and efficient.</p>
            </div>
            <div class="service-item">
                <img src="cctv.jpg" alt="CCTV Security">
                <h3>CCTV Security Systems</h3>
                <p>Our advanced CCTV solutions ensure the safety of students and staff with 24/7 surveillance, AI-powered threat detection, and remote monitoring, providing a secure learning environment.</p>
            </div>
            <div class="service-item">
                <img src="steam-lab.jpg" alt="STEAM Learning Labs">
                <h3>STEAM Learning Labs</h3>
                <p>We design and install interactive STEAM labs equipped with robotics, 3D printing, AI kits, and coding platforms, enabling students to engage in hands-on, innovative learning experiences.</p>
            </div>
            <div class="service-item">
                <img src="marketing.jpg" alt="Marketing Initiatives">
                <h3>Marketing Initiatives</h3>
                <p>We provide digital marketing, branding, and outreach solutions to help schools enhance their reputation, increase student enrollments, and establish a strong presence in the education sector.</p>
            </div>
        </div>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Combat Solutions is dedicated to supporting schools and educational institutions with cutting-edge technology and strategic services to enhance learning environments.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p><strong>Phone:</strong> +91-9605061135</p>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 Combat Solutions. All rights reserved.</p>
    </footer>
</body>
</html>
