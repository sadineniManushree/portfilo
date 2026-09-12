# portfilo
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sadineni Manushree — AI & Data Science</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --ink:#0d1117;
    --panel:#141b22;
    --panel-2:#1b232c;
    --line:#2a333d;
    --text:#e7edf3;
    --muted:#8d9aa6;
    --signal:#c6ff3d;
    --signal-dim:#8fb82c;
    --blue:#6fb8ff;
    --radius:2px;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--ink);
    color:var(--text);
    font-family:'Inter', sans-serif;
    line-height:1.6;
    overflow-x:hidden;
  }
  h1,h2,h3{font-family:'Space Grotesk', sans-serif; font-weight:600; letter-spacing:-0.01em;}
  .mono{font-family:'JetBrains Mono', monospace;}
  a{color:inherit; text-decoration:none;}

  /* background grid texture */
  .grid-bg{
    position:fixed; inset:0; z-index:-1;
    background-image:
      linear-gradient(var(--line) 1px, transparent 1px),
      linear-gradient(90deg, var(--line) 1px, transparent 1px);
    background-size:48px 48px;
    opacity:0.18;
    mask-image:radial-gradient(ellipse 80% 60% at 50% 20%, black 40%, transparent 90%);
  }

  header.hero{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    padding:8vh 8vw 6vh;
    position:relative;
    border-bottom:1px solid var(--line);
  }
  .path-line{
    font-family:'JetBrains Mono', monospace;
    font-size:0.8rem;
    color:var(--signal);
    margin-bottom:1.5rem;
    display:flex;
    align-items:center;
    gap:0.5rem;
  }
  .path-line .dot{
    width:6px; height:6px; border-radius:50%;
    background:var(--signal);
    box-shadow:0 0 8px var(--signal);
    animation:pulse 2s infinite ease-in-out;
  }
  @keyframes pulse{
    0%,100%{opacity:1;}
    50%{opacity:0.3;}
  }
  .name{
    font-size:clamp(2.6rem, 7vw, 5.2rem);
    line-height:1.02;
    max-width:16ch;
  }
  .tagline{
    margin-top:1.4rem;
    font-size:clamp(1.05rem, 2vw, 1.3rem);
    color:var(--muted);
    max-width:46ch;
  }
  .tagline strong{color:var(--text); font-weight:500;}

  nav.buttons{
    margin-top:3rem;
    display:flex;
    flex-wrap:wrap;
    gap:0.9rem;
  }
  .nav-btn{
    font-family:'JetBrains Mono', monospace;
    font-size:0.85rem;
    padding:0.85rem 1.4rem;
    border:1px solid var(--line);
    background:var(--panel);
    color:var(--text);
    border-radius:var(--radius);
    cursor:pointer;
    transition:border-color 0.15s ease, background 0.15s ease, transform 0.15s ease;
    display:inline-flex;
    align-items:center;
    gap:0.5rem;
  }
  .nav-btn::before{content:"./"; color:var(--muted);}
  .nav-btn:hover{
    border-color:var(--signal);
    background:var(--panel-2);
    transform:translateY(-2px);
  }

  section{
    padding:7rem 8vw;
    border-bottom:1px solid var(--line);
    max-width:1100px;
    margin:0 auto;
  }
  .section-tag{
    font-family:'JetBrains Mono', monospace;
    font-size:0.78rem;
    color:var(--signal-dim);
    margin-bottom:0.8rem;
  }
  .section-tag::before{content:"# ";}
  h2{font-size:clamp(1.8rem, 3.4vw, 2.6rem); margin-bottom:1.8rem;}

  /* ABOUT */
  .about-grid{
    display:grid;
    grid-template-columns:1.2fr 1fr;
    gap:3.5rem;
    align-items:start;
  }
  .about-text p{color:var(--muted); font-size:1.05rem; max-width:56ch;}
  .about-text p + p{margin-top:1rem;}
  .skills-card{
    background:var(--panel);
    border:1px solid var(--line);
    border-radius:var(--radius);
    padding:1.6rem 1.8rem;
    font-family:'JetBrains Mono', monospace;
    font-size:0.88rem;
  }
  .skills-card .file-label{color:var(--muted); font-size:0.75rem; margin-bottom:1rem; border-bottom:1px solid var(--line); padding-bottom:0.8rem;}
  .skill-row{margin-bottom:0.9rem;}
  .skill-key{color:var(--blue);}
  .skill-val{color:var(--text);}

  /* PROJECTS */
  .project-card{
    background:var(--panel);
    border:1px solid var(--line);
    border-radius:var(--radius);
    padding:2.2rem;
    position:relative;
    overflow:hidden;
  }
  .project-card::before{
    content:"";
    position:absolute; top:0; left:0; width:3px; height:100%;
    background:var(--signal);
  }
  .project-top{
    display:flex; justify-content:space-between; align-items:baseline;
    flex-wrap:wrap; gap:0.6rem;
    margin-bottom:1rem;
  }
  .project-top h3{font-size:1.5rem;}
  .status-pill{
    font-family:'JetBrains Mono', monospace;
    font-size:0.72rem;
    color:var(--signal);
    border:1px solid var(--signal-dim);
    padding:0.25rem 0.6rem;
    border-radius:20px;
  }
  .project-card p{color:var(--muted); max-width:60ch;}
  .tag-row{margin-top:1.4rem; display:flex; flex-wrap:wrap; gap:0.5rem;}
  .tag{
    font-family:'JetBrains Mono', monospace;
    font-size:0.72rem;
    color:var(--muted);
    border:1px solid var(--line);
    padding:0.3rem 0.6rem;
    border-radius:var(--radius);
  }

  /* CASE STUDY */
  .case-wrap{display:grid; grid-template-columns:1fr 1fr; gap:3rem; align-items:center;}
  .case-text p{color:var(--muted); font-size:1.02rem; max-width:52ch;}
  .case-text p + p{margin-top:1rem;}
  .flow-box{
    background:var(--panel);
    border:1px solid var(--line);
    border-radius:var(--radius);
    padding:1.6rem;
  }
  .flow-box svg{width:100%; height:auto; display:block;}
  .flow-node{fill:var(--panel-2); stroke:var(--line); stroke-width:1.5;}
  .flow-node.active{stroke:var(--signal);}
  .flow-text{font-family:'JetBrains Mono', monospace; font-size:11px; fill:var(--text);}
  .flow-arrow{stroke:var(--muted); stroke-width:1.5; fill:none; marker-end:url(#arrowhead);}
  .flow-caption{
    font-family:'JetBrains Mono', monospace;
    font-size:0.72rem; color:var(--muted);
    margin-top:1rem; text-align:center;
  }

  /* CONTACT */
  .contact-card{
    background:var(--panel);
    border:1px solid var(--line);
    border-radius:var(--radius);
    padding:2.4rem;
    display:flex; flex-wrap:wrap; gap:2rem; justify-content:space-between; align-items:center;
  }
  .contact-card p{color:var(--muted); max-width:42ch;}
  .mail-btn{
    font-family:'JetBrains Mono', monospace;
    font-size:0.95rem;
    padding:1rem 1.6rem;
    background:var(--signal);
    color:#0d1117;
    border-radius:var(--radius);
    font-weight:500;
    transition:transform 0.15s ease, background 0.15s ease;
    white-space:nowrap;
  }
  .mail-btn:hover{transform:translateY(-2px); background:#d6ff6b;}

  footer{
    padding:2.5rem 8vw;
    font-family:'JetBrains Mono', monospace;
    font-size:0.78rem;
    color:var(--muted);
    text-align:center;
  }

  @media (max-width:800px){
    .about-grid, .case-wrap{grid-template-columns:1fr;}
    section{padding:5rem 6vw;}
    .contact-card{flex-direction:column; align-items:flex-start;}
  }

  @media (prefers-reduced-motion: reduce){
    .path-line .dot{animation:none;}
    html{scroll-behavior:auto;}
  }
</style>
</head>
<body>

<div class="grid-bg"></div>

<header class="hero">
  <div class="path-line"><span class="dot"></span> student.ai_ds / b.tech</div>
  <h1 class="name">Sadineni<br>Manushree</h1>
  <p class="tagline">I'm a <strong>B.Tech student in AI & Data Science</strong>, learning by building — machine learning models, data tools, and things that make code easier to understand.</p>
  <nav class="buttons">
    <button class="nav-btn" onclick="document.getElementById('about').scrollIntoView()">about</button>
    <button class="nav-btn" onclick="document.getElementById('projects').scrollIntoView()">projects</button>
    <button class="nav-btn" onclick="document.getElementById('case-study').scrollIntoView()">case-study</button>
    <button class="nav-btn" onclick="document.getElementById('contact').scrollIntoView()">contact</button>
  </nav>
</header>

<section id="about">
  <div class="section-tag">about</div>
  <h2>About me</h2>
  <div class="about-grid">
    <div class="about-text">
      <p>I'm an AI & Data Science student interested in machine learning, data analysis, and building useful AI tools.</p>
      <p>I like learning by creating projects and solving practical problems — turning what I study into something that actually runs.</p>
    </div>
    <div class="skills-card">
      <div class="file-label">skills.json</div>
      <div class="skill-row"><span class="skill-key">"programming"</span>: <span class="skill-val">["Python", "C", "C++"]</span></div>
      <div class="skill-row"><span class="skill-key">"data"</span>: <span class="skill-val">["Pandas", "NumPy", "SQL"]</span></div>
      <div class="skill-row"><span class="skill-key">"ai_ml"</span>: <span class="skill-val">["Machine Learning", "Decision Trees", "AI Fundamentals"]</span></div>
      <div class="skill-row"><span class="skill-key">"tools"</span>: <span class="skill-val">["GitHub", "Jupyter Notebook"]</span></div>
    </div>
  </div>
</section>

<section id="projects">
  <div class="section-tag">projects</div>
  <h2>Projects</h2>
  <div class="project-card">
    <div class="project-top">
      <h3>Voluntrix</h3>
      <span class="status-pill">live</span>
    </div>
    <p>A website project focused on connecting people to volunteering opportunities — built to explore real-world front-end development and practical problem solving beyond coursework.</p>
    <div class="tag-row">
      <span class="tag">web development</span>
      <span class="tag">practical build</span>
    </div>
  </div>
</section>

<section id="case-study">
  <div class="section-tag">case study</div>
  <h2>Visualizing how code runs</h2>
  <div class="case-wrap">
    <div class="case-text">
      <p>I'm building a website that shows how code runs step-by-step with pictures, turning tricky concepts like loops and recursion into visual flowcharts.</p>
      <p>The goal is to make execution visible — so a beginner can see what a loop actually does, not just read about it.</p>
    </div>
    <div class="flow-box">
      <svg viewBox="0 0 320 260" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <marker id="arrowhead" markerWidth="8" markerHeight="8" refX="6" refY="3" orient="auto">
            <path d="M0,0 L6,3 L0,6 Z" fill="#8d9aa6"/>
          </marker>
        </defs>
        <rect class="flow-node active" x="110" y="10" width="100" height="36" rx="4"/>
        <text class="flow-text" x="160" y="32" text-anchor="middle">i = 0</text>

        <path class="flow-arrow" d="M160,46 L160,74"/>
        <polygon class="flow-node" points="160,74 210,100 160,126 110,100" />
        <text class="flow-text" x="160" y="104" text-anchor="middle">i &lt; n ?</text>

        <path class="flow-arrow" d="M160,126 L160,154"/>
        <rect class="flow-node" x="105" y="154" width="110" height="36" rx="4"/>
        <text class="flow-text" x="160" y="176" text-anchor="middle">print(i)</text>

        <path class="flow-arrow" d="M160,190 L160,214"/>
        <rect class="flow-node" x="100" y="214" width="120" height="36" rx="4"/>
        <text class="flow-text" x="160" y="236" text-anchor="middle">i = i + 1</text>

        <path class="flow-arrow" d="M100,232 C40,232 40,100 108,100" fill="none"/>
        <path class="flow-arrow" d="M210,100 C270,100 270,20 212,20" fill="none"/>
        <text class="flow-text" x="235" y="14" text-anchor="middle" fill="#8d9aa6">exit</text>
      </svg>
      <div class="flow-caption">for i in range(n): print(i)</div>
    </div>
  </div>
</section>

<section id="contact">
  <div class="section-tag">contact</div>
  <h2>Get in touch</h2>
  <div class="contact-card">
    <p>If you'd like to discuss a project, internship, or collaboration, my inbox is open.</p>
    <a class="mail-btn" href="mailto:sadinenimanushree@gamil.com">sadinenimanushree@gamil.com</a>
  </div>
</section>

<footer>© 2026 Sadineni Manushree — built while learning, one project at a time.</footer>

</body>
</html>
