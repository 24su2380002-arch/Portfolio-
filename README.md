# Portfolio-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: white;
    }

    a.button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background-color: #555;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    a.button:hover {
      background-color: #222;
    }
  </style>
</head>
<body>

  <header>
    <h1>Joselin's Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Joselin, a passionate web developer and designer. I love creating clean and responsive websites using HTML, CSS, and JavaScript.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Project One</h3>
        <p>A simple login page built with HTML.</p>
        <a href="#" class="button">View Project</a>
      </div>
      <div class="project">
        <h3>Project Two</h3>
        <p>A simple register page built with HTML.</p>
        <a href="#" class="button">View Project</a>
      </div>
      <!-- Add more projects as needed -->
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>You can reach me at <strong>danialthanga.durai@gmail.com</strong> or follow me on social media.</p>
  </section>

  <footer>
    <p>&copy; 2025 Joselin. All rights reserved.</p>
  </footer>

</body>
</html>
