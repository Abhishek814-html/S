<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>

  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

  <style>
    html { scroll-behavior: smooth; }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background: #f4f4f4;
      color: #333;
    }
    nav {
      display: flex;
      justify-content: space-between;
      padding: 15px 30px;
      background: #333;
      color: white;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav ul { display: flex; list-style: none; gap: 20px; margin: 0; padding: 0; }
    nav a { color: white; text-decoration: none; transition: color 0.3s; }
    nav a:hover { color: #ff9800; }
    .hero {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(to right, #667eea, #764ba2);
      color: white;
    }
    .hero span { color: #ff9800; }
    .btn {
      display: inline-block;
      padding: 12px 24px;
      background: #ff9800;
      color: white;
      text-decoration: none;
      border-radius: 25px;
      margin-top: 15px;
      transition: background 0.3s;
    }
    .btn:hover { background: #e68900; }
    section { padding: 50px 20px; text-align: center; }
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .project-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
      padding-bottom: 10px;
    }
    .project-card:hover { transform: scale(1.05); }
    .project-card img { width: 100%; height: 200px; object-fit: cover; }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      width: 300px;
      margin: auto;
    }
    input, textarea, button {
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ddd;
    }
    button {
      background: #333;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover { background: #ff9800; }
    footer {
      background: #333;
      color: white;
      padding: 15px;
      text-align: center;
    }
  </style>
</head>
<body>

<header>
  <nav>
    <h1 class="logo">Your Name</h1>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<section id="home" class="hero" data-aos="fade-up">
  <h2>Hi, I'm <span>Your Name</span></h2>
  <p>Web Designer | Developer | Learner</p>
  <a href="#" class="btn">Download Resume</a>
</section>

<section id="about" data-aos="fade-right">
  <h2>About Me</h2>
  <p>Hello! I'm a passionate web designer who loves creating clean and responsive websites. 
     I enjoy learning new technologies and bringing creative ideas to life through code.</p>
</section>

<section id="projects" data-aos="zoom-in">
  <h2>My Projects</h2>
  <div class="project-grid">
    <div class="project-card">
      <img src="https://via.placeholder.com/400x200" alt="Project 1">
      <h3>Project One</h3>
      <p>Short description of the project.</p>
      <a href="#">View Project</a>
    </div>
    <div class="project-card">
      <img src="https://via.placeholder.com/400x200" alt="Project 2">
      <h3>Project Two</h3>
      <p>Short description of the project.</p>
      <a href="#">View Project</a>
    </div>
  </div>
</section>

<section id="contact" data-aos="fade-up">
  <h2>Contact Me</h2>
  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea placeholder="Your Message" required></textarea>
    <button type="submit">Send</button>
  </form>
</section>

<footer>
  <p>© 2025 Your Name. All Rights Reserved.</p>
</footer>

<!-- Inline JS -->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init();
</script>

</body>
</html>