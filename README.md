# index.html
Simple mobile app development
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #333;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background: #575757;
    }
    section {
      padding: 40px;
      text-align: center;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 15px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    .card {
      background: white;
      padding: 20px;
      margin: 20px auto;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      max-width: 500px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Portfolio</h1>
    <p>Web Developer | Designer | Creator</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <div class="card">
      <h2>About Me</h2>
      <p>Hello! I’m learning web development and building awesome websites.My name is Rima Das. 
      I'm pursuing BCA from Netaji Subhash engineering college.Student of 3rd year.This is my first project</p>
    </div>
  </section>

  <section id="projects">
    <div class="card">
      <h2>Projects</h2>
      <p>🚀 Project 1 – My Portfolio Website</p>
      <p>📱 Project 2 – Simple Mobile App Design</p>
    </div>
  </section>

  <section id="contact">
    <div class="card">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:rima58838@gmail.com">rima58838@gmail.com</a></p>
    </div>
  </section>

  <footer>
    <p>© 2025 My Portfolio. All Rights Reserved.</p>
  </footer>
</body>
</html>
