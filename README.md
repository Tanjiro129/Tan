<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    /* Reset & basic styles */
    * { margin:0; padding:0; box-sizing: border-box; font-family: Arial, sans-serif; }
    body { background: #f5f5f5; color: #333; line-height: 1.6; }
    a { text-decoration: none; color: inherit; }

    /* Header */
    header { background: #1f1f1f; color: #fff; padding: 20px; text-align: center; }
    header h1 { margin-bottom: 5px; }
    header p { font-size: 0.9em; color: #ccc; }

    /* Navigation */
    nav { display: flex; justify-content: center; gap: 20px; padding: 10px 0; background: #2a2a2a; }
    nav a { color: #fff; font-weight: bold; }
    nav a:hover { color: #ff6600; }

    /* Sections */
    section { padding: 50px 20px; max-width: 900px; margin: auto; }
    h2 { text-align: center; margin-bottom: 30px; color: #1f1f1f; }

    /* About */
    #about p { text-align: center; max-width: 700px; margin: auto; }

    /* Portfolio grid */
    #portfolio { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .project { background: #fff; padding: 15px; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); text-align: center; }
    .project img { max-width: 100%; border-radius: 10px; }
    .project h3 { margin: 10px 0; }
    .project p { font-size: 0.9em; color: #555; }

    /* Contact form */
    #contact form { display: flex; flex-direction: column; max-width: 500px; margin: auto; gap: 15px; }
    #contact input, #contact textarea { padding: 10px; border-radius: 5px; border: 1px solid #ccc; }
    #contact button { padding: 10px; background: #1f1f1f; color: #fff; border: none; border-radius: 5px; cursor: pointer; }
    #contact button:hover { background: #ff6600; }

    /* Footer */
    footer { text-align: center; padding: 20px; background: #1f1f1f; color: #ccc; }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Your Name</h1>
    <p>Anime Video Editor | Digital Creator</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I am a passionate anime video editor and digital creator. I create cool edits, presets, and content for fans worldwide. Welcome to my portfolio website!</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <h2>My Work</h2>
    <div class="project">
      <img src="project1.jpg" alt="Project 1">
      <h3>Anime Edit 1</h3>
      <p>Description of this project. Add music, CC style, or vibe here.</p>
    </div>
    <div class="project">
      <img src="project2.jpg" alt="Project 2">
      <h3>Anime Edit 2</h3>
      <p>Description of this project. Add music, CC style, or vibe here.</p>
    </div>
    <div class="project">
      <img src="project3.jpg" alt="Project 3">
      <h3>Anime Edit 3</h3>
      <p>Description of this project. Add music, CC style, or vibe here.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form action="https://formspree.io/f/yourformid" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>
