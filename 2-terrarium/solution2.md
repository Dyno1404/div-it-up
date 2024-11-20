<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hridya's Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa;
    }
    header {
      background-color: #343a40;
      color: white;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    section {
      padding: 40px 20px;
    }
    footer {
      background-color: #343a40;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hridya Portfolio</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div id="home" class="hero">
    <h2>Welcome to My Portfolio</h2>
    <img src="https://via.placeholder.com/150" alt="John Doe">
    <p>Hello! I’m John, a passionate web developer and software enthusiast.</p>
  </div>
  <section id="about">
    <h2>About Me</h2>
    <p>I am a web developer with expertise in front-end and back-end development. I enjoy creating beautiful and functional websites.</p>
  </section>
  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Project 1</h3>
        <p>A cool project description goes here.</p>
        <a href="#">View More</a>
      </div>
      <div class="project-card">
        <h3>Project 2</h3>
        <p>A cool project description goes here.</p>
        <a href="#">View More</a>
      </div>
      <div class="project-card">
        <h3>Project 3</h3>
        <p>A cool project description goes here.</p>
        <a href="#">View More</a>
      </div>
    </div>
  </section>
  <footer>
    <p>Connect with me:</p>
    <a href="#">LinkedIn</a> | <a href="#">GitHub</a> | <a href="#">Twitter</a>
    <p>&copy; 2024 John Doe. All rights reserved.</p>
  </footer>
</body>
</html>
