# my-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Manaswi | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Raleway', sans-serif;
      background: linear-gradient(to bottom right, #fdfbfb, #ebedee);
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #222;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #ddd;
      margin: 0 12px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #fff;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #444;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 20px;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      flex: 1 1 40%;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .contact {
      background-color: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .contact a {
      color: #007acc;
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      background-color: #222;
      color: white;
      padding: 30px 20px;
      margin-top: 40px;
    }

    .final-note {
      margin-top: 30px;
      font-size: 1.1rem;
      color: #333;
      text-align: center;
    }
  </style>
</head>
<body>

  <header>
    <h1>Manaswi's Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
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

  <section id="education">
    <h2>Education</h2>
    <p><strong>B.Tech in Computer Science Engineering</strong><br>Current Student</p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <div class="contact">
      <p>Email: <a href="mailto:manaswibichala@gmail.com">manaswibichala@gmail.com</a></p>
      <p>GitHub: <a href="https://github.com/manaswi-7" target="_blank">manaswi-7</a></p>
    </div>
    <div class="final-note">
      <p>💌 Feel free to contact me for further details on <a href="mailto:manaswibichala@gmail.com">manaswibichala@gmail.com</a></p>
    </div>
  </section>

  <footer>
    <p>© 2025 Manaswi | Built with 💖 and HTML</p>
  </footer>

</body>
</html>

