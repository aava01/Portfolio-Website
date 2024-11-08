# Portfolio-Website
A personal portfolio website showcasing my front-end projects
## Project Description
This project is a personal portfolio website that showcases my front-end projects and skills. It serves as a platform to display my work and connect with potential clients or employers. The website includes a gallery of my projects, an about section, and contact information.
## Technologies Used
- HTML
- CSS
- JavaScript
- [Add any additional technologies, libraries, or frameworks]
### `index.html`
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="project-gallery">
      <div class="project">
        <h3>Project 1</h3>
        <p>Short description of project 1.</p>
      </div>
      <div class="project">
        <h3>Project 2</h3>
        <p>Short description of project 2.</p>
      </div>
      <div class="project">
        <h3>Project 3</h3>
        <p>Short description of project 3.</p>
      </div>
      <!-- More projects can be added here -->
    </div>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I'm Ani, a front-end developer with a passion for creating interactive and responsive web designs. This portfolio highlights my recent work and technical skills.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: aniavanesyan497@gmail.com</p>
    <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile">linkedin.com/in/yourprofile</a></p>
  </section>

  <footer>
    <p>&copy; 2024 Ani. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

### styles.css
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  color: #333;
  background-color: #f4f4f9;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

header nav a {
  color: #fff;
  margin: 0 10px;
  text-decoration: none;
}

header nav a:hover {
  text-decoration: underline;
}

section {
  padding: 20px;
  margin: 10px 0;
}

h2 {
  color: #333;
  margin-bottom: 10px;
}

.project-gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.project {
  background-color: #fff;
  border: 1px solid #ddd;
  padding: 15px;
  width: 30%;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.project h3 {
  color: #333;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #333;
  color: #fff;
  margin-top: 20px;
}

### script.js
// script.js - կարող ես ավելացնել JavaScript ֆունկցիաներ ավելացնելու համար
console.log("Welcome to my portfolio website!");

## About me
My name is Ani, and I am a front-end developer with a passion for creating interactive and responsive web designs. 
