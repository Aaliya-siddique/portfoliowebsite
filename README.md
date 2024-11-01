<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Aaliya Siddique | Web Designer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: #fff;
            background-color: #000;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background: #333;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #ff004f;
        }

        .nav-links {
            list-style-type: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            text-decoration: none;
            color: #fff;
            font-size: 16px;
        }

        .hero {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 90vh;
            background-image: url('https://i.pinimg.com/originals/85/30/bd/8530bdc8359eeb15f4e2d242f3dade07.gif'); /* Replace with actual image path */
            background-size: cover;
            background-position: center;
            text-align: center;
        }

        .hero-content h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .hero-content p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            max-width: 600px;
            line-height: 1.5;
        }

        .hero-buttons .btn {
            padding: 10px 20px;
            border: none;
            color: #fff;
            background-color: #ff004f;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1rem;
            transition: background 0.3s;
        }

        .hero-buttons .btn:hover {
            background-color: #ff336f;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        section h2 {
            font-size: 2.5rem;
            color: #ff004f;
            margin-bottom: 20px;
        }

        section p {
            font-size: 1.1rem;
            color: #ccc;
            max-width: 800px;
            margin: 0 auto 40px;
            line-height: 1.6;
        }

        .about {
    background-color: #111;
    padding: 60px 20px;
    text-align: center;
}

.about h2 {
    font-size: 2.5rem;
    color: #ff004f;
    margin-bottom: 20px;
}

.about-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
    gap: 20px;
}

.about-content p {
    font-size: 1.1rem;
    color: #ccc;
    line-height: 1.6;
    margin-top: 20px;
}

.about-image {
    position: relative;
    width: 200px;
    height: 200px;
    overflow: hidden;
    border-radius: 50%;
    border: 5px solid #ff004f; /* Border around the image */
    box-shadow: 0 4px 15px rgba(255, 0, 79, 0.5); /* Subtle shadow for depth */
    transition: transform 0.4s ease, box-shadow 0.4s ease;
}

.about-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.4s ease; /* Smooth zoom effect on hover */
}

.about-image:hover {
    transform: scale(1.1); /* Zoom in on hover */
    box-shadow: 0 8px 20px rgba(255, 0, 79, 0.7); /* Stronger shadow on hover */
}

.about-image img:hover {
    transform: scale(1.2); /* Zoom in the image slightly on hover */
}


        .project-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .project-item {
            background: #222;
            padding: 20px;
            width: 300px;
            border-radius: 10px;
            text-align: left;
            color: #fff;
        }

        .project-item h3 {
            color: #ff004f;
            margin-bottom: 10px;
        }

        .contact-form {
            max-width: 500px;
            margin: 0 auto;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 5px;
            border: none;
        }

        .contact-form button {
            padding: 10px 20px;
            border: none;
            background-color: #ff004f;
            color: #fff;
            font-size: 1rem;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .contact-form button:hover {
            background-color: #ff336f;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Aaliya Portfolio</div>
        <nav>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Hi, I'm Aaliya Siddique<br>Web Designer</h1>
            <p>Bringing ideas to life with sleek and effective web designs.</p>
            <div class="hero-buttons">
                <a href="#projects" class="btn view-work">View Work</a>
                <a href="#contact" class="btn latest-works">Contact Me</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
   
<section class="about" id="about">
    <h2>About Me</h2>
    <div class="about-content">
        <div class="about-image">
            <img src="a2.jpg" alt="Aaliya Siddique">
        </div>
        <p>I'm Aaliya Siddique, a passionate web designer specializing in creating modern, responsive websites. I bring creativity and precision to each project to ensure that every website not only looks great but also provides an exceptional user experience.</p>
    </div>
</section>

    <!-- Services Section -->
    <section id="services">
        <h2>Services</h2>
        <p>
            
            I'm a web developer and artist dedicated to creating visually engaging websites and unique artworks. With a focus on user-friendly design, I offer web development services including custom design, e-commerce solutions, UI/UX, and SEO optimization. 
            <br> My artistic work spans custom paintings and framing, adding a personalized touch to spaces. Each project combines technical skill with creative vision, delivering both digital functionality and visual artistry.</p>
    </section>

    <!-- Projects Section -->
    <section class="projects" id="projects">
        <h2>My Projects</h2>
        <div class="project-list">
            <div class="project-item">
                <h3>Project One</h3>
                <p>A modern e-commerce website that focuses on user experience and performance.</p>
            </div>
            <div class="project-item">
                <h3>Project Two</h3>
                <p>Portfolio website for a photographer, featuring a clean gallery and responsive design.</p>
            </div>
            <div class="project-item">
                <h3>Project Three</h3>
                <p>A landing page for a mobile app, designed to drive engagement and downloads.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Me</h2>
        <p>I'd love to hear about your project! Reach out using the form below or email me at <a href="mailto:aaliyasiddique@gmail.com" style="color: #ff004f;">aaliyasiddique@gmail.com</a>.</p>
        <div class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Aaliya Siddique. All rights reserved.</p>
    </footer>
</body>
</html>
