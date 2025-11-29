# my-portfolio-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header / Navigation -->
    <header>
        <nav class="container">
            <h1 class="logo">MyPortfolio</h1>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <img src="https://via.placeholder.com/150" class="profile-pic" alt="Profile">
            <h2>About Me</h2>
            <p>Hello! I am a beginner web developer learning HTML, CSS, and JavaScript. This is my simple responsive portfolio website built using Flexbox, Grid, and animations.</p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2>My Skills</h2>
            <div class="skills-list">
                <span class="skill">HTML</span>
                <span class="skill">CSS</span>
                <span class="skill">JavaScript</span>
                <span class="skill">Responsive Design</span>
                <span class="skill">Git</span>
                <span class="skill">UI/UX Basics</span>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>Projects</h2>

            <div class="projects-grid">
                <div class="project-card">
                    <h3>Project One</h3>
                    <p>A simple beginner project I created using HTML and CSS.</p>
                    <button class="btn">View</button>
                </div>

                <div class="project-card">
                    <h3>Project Two</h3>
                    <p>A responsive landing page built using Flexbox and Grid.</p>
                    <button class="btn">View</button>
                </div>

                <div class="project-card">
                    <h3>Project Three</h3>
                    <p>A JavaScript mini app for practicing logic and DOM work.</p>
                    <button class="btn">View</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>

            <form>
                <input type="text" placeholder="Your Name">
                <input type="email" placeholder="Email Address">
                <textarea rows="5" placeholder="Your Message"></textarea>
                <button class="btn">Send</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2025 My Portfolio Website</p>
    </footer>

</body>
</html>
