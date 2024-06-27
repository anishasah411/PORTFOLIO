# PORTFOLIO
#HTML CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="por.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h1>Welcome to My Portfolio</h1>
        <p>Hello! I'm Anisha Sah, pursuing a B.Tech degree in CSE in 3rd year. This is my personal portfolio website where you can learn more about me and see some of my work.</p>
    </section>
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a passionate developer with experience in web development, particularly in HTML, CSS, JavaScript, and various front-end frameworks. I love creating beautiful and functional websites.</p>
        <p>In my spare time, I enjoy learning new technologies, contributing to open-source projects, and blogging about web development.</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1: Portfolio Website</h3>
            <p>Description: A personal portfolio website to showcase my skills and projects.</p>
            <p>Technologies: HTML, CSS, JavaScript</p>
            <a href="https://github.com/anishasah/portfolio" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Project 2: Todo List App</h3>
            <p>Description: A simple and interactive todo list application.</p>
            <p>Technologies: React, Node.js, MongoDB</p>
            <a href="https://github.com/anishasah/todo-list" target="_blank">View Project</a>
        </div>
    </section>
    <section id="resume">
        <h2>Resume</h2>
        <p><strong>Education:</strong></p>
        <ul>
            <li>Bachelor's Degree in Computer Science, Manav Rachna International Institute Of Research and Studies, 2024</li>
        </ul>
        <p><strong>Experience:</strong></p>
        <ul>
            <li>Frontend Developer</li>
            <li>Intern at OctaNet Services Pvt Ltd, 2024-2025</li>
        </ul>
        <p><strong>Skills:</strong></p>
        <ul>
            <li>HTML, CSS, JavaScript</li>
            <li>React, Angular, Vue.js</li>
            <li>Node.js, Express</li>
            <li>Python</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>If you'd like to get in touch, feel free to email me at <a href="mailto:anishasah411@gmail.com">anishasah411@gmail.com</a> or connect with me on <a href="https://www.linkedin.com/in/anisha-sah-04a55b254" target="_blank">LinkedIn</a>.</p>
        <form action="https://formspree.io/f/{your_form_id}" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
    <script src="por.js"></script>
</body>
</html>

#CSS CODE:
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 2rem;
    margin: 1rem;
}

.project {
    border: 1px solid #ccc;
    padding: 1rem;
    margin-bottom: 1rem;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
#JS CODE:
document.addEventListener('DOMContentLoaded', function() {
    console.log('DOM fully loaded and parsed');
    // Add JavaScript interactivity here
});
