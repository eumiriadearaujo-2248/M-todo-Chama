<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Método CHAMA — Reorganização emocional para sustentar prosperidade, reconstruir identidade e retomar a narrativa da própria vida. Eumiria de Araújo.">
<meta name="keywords" content="reorganização emocional, prosperidade emocional, autossabotagem, alta sensibilidade, HSP, AHSD, trauma emocional, reconstrução de identidade, clareza emocional">
<title>Método CHAMA 🔥 | Eumiria de Araújo</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400;1,500&family=Cinzel:wght@400;500;600&family=Jost:wght@200;300;400;500&display=swap" rel="stylesheet">

<style>
  :root {
    --obsidian: #0a0a0a;
    --charcoal: #111111;
    --graphite: #1a1a1a;
    --ember: #242424;
    --gold: #c9a84c;
    --gold-light: #e2c077;
    --gold-dim: #8a6d2e;
    --gold-muted: rgba(201,168,76,0.12);
    --cream: #f0ebe0;
    --off-white: #e8e2d4;
    --ghost: rgba(240,235,224,0.06);
    --ash: #888070;
    --font-serif: 'Cormorant Garamond', Georgia, serif;
    --font-display: 'Cinzel', serif;
    --font-body: 'Jost', sans-serif;
  }

  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; font-size: 16px; }

  body {
    background: var(--obsidian);
    color: var(--cream);
    font-family: var(--font-body);
    font-weight: 300;
    overflow-x: hidden;
    cursor: default;
  }

  /* ── NOISE TEXTURE OVERLAY ── */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 9999;
    opacity: 0.4;
  }

  /* ── NAVIGATION ── */
  nav {
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 100;
    padding: 1.5rem 4rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: linear-gradient(to bottom, rgba(10,10,10,0.95) 0%, transparent 100%);
    backdrop-filter: blur(2px);
  }

  .nav-logo {
    font-family: var(--font-display);
    font-size: 1.1rem;
    letter-spacing: 0.3em;
    color: var(--gold);
    text-decoration: none;
    text-transform: uppercase;
  }

  .nav-links {
    display: flex;
    gap: 2.5rem;
    list-style: none;
  }

  .nav-links a {
    font-family: var(--font-body);
    font-size: 0.7rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--ash);
    text-decoration: none;
    transition: color 0.3s ease;
  }

  .nav-links a:hover { color: var(--gold-light); }

  /* ── HERO ── */
  .hero {
    min-height: 100vh;
    position: relative;
    display: flex;
    align-items: center;
    overflow: hidden;
  }

  .hero-bg {
    position: absolute;
    inset: 0;
    background: 
      radial-gradient(ellipse 60% 80% at 70% 50%, rgba(180,100,20,0.18) 0%, transparent 70%),
      radial-gradient(ellipse 40% 60% at 30% 60%, rgba(201,168,76,0.06) 0%, transparent 60%),
      radial-gradient(ellipse 80% 80% at 50% 100%, rgba(100,50,10,0.25) 0%, transparent 60%),
      var(--obsidian);
  }

  .hero-flame {
    position: absolute;
    right: 5%;
    top: 50%;
    transform: translateY(-50%);
    width: 45%;
    max-width: 600px;
    opacity: 0.7;
    animation: flicker 6s ease-in-out infinite;
  }

  @keyframes flicker {
    0%, 100% { opacity: 0.65; transform: translateY(-50%) scale(1); }
    33% { opacity: 0.8; transform: translateY(-51%) scale(1.01); }
    66% { opacity: 0.6; transform: translateY(-49%) scale(0.99); }
  }

  .hero-content {
    position: relative;
    z-index: 2;
    padding: 10rem 4rem 6rem;
    max-width: 680px;
  }

  .hero-eyebrow {
    font-family: var(--font-body);
    font-size: 0.65rem;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 2rem;
    opacity: 0;
    animation: fadeUp 1s ease 0.3s forwards;
  }

  .hero-title {
    font-family: var(--font-display);
    font-size: clamp(3.5rem, 8vw, 7rem);
    font-weight: 500;
    line-height: 0.95;
    color: var(--cream);
    letter-spacing: 0.05em;
    margin-bottom: 0.3rem;
    opacity: 0;
    animation: fadeUp 1s ease 0.5s forwards;
  }

  .hero-title span {
    color: var(--gold);
    display: block;
  }

  .hero-subtitle {
    font-family: var(--font-serif);
    font-size: clamp(1rem, 2vw, 1.3rem);
    font-weight: 300;
    font-style: italic;
    color: var(--ash);
    line-height: 1.6;
    margin-bottom: 3rem;
    max-width: 500px;
    opacity: 0;
    animation: fadeUp 1s ease 0.7s forwards;
  }

  .hero-body {
    font-family: var(--font-serif);
    font-size: 1.15rem;
    line-height: 1.9;
    color: rgba(240,235,224,0.75);
    margin-bottom: 1rem;
    opacity: 0;
    animation: fadeUp 1s ease 0.9s forwards;
  }

  .hero-body strong {
    color: var(--gold-light);
    font-weight: 400;
  }

  .hero-body .line {
    display: block;
    margin-bottom: 0.2rem;
  }

  .hero-body .spacer { display: block; margin-bottom: 0.8rem; }

  .hero-ctas {
    display: flex;
    gap: 1.5rem;
    flex-wrap: wrap;
    margin-top: 3rem;
    opacity: 0;
    animation: fadeUp 1s ease 1.1s forwards;
  }

  /* ── BUTTONS ── */
  .btn-primary {
    display: inline-block;
    padding: 1.1rem 2.8rem;
    background: var(--gold);
    color: var(--obsidian);
    font-family: var(--font-body);
    font-size: 0.7rem;
    font-weight: 500;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    text-decoration: none;
    border: none;
    cursor: pointer;
    transition: all 0.35s ease;
    position: relative;
    overflow: hidden;
  }

  .btn-primary::before {
    content: '';
    position: absolute;
    inset: 0;
    background: var(--gold-light);
    transform: translateX(-101%);
    transition: transform 0.35s ease;
  }

  .btn-primary:hover::before { transform: translateX(0); }
  .btn-primary span { position: relative; z-index: 1; }

  .btn-secondary {
    display: inline-block;
    padding: 1.1rem 2.8rem;
    background: transparent;
    color: var(--cream);
    font-family: var(--font-body);
    font-size: 0.7rem;
    font-weight: 400;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    text-decoration: none;
    border: 1px solid rgba(240,235,224,0.25);
    cursor: pointer;
    transition: all 0.35s ease;
  }

  .btn-secondary:hover {
    border-color: var(--gold);
    color: var(--gold);
  }

  /* ── DIVIDERS ── */
  .gold-line {
    width: 60px;
    height: 1px;
    background: var(--gold);
    margin: 0 auto 3rem;
  }

  .gold-line-left {
    width: 60px;
    height: 1px;
    background: var(--gold);
    margin: 0 0 3rem;
  }

  /* ── SECTIONS ── */
  section {
    position: relative;
    overflow: hidden;
  }

  .section-inner {
    max-width: 1200px;
    margin: 0 auto;
    padding: 8rem 4rem;
  }

  .section-eyebrow {
    font-family: var(--font-body);
    font-size: 0.6rem;
    letter-spacing: 0.5em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1.5rem;
  }

  .section-title {
    font-family: var(--font-serif);
    font-size: clamp(2rem, 5vw, 3.5rem);
    font-weight: 300;
    line-height: 1.2;
    color: var(--cream);
    margin-bottom: 2rem;
  }

  .section-title em {
    font-style: italic;
    color: var(--gold-light);
  }

  /* ── QUOTE BAR ── */
  .quote-bar {
    background: var(--graphite);
    border-left: 2px solid var(--gold);
    padding: 5rem 4rem;
    text-align: center;
  }

  .quote-bar blockquote {
    font-family: var(--font-serif);
    font-size: clamp(1.5rem, 4vw, 2.8rem);
    font-weight: 300;
    font-style: italic;
    color: var(--cream);
    line-height: 1.5;
    max-width: 800px;
    margin: 0 auto;
  }

  .quote-bar blockquote span {
    display: block;
    font-size: 0.65rem;
    font-family: var(--font-body);
    font-style: normal;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--gold);
    margin-top: 2rem;
  }

  /* ── ABOUT SECTION ── */
  .about-section {
    background: var(--charcoal);
  }

  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 6rem;
    align-items: center;
  }

  .about-image-area {
    position: relative;
  }

  .about-image-frame {
    position: relative;
    aspect-ratio: 3/4;
    background: var(--graphite);
    overflow: hidden;
  }

  .about-image-frame::before {
    content: '';
    position: absolute;
    inset: 0;
    background: 
      radial-gradient(ellipse at 40% 30%, rgba(201,168,76,0.15) 0%, transparent 60%),
      radial-gradient(ellipse at 60% 80%, rgba(180,80,10,0.2) 0%, transparent 50%);
  }

  .about-image-placeholder {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 6rem;
    opacity: 0.3;
  }

  .about-frame-deco {
    position: absolute;
    top: -20px;
    left: -20px;
    right: 20px;
    bottom: 20px;
    border: 1px solid rgba(201,168,76,0.3);
    pointer-events: none;
  }

  .about-text .name {
    font-family: var(--font-display);
    font-size: 0.85rem;
    letter-spacing: 0.3em;
    color: var(--gold);
    text-transform: uppercase;
    margin-bottom: 2rem;
  }

  .about-text p {
    font-family: var(--font-serif);
    font-size: 1.1rem;
    line-height: 1.9;
    color: rgba(240,235,224,0.8);
    margin-bottom: 1.5rem;
  }

  .about-text p.highlight {
    color: var(--cream);
    font-size: 1.2rem;
    font-style: italic;
  }

  .expertise-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.8rem;
    margin-top: 2.5rem;
  }

  .tag {
    padding: 0.45rem 1.2rem;
    border: 1px solid rgba(201,168,76,0.35);
    font-family: var(--font-body);
    font-size: 0.62rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold-light);
    transition: all 0.3s ease;
  }

  .tag:hover {
    background: var(--gold-muted);
    border-color: var(--gold);
  }

  /* ── METHOD SECTION ── */
  .method-section {
    background: var(--obsidian);
  }

  .chama-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 0;
    margin-top: 5rem;
    border: 1px solid rgba(201,168,76,0.15);
  }

  .chama-item {
    padding: 3rem 2rem;
    border-right: 1px solid rgba(201,168,76,0.15);
    transition: background 0.4s ease;
    position: relative;
    overflow: hidden;
  }

  .chama-item:last-child { border-right: none; }

  .chama-item::before {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    height: 2px;
    background: var(--gold);
    transform: scaleX(0);
    transition: transform 0.4s ease;
  }

  .chama-item:hover { background: var(--ghost); }
  .chama-item:hover::before { transform: scaleX(1); }

  .chama-letter {
    font-family: var(--font-display);
    font-size: 4rem;
    font-weight: 600;
    color: var(--gold);
    line-height: 1;
    margin-bottom: 1rem;
    opacity: 0.7;
  }

  .chama-word {
    font-family: var(--font-serif);
    font-size: 1rem;
    font-style: italic;
    color: var(--cream);
    margin-bottom: 1rem;
  }

  .chama-desc {
    font-family: var(--font-body);
    font-size: 0.75rem;
    line-height: 1.7;
    color: var(--ash);
    font-weight: 300;
  }

  /* ── BEFORE/AFTER ── */
  .transform-section {
    background: var(--graphite);
  }

  .ba-grid {
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    gap: 4rem;
    align-items: start;
    margin-top: 4rem;
  }

  .ba-divider {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 2rem;
    gap: 0.5rem;
  }

  .ba-arrow {
    font-size: 2rem;
    color: var(--gold);
  }

  .ba-divider-line {
    width: 1px;
    height: 100%;
    min-height: 300px;
    background: linear-gradient(to bottom, transparent, var(--gold), transparent);
  }

  .ba-side {
    padding: 3rem;
    border: 1px solid rgba(201,168,76,0.12);
  }

  .ba-side.before { border-color: rgba(140,140,140,0.2); }
  .ba-side.after { border-color: rgba(201,168,76,0.3); background: rgba(201,168,76,0.03); }

  .ba-label {
    font-family: var(--font-display);
    font-size: 0.65rem;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    margin-bottom: 2rem;
  }

  .ba-side.before .ba-label { color: var(--ash); }
  .ba-side.after .ba-label { color: var(--gold); }

  .ba-list {
    list-style: none;
  }

  .ba-list li {
    font-family: var(--font-serif);
    font-size: 1.05rem;
    padding: 0.8rem 0;
    border-bottom: 1px solid rgba(255,255,255,0.05);
    display: flex;
    align-items: center;
    gap: 1rem;
  }

  .ba-list li::before {
    content: '—';
    color: var(--ash);
    font-size: 0.8rem;
  }

  .ba-side.before .ba-list li { color: rgba(240,235,224,0.5); }
  .ba-side.after .ba-list li { color: var(--cream); }
  .ba-side.after .ba-list li::before { content: '✦'; color: var(--gold); font-size: 0.6rem; }

  /* ── PRODUCTS ── */
  .products-section {
    background: var(--obsidian);
  }

  .products-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2px;
    margin-top: 5rem;
  }

  .product-card {
    background: var(--charcoal);
    padding: 3.5rem 3rem;
    position: relative;
    overflow: hidden;
    transition: background 0.4s ease;
  }

  .product-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 1px;
    background: linear-gradient(to right, transparent, var(--gold), transparent);
    opacity: 0;
    transition: opacity 0.4s ease;
  }

  .product-card:hover { background: var(--graphite); }
  .product-card:hover::before { opacity: 1; }

  .product-card.featured {
    background: var(--graphite);
    grid-column: span 3;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
  }

  .product-card.featured::before { opacity: 0.5; }

  .product-number {
    font-family: var(--font-display);
    font-size: 4rem;
    color: rgba(201,168,76,0.12);
    line-height: 1;
    margin-bottom: 1.5rem;
  }

  .product-tag {
    font-family: var(--font-body);
    font-size: 0.6rem;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1rem;
  }

  .product-name {
    font-family: var(--font-serif);
    font-size: 1.6rem;
    font-weight: 400;
    color: var(--cream);
    margin-bottom: 1.5rem;
    line-height: 1.3;
  }

  .product-desc {
    font-family: var(--font-serif);
    font-size: 1rem;
    font-style: italic;
    line-height: 1.8;
    color: rgba(240,235,224,0.6);
    margin-bottom: 2.5rem;
  }

  /* ── TESTIMONIALS ── */
  .testimonials-section {
    background: var(--charcoal);
  }

  .testimonials-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2px;
    margin-top: 5rem;
  }

  .testimonial-card {
    background: var(--graphite);
    padding: 3rem;
    position: relative;
  }

  .testimonial-card::before {
    content: '\201C';
    font-family: var(--font-serif);
    font-size: 6rem;
    color: rgba(201,168,76,0.15);
    position: absolute;
    top: 1rem;
    left: 2rem;
    line-height: 1;
  }

  .testimonial-text {
    font-family: var(--font-serif);
    font-size: 1.05rem;
    font-style: italic;
    line-height: 1.9;
    color: rgba(240,235,224,0.8);
    margin-bottom: 2rem;
    position: relative;
    z-index: 1;
  }

  .testimonial-author {
    font-family: var(--font-body);
    font-size: 0.65rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--gold);
  }

  .testimonial-role {
    font-family: var(--font-body);
    font-size: 0.65rem;
    color: var(--ash);
    margin-top: 0.3rem;
  }

  /* ── CONTENT / FREE ── */
  .content-section {
    background: var(--obsidian);
  }

  .socials-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 1.5rem;
    margin-top: 4rem;
  }

  .social-card {
    background: var(--graphite);
    padding: 2.5rem 2rem;
    text-align: center;
    text-decoration: none;
    display: block;
    border: 1px solid rgba(201,168,76,0.08);
    transition: all 0.35s ease;
    position: relative;
    overflow: hidden;
  }

  .social-card::before {
    content: '';
    position: absolute;
    inset: 0;
    background: var(--gold-muted);
    opacity: 0;
    transition: opacity 0.35s ease;
  }

  .social-card:hover { border-color: rgba(201,168,76,0.4); }
  .social-card:hover::before { opacity: 1; }

  .social-icon {
    font-size: 2rem;
    margin-bottom: 1rem;
    display: block;
  }

  .social-name {
    font-family: var(--font-display);
    font-size: 0.65rem;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    color: var(--gold);
    display: block;
    margin-bottom: 1rem;
  }

  .social-btn {
    font-family: var(--font-body);
    font-size: 0.6rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--ash);
    border: 1px solid rgba(201,168,76,0.2);
    padding: 0.4rem 1rem;
    display: inline-block;
    transition: all 0.3s ease;
    position: relative;
    z-index: 1;
  }

  .social-card:hover .social-btn {
    color: var(--gold);
    border-color: var(--gold);
  }

  /* ── FAQ ── */
  .faq-section {
    background: var(--charcoal);
  }

  .faq-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2px;
    margin-top: 5rem;
  }

  .faq-item {
    background: var(--graphite);
    padding: 3rem;
    border-left: 2px solid transparent;
    transition: border-color 0.3s ease;
    cursor: pointer;
  }

  .faq-item:hover { border-color: var(--gold-dim); }
  .faq-item.open { border-color: var(--gold); }

  .faq-q {
    font-family: var(--font-serif);
    font-size: 1.15rem;
    font-weight: 400;
    color: var(--cream);
    margin-bottom: 0;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 1rem;
  }

  .faq-toggle {
    color: var(--gold);
    font-size: 1.5rem;
    line-height: 1;
    flex-shrink: 0;
    transition: transform 0.3s ease;
  }

  .faq-item.open .faq-toggle { transform: rotate(45deg); }

  .faq-a {
    font-family: var(--font-serif);
    font-size: 0.95rem;
    font-style: italic;
    line-height: 1.9;
    color: rgba(240,235,224,0.6);
    margin-top: 1.5rem;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.5s ease, margin-top 0.3s ease;
  }

  .faq-item.open .faq-a { max-height: 500px; }

  /* ── FINAL CTA ── */
  .final-cta {
    background: var(--obsidian);
    text-align: center;
    padding: 10rem 4rem;
    position: relative;
    overflow: hidden;
  }

  .final-cta::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 80% 60% at 50% 100%, rgba(180,100,20,0.2) 0%, transparent 60%);
  }

  .final-cta-content { position: relative; z-index: 1; }

  .final-cta .section-title {
    font-size: clamp(2.5rem, 6vw, 5rem);
    max-width: 700px;
    margin: 0 auto 3rem;
  }

  .final-quote {
    font-family: var(--font-serif);
    font-size: clamp(1.1rem, 2.5vw, 1.5rem);
    font-style: italic;
    color: var(--ash);
    max-width: 500px;
    margin: 0 auto 4rem;
    line-height: 1.7;
  }

  /* ── FOOTER ── */
  footer {
    background: var(--charcoal);
    border-top: 1px solid rgba(201,168,76,0.15);
    padding: 4rem;
  }

  .footer-inner {
    max-width: 1200px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    gap: 4rem;
    align-items: start;
  }

  .footer-brand .logo {
    font-family: var(--font-display);
    font-size: 1.5rem;
    color: var(--gold);
    letter-spacing: 0.3em;
    text-transform: uppercase;
    margin-bottom: 1rem;
    display: block;
  }

  .footer-tagline {
    font-family: var(--font-serif);
    font-size: 1rem;
    font-style: italic;
    color: var(--ash);
    line-height: 1.7;
  }

  .footer-nav {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    align-items: center;
  }

  .footer-nav a {
    font-family: var(--font-body);
    font-size: 0.65rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--ash);
    text-decoration: none;
    transition: color 0.3s;
  }

  .footer-nav a:hover { color: var(--gold); }

  .footer-contact {
    text-align: right;
  }

  .footer-contact a {
    display: block;
    font-family: var(--font-body);
    font-size: 0.65rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--ash);
    text-decoration: none;
    margin-bottom: 0.8rem;
    transition: color 0.3s;
  }

  .footer-contact a:hover { color: var(--gold); }

  .footer-bottom {
    max-width: 1200px;
    margin: 3rem auto 0;
    padding-top: 2rem;
    border-top: 1px solid rgba(255,255,255,0.05);
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .footer-bottom p {
    font-family: var(--font-body);
    font-size: 0.6rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: rgba(136,128,112,0.5);
  }

  .footer-bottom a {
    color: rgba(136,128,112,0.5);
    text-decoration: none;
    transition: color 0.3s;
  }

  .footer-bottom a:hover { color: var(--gold); }

  /* ── FIRE SVG ── */
  .fire-deco {
    position: absolute;
    pointer-events: none;
  }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .reveal {
    opacity: 0;
    transform: translateY(40px);
    transition: opacity 0.8s ease, transform 0.8s ease;
  }

  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* ── SCROLLBAR ── */
  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: var(--obsidian); }
  ::-webkit-scrollbar-thumb { background: var(--gold-dim); }

  /* ── RESPONSIVE ── */
  @media (max-width: 900px) {
    nav { padding: 1.2rem 2rem; }
    .nav-links { display: none; }
    .hero-content { padding: 8rem 2rem 4rem; }
    .hero-flame { width: 60%; right: -10%; opacity: 0.4; }
    .section-inner { padding: 5rem 2rem; }
    .about-grid { grid-template-columns: 1fr; gap: 3rem; }
    .chama-grid { grid-template-columns: 1fr 1fr; }
    .chama-item:nth-child(5) { grid-column: span 2; }
    .products-grid { grid-template-columns: 1fr; }
    .product-card.featured { grid-column: auto; grid-template-columns: 1fr; }
    .testimonials-grid { grid-template-columns: 1fr; }
    .socials-grid { grid-template-columns: repeat(3, 1fr); }
    .faq-grid { grid-template-columns: 1fr; }
    .ba-grid { grid-template-columns: 1fr; }
    .ba-divider { display: none; }
    .footer-inner { grid-template-columns: 1fr; text-align: center; }
    .footer-contact { text-align: center; }
    .footer-bottom { flex-direction: column; gap: 1rem; text-align: center; }
  }
</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>
  <a href="#" class="nav-logo">MÉTODO CHAMA</a>
  <ul class="nav-links">
    <li><a href="#metodo">O Método</a></li>
    <li><a href="#eumiria">Eumiria</a></li>
    <li><a href="#servicos">Serviços</a></li>
    <li><a href="#depoimentos">Depoimentos</a></li>
    <li><a href="#faq">FAQ</a></li>
    <li><a href="#servicos" class="btn-primary" style="padding:0.6rem 1.5rem"><span>Entrar</span></a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero" id="home">
  <div class="hero-bg"></div>

  <!-- SVG Fire -->
  <svg class="hero-flame" viewBox="0 0 400 600" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <defs>
      <radialGradient id="fire1" cx="50%" cy="100%" r="50%">
        <stop offset="0%" stop-color="#c9a84c" stop-opacity="0.9"/>
        <stop offset="40%" stop-color="#d4631a" stop-opacity="0.7"/>
        <stop offset="100%" stop-color="#8b1a00" stop-opacity="0"/>
      </radialGradient>
      <radialGradient id="fire2" cx="50%" cy="80%" r="40%">
        <stop offset="0%" stop-color="#fff7d6" stop-opacity="0.6"/>
        <stop offset="100%" stop-color="#c9a84c" stop-opacity="0"/>
      </radialGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="8" result="blur"/>
        <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
    </defs>
    <!-- Outer flame -->
    <path d="M200 580 C80 500 20 400 60 280 C80 200 60 140 100 80 C120 40 140 20 200 0 C180 60 200 80 220 60 C260 20 280 40 300 100 C340 160 340 220 320 300 C360 220 350 140 330 80 C370 180 400 280 380 380 C360 460 300 530 200 580Z" fill="url(#fire1)" filter="url(#glow)"/>
    <!-- Inner flame -->
    <path d="M200 540 C120 480 80 400 100 320 C120 260 100 200 140 140 C160 110 180 80 200 60 C190 100 200 120 215 100 C240 70 260 90 270 130 C290 190 280 250 260 310 C290 240 280 170 265 120 C295 200 310 280 290 360 C275 430 240 500 200 540Z" fill="url(#fire2)"/>
    <!-- Phoenix hint -->
    <ellipse cx="200" cy="500" rx="80" ry="20" fill="rgba(201,168,76,0.15)" filter="url(#glow)"/>
  </svg>

  <div class="hero-content">
    <p class="hero-eyebrow">Reorganização Emocional · Identidade · Prosperidade</p>

    <h1 class="hero-title">
      MÉTODO
      <span>CHAMA 🐦‍🔥</span>
    </h1>

    <p class="hero-subtitle">
      Reorganização emocional para sustentar prosperidade, reconstruir identidade e retomar a narrativa da própria vida.
    </p>

    <div class="hero-body">
      <span class="line">Você não está atrasado.</span>
      <span class="spacer"></span>
      <span class="line">Você está tentando construir prosperidade</span>
      <span class="line">sobre um sistema emocional em colapso.</span>
      <span class="spacer"></span>
      <span class="line">Enquanto tenta crescer,</span>
      <span class="line">uma parte sua ainda está ocupada apenas tentando sobreviver.</span>
      <span class="spacer"></span>
      <span class="line">O problema não é falta de <strong>força</strong>.</span>
      <span class="line">É falta de <strong>estrutura</strong>.</span>
    </div>

    <div class="hero-ctas">
      <a href="#checkout" class="btn-primary"><span>QUERO SAIR DO PADRÃO</span></a>
      <a href="#palestra" class="btn-secondary">ASSISTIR A PALESTRA</a>
    </div>
  </div>
</section>

<!-- QUOTE BAR 1 -->
<div class="quote-bar">
  <blockquote>
    "Eu não ensino você a sentir menos.
    <br>Eu ensino você a não se perder no que sente."
    <span>— Eumiria de Araújo</span>
  </blockquote>
</div>

<!-- MÉTODO SECTION -->
<section class="method-section" id="metodo">
  <div class="section-inner">
    <p class="section-eyebrow reveal">O Método</p>
    <div class="gold-line-left reveal"></div>
    <h2 class="section-title reveal">
      Você não precisa de cura.<br>
      <em>Precisa de direção.</em>
    </h2>
    <p class="section-title" style="font-size:1.1rem; font-family:var(--font-serif); font-weight:300; color:var(--ash); margin-top:-1rem; reveal">
      CHAMA é um acrônimo vivo. Cada letra é uma etapa da sua reorganização.
    </p>

    <div class="chama-grid reveal">
      <div class="chama-item">
        <div class="chama-letter">C</div>
        <div class="chama-word">Consciência</div>
        <div class="chama-desc">Reconhecer os padrões que controlam suas escolhas sem que você perceba. Antes de mudar qualquer coisa, é preciso ver.</div>
      </div>
      <div class="chama-item">
        <div class="chama-letter">H</div>
        <div class="chama-word">Hierarquia Emocional</div>
        <div class="chama-desc">Organizar o que sente para que as emoções sirvam à sua vida — não a destruam. Estrutura antes de intensidade.</div>
      </div>
      <div class="chama-item">
        <div class="chama-letter">A</div>
        <div class="chama-word">Ação Estruturada</div>
        <div class="chama-desc">Movimento com direção. Não qualquer movimento — aquele que nasce de clareza interna, não de desespero.</div>
      </div>
      <div class="chama-item">
        <div class="chama-letter">M</div>
        <div class="chama-word">Movimento Financeiro</div>
        <div class="chama-desc">Prosperidade material como consequência de prosperidade emocional. O dinheiro segue o estado interno.</div>
      </div>
      <div class="chama-item">
        <div class="chama-letter">A</div>
        <div class="chama-word">Autorresponsabilidade Expansiva</div>
        <div class="chama-desc">Assumir a própria vida sem culpa, sem colapso — com a dignidade de quem reconhece seu poder real.</div>
      </div>
    </div>
  </div>
</section>

<!-- BEFORE / AFTER -->
<section class="transform-section">
  <div class="section-inner">
    <p class="section-eyebrow reveal">A Transformação</p>
    <div class="gold-line-left reveal"></div>
    <h2 class="section-title reveal">
      Quando a estrutura chega,<br>
      <em>tudo responde diferente.</em>
    </h2>

    <div class="ba-grid">
      <div class="ba-side before reveal">
        <div class="ba-label">Antes do CHAMA</div>
        <ul class="ba-list">
          <li>Caos emocional</li>
          <li>Exaustão constante</li>
          <li>Culpa como modo de vida</li>
          <li>Autossabotagem</li>
          <li>Dinheiro que não permanece</li>
          <li>Relacionamentos repetitivos</li>
          <li>Vida reativa</li>
          <li>Identidade fragmentada</li>
        </ul>
      </div>

      <div class="ba-divider">
        <span class="ba-arrow">🔥</span>
        <div class="ba-divider-line"></div>
      </div>

      <div class="ba-side after reveal">
        <div class="ba-label">Depois do CHAMA</div>
        <ul class="ba-list">
          <li>Clareza interna</li>
          <li>Estrutura emocional</li>
          <li>Segurança em si mesma</li>
          <li>Prosperidade sustentada</li>
          <li>Posicionamento real</li>
          <li>Expansão contínua</li>
          <li>Vida autoral</li>
          <li>Identidade reconstituída</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- QUOTE BAR 2 -->
<div class="quote-bar" style="background:var(--obsidian);">
  <blockquote>
    "Você não precisa de mais força.<br>Você precisa de estrutura."
    <span>— Método CHAMA</span>
  </blockquote>
</div>

<!-- EUMIRIA -->
<section class="about-section" id="eumiria">
  <div class="section-inner">
    <p class="section-eyebrow reveal">Quem Guia Essa Travessia</p>
    <div class="gold-line-left reveal"></div>

    <div class="about-grid">
      <div class="about-image-area reveal">
        <div class="about-frame-deco"></div>
        <div class="about-image-frame">
          <div class="about-image-placeholder">🐦‍🔥</div>
        </div>
      </div>

      <div class="about-text reveal">
        <div class="name">Eumiria de Araújo</div>

        <p class="highlight">Sou pesquisadora contemporânea da experiência humana.</p>
        <p>Psicanalista, terapeuta integrativa, mentora e condutora de clareza emocional.</p>
        <p>Mas antes de qualquer título, eu fui a mulher que precisou sobreviver ao próprio caos antes de conseguir explicá-lo.</p>
        <p>Durante muitos anos, minha intensidade foi interpretada como descontrole. Minha profundidade emocional foi confundida com instabilidade. Meu excesso de sentir recebeu nomes que não traduziam minha realidade.</p>
        <p>Fui rotulada. Fui mal compreendida. Fui ensinada a desconfiar de mim mesma.</p>
        <p>Passei anos tentando corrigir algo que nunca foi defeito — apenas ausência de nome.</p>
        <p class="highlight">Nomear corretamente muda destinos.</p>
        <p>Hoje, meu trabalho não é sobre motivação. É sobre reorganização. Eu não ensino pessoas a serem mais fortes. Eu ensino pessoas a sustentarem a própria vida sem se abandonarem no processo.</p>
        <p>Minha autoridade não nasceu do discurso. Nasceu da travessia.</p>
        <p>Eu encontrei o mapa sozinha. Agora, transformo esse mapa em direção para quem ainda está tentando sobreviver no próprio incêndio.</p>

        <div class="expertise-tags">
          <span class="tag">Psicanálise</span>
          <span class="tag">Terapia Integrativa</span>
          <span class="tag">Clareza Emocional</span>
          <span class="tag">Reorganização de Vida</span>
          <span class="tag">Alta Sensibilidade · AHSD</span>
          <span class="tag">Prosperidade Emocional</span>
          <span class="tag">Reconstrução de Identidade</span>
          <span class="tag">Mentoria Estratégica</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section class="products-section" id="servicos">
  <div class="section-inner">
    <p class="section-eyebrow reveal">Serviços e Produtos</p>
    <div class="gold-line-left reveal"></div>
    <h2 class="section-title reveal">
      Escolha sua<br>
      <em>entrada na travessia.</em>
    </h2>

    <div class="products-grid">

      <!-- Featured: Palestra -->
      <div class="product-card featured reveal" id="palestra">
        <div>
          <div class="product-tag">Destaque · Palestra Principal</div>
          <h3 class="product-name">Aula Magna<br>Método CHAMA</h3>
          <p class="product-desc">
            "Você não é fraco.<br>
            Você só nunca aprendeu<br>
            a se organizar emocionalmente."
          </p>
          <p style="font-family:var(--font-body); font-size:0.85rem; line-height:1.8; color:var(--ash); margin-bottom:2.5rem;">
            Uma palestra que não é sobre motivação. É sobre reorganização profunda. Uma experiência que muda a maneira como você se percebe — e, consequentemente, como você vive.
          </p>
          <a href="#checkout-palestra" class="btn-primary"><span>GARANTIR MINHA VAGA</span></a>
        </div>
        <div style="display:flex; align-items:center; justify-content:center; font-size:8rem; opacity:0.25;">🐦‍🔥</div>
      </div>

      <!-- Método Completo -->
      <div class="product-card reveal" id="checkout">
        <div class="product-number">01</div>
        <div class="product-tag">Programa Principal</div>
        <h3 class="product-name">Método CHAMA Completo</h3>
        <p class="product-desc">
          O programa de reorganização emocional completo. Das cinco etapas à transformação sustentada. Para quem está pronto para sair do padrão.
        </p>
        <a href="#hotmart" class="btn-primary"><span>ENTRAR NO MÉTODO</span></a>
      </div>

      <!-- Mentoria -->
      <div class="product-card reveal">
        <div class="product-number">02</div>
        <div class="product-tag">Alta Performance</div>
        <h3 class="product-name">Mentoria Individual Premium</h3>
        <p class="product-desc">
          Acompanhamento estratégico e profundo. Eumiria ao seu lado, conduzindo sua travessia pessoal com precisão e atenção total.
        </p>
        <a href="#calendly" class="btn-primary"><span>APLICAR PARA MENTORIA</span></a>
      </div>

      <!-- Livro -->
      <div class="product-card reveal">
        <div class="product-number">03</div>
        <div class="product-tag">Literatura</div>
        <h3 class="product-name">Livro Autobiográfico</h3>
        <p class="product-desc">
          A história completa da travessia. O mapa encontrado no incêndio, transformado em palavras para quem ainda está dentro do fogo.
        </p>
        <a href="#livro" class="btn-primary"><span>QUERO LER</span></a>
      </div>

      <!-- Consultoria -->
      <div class="product-card reveal">
        <div class="product-number">04</div>
        <div class="product-tag">Exclusivo</div>
        <h3 class="product-name">Consultoria Estratégica Emocional</h3>
        <p class="product-desc">
          Para empresas, líderes e profissionais que compreendem que a performance externa nasce de organização interna.
        </p>
        <a href="#agendar" class="btn-primary"><span>AGENDAR</span></a>
      </div>

    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials-section" id="depoimentos">
  <div class="section-inner">
    <p class="section-eyebrow reveal">Depoimentos</p>
    <div class="gold-line-left reveal"></div>
    <h2 class="section-title reveal">
      Quando a estrutura chega,<br>
      <em>a vida responde.</em>
    </h2>

    <div class="testimonials-grid">
      <div class="testimonial-card reveal">
        <p class="testimonial-text">
          Eu tentei terapia, coaching, cursos. Nada chegava onde o Método CHAMA chegou. Eumiria não me ensinou a ser diferente — ela me ensinou a entender quem eu já sou. E isso mudou absolutamente tudo.
        </p>
        <div class="testimonial-author">M. R.</div>
        <div class="testimonial-role">Empreendedora · São Paulo</div>
      </div>

      <div class="testimonial-card reveal">
        <p class="testimonial-text">
          Eu vivia em modo de sobrevivência há anos sem perceber. Achava que era falta de força. Depois do CHAMA, entendi que era ausência de estrutura. Hoje minha vida financeira e emocional são completamente diferentes.
        </p>
        <div class="testimonial-author">L. C.</div>
        <div class="testimonial-role">Advogado · Rio de Janeiro</div>
      </div>

      <div class="testimonial-card reveal">
        <p class="testimonial-text">
          A palestra da Eumiria foi a primeira vez que alguém descreveu minha experiência interna com precisão. Saí de lá sabendo que não havia nada de errado comigo — só faltava nome, direção e estrutura.
        </p>
        <div class="testimonial-author">A. S.</div>
        <div class="testimonial-role">Professora · Belo Horizonte</div>
      </div>

      <div class="testimonial-card reveal">
        <p class="testimonial-text">
          Sou HSP e passei anos achando que era o problema. O Método CHAMA me devolveu a mim mesma. Hoje opero com a intensidade que sempre tive — mas com direção, não com destruição.
        </p>
        <div class="testimonial-author">F. M.</div>
        <div class="testimonial-role">Designer · Florianópolis</div>
      </div>

      <div class="testimonial-card reveal">
        <p class="testimonial-text">
          A mentoria individual com a Eumiria foi o investimento mais significativo que já fiz em mim. Não porque ela me deu respostas — mas porque me ensinou a fazer as perguntas certas para a pessoa certa: eu mesma.
        </p>
        <div class="testimonial-author">P. A.</div>
        <div class="testimonial-role">Médica · Recife</div>
      </div>

      <div class="testimonial-card reveal">
        <p class="testimonial-text">
          Eu vim da palestra sem acreditar que algo iria me atingir tão fundo. Saí sabendo que estava construindo prosperidade sobre colapso. Três meses depois, tudo mudou — carreira, relacionamentos, finanças.
        </p>
        <div class="testimonial-author">D. B.</div>
        <div class="testimonial-role">Executivo · Brasília</div>
      </div>
    </div>
  </div>
</section>

<!-- FREE CONTENT -->
<section class="content-section">
  <div class="section-inner">
    <p class="section-eyebrow reveal">Conteúdo Gratuito</p>
    <div class="gold-line-left reveal"></div>
    <h2 class="section-title reveal">
      Antes da compra,<br>
      <em>vem a clareza.</em>
    </h2>

    <div class="socials-grid">
      <a href="#instagram" class="social-card reveal">
        <span class="social-icon">📸</span>
        <span class="social-name">Instagram</span>
        <span class="social-btn">ACESSAR</span>
      </a>
      <a href="#youtube" class="social-card reveal">
        <span class="social-icon">▶️</span>
        <span class="social-name">YouTube</span>
        <span class="social-btn">ACESSAR</span>
      </a>
      <a href="#tiktok" class="social-card reveal">
        <span class="social-icon">🎵</span>
        <span class="social-name">TikTok</span>
        <span class="social-btn">ACESSAR</span>
      </a>
      <a href="#whatsapp" class="social-card reveal">
        <span class="social-icon">💬</span>
        <span class="social-name">Canal WhatsApp</span>
        <span class="social-btn">ENTRAR</span>
      </a>
      <a href="#telegram" class="social-card reveal">
        <span class="social-icon">✈️</span>
        <span class="social-name">Telegram</span>
        <span class="social-btn">ENTRAR</span>
      </a>
    </div>
  </div>
</section>

<!-- FAQ -->
<section class="faq-section" id="faq">
  <div class="section-inner">
    <p class="section-eyebrow reveal">Perguntas Frequentes</p>
    <div class="gold-line-left reveal"></div>
    <h2 class="section-title reveal">
      Antes de decidir,<br>
      <em>esclareça.</em>
    </h2>

    <div class="faq-grid">
      <div class="faq-item reveal" onclick="toggleFaq(this)">
        <div class="faq-q">
          Isso é terapia?
          <span class="faq-toggle">+</span>
        </div>
        <div class="faq-a">
          O Método CHAMA não é terapia clínica, embora Eumiria seja psicanalista e terapeuta. É um programa de reorganização emocional estratégica — uma metodologia própria que integra psicanálise, terapia integrativa e desenvolvimento humano. Ele pode ser complementar à terapia, mas funciona com autonomia própria.
        </div>
      </div>

      <div class="faq-item reveal" onclick="toggleFaq(this)">
        <div class="faq-q">
          Serve para homens e mulheres?
          <span class="faq-toggle">+</span>
        </div>
        <div class="faq-a">
          Sim. O Método CHAMA foi desenhado para qualquer pessoa que vive padrões repetitivos de autossabotagem, caos emocional ou bloqueios de prosperidade — independente de gênero. A experiência humana de fragmentação não tem gênero.
        </div>
      </div>

      <div class="faq-item reveal" onclick="toggleFaq(this)">
        <div class="faq-q">
          É apenas para pessoas de alta sensibilidade (HSP/AHSD)?
          <span class="faq-toggle">+</span>
        </div>
        <div class="faq-a">
          Não exclusivamente. Embora o Método CHAMA dialogue profundamente com a experiência de pessoas altamente sensíveis, ele foi desenvolvido para qualquer pessoa que sente que vive uma vida que não escolheu conscientemente — seja qual for a causa da fragmentação interna.
        </div>
      </div>

      <div class="faq-item reveal" onclick="toggleFaq(this)">
        <div class="faq-q">
          Como funciona a mentoria individual?
          <span class="faq-toggle">+</span>
        </div>
        <div class="faq-a">
          A mentoria é um acompanhamento premium e personalizado com Eumiria. Após a aplicação, há uma conversa inicial de alinhamento, seguida de sessões estratégicas com frequência definida em conjunto. O processo é conduzido de acordo com a realidade específica de cada pessoa.
        </div>
      </div>

      <div class="faq-item reveal" onclick="toggleFaq(this)">
        <div class="faq-q">
          Posso começar do zero?
          <span class="faq-toggle">+</span>
        </div>
        <div class="faq-a">
          Sim. O Método CHAMA foi construído para ser o ponto de partida — não uma continuação. Você não precisa de conhecimento prévio em psicologia ou desenvolvimento pessoal. Precisa apenas de disposição para honestidade interna.
        </div>
      </div>

      <div class="faq-item reveal" onclick="toggleFaq(this)">
        <div class="faq-q">
          Quanto tempo leva a transformação?
          <span class="faq-toggle">+</span>
        </div>
        <div class="faq-a">
          A reorganização emocional não tem prazo fixo — tem marcos. Muitas pessoas relatam clareza significativa nas primeiras semanas. A transformação profunda e sustentada é um processo. O Método CHAMA fornece as ferramentas; você determina a velocidade com sua presença e comprometimento.
        </div>
      </div>
    </div>
  </div>
</section>

<!-- QUOTE BAR 3 -->
<div class="quote-bar" style="background:var(--obsidian);">
  <blockquote>
    "O problema nunca foi a intensidade.<br>Foi a ausência de direção."
    <span>— Método CHAMA</span>
  </blockquote>
</div>

<!-- FINAL CTA -->
<section class="final-cta">
  <div class="final-cta-content">
    <p class="section-eyebrow" style="text-align:center; margin-bottom:2rem;">O Momento É Agora</p>
    <h2 class="section-title" style="font-size:clamp(2.5rem,6vw,5rem); max-width:700px; margin:0 auto 2rem;">
      Você já viveu<br>
      <em>o suficiente no caos.</em>
    </h2>
    <p class="final-quote">
      A chama que está dentro de você não veio para te destruir.<br>
      Ela está esperando por direção.
    </p>
    <div style="display:flex; gap:1.5rem; justify-content:center; flex-wrap:wrap;">
      <a href="#checkout" class="btn-primary" style="font-size:0.75rem; padding:1.3rem 3.5rem;"><span>QUERO SAIR DO PADRÃO</span></a>
      <a href="#palestra" class="btn-secondary" style="font-size:0.75rem; padding:1.3rem 3.5rem;">ASSISTIR A PALESTRA</a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <div class="footer-brand">
      <span class="logo">MÉTODO CHAMA 🔥</span>
      <p class="footer-tagline">
        "Nem todo incêndio veio para destruir.<br>
        Alguns vieram para revelar quem você é."
      </p>
      <p style="font-family:var(--font-body); font-size:0.6rem; letter-spacing:0.2em; text-transform:uppercase; color:rgba(136,128,112,0.4); margin-top:1.5rem;">
        Eumiria de Araújo
      </p>
    </div>

    <nav class="footer-nav">
      <a href="#home">Início</a>
      <a href="#metodo">O Método</a>
      <a href="#eumiria">Eumiria</a>
      <a href="#servicos">Serviços</a>
      <a href="#depoimentos">Depoimentos</a>
      <a href="#faq">FAQ</a>
      <a href="#politica">Política de Privacidade</a>
    </nav>

    <div class="footer-contact">
      <a href="#instagram">Instagram</a>
      <a href="#whatsapp">WhatsApp</a>
      <a href="#telegram">Telegram</a>
      <a href="mailto:contato@metodochama.com.br">E-mail</a>
      <a href="#calendly" style="margin-top:1.5rem; color:var(--gold);">Agendar Conversa →</a>
    </div>
  </div>

  <div class="footer-bottom">
    <p>© 2024 Método CHAMA · Eumiria de Araújo · Todos os direitos reservados</p>
    <p><a href="#politica">Política de Privacidade</a> · <a href="#termos">Termos de Uso</a></p>
  </div>
</footer>

<script>
  // FAQ Toggle
  function toggleFaq(el) {
    const isOpen = el.classList.contains('open');
    document.querySelectorAll('.faq-item').forEach(i => i.classList.remove('open'));
    if (!isOpen) el.classList.add('open');
  }

  // Scroll Reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry, i) => {
      if (entry.isIntersecting) {
        setTimeout(() => {
          entry.target.classList.add('visible');
        }, 80 * (Array.from(reveals).indexOf(entry.target) % 5));
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.08 });

  reveals.forEach(r => observer.observe(r));

  // Nav scroll effect
  const nav = document.querySelector('nav');
  window.addEventListener('scroll', () => {
    if (window.scrollY > 80) {
      nav.style.background = 'rgba(10,10,10,0.97)';
      nav.style.backdropFilter = 'blur(12px)';
    } else {
      nav.style.background = 'linear-gradient(to bottom, rgba(10,10,10,0.95) 0%, transparent 100%)';
      nav.style.backdropFilter = 'blur(2px)';
    }
  });

  // Smooth stagger on CHAMA grid
  document.querySelectorAll('.chama-item').forEach((item, i) => {
    item.style.animationDelay = `${i * 0.1}s`;
  });
</script>

</body>
</html>
