<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
  
  <!-- AOS Animation Library -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body>

<!-- Navbar -->
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

<!-- Hero Section -->
<section id="home" class="hero" data-aos="fade-up">
  <h2>Hi, I'm <span>Your Name</span></h2>
  <p>Web Designer | Developer | Learner</p>
  <a href="resume.pdf" download class="btn">Download Resume</a>
</section>

<!-- About Section -->
<section id="about" data-aos="fade-right">
  <h2>About Me</h2>
  <p>Hello! I'm a passionate web designer who loves creating clean and responsive websites.</p>
</section>

<!-- Projects Section -->
<section id="projects" data-aos="zoom-in">
  <h2>My Projects</h2>
  <div class="project-grid">
    <div class="project-card">
      <img src="images/project1.jpg" alt="Project 1">
      <h3>Project One</h3>
      <p>Short description of the project.</p>
      <a href="#">View Project</a>
    </div>
    <div class="project-card">
      <img src="images/project2.jpg" alt="Project 2">
      <h3>Project Two</h3>
      <p>Short description of the project.</p>
      <a href="#">View Project</a>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" data-aos="fade-up">
  <h2>Contact Me</h2>
  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea placeholder="Your Message"></textarea>
    <button type="submit">Send</button>
  </form>
</section>

<footer>
  <p>© 2025 Your Name. All Rights Reserved.</p>
</footer>

<!-- JS -->
<script src="script.js"></script>
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init();
</script>

</body>
</html>