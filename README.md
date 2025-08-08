 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>B.I.D. AUDIO</title>
  <link rel="stylesheet" href="styles.css" />
:root {
  --bg: #0B0D0F;
  --red: #3B0A0F;
  --gold: #D4AF37;
  --turquoise: #00CED1;
  --text: #F5DEB3;
  --muted: #A9A9A9;
  --font-main: 'Inter', sans-serif;
  --font-heading: 'Montserrat', sans-serif;
}

body {
  margin: 0;
  font-family: var(--font-main);
  background: var(--bg);
  color: var(--text);
}

header {
  background: linear-gradient(to right, var(--red), var(--bg));
  padding: 1rem 2rem;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  height: 60px;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1rem;
  padding: 0;
  margin: 0;
}

.nav-links a {
  color: var(--text);
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 5rem 2rem;
  background: radial-gradient(circle at center, var(--red), var(--bg));
}

.hero-logo {
  height: 100px;
  margin-bottom: 1rem;
}

.hero-title {
  font-family: var(--font-heading);
  font-size: 2.5rem;
  margin: 0.5rem 0;
  color: var(--gold);
}

.hero-tagline {
  font-size: 1.2rem;
  color: var(--turquoise);
  margin-bottom: 2rem;
}

.btn {
  background: var(--gold);
  color: var(--bg);
  padding: 0.75rem 1.5rem;
  border: none;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
  transition: background 0.3s;
}

.btn:hover {
  background: var(--turquoise);
}

footer {
  text-align: center;
  padding: 1rem;
  font-size: 0.9rem;
  color: var(--muted);
}
  <script src="app.js" defer></script>
</head>
<body>
  <header>
    <nav class="navbar">
      <img src="assets/logo.png" alt="B.I.D. AUDIO Logo" class="logo" />
      <ul class="nav-links">
        <li><a href="about.html">About</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="samples.html">Samples</a></li>
        <li><a href="pricing.html">Pricing</a></li>
        <li><a href="branding.html">Branding</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="blog.html">Blog</a></li>
      </ul>
    </nav>
  </header>

  <main class="hero">
    <div class="hero-content">
      <img src="assets/logo.png" alt="B.I.D. AUDIO Logo" class="hero-logo" />
      <h1 class="hero-title">Let Your Identity Be Heard</h1>
      <p class="hero-tagline">BRAND YOUR IDENTITY W/ SOUND</p>
      <a href="about.html" class="btn">Explore Our Vision</a>
    </div>
  </main>

  <footer>
    <p>&copy; 2025 B.I.D. AUDIO</p>
  </footer>
</body>
</html>¹
