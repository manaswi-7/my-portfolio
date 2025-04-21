<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Manaswi | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      scroll-behavior: smooth;
      transition: all 0.5s ease;
    }
    header {
      position: fixed;
      top: 0; left: 0;
      width: 100%;
      padding: 15px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(0, 0, 0, 0.6);
      backdrop-filter: blur(10px);
      z-index: 1000;
    }
    .logo {
      font-size: 1.8rem;
      font-weight: bold;
      color: #00ffff;
      text-transform: uppercase;
    }
    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
      position: relative;
      transition: all 0.3s ease;
    }
    nav a:before {
      content: '';
      position: absolute;
      width: 100%;
      height: 2px;
      background: #00ffff;
      bottom: -5px;
      left: 0;
      transform: scaleX(0);
      transform-origin: bottom right;
      transition: transform 0.3s ease;
    }
    nav a:hover:before {
      transform: scaleX(1);
      transform-origin: bottom left;
    }
    section {
      padding: 100px 50px 60px;
      max-width: 1000px;
      margin: auto;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding-top: 150px;
    }
    .hero h1 {
      font-size: 3rem;
      animation: fadeIn 2s ease-in-out;
    }
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
    .hero h1 span {
      color: #00ffff;
      animation: glow 2s infinite alternate;
    }
    @keyframes glow {
      from { text-shadow: 0 0 10px #00ffff; }
      to { text-shadow: 0 0 20px #00ffff; }
    }
    .hero p {
      margin-top: 15px;
      color: #cfcfcf;
      font-size: 1.2rem;
    }
    h2 {
      font-size: 2.2rem;
      margin-bottom: 20px;
      color: #00ffff;
      text-align: center;
    }
    p {
      font-size: 1.1rem;
      text-align: center;
      line-height: 1.6;
    }
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      margin-top: 30px;
      padding: 10px;
    }
    .skills-grid div {
      background: rgba(255, 255, 255, 0.05);
      padding: 15px;
      text-align: center;
      border-radius: 10px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      transition: transform 0.3s, background 0.3s;
    }
    .skills-grid div:hover {
      transform: scale(1.05);
      background: rgba(0, 255, 255, 0.1);
    }
    .project-card {
      max-width: 400px;
      background: rgba(255,255,255,0.05);
      padding: 20px;
      border-radius: 15px;
      border: 1px solid rgba(255,255,255,0.1);
      text-align: center;
      transition: all 0.3s ease;
    }
    .project-card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    .coding-profiles {
      display: flex;
      justify-content: center;
      gap: 40px;
      margin-top: 30px;
      flex-wrap: wrap;
    }
    .coding-profile {
      background: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      width: 150px;
      transition: transform 0.3s, background 0.3s;
    }
    .coding-profile:hover {
      transform: scale(1.1);
      background: rgba(0, 255, 255, 0.2);
    }
    .coding-profile img {
      width: 80px;
      height: 80px;
      margin-bottom: 10px;
      border-radius: 50%;
    }
    footer {
      text-align: center;
      padding: 30px;
      background: rgba(0, 0, 0, 0.4);
      margin-top: 60px;
      font-size: 0.9rem;
    }
    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
        padding: 15px 30px;
      }
      nav ul {
        flex-direction: column;
        gap: 10px;
        margin-top: 10px;
      }
      .hero h1 {
        font-size: 2.4rem;
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
        <li><a href="#coding-profiles">Coding Profiles</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Hey, I'm <span>Manaswi</span></h1>
    <p>Creative coder | CSE Student | Tech Enthusiast</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a Computer Science Engineering student with a passion for technology, problem-solving, and software development. I enjoy taking on challenges and working on projects that allow me to expand my skill set. Currently, I am exploring various domains in software development, AI, and web technologies.</p>
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
    <p><strong>B.Tech in Computer Science Engineering</strong><br/>Currently pursuing</p>
  </section>

  <section id="coding-profiles">
    <h2>Coding Profiles</h2>
    <div class="coding-profiles">
      <div class="coding-profile">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/46/LeetCode_logo_2021.svg" alt="LeetCode">
        <p><a href="https://leetcode.com/u/lr7vdo8ywa/" target="_blank">LeetCode</a></p>
      </div>
      <div class="coding-profile">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/CodeChef_logo.png" alt="CodeChef">
        <p><a href="https://www.codechef.com/users/manaswi_b" target="_blank">CodeChef</a></p>
      </div>
      <div class="coding-profile">
        <img src="https://www.mentorpick.com/assets/images/logo.png" alt="MentorPick">
        <p><a href="https://mentorpick.com/profile/23251a0571-manaswi" target="_blank">MentorPick</a></p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div style="display: flex; flex-wrap: wrap; gap: 30px; justify-content: center; align-items: center; margin-top: 30px;">
      <div class="project-card">
        <img src="https://via.placeholder.com/350x200.png?text=LULC+Project" alt="LULC Project">
        <h3 style="color: #00ffff;">LULC Classification</h3>
        <p style="color: #ccc;">A Land Use and Land Cover classification tool using satellite imagery and a pre-trained ResNet50 model. Built with Streamlit and geospatial data focused on Indian cities.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:manaswibichala@gmail.com">manaswibichala@gmail.com</a></p>
    <p>Phone: <a href="tel:+916301797314">6301797314</a></p>
    <p style="margin-top: 20px;">Feel free to reach out for further details!</p>
  </section>

  <footer>
    <p>© 2025 Manaswi — Designed with 💙 in HTML & CSS</p>
  </footer>

</body>
</html>


