
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Manaswi | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
      scroll-behavior: smooth;
    }
    header {
      position: fixed;
      top: 0; left: 0;
      width: 100%;
      background: rgba(0, 0, 0, 0.6);
      backdrop-filter: blur(10px);
      padding: 15px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
    }
    .logo {
      font-size: 1.8rem;
      font-weight: bold;
      color: #00ffff;
    }
    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      position: relative;
      transition: 0.3s;
    }
    nav a::after {
      content: '';
      position: absolute;
      width: 100%;
      height: 2px;
      background: #00ffff;
      left: 0;
      bottom: -5px;
      transform: scaleX(0);
      transform-origin: right;
      transition: transform 0.3s ease;
    }
    nav a:hover::after {
      transform: scaleX(1);
      transform-origin: left;
    }
    section {
      padding: 100px 50px 60px;
      max-width: 1000px;
      margin: auto;
    }
    .hero {
      text-align: center;
      padding-top: 150px;
    }
    .hero h1 {
      font-size: 3rem;
      color: #00ffff;
      text-shadow: 0 0 10px #00ffff;
    }
    .hero p {
      font-size: 1.2rem;
      margin-top: 10px;
      color: #ddd;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      text-align: center;
      color: #00ffff;
    }
    p {
      font-size: 1.1rem;
      text-align: center;
      line-height: 1.6;
    }
    .skills-grid, .coding-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
      gap: 20px;
      margin-top: 30px;
      text-align: center;
    }
    .skills-grid div, .coding-grid div {
      padding: 15px;
      background: rgba(255,255,255,0.1);
      border-radius: 10px;
      transition: 0.3s ease;
    }
    .skills-grid div:hover, .coding-grid div:hover {
      background: rgba(0,255,255,0.2);
      transform: scale(1.05);
    }
    .project-box {
      margin-top: 30px;
      padding: 20px;
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
      text-align: center;
    }
    .project-box h3 {
      color: #00ffff;
      margin-bottom: 10px;
    }
    footer {
      text-align: center;
      padding: 30px;
      background: rgba(0, 0, 0, 0.4);
      font-size: 0.9rem;
      margin-top: 60px;
    }
    a {
      color: #00ffff;
      text-decoration: none;
    }
    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        gap: 10px;
      }
      .hero h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">Manaswi</div>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#profiles">Profiles</a></li>
        <li><a href="#project">Project</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Hi, I'm Manaswi</h1>
    <p>A Computer Science Engineering student passionate about coding and learning new technologies.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am currently pursuing B.Tech in Computer Science Engineering. I enjoy building projects and solving problems through code. I love exploring technologies in development and AI. I'm always eager to learn and grow as a developer.</p>
  </section>

  <section id="skills">
    <h2>My Skills</h2>
    <div class="skills-grid">
      <div>C</div>
      <div>Java</div>
      <div>Python</div>
      <div>Data Structures</div>
      <div>HTML</div>
      <div>CSS</div>
      <div>Bootstrap</div>
      <div>React</div>
    </div>
  </section>

  <section id="education">
    <h2>Education</h2>
    <p>B.Tech in Computer Science Engineering<br/>Currently pursuing</p>
  </section>

  <section id="profiles">
    <h2>Coding Profiles</h2>
    <div class="coding-grid">
      <div><a href="https://leetcode.com/u/lr7vdo8ywa/" target="_blank">LeetCode</a></div>
      <div><a href="https://www.codechef.com/users/manaswi_b" target="_blank">CodeChef</a></div>
      <div><a href="https://mentorpick.com/profile/23251a0571-manaswi" target="_blank">MentorPick</a></div>
    </div>
  </section>

  <section id="project">
    <h2>Project</h2>
    <div class="project-box">
      <h3>LULC Classification</h3>
      <p>A Land Use and Land Cover classification tool using satellite imagery and a pre-trained ResNet50 model. Built with Streamlit and geospatial data focused on Indian cities.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:manaswibichala@gmail.com">manaswibichala@gmail.com</a></p>
    <p>Phone: <a href="tel:+916301797314">6301797314</a></p>
    <p style="margin-top: 20px;">Feel free to contact me for further details!</p>
  </section>

  <footer>
    <p>© 2025 Manaswi — Built with 💙 using HTML & CSS</p>
  </footer>

</body>
</html>
