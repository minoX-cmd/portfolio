<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Web Developer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background: #f5f5f5;
      color: #333;
    }

    header {
      background: #111;
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .project {
      flex: 1 1 250px;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .contact {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 30px 20px;
    }

    a {
      color: #0066cc;
      text-decoration: none;
    }

    @media (max-width: 600px) {
      .projects {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Med.Amine Abdeljawed</h1>
    <p>HTML/CSS Web Developer</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>I’m a passionate frontend web developer who loves building clean, responsive websites. I specialize in HTML and CSS, and I'm working toward building a better future through code.</p>
  </section>

  <section>
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Landing Page</h3>
        <p>A clean and modern landing page for a fictional product.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>Portfolio Site</h3>
        <p>This very portfolio site you're looking at. Built from scratch.</p>
        <a href="#">View Project</a>
      </div>
    </div>
  </section>

  <section class="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:your.email@example.com">amiindjappa@gmail.com
    </a></p>
  </section>

</body>
</html>
