<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tharun Naredla — Portfolio</title>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: "Segoe UI", Arial, sans-serif;
      background: #f4f6f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #1a1a1a, #343a40);
      color: #fff;
      text-align: center;
      padding: 4rem 2rem 2rem;
      border-bottom: 5px solid #00aced;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
    }

    /* Navbar */
    nav {
      margin-top: 1.5rem;
    }
    nav a {
      display: inline-block;
      margin: 0.5rem;
      padding: 0.6rem 1.2rem;
      background: #00aced;
      color: #fff;
      border-radius: 25px;
      font-size: 1rem;
      text-decoration: none;
      transition: all 0.3s ease;
    }
    nav a:hover {
      background: #0073b1;
      transform: scale(1.05);
    }

    /* Sections */
    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 2rem;
      font-size: 2rem;
      color: #0073b1;
    }

    .skills span {
      display: inline-block;
      margin: 0.5rem;
      padding: 0.5rem 1rem;
      background: #e0e0e0;
      border-radius: 8px;
      font-size: 0.95rem;
      transition: 0.3s;
    }
    .skills span:hover {
      background: #00aced;
      color: #fff;
    }

    .project {
      margin-bottom: 2rem;
      background: #fff;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .project:hover {
      transform: translateY(-5px);
    }

    .contact {
      text-align: center;
    }
    .contact a {
      display: inline-block;
      margin: 0.5rem;
      padding: 0.7rem 1.3rem;
      background: #0073b1;
      color: #fff;
      text-decoration: none;
      border-radius: 25px;
      transition: 0.3s;
    }
    .contact a:hover {
      background: #005582;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #777;
      background: #f1f1f1;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tharun Naredla</h1>
    <p>Senior Mechanical Design Engineer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p style="text-align:center; max-width:700px; margin:auto;">
      Experienced Product Development and Design Engineer with a history of working in the consumer services industry. 
      Skilled in Fusion 360, SolidWorks, AutoCAD, Solid Edge, and rapid prototyping with 3D printing.
      Passionate about mechanical design, prototyping, and building innovative solutions.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills" style="text-align:center;">
      <span>Fusion 360</span>
      <span>SolidWorks</span>
      <span>AutoCAD</span>
      <span>Solid Edge</span>
      <span>3D Printing</span>
      <span>Prototyping</span>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Automatic Food Cooking Machine (Mome)</h3>
      <p>Designed and developed a semi-automated cooking machine aimed at simplifying household cooking tasks.</p>
    </div>
    <div class="project">
      <h3>Line Follower Robot</h3>
      <p>Designed a compact PCB-controlled robot for following pre-defined paths without microcontrollers.</p>
    </div>
    <div class="project">
      <h3>Water Level & Quality Monitoring Device</h3>
      <p>Developed a water management system with instant quality measurement features for Neerovel.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="contact">
      <a href="mailto:tharun@example.com">Email Me</a>
      <a href="https://www.linkedin.com/in/tharun-naredla" target="_blank">LinkedIn</a>
      <a href="https://github.com/tharun" target="_blank">GitHub</a>
    </div>
  </section>

  <footer>
    <p>© 2025 Tharun Naredla. All Rights Reserved.</p>
  </footer>
</body>
</html>

  <section id="about">
    <h2>About Me</h2>
    <p>Experienced Product Development and Design Engineer with a demonstrated history of working in the consumer services industry. Skilled in Fusion 360, SolidWorks, AutoCAD, and Solid Edge. Extensive experience in 3D printing and prototyping. Strong engineering professional with a B.Tech in Mechanical Engineering from Sri Vasavi Engineering College, Pedatadepalli, Tadepalligudem (CC-A8). Currently pursuing an M.Tech in Design Engineering from BITS Pilani.</p>
    <p>With over six years of experience, I lead the Mechanical and Hardware team in product development and design, delivering innovative solutions across industries.</p>
  </section>

  <section id="skills">
    <h2>Skills & Technologies</h2>
    <div class="skills">
      <span>Fusion 360</span>
      <span>SolidWorks</span>
      <span>AutoCAD</span>
      <span>Solid Edge</span>
      <span>ANSYS</span>
      <span>MATLAB</span>
      <span>3D Printing</span>
      <span>Prototyping</span>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Buchuk & Mome</h3>
      <p>Automatic food cooking machine (patented). Innovated and developed into a commercial product under the brand Mome.</p>
    </div>
    <div class="project">
      <h3>Simmr</h3>
      <p>A consumer product design initiative with focus on efficient cooking and usability.</p>
    </div>
    <div class="project">
      <h3>Neerovel</h3>
      <p>Developed water level management and water quality measuring systems capable of providing instant results.</p>
    </div>
    <div class="project">
      <h3>Neogreens</h3>
      <p>Product development for sustainable agri-tech solutions.</p>
    </div>
    <div class="project">
      <h3>Consultant Designer</h3>
      <p>Provided design consultancy for Intellobots, Deeploop Technologies,TrakItNow and other startups in robotics and consumer products.</p>
    </div>
  </section>

  <section id="experience">
    <h2>Experience</h2>
    <p>Over six years of experience in product development and design, currently leading the Mechanical and Hardware team at Quainnt Techsoft Pvt Ltd, Hyderabad. Specialized in prototyping, design validation, and full-cycle product development.</p>
  </section>

  <section id="education">
    <h2>Education & Achievements</h2>
    <ul>
      <li>B.Tech in Mechanical Engineering — Sri Vasavi Engineering College, Tadepalligudem</li>
      <li>M.Tech in Design Engineering — BITS Pilani (Pursuing)</li>
      <li>Patent Holder: Automatic Food Cooking Robot</li>
      <li>Guest Lecturer at multiple engineering colleges on design and entrepreneurship</li>
      <li>Panel Member for student entrepreneurs session at Geethanjali College</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Phone: <a href="tel:+918897234230">+91 8897234230</a></p>
    <p>Email: <a href="mailto:naredlatharun@gmail.com">naredlatharun@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/tharun-naredla" target="_blank">linkedin.com/in/tharun-naredla</a></p>
  </section>

  <footer>
    &copy; 2025 Tharun Naredla. All rights reserved.
  </footer>
</body>
</html>
