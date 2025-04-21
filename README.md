<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Srilekha | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0f0f0f;
      color: #fff;
      scroll-behavior: smooth;
    }

    #particles-js {
      position: fixed;
      width: 100%;
      height: 100%;
      z-index: -1;
      background: #0f0f0f;
    }

    header {
      background: rgba(26, 26, 26, 0.85);
      padding: 2rem;
      text-align: center;
      position: relative;
      z-index: 1;
    }

    h1 {
      font-size: 2.8rem;
      margin: 0;
      color: #00ffe7;
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      color: #ccc;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00ffe7;
    }

    section {
      padding: 4rem 2rem;
      max-width: 900px;
      margin: auto;
      position: relative;
      z-index: 1;
    }

    h2 {
      font-size: 2rem;
      color: #00ffe7;
      margin-bottom: 1rem;
    }

    .highlight {
      color: #00ffe7;
    }

    .card {
      background: rgba(26, 26, 26, 0.9);
      border-radius: 1rem;
      padding: 2rem;
      margin: 1rem 0;
      box-shadow: 0 4px 12px rgba(0, 255, 231, 0.2);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 16px rgba(0, 255, 231, 0.3);
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: rgba(17, 17, 17, 0.9);
      font-size: 0.9rem;
      position: relative;
      z-index: 1;
    }

    a.button {
      display: inline-block;
      margin-top: 1rem;
      margin-right: 1rem;
      padding: 0.7rem 1.5rem;
      border-radius: 5px;
      background-color: #00ffe7;
      color: #000;
      font-weight: bold;
      text-decoration: none;
      transition: 0.3s;
    }

    a.button:hover {
      background: #00c9b7;
    }

    ul.skills-list {
      list-style-type: square;
      padding-left: 1.5rem;
    }

    form input, form textarea {
      width: 100%;
      padding: 0.75rem;
      margin: 0.5rem 0;
      border-radius: 5px;
      border: none;
      font-family: 'Poppins', sans-serif;
    }

    form button {
      background-color: #00ffe7;
      border: none;
      padding: 0.7rem 1.5rem;
      border-radius: 5px;
      color: #000;
      font-weight: bold;
      cursor: pointer;
    }

    @media screen and (max-width: 600px) {
      h1 {
        font-size: 2rem;
      }

      h2 {
        font-size: 1.5rem;
      }

      nav a {
        display: block;
        margin: 0.5rem 0;
      }
    }
  </style>
</head>
<body>

  <div id="particles-js"></div>

  <header>
    <h1>Hi, I'm <span class="highlight">Srilekha</span> 👩‍💻</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>👋 About Me</h2>
    <div class="card">
      <p>
        I'm an enthusiastic <span class="highlight">Information Technology student</span> passionate about building Web applications,
        solving real-world problems through code, and becoming a future <span class="highlight">SDE at Microsoft</span>. 💙
        I love exploring tech and crafting clean, functional websites!
      </p>
    </div>
  </section>

  <section id="skills">
    <h2>💡 My Skills</h2>
    <div class="card">
      <ul class="skills-list">
        <li><strong>Languages:</strong> C, C++, Python, JavaScript, SQL</li>
        <li><strong>Web Development:</strong> HTML, CSS, JavaScript, React</li>
        <li><strong>Tools:</strong> Git, GitHub, VS Code, Postman</li>
        <li><strong>Cloud:</strong> Learning AWS ☁️</li>
      </ul>
    </div>
  </section>
  <section id="contact">
    <h2>📬 Contact Me</h2>
    <div class="card">
      <p>Email: <a href="mailto:akkipellisrilekha@gmail.com" class="highlight">akkipellisrilekha@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/srilekha-akkipelli-31a346293/" class="highlight" target="_blank">linkedin.com/in/https://www.linkedin.com/in/srilekha-akkipelli-31a346293/</a></p>
      <p>Code Chef: <a href="https://www.codechef.com/users/srilekha1266" class="highlight" target="_blank">https://www.codechef.com/users/srilekha1266</a></p>
      <p>LeetCode: <a href="https://leetcode.com/u/srilekha0/" class="hilight" target="_blank">https://leetcode.com/u/srilekha0/</a></p>
      <a class="button" href="mailto:akkipellisrilekha@gmail.com">Email Me</a>
      <a class="button" href="https://www.linkedin.com/in/srilekha-akkipelli-31a346293/" target="_blank">Visit LinkedIn</a>
      <a class="button" href="https://www.codechef.com/users/srilekha1266" target="_blank">Visit My CodeChef Profile</a>
    </div>
  </section>

  <section id="projects">
    <h2>🚀 My Projects</h2>
    <div class="card">
      <h3>Interview Maze</h3>
      <p>A web app that displays interview questions by domain like SDE, UPSC, and more. Built with HTML, CSS, and JavaScript.</p>
    </div>
    <div class="card">
      <h3>Email to WhatsApp Alerts</h3>
      <p>Used Gmail API + Twilio to send WhatsApp alerts from emails (subject + sender) using Python. Polling every 10 mins.</p>
    </div>
  </section>

  <section id="contact">
    <h2>📬 Contact Me</h2>
    <div class="card">
      <form action="https://formspree.io/f/yourformid" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="text" name="phone" placeholder="Phone Number">
        <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    Made with 💖 by Srilekha | © 2025
  </footer>

  <script>
    particlesJS("particles-js", {
      "particles": {
        "number": {
          "value": 80,
          "density": {
            "enable": true,
            "value_area": 800
          }
        },
        "color": { "value": "#00ffe7" },
        "shape": {
          "type": "circle",
          "stroke": { "width": 0, "color": "#000" }
        },
        "opacity": {
          "value": 0.5,
          "random": true
        },
        "size": {
          "value": 3,
          "random": true
        },
        "line_linked": {
          "enable": true,
          "distance": 150,
          "color": "#00ffe7",
          "opacity": 0.4,
          "width": 1
        },
        "move": {
          "enable": true,
          "speed": 2,
          "direction": "none",
          "out_mode": "bounce"
        }
      },
      "interactivity": {
        "detect_on": "canvas",
        "events": {
          "onhover": { "enable": true, "mode": "grab" },
          "onclick": { "enable": true, "mode": "push" },
          "resize": true
        },
        "modes": {
          "grab": {
            "distance": 140,
            "line_linked": { "opacity": 0.7 }
          },
          "push": {
            "particles_nb": 4
          }
        }
      },
      "retina_detect": true
    });
  </script>

</body>
</html>
