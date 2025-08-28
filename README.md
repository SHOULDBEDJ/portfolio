<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dheeraj Manohar Katwe – Portfolio</title>
  <meta name="description" content="Software Engineer | AI & Full‑Stack Developer – Portfolio of Dheeraj Manohar Katwe" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg: #0b0f17;         /* page background */
      --card: #121826;       /* card background */
      --text: #e5e7eb;       /* primary text */
      --subtext: #94a3b8;    /* secondary text */
      --brand: #2563eb;      /* updated accent */
      --brand-2:#f97316;     /* updated accent 2 */
      --muted: #1f2937;      /* borders */
    }
    *{box-sizing:border-box}
    html,body{margin:0}
    body{
      font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans", "Apple Color Emoji", "Segoe UI Emoji";
      background: radial-gradient(1200px 800px at 80% -10%, rgba(37,99,235,.15), transparent 60%),
                  radial-gradient(1200px 800px at 10% 110%, rgba(249,115,22,.15), transparent 60%),
                  var(--bg);
      color: var(--text);
      line-height: 1.6;
      overflow-x: hidden;
    }
    a{color: inherit}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    .pill{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:999px;background:rgba(37,99,235,.12);border:1px solid rgba(37,99,235,.35);color:#dbeafe;font-weight:600;font-size:12px;letter-spacing:.2px}
    header{position:sticky;top:0;backdrop-filter: blur(10px);background: linear-gradient(180deg, rgba(11,15,23,.7), rgba(11,15,23,.3) 70%, transparent);z-index:50;border-bottom:1px solid rgba(255,255,255,.06)}
    nav{display:flex;align-items:center;justify-content:space-between;padding:14px 24px}
    nav .links{display:flex;gap:18px}
    nav a{opacity:.9;text-decoration:none;font-weight:600}
    nav a:hover{opacity:1;color:#fff}

    /* Hero */
    .hero{padding:80px 0 40px}
    .hero-inner{display:grid;grid-template-columns:1.2fr .8fr;gap:32px;align-items:center}
    .title{font-size:44px;line-height:1.15;margin:12px 0 8px;font-weight:800}
    .gradient{background: linear-gradient(90deg, var(--brand), var(--brand-2));-webkit-background-clip:text;background-clip:text;color:transparent}
    .subtitle{color:var(--subtext);max-width:720px}
    .cta{display:flex;gap:12px;margin-top:22px}
    .btn{padding:12px 16px;border-radius:14px;border:1px solid var(--muted);background:#0f1523;font-weight:700;text-decoration:none;display:inline-flex;align-items:center;gap:10px}
    .btn.primary{background: linear-gradient(90deg, var(--brand), var(--brand-2));color:#0b0f17;border:none}
    .btn:hover{transform: translateY(-1px);box-shadow:0 8px 20px rgba(34,211,238,.12)}
    .hero-card{background:linear-gradient(180deg, rgba(37,99,235,.12), rgba(249,115,22,.08));border:1px solid rgba(255,255,255,.08);padding:22px;border-radius:16px}

    /* Sections */
    section{padding:52px 0;border-top:1px solid rgba(255,255,255,.06)}
    .section-title{font-size:22px;margin:0 0 18px;font-weight:800}
    .grid{display:grid;gap:18px}
    .grid.cols-2{grid-template-columns:repeat(2,1fr)}
    .grid.cols-3{grid-template-columns:repeat(3,1fr)}

    /* Cards */
    .card{background:var(--card);border:1px solid rgba(255,255,255,.07);border-radius:16px;padding:18px}
    .card h3{margin:6px 0 8px;font-size:18px}
    .badge{display:inline-block;background:rgba(255,255,255,.06);padding:6px 10px;border-radius:999px;font-weight:600;font-size:12px;margin:4px 6px 0 0;color:#cbd5e1;border:1px solid rgba(255,255,255,.08)}

    /* Timeline */
    .timeline{position:relative;margin-left:10px}
    .timeline:before{content:"";position:absolute;left:8px;top:0;bottom:0;width:2px;background:rgba(255,255,255,.1)}
    .tl-item{position:relative;padding-left:28px;margin:14px 0}
    .tl-item:before{content:"";position:absolute;left:2px;top:.55rem;width:12px;height:12px;border-radius:999px;background:linear-gradient(90deg, var(--brand), var(--brand-2));box-shadow:0 0 0 3px rgba(37,99,235,.15)}
    .muted{color:var(--subtext)}

    /* Footer */
    footer{padding:36px 0;color:var(--subtext);font-size:14px}

    /* Responsive */
    @media (max-width: 900px){
      .hero-inner{grid-template-columns:1fr}
      .grid.cols-2{grid-template-columns:1fr}
      .grid.cols-3{grid-template-columns:1fr}
      .title{font-size:36px}
    }

    /* Simple reveal animation */
    .reveal{opacity:0;transform:translateY(10px);transition:all .5s ease}
    .reveal.show{opacity:1;transform:none}
  </style>
</head>
<body>
  <header>
    <nav class="container">
      <div style="display:flex;align-items:center;gap:10px;font-weight:900;letter-spacing:.3px">
        <span class="pill">Portfolio</span>
        <span>Dheeraj M. Katwe</span>
      </div>
      <div class="links">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#education">Education</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <!-- HERO -->
  <section class="hero container">
    <div class="hero-inner">
      <div>
        <div class="pill">Software Engineer • AI & Full‑Stack</div>
        <h1 class="title">Hi, I'm <span class="gradient">Dheeraj Manohar Katwe</span> 👋</h1>
        <p class="subtitle">
          Crafting innovative digital experiences through <strong>AI/ML</strong> and <strong>full‑stack development</strong>. Passionate about blending technology and creativity to deliver impactful, user‑focused solutions.
        </p>
        <div class="cta">
          <a class="btn primary" href="./resume_dheeraj_manohar_katwe.pdf" download>
            ⬇️ Download Resume
          </a>
          <a class="btn" href="#contact">✉️ Contact Me</a>
        </div>
      </div>
      <div class="hero-card">
        <h3 style="margin:0 0 8px">Quick Snapshot</h3>
        <ul style="margin:0;padding-left:18px;color:var(--subtext)">
          <li>AI/ML: TensorFlow/Keras, OpenCV, CNNs</li>
          <li>Frontend: HTML, CSS, JavaScript, React, Angular, Vue</li>
          <li>Backend: Node/Express, Django, ASP.NET, PHP, Laravel</li>
          <li>Databases: MySQL, MongoDB, PostgreSQL, SQL Server, SQLite</li>
          <li>Tools: Git, VS Code, Jupyter, FlutterFlow</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="container reveal">
    <h2 class="section-title">About Me</h2>
    <div class="card">
      <p>
        I’m a software engineer passionate about turning ideas into reliable products. I build across the stack and apply
        machine learning to solve real problems. Recent highlights include a CNN‑based leaf disease classifier and a
        full‑featured library management system.
      </p>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills" class="container reveal">
    <h2 class="section-title">Skills</h2>
    <div class="grid cols-3">
      <div class="card">
        <h3>Frontend</h3>
        <p class="muted">HTML, CSS, JavaScript, React, Angular, Vue.js, Flutter, WordPress</p>
      </div>
      <div class="card">
        <h3>Backend</h3>
        <p class="muted">Node.js, Express.js, PHP, Django, ASP.NET, Laravel, Python, Java, C, C++, C#</p>
      </div>
      <div class="card">
        <h3>Databases</h3>
        <p class="muted">MySQL, MongoDB, PostgreSQL, SQL Server, SQLite</p>
      </div>
      <div class="card">
        <h3>AI/ML & Libraries</h3>
        <p class="muted">TensorFlow/Keras, OpenCV, NumPy, Pandas, Matplotlib</p>
      </div>
      <div class="card">
        <h3>Tools & Platforms</h3>
        <p class="muted">VS Code, Git, Jupyter Notebook, FlutterFlow</p>
      </div>
      <div class="card">
        <h3>Soft Skills</h3>
        <p class="muted">Problem‑solving, Clean code, Team collaboration, Documentation</p>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="container reveal">
    <h2 class="section-title">Projects</h2>

    <div class="grid cols-2">
      <article class="card">
        <div class="badge">AI / Computer Vision</div>
        <h3>Leaf Disease Detection System</h3>
        <p class="muted">
          CNN‑powered system using Python, TensorFlow/Keras and OpenCV to identify plant types and classify leaves as
          healthy or diseased, improving agricultural decision‑making.
        </p>
        <p style="margin-top:10px"><strong>Tech:</strong> Python, TensorFlow/Keras (CNN), OpenCV, NumPy, Pandas, Matplotlib</p>
      </article>

      <article class="card">
        <div class="badge">Full‑Stack</div>
        <h3>Library Management System</h3>
        <p class="muted">
          Application built with Python (Tkinter/Django) and SQL to manage inventory, member registration, borrowing &
          returns, fine calculation, real‑time availability and overdue alerts.
        </p>
        <p style="margin-top:10px"><strong>Tech:</strong> Python (Tkinter/Django), SQLite/MySQL, HTML, CSS, JavaScript</p>
      </article>

      <article class="card">
        <div class="badge">Web Development</div>
        <h3>Personal Portfolio Website</h3>
        <p class="muted">
          A responsive and interactive portfolio showcasing my skills, projects, and professional journey. Built to attract recruiters and demonstrate design + development abilities.
        </p>
        <p style="margin-top:10px"><strong>Tech:</strong> HTML, CSS, JavaScript</p>
      </article>
    </div>
  </section>

  <!-- EDUCATION -->
  <section id="education" class="container reveal">
    <h2 class="section-title">Education</h2>
    <div class="timeline">
      <div class="tl-item">
        <h3>BE in AI & ML – G M Institute of Technology, Davangere</h3>
        <div class="muted">CGPA: 7.5 • Feb 2023 – Apr 2025</div>
      </div>
      <div class="tl-item">
        <h3>Diploma in Computer Science – Government Polytechnic Hubli</h3>
        <div class="muted">CGPA: 7.4 • Aug 2018 – 2021</div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="container reveal">
    <h2 class="section-title">Contact</h2>
    <div class="grid cols-2">
      <div class="card">
        <p class="muted">Let’s collaborate or talk about opportunities.</p>
        <p><strong>Phone:</strong> <a href="tel:9113565802">+91 9113565802</a></p>
        <p><strong>Email:</strong> <a href="mailto:dhirajkatwe109@gmail.com">dhirajkatwe109@gmail.com</a></p>
        <p><strong>Location:</strong> Hubli, India</p>
      </div>
      <div class="card">
        <p><a class="btn" href="https://www.linkedin.com/in/dhiraj-katwe-9a95b6370" target="_blank" rel="noreferrer">🔗 LinkedIn</a></p>
        <p><a class="btn" href="https://github.com/SHOULDBEDJ" target="_blank" rel="noreferrer">💻 GitHub</a></p>
      </div>
    </div>
  </section>

  <footer class="container">
    © <span id="year"></span> Dheeraj Manohar Katwe — Built with ❤️ and clean code.
  </footer>
  
  <script>
    // year
    document.getElementById('year').textContent = new Date().getFullYear();
    // simple reveal on scroll
    const els = document.querySelectorAll('.reveal');
    const io = new IntersectionObserver((entries)=>{
      entries.forEach(e=>{ if(e.isIntersecting){ e.target.classList.add('show'); io.unobserve(e.target); } });
    }, {threshold:.12});
    els.forEach(el=>io.observe(el));
  </script>
</body>
</html>
