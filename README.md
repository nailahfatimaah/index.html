<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alex Styles Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background: linear-gradient(to right, red, blue, yellow);
      color: white;
      text-align: center;
      padding: 1.5rem;
    }

    nav {
      margin-top: 0.5rem;
    }

    nav a {
      margin: 0 1rem;
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: yellow;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      margin-bottom: 1rem;
      color: #e63946;
    }

    /* Flexbox Portfolio */
    .portfolio {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      background: white;
      border: 2px solid #457b9d;
      border-radius: 8px;
      padding: 1rem;
      width: 250px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #eee;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Alex Styles</h1>
    <p>Graphic Designer Portfolio</p>
    <nav>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m Alex Styles, a passionate graphic designer who loves creating clean, modern, and colorful designs that connect with people.</p>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio">
      <div class="card">Project 1</div>
      <div class="card">Project 2</div>
      <div class="card">Project 3</div>
      <div class="card">Project 4</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: alex.styles@example.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Alex Styles</p>
  </footer>

</body>
</html>
