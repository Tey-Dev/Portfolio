---
layout: default
---

<link rel="stylesheet" href="style.css">

<div class="container">
  <div class="left-section">
    <div class="profile-section">
      <img src="avatar1.png" alt="Profile Picture" class="avatar">
      <h1>Teymarr Page</h1>
      <div class="title">Front-End Developer | UI/UX Designer</div>
    </div>
    
    <div class="about-section">
      <h2>About Me</h2>
      <p>I'm a passionate developer focused on creating beautiful and functional web experiences. I specialize in frontend development and UI/UX design.</p>
    </div>
    
    <div class="contact-links">
      <a href="mailto:teymarrpage@tuta.io">Email</a>
      <a href="https://linkedin.com/in/teymarrpagedev/">LinkedIn</a>
      <a href="https://github.com/tey-dev">GitHub</a>
      <a href="path/to/resume.pdf">Resume</a>
    </div>
  </div>

  <div class="projects-section">
    <h2>Work</h2>
    {% for post in site.posts %}
    <div class="project-card">
      <h3>{{ post.title }}</h3>
      <p>{{ post.description }}</p>
      <div class="project-links">
      </div>
    </div>
    {% endfor %}
  </div>
</div>

