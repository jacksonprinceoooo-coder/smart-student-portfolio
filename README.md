<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Smart Student Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #0077cc;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav ul {
      list-style: none;
      padding: 0;
      margin: 10px 0 0;
    }

    nav ul li {
      display: inline;
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      background-color: white;
      margin: 20px;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #0077cc;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    button {
      background-color: #0077cc;
      color: white;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      border-radius: 4px;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#certifications">Certifications</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate student with interests in programming, problem-solving, and Tamil culture.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>Python Arithmetic Calculator</li>
      <li>Natural Resources Research Report</li>
      <li>GitHub Portfolio Website</li>
    </ul>
  </section>

  <section id="certifications">
    <h2>Certifications</h2>
    <p>Completed courses in Python, Web Development, and Data Analysis.</p>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <a href="resume.pdf" download>Download My Resume</a>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Smart Student Portfolio</p>
  </footer>
</body>
</html>
