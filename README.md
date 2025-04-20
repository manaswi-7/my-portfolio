# my-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Manaswi's Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      color: #333;
    }

    header {
      background-color: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #444;
      border-bottom: 2px solid #ddd;
      padding-bottom: 10px;
    }

    .skills, .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      flex: 1 1 40%;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .contact {
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
    }

    footer {
      text-align: center;
      background-color: #222;
      color: white;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>Manaswi's Portfolio</h1>
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#education">Education</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="about">
  <h2>About Me</h2>
  <p>Hello! I'm Manaswi, a B.Tech Computer Science Engineering student with a passion for learning and building useful things. I'm currently exploring full-stack development and love combining tech with creativity. 💻✨</p>
</section>

<section id="skills">
  <h2>Skills</h2>
  <div class="skills">
    <div class="card"><strong>C</strong><br>Programming fundamentals</div>
    <div class="card"><strong>Java</strong><br>Object-oriented programming</div>
    <div class="card"><strong>Python</strong><br>Versatile programming language</div>
    <div class="card"><strong>Data Structures</strong><br>Problem solving & efficiency</div>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="projects">
    <div class="card">
      <strong>LULC Classification App</strong>
      <p>A web app using Streamlit, satellite images, and ResNet50 to classify land use in Indian cities.</p>
    </div>
    <div class="card">
      <strong>CareerLink App (Idea)</strong>
      <p>A mobile app that connects students with professionals & AI for career advice.</p>
    </div>
  </div>
</section>

<section id="education">
  <h2>Education</h2>
  <p><strong>B.Tech in Computer Science Engineering</strong><br>Current Student</p>
</section>

<section id="contact">
  <h2>Contact Me</h2>
  <div class="contact">
    <p>Email: your-email@example.com</p>
    <p>GitHub: <a href="https://github.com/manaswi-7" target="_blank">manaswi-7</a></p>
    <p>LinkedIn: <a href="#" target="_blank">[Add your LinkedIn]</a></p>
  </div>
</section>

<footer>
  <p>© 2025 Manaswi | Built with 💖 and HTML</p>
</footer>

</body>
</html>
