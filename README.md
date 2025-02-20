<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>My Portfolio</title>
  <meta name="description" content="">
  <meta name="viewport" content="width=device-width,
initial-scale=1">
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <canvas id="particleCanvas"></canvas>
  <!-- NavBar -->
  <nav class="navbar">
    <div class="nav-container">
      <h1>Your Name</h1>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </nav>
  
<!-- About Me Section-->
<section id="about">
  <div class="about-content">
    <div class="intro-section">
      <h2>Your Name</h2>
      <h3>Web Developer</h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing
elit. Quibusdam dicta nihil dignissimos dolorum
          magnam neque doloribus. Perferendis amet
distinctio doloribus, iure expedita ratione recusandae
deleniti aspernatur, consectetur, eligendi
labore? Ut?Lorem ipsum dolor sit amet consectetur,
adipisicing elit. Similique eius tempore at quae
odit quod asperiores non quasi neque laboriosam
illo ipsa exercitationem, ipsam incidunt quo est
beatae rem ea.
</p>
<div class="social-links">
<a href="https://github.com/YourGitHubUsername"
class="contact-link">
<svg xmlns="http://www.w3.org/2000/svg"
width="24" height="24" viewBox="0 0 24 24" fill="none"
stroke="currentColor" strokeWidth="2">
<path
d="M9 19c-5 1.5-5-2.5-7-3m14
6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44
0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0
0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0
0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22">
</path>
</svg>
<span>GitHub</span>
</a>
<a href="mailto:Your Email address"
class="contact-link">
<svg xmlns="http://www.w3.org/2000/svg"
width="24" height="24" viewBox="0 0 24 24" fill="none"
stroke="currentColor" strokeWidth="2">
<path d="M4 4h16c1.1 0 2 .9 2 2v12c0
1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z">
</path>
<polyline points="22,6 12,13
2,6"></polyline>
</svg>
<span>Email</span>
</a>
</div>
</div>
</div>
<img src="assets/profile-placeholder (1).jpg" alt="Profile"
class="profile-img">
</section>
<section id="skills">
<div class="skills-container">
<h3>Skills & Technologies</h3>
<div class="skills-grid">
<!-- Frontend Development -->
<div class="skill-category">
<h4>Frontend</h4>
<div class="skill-items">
<span class="skill-tag">JavaScript</span>
<span class="skill-tag">HTML5</span>
<span class="skill-tag">CSS3</span>
</div>
</div>
<!-- Backend Development -->
<div class="skill-category">
<h4>Backend</h4>
<div class="skill-items">
<span class="skill-tag">Java</span>
</div>
</div>
<!-- Developer Tools -->
<div class="skill-category">
<h4>Tools & Practices</h4>
<div class="skill-items">
<span class="skill-tag">Git</span>
<span class="skill-tag">GitHub</span>
<span class="skill-tag">VS Code</span>
</div>
</div>
</div>
</div>
</section>
<!-- Projects Section -->
<section id="projects">
<h2>My Projects</h2>
<div class="projects-container">
<div class="project-card">
<div class="project-image">
<img src="TBD.png" alt="My Portfolio">
</div>
<div class="project-content">
<h3>My Portfolio</h3>
<p>A responsive personal portfolio website
developed during an 8-week workshop, featuring an about
section, skills showcase, project gallery,
and contact form. The site implements modern design
principles with smooth scrolling navigation
and interactive elements.</p>
<div class="tech-stack">
<span>HTML</span>
<span>JavaScript</span>
<span>CSS</span>
</div>
<div class="project-links">
<a href="Your Github link"
class="project-link" target="_blank">
<svg xmlns="http://www.w3.org/2000/svg"
width="24" height="24" viewBox="0 0 24 24"
fill="none" stroke="currentColor"
stroke-width="2">
<path d="M18 13v6a2 2 0 0 1-2 2H5a2 2
0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path>
<polyline points="15 3 21 3 21
9"></polyline>
<line x1="10" y1="14" x2="21"
y2="3"></line>
</svg>
</a>
</a>
</div>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section id="contact">
<h2>Contact Me</h2>
<form class="contact-form"
action="https://api.web3forms.com/submit" method="POST">
<input type="hidden" name="access_key" value="Your
accesskey">
<div class="form-group">
<label for="name">Name</label>
<input type="text" id="name" name="name" required>
</div>
<div class="form-group">
<label for="email">Email</label>
<input type="email" id="email" name="email" required>
</div>
<div class="form-group">
<label for="message">Message</label>
<textarea id="message" name="message" rows="5"
required></textarea>
</div>
<button type="submit">Send Message</button>
</form>
</section>
<script src="app.js"></script>
<script src="particles.js"></script>
</body>
</html>
