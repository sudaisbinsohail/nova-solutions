<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nova Solution — Digital Innovation Studio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  :root {
    --bg: #060810;
    --surface: #0d1120;
    --card: #111827;
    --border: rgba(255,255,255,0.07);
    --accent: #00d4ff;
    --accent2: #7c3aed;
    --accent3: #f59e0b;
    --text: #f0f4ff;
    --muted: #8892a4;
    --font-display: 'Syne', sans-serif;
    --font-body: 'DM Sans', sans-serif;
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--font-body);
    font-weight: 300;
    overflow-x: hidden;
    cursor: none;
  }

  /* Custom Cursor */
  .cursor {
    position: fixed;
    width: 10px; height: 10px;
    background: var(--accent);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transition: transform 0.1s;
    mix-blend-mode: screen;
  }
  .cursor-ring {
    position: fixed;
    width: 36px; height: 36px;
    border: 1.5px solid rgba(0,212,255,0.4);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9998;
    transition: transform 0.18s ease, width 0.2s, height 0.2s;
    transform: translate(-50%,-50%);
  }
  .cursor-ring.hovered { width: 56px; height: 56px; border-color: var(--accent); }

  /* Noise overlay */
  body::before {
    content: '';
    position: fixed; inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.035'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 1000;
    opacity: 0.4;
  }

  /* NAV */
  nav {
    position: fixed; top: 0; left: 0; right: 0;
    z-index: 100;
    padding: 24px 60px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    backdrop-filter: blur(20px);
    background: rgba(6,8,16,0.7);
    border-bottom: 1px solid var(--border);
    transition: padding 0.3s;
  }
  .logo {
    font-family: var(--font-display);
    font-weight: 800;
    font-size: 22px;
    letter-spacing: -0.5px;
    color: var(--text);
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .logo-mark {
    width: 32px; height: 32px;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    font-size: 16px;
    font-weight: 800;
    color: white;
    flex-shrink: 0;
  }
  .nav-links {
    display: flex; gap: 36px;
    list-style: none;
  }
  .nav-links a {
    color: var(--muted);
    text-decoration: none;
    font-size: 14px;
    font-weight: 400;
    letter-spacing: 0.3px;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--text); }
  .nav-cta {
    background: transparent;
    border: 1px solid rgba(0,212,255,0.4);
    color: var(--accent);
    padding: 10px 24px;
    border-radius: 6px;
    font-family: var(--font-body);
    font-size: 14px;
    font-weight: 500;
    cursor: none;
    transition: background 0.2s, border-color 0.2s;
    letter-spacing: 0.3px;
  }
  .nav-cta:hover { background: rgba(0,212,255,0.08); border-color: var(--accent); }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    overflow: hidden;
    padding: 120px 60px 80px;
  }

  /* Background grid */
  .hero::after {
    content: '';
    position: absolute; inset: 0;
    background-image:
      linear-gradient(rgba(0,212,255,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,212,255,0.03) 1px, transparent 1px);
    background-size: 60px 60px;
    mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 40%, transparent 100%);
  }

  /* Glow orbs */
  .orb {
    position: absolute;
    border-radius: 50%;
    filter: blur(80px);
    pointer-events: none;
  }
  .orb-1 {
    width: 500px; height: 500px;
    background: radial-gradient(circle, rgba(0,212,255,0.12) 0%, transparent 70%);
    top: -100px; left: -100px;
    animation: drift1 12s ease-in-out infinite alternate;
  }
  .orb-2 {
    width: 400px; height: 400px;
    background: radial-gradient(circle, rgba(124,58,237,0.15) 0%, transparent 70%);
    bottom: -50px; right: -50px;
    animation: drift2 15s ease-in-out infinite alternate;
  }
  .orb-3 {
    width: 300px; height: 300px;
    background: radial-gradient(circle, rgba(245,158,11,0.08) 0%, transparent 70%);
    top: 50%; right: 20%;
    animation: drift1 18s ease-in-out infinite alternate-reverse;
  }
  @keyframes drift1 { from { transform: translate(0,0); } to { transform: translate(40px, 30px); } }
  @keyframes drift2 { from { transform: translate(0,0); } to { transform: translate(-30px, 20px); } }

  .hero-inner {
    position: relative;
    z-index: 2;
    max-width: 900px;
    text-align: center;
  }

  .hero-badge {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: rgba(0,212,255,0.06);
    border: 1px solid rgba(0,212,255,0.2);
    border-radius: 100px;
    padding: 8px 18px;
    font-size: 12px;
    font-weight: 500;
    color: var(--accent);
    letter-spacing: 0.8px;
    text-transform: uppercase;
    margin-bottom: 32px;
    animation: fadeUp 0.8s ease both;
  }
  .badge-dot {
    width: 6px; height: 6px;
    background: var(--accent);
    border-radius: 50%;
    animation: pulse 2s ease infinite;
  }
  @keyframes pulse { 0%,100%{opacity:1;} 50%{opacity:0.3;} }

  .hero h1 {
    font-family: var(--font-display);
    font-size: clamp(48px, 7vw, 88px);
    font-weight: 800;
    line-height: 1.0;
    letter-spacing: -2px;
    margin-bottom: 24px;
    animation: fadeUp 0.8s 0.15s ease both;
  }
  .hero h1 .line-1 { display: block; color: var(--text); }
  .hero h1 .line-2 {
    display: block;
    background: linear-gradient(90deg, var(--accent) 0%, var(--accent2) 60%, var(--accent3) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero-sub {
    font-size: 18px;
    font-weight: 300;
    color: var(--muted);
    max-width: 560px;
    margin: 0 auto 44px;
    line-height: 1.7;
    animation: fadeUp 0.8s 0.3s ease both;
  }

  .hero-ctas {
    display: flex;
    gap: 16px;
    justify-content: center;
    flex-wrap: wrap;
    animation: fadeUp 0.8s 0.45s ease both;
  }
  .btn-primary {
    background: linear-gradient(135deg, var(--accent) 0%, #0099bb 100%);
    color: #000;
    font-family: var(--font-body);
    font-weight: 600;
    font-size: 15px;
    padding: 14px 32px;
    border: none;
    border-radius: 8px;
    cursor: none;
    transition: opacity 0.2s, transform 0.2s;
    letter-spacing: 0.2px;
    text-decoration: none;
    display: inline-block;
  }
  .btn-primary:hover { opacity: 0.85; transform: translateY(-2px); }
  .btn-ghost {
    background: transparent;
    color: var(--text);
    font-family: var(--font-body);
    font-weight: 400;
    font-size: 15px;
    padding: 14px 32px;
    border: 1px solid var(--border);
    border-radius: 8px;
    cursor: none;
    transition: border-color 0.2s, background 0.2s, transform 0.2s;
    text-decoration: none;
    display: inline-block;
  }
  .btn-ghost:hover { border-color: rgba(255,255,255,0.2); background: rgba(255,255,255,0.04); transform: translateY(-2px); }

  .hero-stats {
    display: flex;
    gap: 48px;
    justify-content: center;
    margin-top: 64px;
    padding-top: 48px;
    border-top: 1px solid var(--border);
    animation: fadeUp 0.8s 0.6s ease both;
  }
  .stat { text-align: center; }
  .stat-num {
    font-family: var(--font-display);
    font-size: 36px;
    font-weight: 800;
    color: var(--text);
    letter-spacing: -1px;
    line-height: 1;
  }
  .stat-num span { color: var(--accent); }
  .stat-label { font-size: 13px; color: var(--muted); margin-top: 6px; letter-spacing: 0.3px; }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to { opacity: 1; transform: translateY(0); }
  }

  /* SECTIONS */
  section { padding: 100px 60px; }
  .section-label {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 16px;
  }
  .section-title {
    font-family: var(--font-display);
    font-size: clamp(32px, 4vw, 52px);
    font-weight: 800;
    letter-spacing: -1.5px;
    line-height: 1.1;
    margin-bottom: 20px;
  }
  .section-desc {
    font-size: 17px;
    color: var(--muted);
    font-weight: 300;
    line-height: 1.7;
    max-width: 500px;
  }

  /* MARQUEE */
  .marquee-section {
    padding: 28px 0;
    background: var(--surface);
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    overflow: hidden;
  }
  .marquee-track {
    display: flex;
    gap: 64px;
    animation: marquee 20s linear infinite;
    width: max-content;
  }
  .marquee-item {
    font-family: var(--font-display);
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: var(--muted);
    white-space: nowrap;
    display: flex;
    align-items: center;
    gap: 16px;
  }
  .marquee-item::after { content: '◆'; color: var(--accent); font-size: 8px; }
  @keyframes marquee { from { transform: translateX(0); } to { transform: translateX(-50%); } }

  /* SERVICES */
  .services { background: var(--bg); }
  .services-header {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
    align-items: end;
    margin-bottom: 64px;
  }
  .services-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    border-radius: 16px;
    overflow: hidden;
  }
  .service-card {
    background: var(--card);
    padding: 36px 32px;
    transition: background 0.3s;
    position: relative;
    overflow: hidden;
  }
  .service-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.4s ease;
  }
  .service-card:hover::before { transform: scaleX(1); }
  .service-card:hover { background: #161d2e; }
  .service-icon {
    width: 48px; height: 48px;
    border-radius: 12px;
    display: flex; align-items: center; justify-content: center;
    font-size: 22px;
    margin-bottom: 20px;
    transition: transform 0.3s;
  }
  .service-card:hover .service-icon { transform: scale(1.1) rotate(-4deg); }
  .service-card h3 {
    font-family: var(--font-display);
    font-size: 18px;
    font-weight: 700;
    margin-bottom: 10px;
    letter-spacing: -0.3px;
  }
  .service-card p {
    font-size: 14px;
    color: var(--muted);
    line-height: 1.65;
    font-weight: 300;
  }
  .service-tag {
    display: inline-block;
    margin-top: 16px;
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 1px;
    text-transform: uppercase;
    padding: 4px 10px;
    border-radius: 4px;
    background: rgba(0,212,255,0.08);
    color: var(--accent);
  }

  /* PROCESS */
  .process { background: var(--surface); }
  .process-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 32px;
    margin-top: 64px;
  }
  .process-step {
    position: relative;
  }
  .process-step:not(:last-child)::after {
    content: '';
    position: absolute;
    top: 20px;
    left: calc(100% + 16px);
    width: calc(100% - 56px);
    height: 1px;
    background: linear-gradient(90deg, var(--accent), transparent);
    opacity: 0.3;
  }
  .step-num {
    font-family: var(--font-display);
    font-size: 11px;
    font-weight: 800;
    letter-spacing: 2px;
    color: var(--accent);
    margin-bottom: 12px;
  }
  .step-icon {
    width: 40px; height: 40px;
    background: rgba(0,212,255,0.08);
    border: 1px solid rgba(0,212,255,0.15);
    border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
    margin-bottom: 16px;
  }
  .process-step h4 {
    font-family: var(--font-display);
    font-size: 17px;
    font-weight: 700;
    margin-bottom: 8px;
  }
  .process-step p {
    font-size: 14px;
    color: var(--muted);
    line-height: 1.6;
    font-weight: 300;
  }

  /* TECH STACK */
  .tech { background: var(--bg); }
  .tech-inner {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 80px;
    align-items: center;
  }
  .tech-pills {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    margin-top: 48px;
  }
  .tech-pill {
    display: flex;
    align-items: center;
    gap: 10px;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 100px;
    padding: 10px 18px;
    font-size: 13px;
    font-weight: 500;
    color: var(--text);
    transition: border-color 0.2s, background 0.2s, transform 0.2s;
    cursor: default;
  }
  .tech-pill:hover {
    border-color: rgba(0,212,255,0.3);
    background: rgba(0,212,255,0.05);
    transform: translateY(-2px);
  }
  .tech-pill-icon { font-size: 16px; }

  /* WHY US */
  .why { background: var(--surface); }
  .why-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 28px;
    margin-top: 64px;
  }
  .why-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 16px;
    padding: 32px;
    transition: border-color 0.3s, transform 0.3s;
  }
  .why-card:hover { border-color: rgba(0,212,255,0.2); transform: translateY(-4px); }
  .why-card .icon { font-size: 28px; margin-bottom: 16px; }
  .why-card h4 {
    font-family: var(--font-display);
    font-size: 17px;
    font-weight: 700;
    margin-bottom: 10px;
  }
  .why-card p { font-size: 14px; color: var(--muted); line-height: 1.65; font-weight: 300; }

  /* CTA SECTION */
  .cta-section {
    background: var(--bg);
    padding: 100px 60px;
  }
  .cta-box {
    background: linear-gradient(135deg, rgba(0,212,255,0.06) 0%, rgba(124,58,237,0.06) 100%);
    border: 1px solid rgba(0,212,255,0.15);
    border-radius: 24px;
    padding: 80px 60px;
    text-align: center;
    max-width: 800px;
    margin: 0 auto;
    position: relative;
    overflow: hidden;
  }
  .cta-box::before {
    content: '';
    position: absolute;
    top: -1px; left: 20%; right: 20%;
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--accent), var(--accent2), transparent);
  }
  .cta-box h2 {
    font-family: var(--font-display);
    font-size: clamp(32px, 4vw, 52px);
    font-weight: 800;
    letter-spacing: -1.5px;
    margin-bottom: 20px;
  }
  .cta-box p {
    font-size: 17px;
    color: var(--muted);
    font-weight: 300;
    margin-bottom: 40px;
    line-height: 1.7;
  }
  .cta-buttons { display: flex; gap: 14px; justify-content: center; flex-wrap: wrap; }

  /* FOOTER */
  footer {
    background: var(--surface);
    border-top: 1px solid var(--border);
    padding: 60px;
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 40px;
  }
  .footer-brand p {
    font-size: 14px;
    color: var(--muted);
    font-weight: 300;
    margin-top: 14px;
    line-height: 1.7;
    max-width: 280px;
  }
  .footer-col h5 {
    font-family: var(--font-display);
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 0.5px;
    margin-bottom: 20px;
    color: var(--text);
  }
  .footer-col ul { list-style: none; }
  .footer-col ul li { margin-bottom: 10px; }
  .footer-col ul li a {
    color: var(--muted);
    text-decoration: none;
    font-size: 14px;
    font-weight: 300;
    transition: color 0.2s;
  }
  .footer-col ul li a:hover { color: var(--accent); }
  .footer-bottom {
    background: var(--surface);
    border-top: 1px solid var(--border);
    padding: 20px 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .footer-bottom p { font-size: 13px; color: var(--muted); font-weight: 300; }
  .social-links { display: flex; gap: 16px; }
  .social-links a {
    width: 34px; height: 34px;
    border: 1px solid var(--border);
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    color: var(--muted);
    font-size: 14px;
    text-decoration: none;
    transition: border-color 0.2s, color 0.2s;
  }
  .social-links a:hover { border-color: var(--accent); color: var(--accent); }

  /* Scroll reveal */
  .reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.visible { opacity: 1; transform: translateY(0); }

  /* Responsive */
  @media (max-width: 900px) {
    nav { padding: 20px 24px; }
    .nav-links { display: none; }
    section { padding: 70px 24px; }
    .hero { padding: 100px 24px 60px; }
    .services-header, .tech-inner { grid-template-columns: 1fr; }
    .services-grid { grid-template-columns: 1fr; }
    .process-grid { grid-template-columns: 1fr 1fr; }
    .why-grid { grid-template-columns: 1fr; }
    footer { grid-template-columns: 1fr 1fr; padding: 40px 24px; }
    .footer-bottom { padding: 16px 24px; flex-direction: column; gap: 12px; }
    .hero-stats { gap: 28px; }
    .cta-box { padding: 48px 28px; }
    .cta-section { padding: 70px 24px; }
    body { cursor: auto; }
    .cursor, .cursor-ring { display: none; }
  }
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- NAV -->
<nav>
  <a href="#" class="logo">
    <div class="logo-mark">N</div>
    Nova Solution
  </a>
  <ul class="nav-links">
    <li><a href="#services">Services</a></li>
    <li><a href="#process">Process</a></li>
    <li><a href="#tech">Tech Stack</a></li>
    <li><a href="#why">Why Us</a></li>
  </ul>
  <button class="nav-cta" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Get in Touch</button>
</nav>

<!-- HERO -->
<section class="hero" id="home">
  <div class="orb orb-1"></div>
  <div class="orb orb-2"></div>
  <div class="orb orb-3"></div>
  <div class="hero-inner">
    <div class="hero-badge">
      <span class="badge-dot"></span>
      Digital Innovation Studio
    </div>
    <h1>
      <span class="line-1">We Build Digital</span>
      <span class="line-2">Experiences That Scale</span>
    </h1>
    <p class="hero-sub">From mobile apps to AI-powered platforms — Nova Solution crafts high-performance digital products that grow your business.</p>
    <div class="hero-ctas">
      <a href="#services" class="btn-primary">Explore Our Work</a>
      <a href="#contact" class="btn-ghost">Start a Project →</a>
    </div>
    <div class="hero-stats">
      <div class="stat">
        <div class="stat-num">50<span>+</span></div>
        <div class="stat-label">Projects Delivered</div>
      </div>
      <div class="stat">
        <div class="stat-num">98<span>%</span></div>
        <div class="stat-label">Client Satisfaction</div>
      </div>
      <div class="stat">
        <div class="stat-num">6<span>+</span></div>
        <div class="stat-label">Core Specialisms</div>
      </div>
    </div>
  </div>
</section>

<!-- MARQUEE -->
<div class="marquee-section">
  <div class="marquee-track">
    <span class="marquee-item">Mobile Development</span>
    <span class="marquee-item">Web Development</span>
    <span class="marquee-item">Bubble.io</span>
    <span class="marquee-item">GoHighLevel</span>
    <span class="marquee-item">AI Integration</span>
    <span class="marquee-item">Software Consulting</span>
    <span class="marquee-item">Mobile Development</span>
    <span class="marquee-item">Web Development</span>
    <span class="marquee-item">Bubble.io</span>
    <span class="marquee-item">GoHighLevel</span>
    <span class="marquee-item">AI Integration</span>
    <span class="marquee-item">Software Consulting</span>
  </div>
</div>

<!-- SERVICES -->
<section class="services" id="services">
  <div class="services-header reveal">
    <div>
      <div class="section-label">What We Do</div>
      <h2 class="section-title">End-to-end digital solutions</h2>
    </div>
    <p class="section-desc">We combine deep technical expertise with strategic thinking to deliver software that makes a measurable impact.</p>
  </div>
  <div class="services-grid reveal">
    <div class="service-card">
      <div class="service-icon" style="background:rgba(0,212,255,0.1);">📱</div>
      <h3>Mobile Development</h3>
      <p>Native & cross-platform apps for iOS and Android. Smooth UX, robust architecture, and App Store-ready delivery.</p>
      <span class="service-tag">iOS · Android · React Native</span>
    </div>
    <div class="service-card">
      <div class="service-icon" style="background:rgba(124,58,237,0.1);">🌐</div>
      <h3>Web Development</h3>
      <p>Fast, scalable web platforms built with modern frameworks. From landing pages to complex SaaS dashboards.</p>
      <span class="service-tag" style="background:rgba(124,58,237,0.1);color:#a78bfa;">React · Next.js · Node</span>
    </div>
    <div class="service-card">
      <div class="service-icon" style="background:rgba(245,158,11,0.1);">⚡</div>
      <h3>Bubble.io Development</h3>
      <p>Expert no-code MVPs and full products on Bubble.io. Launch faster without sacrificing quality or scalability.</p>
      <span class="service-tag" style="background:rgba(245,158,11,0.1);color:#fbbf24;">No-Code · MVP · SaaS</span>
    </div>
    <div class="service-card">
      <div class="service-icon" style="background:rgba(16,185,129,0.1);">📈</div>
      <h3>GoHighLevel</h3>
      <p>Custom GHL setups, automation funnels, CRM configurations, and white-label agency deployments.</p>
      <span class="service-tag" style="background:rgba(16,185,129,0.1);color:#34d399;">CRM · Funnels · Automation</span>
    </div>
    <div class="service-card">
      <div class="service-icon" style="background:rgba(239,68,68,0.1);">🤖</div>
      <h3>AI Integration</h3>
      <p>Embed GPT-4, Claude, and custom ML models into your products. Chatbots, data pipelines, and intelligent features.</p>
      <span class="service-tag" style="background:rgba(239,68,68,0.1);color:#f87171;">GPT · Claude · Automation</span>
    </div>
    <div class="service-card">
      <div class="service-icon" style="background:rgba(168,85,247,0.1);">🔧</div>
      <h3>Software Consulting</h3>
      <p>Architecture reviews, tech stack strategy, team augmentation, and ongoing technical advisory for growing companies.</p>
      <span class="service-tag" style="background:rgba(168,85,247,0.1);color:#c084fc;">Strategy · Architecture</span>
    </div>
  </div>
</section>

<!-- PROCESS -->
<section class="process" id="process">
  <div class="reveal" style="text-align:center; max-width:600px; margin:0 auto;">
    <div class="section-label">How We Work</div>
    <h2 class="section-title">Our process, refined</h2>
    <p class="section-desc" style="margin:0 auto;">A clear, structured approach that keeps projects on time, on budget, and on brief.</p>
  </div>
  <div class="process-grid reveal">
    <div class="process-step">
      <div class="step-num">01</div>
      <div class="step-icon">💡</div>
      <h4>Discovery</h4>
      <p>Deep-dive into your goals, users, and constraints. We define scope, KPIs, and technical requirements.</p>
    </div>
    <div class="process-step">
      <div class="step-num">02</div>
      <div class="step-icon">🎨</div>
      <h4>Design & Plan</h4>
      <p>Wireframes, UI design, system architecture. You approve every decision before we write a line of code.</p>
    </div>
    <div class="process-step">
      <div class="step-num">03</div>
      <div class="step-icon">⚙️</div>
      <h4>Build & Iterate</h4>
      <p>Agile sprints with weekly demos. Continuous feedback loops ensure the product evolves with your vision.</p>
    </div>
    <div class="process-step">
      <div class="step-num">04</div>
      <div class="step-icon">🚀</div>
      <h4>Launch & Grow</h4>
      <p>QA-tested, deployed, and supported post-launch. We stay on to monitor, optimize, and scale.</p>
    </div>
  </div>
</section>

<!-- TECH STACK -->
<section class="tech" id="tech">
  <div class="tech-inner">
    <div class="reveal">
      <div class="section-label">Tech Stack</div>
      <h2 class="section-title">Built with the best tools</h2>
      <p class="section-desc">We choose the right technology for your specific needs — not what's trendy.</p>
    </div>
    <div class="tech-pills reveal">
      <div class="tech-pill"><span class="tech-pill-icon">⚛️</span> React / Next.js</div>
      <div class="tech-pill"><span class="tech-pill-icon">📱</span> React Native</div>
      <div class="tech-pill"><span class="tech-pill-icon">🟢</span> Node.js</div>
      <div class="tech-pill"><span class="tech-pill-icon">🫧</span> Bubble.io</div>
      <div class="tech-pill"><span class="tech-pill-icon">📊</span> GoHighLevel</div>
      <div class="tech-pill"><span class="tech-pill-icon">🤖</span> OpenAI / GPT-4</div>
      <div class="tech-pill"><span class="tech-pill-icon">🧠</span> Claude AI</div>
      <div class="tech-pill"><span class="tech-pill-icon">🔥</span> Firebase</div>
      <div class="tech-pill"><span class="tech-pill-icon">🐘</span> PostgreSQL</div>
      <div class="tech-pill"><span class="tech-pill-icon">☁️</span> AWS / Vercel</div>
      <div class="tech-pill"><span class="tech-pill-icon">🐳</span> Docker</div>
      <div class="tech-pill"><span class="tech-pill-icon">🔗</span> REST & GraphQL</div>
      <div class="tech-pill"><span class="tech-pill-icon">💜</span> TypeScript</div>
      <div class="tech-pill"><span class="tech-pill-icon">🎭</span> Tailwind CSS</div>
    </div>
  </div>
</section>

<!-- WHY US -->
<section class="why" id="why">
  <div class="reveal" style="text-align:center; max-width:600px; margin:0 auto 0;">
    <div class="section-label">Why Nova</div>
    <h2 class="section-title">Partners, not just vendors</h2>
    <p class="section-desc" style="margin:0 auto;">We invest in your success like it's our own.</p>
  </div>
  <div class="why-grid reveal">
    <div class="why-card">
      <div class="icon">⚡</div>
      <h4>Fast Turnaround</h4>
      <p>Lean team, zero bureaucracy. We move quickly without cutting corners on quality or testing.</p>
    </div>
    <div class="why-card">
      <div class="icon">🎯</div>
      <h4>Outcome-Focused</h4>
      <p>We measure success by your results — signups, revenue, retention — not just deliverables shipped.</p>
    </div>
    <div class="why-card">
      <div class="icon">🔍</div>
      <h4>Full Transparency</h4>
      <p>Weekly progress updates, open codebases, and honest conversations. No surprises, ever.</p>
    </div>
    <div class="why-card">
      <div class="icon">🏗️</div>
      <h4>Scalable Architecture</h4>
      <p>We build for where you're going, not just where you are today. Future-proof from day one.</p>
    </div>
    <div class="why-card">
      <div class="icon">🤝</div>
      <h4>Long-term Partnership</h4>
      <p>Many of our clients have worked with us for years. We become an extension of your team.</p>
    </div>
    <div class="why-card">
      <div class="icon">🌍</div>
      <h4>Global Expertise</h4>
      <p>Remote-first team with experience delivering for clients across the US, Europe, and MENA.</p>
    </div>
  </div>
</section>

<!-- CTA -->
<div class="cta-section" id="contact">
  <div class="cta-box reveal">
    <h2>Ready to build something great?</h2>
    <p>Tell us about your project and we'll get back to you within 24 hours with a tailored proposal.</p>
    <div class="cta-buttons">
      <a href="mailto:hello@novasolution.io" class="btn-primary">hello@novasolution.io</a>
      <a href="#" class="btn-ghost">Schedule a Call →</a>
    </div>
  </div>
</div>

<!-- FOOTER -->
<footer>
  <div class="footer-brand">
    <a href="#" class="logo" style="text-decoration:none;">
      <div class="logo-mark">N</div>
      Nova Solution
    </a>
    <p>A digital product studio specializing in mobile, web, no-code, and AI solutions for startups and scale-ups.</p>
  </div>
  <div class="footer-col">
    <h5>Services</h5>
    <ul>
      <li><a href="#">Mobile Development</a></li>
      <li><a href="#">Web Development</a></li>
      <li><a href="#">Bubble.io</a></li>
      <li><a href="#">GoHighLevel</a></li>
      <li><a href="#">AI Integration</a></li>
    </ul>
  </div>
  <div class="footer-col">
    <h5>Company</h5>
    <ul>
      <li><a href="#">About</a></li>
      <li><a href="#">Process</a></li>
      <li><a href="#">Case Studies</a></li>
      <li><a href="#">Blog</a></li>
    </ul>
  </div>
  <div class="footer-col">
    <h5>Contact</h5>
    <ul>
      <li><a href="#">hello@novasolution.io</a></li>
      <li><a href="#">Schedule a Call</a></li>
      <li><a href="#">LinkedIn</a></li>
      <li><a href="#">Twitter / X</a></li>
    </ul>
  </div>
</footer>
<div class="footer-bottom">
  <p>© 2025 Nova Solution. All rights reserved.</p>
  <div class="social-links">
    <a href="#" title="LinkedIn">in</a>
    <a href="#" title="Twitter">𝕏</a>
    <a href="#" title="GitHub">⌥</a>
  </div>
</div>

<script>
  // Custom cursor
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;
  document.addEventListener('mousemove', e => {
    mx = e.clientX; my = e.clientY;
    cursor.style.left = (mx - 5) + 'px';
    cursor.style.top = (my - 5) + 'px';
  });
  function animateRing() {
    rx += (mx - rx) * 0.14;
    ry += (my - ry) * 0.14;
    ring.style.left = rx + 'px';
    ring.style.top = ry + 'px';
    requestAnimationFrame(animateRing);
  }
  animateRing();
  document.querySelectorAll('a, button, .service-card, .why-card, .tech-pill').forEach(el => {
    el.addEventListener('mouseenter', () => ring.classList.add('hovered'));
    el.addEventListener('mouseleave', () => ring.classList.remove('hovered'));
  });

  // Scroll reveal
  const observer = new IntersectionObserver(entries => {
    entries.forEach((e, i) => {
      if (e.isIntersecting) {
        e.target.style.transitionDelay = (i * 0.05) + 's';
        e.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });
  document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
</script>
</body>
</html>
