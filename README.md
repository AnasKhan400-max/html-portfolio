<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Tech Portfolio</title>
    <link rel="stylesheet" href="css/style.css"> <!-- Link to your CSS -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500&display=swap" rel="stylesheet"> <!-- Google Font -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/particles.js/2.0.0/particles.min.js"></script> <!-- Particle.js -->
</head>
<body>
    <!-- Particles.js background -->
    <div id="particles-js"></div>

    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home">
        <h1>Welcome to My Tech Portfolio</h1>
        <p>I'm Anas Khan, a web developer passionate about creating amazing web experiences.</p>
        <a href="#projects" class="btn">View My Work</a>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="images/profile.jpg" alt="Anas Khan">
        <p>I have 2 years of experience as a web developer, with skills in HTML, CSS, JavaScript, and more!</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <div class="project-container">
            <div class="project-card">
                <h3>Project Title 1</h3>
                <p>A brief description of this project. It was built using technologies XYZ.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <div class="project-card">
                <h3>Project Title 2</h3>
                <p>A brief description of this project. It was built using technologies XYZ.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <div class="project-card">
                <h3>Project Title 3</h3>
                <p>A brief description of this project. It was built using technologies XYZ.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <!-- Add more project cards as necessary -->
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Anas Khan. All rights reserved.</p>
    </footer>

    <!-- Include the Particle.js script -->
    <script>
        particlesJS.load('particles-js', 'particles.json', function() {
            console.log('Particles.js loaded');
        });
    </script>
</body>
</html>
