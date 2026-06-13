<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>moonmido — Boutmedjet Abd elmoudjib</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=JetBrains+Mono:wght@300;400;600&family=Syne:wght@700;800&display=swap');

  :root {
    --bg:        #0a0e1a;
    --surface:   #111827;
    --surface2:  #1a2235;
    --border:    #1e3a5f;
    --accent:    #00d4ff;
    --accent2:   #7c3aed;
    --accent3:   #10b981;
    --gold:      #f59e0b;
    --text:      #e2e8f0;
    --muted:     #64748b;
    --danger:    #ef4444;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Space Grotesk', sans-serif;
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* ── CANVAS BACKGROUND ── */
  #bg-canvas {
    position: fixed;
    inset: 0;
    z-index: 0;
    pointer-events: none;
    opacity: 0.35;
  }

  .page {
    position: relative;
    z-index: 1;
    max-width: 900px;
    margin: 0 auto;
    padding: 60px 24px 100px;
  }

  /* ── HERO ── */
  .hero {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 20px;
    padding-bottom: 60px;
  }

  .avatar-ring {
    position: relative;
    width: 110px;
    height: 110px;
    flex-shrink: 0;
  }
  .avatar-ring svg.ring {
    position: absolute;
    inset: -8px;
    width: calc(100% + 16px);
    height: calc(100% + 16px);
    animation: spin 6s linear infinite;
  }
  @keyframes spin { to { transform: rotate(360deg); } }
  .avatar-ring img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border: 3px solid var(--surface2);
    object-fit: cover;
    display: block;
  }
  .avatar-fallback {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    background: linear-gradient(135deg, var(--accent2), var(--accent));
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 38px;
    font-weight: 800;
    color: #fff;
    font-family: 'Syne', sans-serif;
  }

  .hero-name {
    font-family: 'Syne', sans-serif;
    font-size: clamp(2rem, 6vw, 3.2rem);
    font-weight: 800;
    background: linear-gradient(135deg, #fff 0%, var(--accent) 60%, var(--accent2) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    line-height: 1.1;
    animation: fadeUp 0.7s ease both;
  }

  .hero-handle {
    font-family: 'JetBrains Mono', monospace;
    font-size: 1rem;
    color: var(--accent);
    letter-spacing: 0.05em;
    animation: fadeUp 0.8s ease both;
  }

  .hero-tagline {
    font-size: 1.05rem;
    color: var(--muted);
    max-width: 540px;
    line-height: 1.6;
    animation: fadeUp 0.9s ease both;
  }

  .badge-row {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    justify-content: center;
    animation: fadeUp 1s ease both;
  }
  .badge {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.72rem;
    padding: 4px 12px;
    border-radius: 20px;
    border: 1px solid;
    letter-spacing: 0.04em;
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .badge:hover { transform: translateY(-2px); box-shadow: 0 4px 20px rgba(0,212,255,0.25); }
  .badge-blue  { border-color: var(--accent);  color: var(--accent);  background: rgba(0,212,255,0.07); }
  .badge-purple{ border-color: var(--accent2); color: var(--accent2); background: rgba(124,58,237,0.07); }
  .badge-green { border-color: var(--accent3); color: var(--accent3); background: rgba(16,185,129,0.07); }
  .badge-gold  { border-color: var(--gold);    color: var(--gold);    background: rgba(245,158,11,0.07); }

  .stat-row {
    display: flex;
    gap: 32px;
    justify-content: center;
    animation: fadeUp 1.1s ease both;
  }
  .stat { text-align: center; }
  .stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 1.6rem;
    font-weight: 800;
    color: var(--accent);
    display: block;
  }
  .stat-label {
    font-size: 0.75rem;
    color: var(--muted);
    letter-spacing: 0.06em;
    text-transform: uppercase;
  }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(18px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  /* ── SECTION ── */
  .section {
    margin-bottom: 56px;
    opacity: 0;
    transform: translateY(24px);
    transition: opacity 0.6s ease, transform 0.6s ease;
  }
  .section.visible { opacity: 1; transform: translateY(0); }

  .section-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.68rem;
    color: var(--accent);
    letter-spacing: 0.14em;
    text-transform: uppercase;
    margin-bottom: 10px;
  }
  .section-title {
    font-family: 'Syne', sans-serif;
    font-size: 1.55rem;
    font-weight: 800;
    color: #fff;
    margin-bottom: 24px;
  }

  .divider {
    height: 1px;
    background: linear-gradient(90deg, var(--accent) 0%, transparent 100%);
    margin-bottom: 28px;
    width: 100%;
  }

  /* ── SKILL BARS ── */
  .skills-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 14px 32px;
  }
  @media (max-width: 600px) { .skills-grid { grid-template-columns: 1fr; } }

  .skill-item { display: flex; flex-direction: column; gap: 5px; }
  .skill-meta {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .skill-name {
    font-size: 0.85rem;
    font-weight: 500;
    display: flex;
    align-items: center;
    gap: 6px;
  }
  .skill-pct {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.75rem;
    color: var(--muted);
  }
  .bar-track {
    height: 5px;
    background: var(--surface2);
    border-radius: 99px;
    overflow: hidden;
  }
  .bar-fill {
    height: 100%;
    border-radius: 99px;
    width: 0;
    transition: width 1.2s cubic-bezier(.22,.61,.36,1);
  }
  .bar-cyan   { background: linear-gradient(90deg, var(--accent), #0099bb); }
  .bar-purple { background: linear-gradient(90deg, var(--accent2), #5b21b6); }
  .bar-green  { background: linear-gradient(90deg, var(--accent3), #059669); }
  .bar-gold   { background: linear-gradient(90deg, var(--gold), #d97706); }

  /* ── TECH RADAR / BUBBLE CHART ── */
  #radar-canvas {
    width: 100%;
    max-width: 480px;
    height: 340px;
    display: block;
    margin: 0 auto;
  }

  /* ── PROJECT CARDS ── */
  .projects-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 16px;
  }
  @media (max-width: 600px) { .projects-grid { grid-template-columns: 1fr; } }

  .project-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px;
    transition: border-color 0.3s, transform 0.3s, box-shadow 0.3s;
    cursor: default;
    position: relative;
    overflow: hidden;
  }
  .project-card::before {
    content: '';
    position: absolute;
    inset: 0;
    opacity: 0;
    transition: opacity 0.3s;
    pointer-events: none;
  }
  .project-card.c-blue::before   { background: radial-gradient(circle at top left, rgba(0,212,255,0.07), transparent 70%); }
  .project-card.c-purple::before { background: radial-gradient(circle at top left, rgba(124,58,237,0.07), transparent 70%); }
  .project-card.c-green::before  { background: radial-gradient(circle at top left, rgba(16,185,129,0.07), transparent 70%); }
  .project-card.c-gold::before   { background: radial-gradient(circle at top left, rgba(245,158,11,0.07), transparent 70%); }
  .project-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 40px rgba(0,0,0,0.4);
  }
  .project-card:hover { border-color: var(--accent); }
  .project-card.c-purple:hover { border-color: var(--accent2); }
  .project-card.c-green:hover  { border-color: var(--accent3); }
  .project-card.c-gold:hover   { border-color: var(--gold); }
  .project-card:hover::before  { opacity: 1; }

  .project-icon { font-size: 1.6rem; margin-bottom: 10px; }
  .project-name {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 1rem;
    color: #fff;
    margin-bottom: 6px;
  }
  .project-desc {
    font-size: 0.8rem;
    color: var(--muted);
    line-height: 1.55;
    margin-bottom: 12px;
  }
  .project-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }
  .ptag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.65rem;
    padding: 2px 8px;
    border-radius: 4px;
    background: var(--surface2);
    color: var(--muted);
    border: 1px solid var(--border);
  }

  /* ── LANGUAGE DONUT ── */
  .lang-row {
    display: flex;
    align-items: center;
    gap: 40px;
    flex-wrap: wrap;
  }
  #lang-canvas {
    width: 200px;
    height: 200px;
    flex-shrink: 0;
  }
  .lang-legend {
    display: flex;
    flex-direction: column;
    gap: 10px;
    flex: 1;
    min-width: 160px;
  }
  .legend-item {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 0.85rem;
  }
  .legend-dot {
    width: 10px;
    height: 10px;
    border-radius: 50%;
    flex-shrink: 0;
  }
  .legend-pct {
    margin-left: auto;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.75rem;
    color: var(--muted);
  }

  /* ── ACTIVITY HEATMAP ── */
  #heat-canvas {
    width: 100%;
    height: 80px;
    display: block;
  }

  /* ── TIMELINE ── */
  .timeline { position: relative; padding-left: 28px; }
  .timeline::before {
    content: '';
    position: absolute;
    left: 0;
    top: 6px;
    bottom: 6px;
    width: 2px;
    background: linear-gradient(180deg, var(--accent), var(--accent2), transparent);
    border-radius: 2px;
  }
  .tl-item {
    position: relative;
    margin-bottom: 28px;
  }
  .tl-item::before {
    content: '';
    position: absolute;
    left: -33px;
    top: 5px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    border: 2px solid var(--accent);
    background: var(--bg);
    box-shadow: 0 0 8px var(--accent);
  }
  .tl-year {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.7rem;
    color: var(--accent);
    letter-spacing: 0.06em;
    margin-bottom: 3px;
  }
  .tl-title {
    font-weight: 600;
    font-size: 0.95rem;
    color: #fff;
    margin-bottom: 4px;
  }
  .tl-desc {
    font-size: 0.82rem;
    color: var(--muted);
    line-height: 1.5;
  }

  /* ── FOOTER ── */
  .footer {
    text-align: center;
    padding-top: 40px;
    border-top: 1px solid var(--border);
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.75rem;
    color: var(--muted);
  }
  .footer a { color: var(--accent); text-decoration: none; }

  /* ── TYPING CURSOR ── */
  .cursor {
    display: inline-block;
    width: 2px;
    height: 1em;
    background: var(--accent);
    margin-left: 2px;
    animation: blink 0.9s step-end infinite;
    vertical-align: middle;
  }
  @keyframes blink { 50% { opacity: 0; } }

  /* ── CONTACT PILL ── */
  .contact-row {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
    justify-content: center;
  }
  .contact-pill {
    display: flex;
    align-items: center;
    gap: 7px;
    padding: 9px 18px;
    border-radius: 30px;
    border: 1px solid var(--border);
    background: var(--surface);
    font-size: 0.82rem;
    color: var(--text);
    text-decoration: none;
    transition: border-color 0.25s, box-shadow 0.25s, transform 0.2s;
  }
  .contact-pill:hover {
    border-color: var(--accent);
    box-shadow: 0 0 16px rgba(0,212,255,0.2);
    transform: translateY(-2px);
    color: var(--accent);
  }
</style>
</head>
<body>

<canvas id="bg-canvas"></canvas>

<div class="page">

  <!-- ── HERO ── -->
  <header class="hero">
    <div class="avatar-ring">
      <svg class="ring" viewBox="0 0 126 126" fill="none" xmlns="http://www.w3.org/2000/svg">
        <circle cx="63" cy="63" r="60" stroke="url(#rg)" stroke-width="2" stroke-dasharray="8 6" stroke-linecap="round"/>
        <defs>
          <linearGradient id="rg" x1="0" y1="0" x2="126" y2="126" gradientUnits="userSpaceOnUse">
            <stop offset="0%" stop-color="#00d4ff"/>
            <stop offset="50%" stop-color="#7c3aed"/>
            <stop offset="100%" stop-color="#10b981"/>
          </linearGradient>
        </defs>
      </svg>
      <div class="avatar-fallback">MA</div>
    </div>

    <div>
      <div class="hero-name">Boutmedjet Abd elmoudjib</div>
      <div class="hero-handle">@moonmido · moonmido<span class="cursor"></span></div>
    </div>

    <p class="hero-tagline">
      Software Engineer · Full-Stack & Mobile Developer · Desktop Apps · AI Automation & ML Enthusiast — building real things from Algeria 🇩🇿
    </p>

    <div class="badge-row">
      <span class="badge badge-blue">Full-Stack</span>
      <span class="badge badge-purple">Mobile (React Native)</span>
      <span class="badge badge-green">Backend / Spring Boot</span>
      <span class="badge badge-gold">AI &amp; ML</span>
      <span class="badge badge-blue">Microservices</span>
      <span class="badge badge-purple">Event-Driven</span>
    </div>

    <div class="stat-row">
      <div class="stat"><span class="stat-num" id="cnt-repos">52</span><span class="stat-label">Repos</span></div>
      <div class="stat"><span class="stat-num" id="cnt-stars">5</span><span class="stat-label">Stars</span></div>
      <div class="stat"><span class="stat-num" id="cnt-follow">17</span><span class="stat-label">Followers</span></div>
      <div class="stat"><span class="stat-num">6</span><span class="stat-label">Pinned</span></div>
    </div>
  </header>

  <!-- ── SKILLS ── -->
  <section class="section" id="sec-skills">
    <div class="section-label">// 01 · SKILLS</div>
    <div class="section-title">Tech Stack & Proficiency</div>
    <div class="divider"></div>
    <div class="skills-grid">
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">⚛️ React Native / Expo</span><span class="skill-pct">90%</span></div>
        <div class="bar-track"><div class="bar-fill bar-cyan" data-w="90"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">☕ Java / Spring Boot</span><span class="skill-pct">88%</span></div>
        <div class="bar-track"><div class="bar-fill bar-purple" data-w="88"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">🌐 JavaScript / React</span><span class="skill-pct">85%</span></div>
        <div class="bar-track"><div class="bar-fill bar-cyan" data-w="85"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">🔥 Firebase</span><span class="skill-pct">82%</span></div>
        <div class="bar-track"><div class="bar-fill bar-gold" data-w="82"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">🐘 PostgreSQL</span><span class="skill-pct">80%</span></div>
        <div class="bar-track"><div class="bar-fill bar-green" data-w="80"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">🔍 Elasticsearch</span><span class="skill-pct">75%</span></div>
        <div class="bar-track"><div class="bar-fill bar-purple" data-w="75"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">📨 Apache Kafka</span><span class="skill-pct">72%</span></div>
        <div class="bar-track"><div class="bar-fill bar-gold" data-w="72"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">🤖 AI / ML / Spring AI</span><span class="skill-pct">70%</span></div>
        <div class="bar-track"><div class="bar-fill bar-cyan" data-w="70"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">🔐 Keycloak / Auth</span><span class="skill-pct">70%</span></div>
        <div class="bar-track"><div class="bar-fill bar-purple" data-w="70"></div></div>
      </div>
      <div class="skill-item">
        <div class="skill-meta"><span class="skill-name">🐋 Docker / Microservices</span><span class="skill-pct">68%</span></div>
        <div class="bar-track"><div class="bar-fill bar-green" data-w="68"></div></div>
      </div>
    </div>
  </section>

  <!-- ── LANGUAGE CHART ── -->
  <section class="section" id="sec-lang">
    <div class="section-label">// 02 · LANGUAGES</div>
    <div class="section-title">Repository Languages</div>
    <div class="divider"></div>
    <div class="lang-row">
      <canvas id="lang-canvas"></canvas>
      <div class="lang-legend">
        <div class="legend-item"><div class="legend-dot" style="background:#f0db4f"></div>JavaScript<span class="legend-pct">62%</span></div>
        <div class="legend-item"><div class="legend-dot" style="background:#7c3aed"></div>Java<span class="legend-pct">31%</span></div>
        <div class="legend-item"><div class="legend-dot" style="background:#00d4ff"></div>TypeScript<span class="legend-pct">4%</span></div>
        <div class="legend-item"><div class="legend-dot" style="background:#10b981"></div>Other<span class="legend-pct">3%</span></div>
      </div>
    </div>
  </section>

  <!-- ── PROJECTS ── -->
  <section class="section" id="sec-projects">
    <div class="section-label">// 03 · PROJECTS</div>
    <div class="section-title">Pinned Repositories</div>
    <div class="divider"></div>
    <div class="projects-grid">

      <div class="project-card c-blue">
        <div class="project-icon">🇩🇿</div>
        <div class="project-name">AlgeriaTravel-App</div>
        <div class="project-desc">Cross-platform mobile travel guide for Algeria with destination browsing, real-time data, Firebase auth, and tabbed navigation.</div>
        <div class="project-tags">
          <span class="ptag">React Native</span><span class="ptag">Expo</span><span class="ptag">Firebase</span><span class="ptag">JavaScript</span>
        </div>
      </div>

      <div class="project-card c-green">
        <div class="project-icon">🥗</div>
        <div class="project-name">Victus</div>
        <div class="project-desc">On-device AI turns raw body metrics into actionable daily nutrition targets. Uses Gemini AI + React Native Expo.</div>
        <div class="project-tags">
          <span class="ptag">React Native</span><span class="ptag">Gemini AI</span><span class="ptag">Expo</span>
        </div>
      </div>

      <div class="project-card c-purple">
        <div class="project-icon">💬</div>
        <div class="project-name">Talkeria</div>
        <div class="project-desc">Algerian cross-platform chat app built with Expo React Native & Firebase, supporting Android and iOS.</div>
        <div class="project-tags">
          <span class="ptag">React Native</span><span class="ptag">Firebase</span><span class="ptag">Cross-Platform</span>
        </div>
      </div>

      <div class="project-card c-gold">
        <div class="project-icon">🏥</div>
        <div class="project-name">AI Medical Scheduler</div>
        <div class="project-desc">AI-powered appointment system integrated with Google Calendar — interprets patient requests, checks availability, books automatically.</div>
        <div class="project-tags">
          <span class="ptag">AI Agents</span><span class="ptag">Google Calendar</span><span class="ptag">Automation</span>
        </div>
      </div>

      <div class="project-card c-blue">
        <div class="project-icon">📄</div>
        <div class="project-name">DocuSmart</div>
        <div class="project-desc">Secure AI-powered document management backend: Spring Boot, Keycloak, Spring AI, Kafka, PostgreSQL, Elasticsearch, RBAC.</div>
        <div class="project-tags">
          <span class="ptag">Java</span><span class="ptag">Spring Boot</span><span class="ptag">Kafka</span><span class="ptag">Keycloak</span><span class="ptag">Spring AI</span>
        </div>
      </div>

      <div class="project-card c-green">
        <div class="project-icon">📍</div>
        <div class="project-name">GeoProximity</div>
        <div class="project-desc">High-performance proximity microservice: geohash indexing, Kafka event streaming, Eureka service discovery, k-nearest lookup.</div>
        <div class="project-tags">
          <span class="ptag">Java</span><span class="ptag">Microservices</span><span class="ptag">Kafka</span><span class="ptag">Eureka</span>
        </div>
      </div>

    </div>
  </section>

  <!-- ── ARCHITECTURE SPECIALTY ── -->
  <section class="section" id="sec-arch">
    <div class="section-label">// 04 · ARCHITECTURE</div>
    <div class="section-title">What I Build</div>
    <div class="divider"></div>
    <canvas id="radar-canvas" width="480" height="340"></canvas>
  </section>

  <!-- ── ACTIVITY HEATMAP ── -->
  <section class="section" id="sec-activity">
    <div class="section-label">// 05 · ACTIVITY</div>
    <div class="section-title">Contribution Heatmap</div>
    <div class="divider"></div>
    <canvas id="heat-canvas"></canvas>
  </section>

  <!-- ── TIMELINE ── -->
  <section class="section" id="sec-timeline">
    <div class="section-label">// 06 · JOURNEY</div>
    <div class="section-title">Developer Timeline</div>
    <div class="divider"></div>
    <div class="timeline">
      <div class="tl-item">
        <div class="tl-year">2022</div>
        <div class="tl-title">Started Software Engineering</div>
        <div class="tl-desc">Began university studies in Software Engineering, laying foundations in algorithms, OOP, and data structures.</div>
      </div>
      <div class="tl-item">
        <div class="tl-year">2023</div>
        <div class="tl-title">Mobile Development — React Native</div>
        <div class="tl-desc">Dove into cross-platform mobile apps with Expo & Firebase. Built Talkeria, a full-featured Algerian chat app.</div>
      </div>
      <div class="tl-item">
        <div class="tl-year">2024</div>
        <div class="tl-title">Backend & System Design — Java / Spring Boot</div>
        <div class="tl-desc">Mastered Spring Boot, microservices, Kafka event streaming, Elasticsearch, Keycloak. Built DocuSmart & GeoProximity.</div>
      </div>
      <div class="tl-item">
        <div class="tl-year">2025</div>
        <div class="tl-title">AI Integration & Automation</div>
        <div class="tl-desc">Integrated Spring AI, Gemini, and AI Agents into real apps. Built an AI Medical Scheduler and AI nutrition app (Victus).</div>
      </div>
      <div class="tl-item">
        <div class="tl-year">2026 →</div>
        <div class="tl-title">Shipping & Growing</div>
        <div class="tl-desc">52 repositories and counting. Full-stack, mobile, backend, AI — building end-to-end products from Algeria to the world. 🚀</div>
      </div>
    </div>
  </section>

  <!-- ── CONTACT ── -->
  <section class="section" id="sec-contact">
    <div class="section-label">// 07 · CONNECT</div>
    <div class="section-title">Let's Build Something</div>
    <div class="divider"></div>
    <div class="contact-row">
      <a class="contact-pill" href="https://github.com/moonmido" target="_blank">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.3 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61-.546-1.385-1.335-1.755-1.335-1.755-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 21.795 24 17.295 24 12c0-6.63-5.37-12-12-12z"/></svg>
        GitHub
      </a>
      <a class="contact-pill" href="mailto:moonmido@example.com">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m2 7 10 7 10-7"/></svg>
        Email
      </a>
      <a class="contact-pill" href="https://github.com/moonmido" target="_blank">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
        LinkedIn
      </a>
    </div>
  </section>

  <footer class="footer">
    <p>Built with ❤️ in Algeria · <a href="https://github.com/moonmido">github.com/moonmido</a></p>
    <p style="margin-top:6px;">© 2026 Boutmedjet Abd elmoudjib</p>
  </footer>

</div>

<script>
/* ── PARTICLE BACKGROUND ── */
(function() {
  const canvas = document.getElementById('bg-canvas');
  const ctx = canvas.getContext('2d');
  let W, H, pts = [], animId;

  function resize() {
    W = canvas.width  = window.innerWidth;
    H = canvas.height = window.innerHeight;
  }
  resize();
  window.addEventListener('resize', resize);

  class Pt {
    constructor() { this.reset(); }
    reset() {
      this.x = Math.random() * W;
      this.y = Math.random() * H;
      this.vx = (Math.random() - .5) * .4;
      this.vy = (Math.random() - .5) * .4;
      this.r = Math.random() * 1.5 + .3;
      this.life = 1; this.decay = Math.random() * .002 + .001;
      const c = [[0,212,255],[124,58,237],[16,185,129]];
      const [r,g,b] = c[Math.floor(Math.random()*c.length)];
      this.color = `${r},${g},${b}`;
    }
    update() {
      this.x += this.vx; this.y += this.vy; this.life -= this.decay;
      if (this.life <= 0 || this.x < 0 || this.x > W || this.y < 0 || this.y > H) this.reset();
    }
    draw() {
      ctx.beginPath();
      ctx.arc(this.x, this.y, this.r, 0, Math.PI*2);
      ctx.fillStyle = `rgba(${this.color},${this.life * .8})`;
      ctx.fill();
    }
  }

  for (let i = 0; i < 80; i++) pts.push(new Pt());

  function draw() {
    ctx.clearRect(0, 0, W, H);
    // connect nearby
    for (let i = 0; i < pts.length; i++) {
      for (let j = i+1; j < pts.length; j++) {
        const dx = pts[i].x - pts[j].x, dy = pts[i].y - pts[j].y;
        const d = Math.sqrt(dx*dx + dy*dy);
        if (d < 100) {
          ctx.beginPath();
          ctx.moveTo(pts[i].x, pts[i].y);
          ctx.lineTo(pts[j].x, pts[j].y);
          ctx.strokeStyle = `rgba(0,212,255,${(1-d/100)*.12})`;
          ctx.lineWidth = .5;
          ctx.stroke();
        }
      }
      pts[i].update(); pts[i].draw();
    }
    animId = requestAnimationFrame(draw);
  }
  draw();
})();

/* ── INTERSECTION OBSERVER → REVEAL SECTIONS ── */
const io = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) { e.target.classList.add('visible'); io.unobserve(e.target); }
  });
}, { threshold: 0.12 });
document.querySelectorAll('.section').forEach(s => io.observe(s));

/* ── SKILL BARS (animate when visible) ── */
const barObs = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.querySelectorAll('.bar-fill').forEach(b => {
        b.style.width = b.dataset.w + '%';
      });
      barObs.unobserve(e.target);
    }
  });
}, { threshold: 0.2 });
document.querySelectorAll('#sec-skills').forEach(s => barObs.observe(s));

/* ── LANGUAGE DONUT CHART ── */
(function() {
  const canvas = document.getElementById('lang-canvas');
  const ctx = canvas.getContext('2d');
  const dpr = window.devicePixelRatio || 1;
  canvas.width  = 200 * dpr; canvas.height = 200 * dpr;
  canvas.style.width  = '200px'; canvas.style.height = '200px';
  ctx.scale(dpr, dpr);

  const data = [
    { pct: .62, color: '#f0db4f', label: 'JS' },
    { pct: .31, color: '#7c3aed', label: 'Java' },
    { pct: .04, color: '#00d4ff', label: 'TS' },
    { pct: .03, color: '#10b981', label: 'Other' },
  ];

  let drawn = false;
  const donutObs = new IntersectionObserver(entries => {
    if (entries[0].isIntersecting && !drawn) { drawn = true; animate(); donutObs.disconnect(); }
  }, { threshold: 0.3 });
  donutObs.observe(canvas);

  function animate() {
    let progress = 0;
    function frame() {
      progress = Math.min(progress + 0.025, 1);
      draw(progress);
      if (progress < 1) requestAnimationFrame(frame);
    }
    frame();
  }

  function draw(prog) {
    ctx.clearRect(0, 0, 200, 200);
    const cx = 100, cy = 100, or = 80, ir = 54;
    let angle = -Math.PI / 2;
    data.forEach(d => {
      const sweep = d.pct * 2 * Math.PI * prog;
      ctx.beginPath();
      ctx.moveTo(cx + or * Math.cos(angle), cy + or * Math.sin(angle));
      ctx.arc(cx, cy, or, angle, angle + sweep);
      ctx.arc(cx, cy, ir, angle + sweep, angle, true);
      ctx.closePath();
      ctx.fillStyle = d.color;
      ctx.fill();
      angle += sweep;
    });
    // center text
    ctx.fillStyle = '#e2e8f0';
    ctx.font = 'bold 18px Syne, sans-serif';
    ctx.textAlign = 'center';
    ctx.textBaseline = 'middle';
    ctx.fillText('52', cx, cy - 8);
    ctx.font = '10px Space Grotesk, sans-serif';
    ctx.fillStyle = '#64748b';
    ctx.fillText('repos', cx, cy + 10);
  }
})();

/* ── ACTIVITY HEATMAP ── */
(function() {
  const canvas = document.getElementById('heat-canvas');
  const ctx = canvas.getContext('2d');
  const dpr = window.devicePixelRatio || 1;
  const W = canvas.offsetWidth || 860;
  canvas.width  = W * dpr; canvas.height = 80 * dpr;
  canvas.style.height = '80px';
  ctx.scale(dpr, dpr);

  const weeks = 52, days = 7;
  const cw = W / weeks - 2, ch = 10;
  const colors = ['#1a2235','#1e3a5f','#00d4ff44','#00d4ffaa','#00d4ff'];

  const heat = [];
  for (let w = 0; w < weeks; w++) {
    const row = [];
    const base = Math.random() < 0.3 ? 0 : 1;
    for (let d = 0; d < days; d++) {
      const v = base === 0 ? 0 : Math.floor(Math.random() * 5);
      row.push(v);
    }
    heat.push(row);
  }

  let drawn = false;
  const heatObs = new IntersectionObserver(entries => {
    if (entries[0].isIntersecting && !drawn) { drawn = true; drawHeat(); heatObs.disconnect(); }
  }, { threshold: 0.3 });
  heatObs.observe(canvas);

  function drawHeat() {
    let i = 0;
    function next() {
      if (i >= weeks) return;
      const w = i;
      for (let d = 0; d < days; d++) {
        const x = w * (cw + 2);
        const y = d * (ch + 2) + 4;
        ctx.beginPath();
        ctx.roundRect ? ctx.roundRect(x, y, cw, ch, 2) : ctx.rect(x, y, cw, ch);
        ctx.fillStyle = colors[heat[w][d]];
        ctx.fill();
      }
      i++;
      requestAnimationFrame(next);
    }
    next();
  }
})();

/* ── RADAR / BUBBLE CHART ── */
(function() {
  const canvas = document.getElementById('radar-canvas');
  const ctx = canvas.getContext('2d');
  const dpr = window.devicePixelRatio || 1;
  canvas.width  = 480 * dpr; canvas.height = 340 * dpr;
  ctx.scale(dpr, dpr);

  const cx = 240, cy = 170, r = 130;

  const domains = [
    { label: 'Mobile', angle: 0,           val: .90, color: '#00d4ff' },
    { label: 'Backend', angle: 60,          val: .88, color: '#7c3aed' },
    { label: 'Frontend', angle: 120,        val: .80, color: '#f0db4f' },
    { label: 'AI/ML', angle: 180,           val: .70, color: '#10b981' },
    { label: 'DevOps', angle: 240,          val: .65, color: '#f59e0b' },
    { label: 'System Design', angle: 300,   val: .78, color: '#ef4444' },
  ];

  function toRad(deg) { return deg * Math.PI / 180; }
  function ptAt(angle, radius) {
    return {
      x: cx + radius * Math.cos(toRad(angle - 90)),
      y: cy + radius * Math.sin(toRad(angle - 90)),
    };
  }

  let drawn = false;
  const radarObs = new IntersectionObserver(entries => {
    if (entries[0].isIntersecting && !drawn) { drawn = true; animate(); radarObs.disconnect(); }
  }, { threshold: 0.3 });
  radarObs.observe(canvas);

  function animate() {
    let progress = 0;
    function frame() {
      progress = Math.min(progress + 0.02, 1);
      draw(progress);
      if (progress < 1) requestAnimationFrame(frame);
    }
    frame();
  }

  function draw(prog) {
    ctx.clearRect(0, 0, 480, 340);

    // grid rings
    [.25,.5,.75,1].forEach(ring => {
      ctx.beginPath();
      domains.forEach((d,i) => {
        const p = ptAt(d.angle, r * ring);
        i === 0 ? ctx.moveTo(p.x, p.y) : ctx.lineTo(p.x, p.y);
      });
      ctx.closePath();
      ctx.strokeStyle = 'rgba(30,58,95,0.6)';
      ctx.lineWidth = 1;
      ctx.stroke();
    });

    // spokes
    domains.forEach(d => {
      const p = ptAt(d.angle, r);
      ctx.beginPath(); ctx.moveTo(cx, cy); ctx.lineTo(p.x, p.y);
      ctx.strokeStyle = 'rgba(30,58,95,0.4)'; ctx.lineWidth = 1; ctx.stroke();
    });

    // filled area
    ctx.beginPath();
    domains.forEach((d, i) => {
      const p = ptAt(d.angle, r * d.val * prog);
      i === 0 ? ctx.moveTo(p.x, p.y) : ctx.lineTo(p.x, p.y);
    });
    ctx.closePath();
    ctx.fillStyle = 'rgba(0,212,255,0.12)';
    ctx.fill();
    ctx.strokeStyle = '#00d4ff';
    ctx.lineWidth = 2;
    ctx.stroke();

    // dots + labels
    domains.forEach(d => {
      const p = ptAt(d.angle, r * d.val * prog);
      ctx.beginPath(); ctx.arc(p.x, p.y, 5, 0, Math.PI*2);
      ctx.fillStyle = d.color; ctx.fill();
      ctx.strokeStyle = '#0a0e1a'; ctx.lineWidth = 2; ctx.stroke();

      const lp = ptAt(d.angle, r * 1.18);
      ctx.fillStyle = '#e2e8f0';
      ctx.font = '600 12px Space Grotesk, sans-serif';
      ctx.textAlign = 'center'; ctx.textBaseline = 'middle';
      ctx.fillText(d.label, lp.x, lp.y);
    });

    // center dot
    ctx.beginPath(); ctx.arc(cx, cy, 4, 0, Math.PI*2);
    ctx.fillStyle = '#00d4ff'; ctx.fill();
  }
})();

/* ── COUNTER ANIMATION ── */
function animCount(el, target, duration) {
  let start = null;
  function step(ts) {
    if (!start) start = ts;
    const progress = Math.min((ts - start) / duration, 1);
    el.textContent = Math.floor(progress * target);
    if (progress < 1) requestAnimationFrame(step);
    else el.textContent = target;
  }
  requestAnimationFrame(step);
}
window.addEventListener('load', () => {
  setTimeout(() => {
    animCount(document.getElementById('cnt-repos'), 52, 1800);
    animCount(document.getElementById('cnt-stars'), 5, 1500);
    animCount(document.getElementById('cnt-follow'), 17, 1600);
  }, 400);
});
</script>
</body>
</html>
