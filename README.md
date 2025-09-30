<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tharun Naredla — Portfolio</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:wght@400;700&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
      font-size: 18px; /* bigger base font */
    }
    header {
      background: #808080; /* grey background */
      color: white;
      text-align: center;
      padding: 3rem 1rem;
      font-family: 'Libre Baskerville', serif; /* Baskerville style */
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
    }
    header h2 {
      margin: 0.5rem 0 0;
      font-weight: normal;
      font-size: 1.6rem;
    }
    header img {
      margin-top: 1rem;
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 4px solid white;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1rem;
    }
    section {
      margin-bottom: 2rem;
    }
    h3 {
      font-size: 1.6rem;
      margin-bottom: 0.8rem;
    }
    p {
      line-height: 1.6;
      font-size: 1.1rem;
    }
    .project {
      background: white;
      padding: 1rem;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin-bottom: 1.5rem;
    }
    .project img {
      width: 100%;
      border-radius: 12px;
      margin: 1rem 0;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #333;
      color: white;
    }
    footer a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-size: 1.2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tharun Naredla</h1>
    <h2>Senior Mechanical Design Engineer</h2>
    <img src="profile.jpg" alt="Tharun Naredla">
  </header>

  <main>
    <section>
      <h3>About Me</h3>
      <p>
        Experienced Product Development and Design Engineer with a demonstrated history of working in the consumer services industry.
        Skilled in Fusion 360, SolidWorks, AutoCAD, and Solid Edge. Lots of experience in 3D printing and prototyping.
      </p>
    </section>

    <section>
      <h3>Projects</h3>
      <div class="project">
        <h4>Automatic Food Cooking Machine (Mome)</h4>
        <img src="mome.jpg" alt="Mome Project">
        <p>Designed and developed a semi-automated cooking machine aimed at simplifying household cooking tasks.</p>
      </div>
      <div class="project">
        <h4>Line Follower Robot PCB</h4>
        <img src="robot.jpg" alt="Robot Project">
        <p>Created a custom PCB design for a line follower robot without a microcontroller, using an L9110S motor driver.</p>
      </div>
    </section>
  </main>

  <footer>
    <a href="https://github.com/TharunNaredla" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/tharun-naredla" target="_blank">LinkedIn</a>
  </footer>
</body>
</html>
