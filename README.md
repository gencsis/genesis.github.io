<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="hero">
        <div class="hero-content">
            <h1>Genesis Escobar</h1>
            <p>Sofware Engineer and Developer</p>
        </div>
    </section>
    <section id="about">
        <h2>About Me</h2>
        <p>Hi, my name is Genesis Esocbar, I am a student at Louisiana State University studying computer science with a concentration of softare development.</p>
    </section>
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="project">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project 1</h3>
            <p>Description of project 1.</p>
        </div>
        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <h3>Project 2</h3>
            <p>Description of project 2.</p>
        </div>
        <!-- Add more project sections as needed -->
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Contact information and a contact form can go here.</p>
    </section>
    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
</body>
</html>


/* Reset some default styles */
body, h1, h2, p, ul {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #222;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    background-color: #222;
    padding: 10px 0;
}

nav li {
    margin: 0 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

section {
    background-color: #fff;
    margin: 20px;
    padding: 40px;
    border-radius: 8px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
}

.hero-content {
    text-align: center;
    padding: 60px;
    background-image: url('hero-bg.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
}

h1 {
    font-size: 2.5em;
}

.project {
    margin-bottom: 40px;
}

.project img {
    max-width: 100%;
}

.project h3 {
    font-size: 1.5em;
    margin: 10px 0;
}

.project p {
    font-size: 1.1em;
}

footer {
    text-align: center;
    background-color: #222;
    color: #fff;
    padding: 10px;
}
