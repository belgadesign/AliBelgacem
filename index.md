<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ali Belgacem Portfolio</title>
<style>
/* Reset */
* { margin: 0; padding: 0; box-sizing: border-box; }

body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
    color: #333;
    line-height: 1.6;
    scroll-behavior: smooth;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 80px 20px 40px;
}

header img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid white;
    margin-bottom: 20px;
}

header h1 {
    margin: 10px 0 5px;
    font-size: 2.5rem;
}

header p {
    font-size: 1.2rem;
}

/* Navigation */
nav {
    position: sticky;
    top: 0;
    background: white;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    z-index: 100;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    display: block;
    padding: 15px;
    color: #333;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #4CAF50;
}

/* Sections */
section {
    max-width: 1000px;
    margin: 50px auto;
    padding: 0 20px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    padding-bottom: 40px;
}

section h2 {
    text-align: center;
    margin: 30px 0 20px;
    color: #4CAF50;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    margin: 10px 0;
}

/* Projects */
.projects .project {
    margin-bottom: 20px;
    padding: 10px 20px;
    border-left: 4px solid #4CAF50;
    background: #f9f9f9;
    border-radius: 5px;
}

/* GitHub Stats */
.stats img {
    display: block;
    margin: 20px auto;
    max-width: 100%;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 30px 20px;
}

footer a {
    color: #4CAF50;
    margin: 0 10px;
    text-decoration: none;
}

/* Blockquote */
blockquote {
    font-style: italic;
    color: #555;
    border-left: 4px solid #4CAF50;
    margin: 20px;
    padding-left: 15px;
}

/* Responsive */
@media(max-width: 768px) {
    header h1 { font-size: 2rem; }
    header p { font-size: 1rem; }
    nav ul { flex-direction: column; }
    nav ul li { margin: 5px 0; }
}
</style>
</head>
<body>

<header id="home">
    <img src="[profile.jpg](https://avatars.githubusercontent.com/u/73390640?v=4)" alt="Ali Belgacem">
    <h1>Ali Belgacem</h1>
    <p>Computer Engineer | PhD Candidate in AI | Delphi & Java Developer</p>
</header>

<nav>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#technologies">Technologies</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#github">GitHub</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#philosophy">Philosophy</a></li>
    </ul>
</nav>

<section id="about">
    <h2>🚀 About Me</h2>
    <ul>
        <li>🎓 PhD Researcher focusing on <strong>Machine learning based Temporal knowledge graphs, Completion and repair</strong></li>
        <li>💻 Developer specializing in <strong>Delphi & Java applications</strong></li>
        <li>🤖 Passionate about <strong>Machine Learning, Deep Learning, Data Mining</strong></li>
        <li>🧠 Interested in software architecture, optimization, and intelligent systems</li>
        <li>🌍 Always learning, exploring, and creating</li>
    </ul>
</section>

<section id="technologies">
    <h2>🔧 Technologies & Tools</h2>
    <h3>Languages</h3>
    <p>Java • Delphi • Python • SQL • C • HTML/CSS</p>
    <h3>AI & Data</h3>
    <p>Machine Learning • Deep Learning • Data Mining • Data Analysis</p>
    <h3>Software & Tools</h3>
    <p>Git & GitHub • JavaFX • Java Swing • Spring Boot • Embarcadero</p>
</section>

<section id="projects">
    <h2>📂 Featured Projects</h2>
    <div class="projects">
        <div class="project">
            <strong>Library Management System</strong><br>
            Year: 2002 | Language: Delphi | Database: MS Access
        </div>
        <div class="project">
            <strong>Genetic Algorithms vs. Ant Colony Optimization – Comparative Study</strong><br>
            Year: 2006 | Language: C++<br>
            Comparative study applied to the Traveling Salesman Problem using genetic algorithms and ant colony optimization methods
        </div>
        <div class="project">
            <strong>Distributed Database Design</strong><br>
            Year: 2013 | Language: Java | Database: Oracle
        </div>
    </div>
</section>

<section id="github">
    <h2>📊 GitHub Stats</h2>
    <div class="stats">
        <img src="https://github-readme-stats.vercel.app/api?username=belgadesign&show_icons=true&theme=default" alt="GitHub Stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=belgadesign&layout=compact" alt="Top Languages">
        <img src="https://komarev.com/ghpvc/?username=belgadesign" alt="Profile Views">
    </div>
</section>

<section id="contact">
    <h2>📫 Contact</h2>
    <p>✉️ Email: <a href="mailto:alibelgacem1983@gmail.com">alibelgacem1983@gmail.com</a><br>
    🔗 LinkedIn: <a href="https://www.linkedin.com/in/ali-belgacem-500106170" target="_blank">https://www.linkedin.com/in/ali-belgacem-500106170</a></p>
</section>

<section id="philosophy">
    <h2>🌱 Philosophy</h2>
    <blockquote>“Always improving, always experimenting, always building.”</blockquote>
</section>

<footer>
    <p>Connect with me:</p>
    <a href="https://linkedin.com/in/ali-belgacem-500106170" target="_blank">LinkedIn</a>
    <a href="https://github.com/belgadesign" target="_blank">GitHub</a>
    <a href="mailto:alibelgacem1983@gmail.com">Email</a>
</footer>

</body>
</html>
