- 👋 Hi, I’m @denzil mugala
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me .../0707594829
- 😄 Pronouns: ...mbwa ke
- ⚡ Fun fact: ...player boy
<!---
denzilaaa/denzilaaa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Denzil • Creator from Nairobi</title>
  <meta name="description" content="Denzil's personal website — projects, ideas, and ways to connect." />
  <meta name="robots" content="index,follow" />
  <link rel="canonical" href="https://yourdomain.com/" />

  <!-- Open Graph / Twitter -->
  <meta property="og:title" content="Denzil — Creator from Nairobi" />
  <meta property="og:description" content="Projects, notes, and ways to connect." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://yourdomain.com/" />
  <meta name="twitter:card" content="summary_large_image" />

  <!-- Favicon (replace with your file) -->
  <link rel="icon" href="/favicon.ico" />

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet" />

  <link rel="stylesheet" href="styles.css" />
  <meta name="theme-color" content="#ffffff" />
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <header class="site-header" role="banner">
    <nav class="nav" aria-label="Primary navigation">
      <a class="logo" href="/" aria-label="Homepage">Denzil</a>
      <button class="nav-toggle" aria-expanded="false" aria-controls="primary-nav">Menu</button>
      <ul id="primary-nav" class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <section class="hero" aria-labelledby="hero-heading">
      <h1 id="hero-heading">Hi — I’m Denzil: builder, romantic, and tech curious from Nairobi.</h1>
      <p>I make clear docs, playful experiences, and practical web tools.</p>
      <div class="cta">
        <a class="btn primary" href="#projects">See my work</a>
        <a class="btn" href="#contact">Get in touch</a>
      </div>
    </section>
  </header>

  <main id="main" role="main">
    <section id="about" class="section about" aria-labelledby="about-heading">
      <h2 id="about-heading">About</h2>
      <p>I mix creativity with method. From refining official documents to exploring cybersecurity tools (Nmap, SQLmap, Wireshark), I enjoy turning ideas into clean, usable things. I’m based in Tigoni, Kiambu — chai, greenery, and good vibes.</p>
      <ul class="highlights">
        <li><strong>Focus:</strong> Web fundamentals, clean formatting, ethical hacking concepts</li>
        <li><strong>Strengths:</strong> Detail, clarity, playful collaboration</li>
        <li><strong>Interests:</strong> Truth-or-dare style games, local humour, wellness</li>
      </ul>
    </section>

    <section id="projects" class="section projects" aria-labelledby="projects-heading">
      <h2 id="projects-heading">Projects</h2>
      <div class="cards">
        <article class="card" aria-labelledby="proj-site">
          <h3 id="proj-site">Personal website</h3>
          <p>A fast, minimal site (this one) built with semantic HTML/CSS, ready for GitHub Pages.</p>
          <a href="#" class="link">View</a>
        </article>

        <article class="card" aria-labelledby="proj-transcript">
          <h3 id="proj-transcript">Clean transcript template</h3>
          <p>Professional document format with clear sections and accurate styling.</p>
          <a href="#" class="link">Preview</a>
        </article>

        <article class="card" aria-labelledby="proj-cyber">
          <h3 id="proj-cyber">Cybersecurity practice</h3>
          <p>Notes and labs on SQL injection, XSS, and network analysis — ethical learning.</p>
          <a href="#" class="link">Read notes</a>
        </article>
      </div>
    </section>

    <section id="contact" class="section contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact</h2>
      <p>Say hello — I’m open to collabs and ideas. Prefer email or WhatsApp?</p>
      <div class="contact-grid">
        <a class="contact-card" href="mailto:denzilmugala2001@gmail.com">
          <span>Email</span>
          <strong>denzilmugala2001@gmail.com</strong>
        </a>

        <a class="contact-card" href="https://wa.me/254716827808" target="_blank" rel="noopener noreferrer">
          <span>WhatsApp</span>
          <strong>+254 716 827 808</strong>
        </a>

        <a class="contact-card" href="https://github.com/denzil001" target="_blank" rel="noopener noreferrer">
          <span>GitHub</span>
          <strong>@denzil001</strong>
        </a>
      </div>
    </section>
  </main>

  <footer class="site-footer" role="contentinfo">
    <p>© <span id="year"></span> Denzil — Built in Nairobi with denzil mugala.</p>
  </footer>

  <script>
    // Set year after DOM is ready
    document.addEventListener('DOMContentLoaded', function () {
      var y = document.getElementById('year');
      if (y) y.textContent = new Date().getFullYear();

      // Simple nav toggle for small screens (progressive enhancement)
      var toggle = document.querySelector('.nav-toggle');
      var nav = document.getElementById('primary-nav');
      if (toggle && nav) {
        toggle.addEventListener('click', function () {
          var expanded = this.getAttribute('aria-expanded') === 'true';
          this.setAttribute('aria-expanded', String(!expanded));
          nav.hidden = expanded;
        });
        // keep nav visible by default on wide screens (CSS should handle)
        nav.hidden = false;
      }
    });
  </script>
</body>
</html>?<soon of sheilah.
