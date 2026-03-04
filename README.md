<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Navya Portfolio</title>
  <style>
    body {
      margin:0;
      font-family: Arial, sans-serif;
      line-height:1.6;
      background:#f5f5f5;
      color:#333;
    }
    header {
      background:#0D47A1;
      color:white;
      padding:60px 20px;
      text-align:center;
    }
    header h1 {
      margin:0;
      font-size:3em;
    }
    header p {
      font-size:1.2em;
      margin-top:10px;
    }
    nav {
      background:#1565C0;
      padding:10px;
      text-align:center;
    }
    nav a {
      color:white;
      margin:0 15px;
      text-decoration:none;
      font-weight:bold;
    }
    section {
      max-width:900px;
      margin:40px auto;
      padding:20px;
      background:white;
      border-radius:8px;
      box-shadow:0 2px 5px rgba(0,0,0,0.1);
    }
    h2 {
      color:#0D47A1;
      margin-bottom:15px;
    }
    ul {
      list-style: square inside;
      padding-left:0;
    }
    footer {
      background:#0D47A1;
      color:white;
      text-align:center;
      padding:20px;
      margin-top:40px;
    }
    .skills div {
      margin-bottom:10px;
    }
    .progress {
      background:#ddd;
      border-radius:10px;
      overflow:hidden;
      height:15px;
    }
    .progress-bar {
      height:15px;
      background:#1565C0;
      width:0%;
    }
    /* Project Card Styles */
    .project-card {
      background: #fff;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }
    .project-card h3 {
      color: #0D47A1;
      margin-bottom: 10px;
    }
    .project-card p {
      margin-bottom: 8px;
    }
    .project-card a {
      color: #1565C0;
      text-decoration: none;
      font-weight: bold;
    }
    .project-card a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Navya</h1>
    <p>Aspiring Technology Professional | Portfolio Website</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome</h2>
    <p>Hello! Welcome to my personal portfolio website. My name is Navya, and I am passionate about technology, software development, web design, and data systems. Explore my work, skills, and projects below.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a student passionate about technology and innovation. My academic journey has allowed me to develop strong skills in programming, database management, and web development. I enjoy building projects that solve real-world problems and improving user experiences through technology.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>

    <!-- FireFighter1 Project -->
    <div class="project-card">
      <h3>FireFighter1 IT Solution</h3>
      <p><strong>Overview:</strong> Developed a comprehensive IT solution for FireFighter1, a company providing wildfire defense systems. Includes hardware, software, data storage, and networking infrastructure to support business operations.</p>
      <p><strong>Technologies & Tools:</strong> Dell Server, HP Workstations, Lenovo Laptops, Shopify, Fishbowl Inventory, QuickBooks, SugarCRM, QNAP NAS, AT&T Business Fiber, TP-Link Router, NETGEAR Switch</p>
      <p><strong>Website/Documentation:</strong> <a href="https://mohammed-likith.weebly.com" target="_blank">View Project Example</a></p>
      <!-- Optional Image -->
      <!-- <img src="images/firefighter1-diagram.png" alt="FireFighter1 Diagram" style="width:100%; border-radius:5px; margin-top:10px;"> -->
    </div>

    <!-- Example Additional Project -->
    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p><strong>Overview:</strong> Built a responsive personal portfolio website to showcase my projects and skills.</p>
      <p><strong>Technologies & Tools:</strong> HTML, CSS, JavaScript</p>
    </div>

  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div>Web Development (HTML, CSS, JS)</div>
    <div>Database Management (SQL, Design)</div>
    <div class="progress"><div class="progress-bar" style="width:80%"></div></div>
    <div>Programming & Algorithms</div>
    <div class="progress"><div class="progress-bar" style="width:75%"></div></div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: navya@email.com</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/navya" target="_blank">linkedin.com/in/navya</a></p>
  </section>

  <footer>
    © 2026 Navya Portfolio
  </footer>

</body>
</html>>
