<!DOCTYPE html>
<html>
<head>
  <title>My Personal Website</title>
  <style>
    /* Background Animation */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      color: white;
      background: linear-gradient(-45deg, #6dd5fa, #2980b9, #6a11cb, #2575fc);
      background-size: 400% 400%;
      animation: gradientBG 10s ease infinite;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header {
      background: rgba(0, 0, 0, 0.6);
      padding: 20px;
      animation: fadeIn 2s;
    }

    nav a {
      margin: 0 15px;
      color: #f1c40f;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffdb4d;
    }

    section {
      padding: 40px 20px;
      animation: fadeIn 2s;
    }

    h2 {
      border-bottom: 2px solid #f1c40f;
      display: inline-block;
      padding-bottom: 5px;
      animation: fadeIn 3s;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin: 10px 0;
      animation: fadeIn 3s;
    }

    .skills span {
      display: inline-block;
      background: #f1c40f;
      color: black;
      padding: 5px 12px;
      margin: 5px;
      border-radius: 5px;
      font-weight: bold;
      transition: transform 0.3s, background 0.3s;
    }
    .skills span:hover {
      transform: scale(1.1);
      background: #ffe066;
    }

    footer {
      background: rgba(0, 0, 0, 0.6);
      padding: 15px;
      margin-top: 20px;
      animation: fadeIn 4s;
    }

    .profile-pic {
      width: 350px;
      border-radius: 50%;
      border: 3px solid white;
      margin: 20px 0;
      animation: fadeIn 2s;
    }

    a {
      color: #f1c40f;
      transition: color 0.3s;
    }
    a:hover {
      color: #ffe066;
    }

    /* Fade-in Animation */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }    }

  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Hi, I'm Noor Jahan</h1>
    <img src="https://via.placeholder.com/150" alt="My Photo" class="profile-pic">
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#hobbies">Hobbies</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Noor Jahan, a BCA graduate passionate about technology, creativity, and problem-solving.  
    This personal website was built completely using my phone 📱.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>My Skills</h2>
    <div class="skills">
      <span>HTML</span>
      <span>CSS</span>
      <span>JavaScript</span>
      <span>Python</span>
      <span>Creative Writing</span>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>My Projects</h2>
    <ul>
      <li><strong>Calculator App</strong> – A simple app built using python</li>
      <li><strong>Portfolio Website</strong> – Showcasing my profile and work.</li>
      <li><strong>E-commerce website</strong> – A productivity tool made in HTML & php.</li>
    </ul>
  </section>

  <!-- Hobbies Section -->
  <section id="hobbies">
    <h2>My Hobbies</h2>
    <ul>
      <li>📖 Reading Books</li>
      <li>🎵 Listening to podcast</li>
      <li>✍️ Writing Blogs</li>
      <li>💻 Learning New Tech</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="noorjahan.66002@gmail.com">noorjahan.66002@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/noor-jahan-01154734b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">linkedin.com/in/Noorjahan </a></p>
    <p>GitHub: <a href="https://github.com/noorjahan66">github.com/noorjahan66</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 My Personal Website | Made with ❤️ on my phone</p>
  </footer>
</body>
  </html>
