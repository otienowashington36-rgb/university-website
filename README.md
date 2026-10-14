<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <meta name="description" content="Learn more about Washington Edison, a web developer based in Kenya passionate about frontend development and modern web design."> <title>About Me | Washington Edison</title>

<style> /* ===== General Styles ===== / { margin: 0; padding: 0; box-sizing: border-box; }

body { font-family: "Segoe UI", Roboto, Helvetica, Arial, sans-serif; background: #ffffff; color: #526174; line-height: 1.8; }

/* ===== About Section ===== */ #about { padding: 80px 20px; }

.about-container { max-width: 960px; margin: 0 auto; }

/* ===== Section Heading ===== */ .about-heading { text-align: center; margin-bottom: 40px; }

.section-label { display: inline-block; margin-bottom: 12px; color: #007bff; font-size: 0.8rem; font-weight: 700; letter-spacing: 3px; text-transform: uppercase; }

.about-title { color: #172b4d; font-size: clamp(2.2rem, 5vw, 3.2rem); font-weight: 800; line-height: 1.2; letter-spacing: -1px; }

.about-title span { color: #007bff; }

.about-subtitle { max-width: 600px; margin: 16px auto 0; font-size: 1.05rem; color: #68778b; }

/* ===== About Card ===== */ .about-content { padding: clamp(24px, 5vw, 45px); background: #f7f9fc; border: 1px solid #e5eaf2; border-top: 4px solid #007bff; border-radius: 18px; box-shadow: 0 12px 35px rgba(23, 43, 77, 0.06); }

.about-content p { margin-bottom: 20px; font-size: 1.02rem; line-height: 1.9; }

.about-content .intro { color: #263b59; font-size: 1.13rem; font-weight: 500; }

.highlight { color: #007bff; font-weight: 700; }

/* ===== Information Cards ===== */ .about-details { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 16px; margin-top: 32px; padding-top: 28px; border-top: 1px solid #e1e7f0; }

.detail-card { display: flex; align-items: flex-start; gap: 12px; padding: 18px 14px; background: #ffffff; border: 1px solid #e5eaf2; border-radius: 12px; transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease; }

.detail-card:hover { transform: translateY(-4px); border-color: #007bff; box-shadow: 0 8px 20px rgba(0, 123, 255, 0.08); }

.detail-icon { font-size: 1.5rem; line-height: 1.5; }

.detail-card h3 { margin-bottom: 4px; color: #172b4d; font-size: 0.9rem; font-weight: 700; }

.detail-card p { margin: 0; color: #68778b; font-size: 0.85rem; line-height: 1.6; overflow-wrap: anywhere; }

/* ===== Mobile Responsive ===== */ @media (max-width: 700px) { #about { padding: 55px 16px; }

.about-heading { margin-bottom: 28px; }

.about-details { grid-template-columns: 1fr; gap: 12px; }

.detail-card { padding: 16px; } }

/* ===== Accessibility ===== / @media (prefers-reduced-motion: reduce) { , ::before, ::after { scroll-behavior: auto !important; transition-duration: 0.01ms !important; animation-duration: 0.01ms !important; animation-iteration-count: 1 !important; } } </style> </head>

<body>

<section id="about" aria-labelledby="about-title"> <div class="about-container">

<header class="about-heading"> <span class="section-label">Get to know me</span>

<h1 class="about-title" id="about-title"> About <span>Me</span> </h1>

<p class="about-subtitle"> A little about who I am, what I do, and what drives me. </p> </header>

<div class="about-content"> <p class="intro"> Hello! I'm <span class="highlight">Washington Edison</span>, a web developer based in Kenya with a passion for creating meaningful digital experiences that combine thoughtful design with reliable functionality. </p>

<p> I focus on <span class="highlight">frontend development</span>, using HTML5, CSS3, and JavaScript to build responsive, accessible, and user-friendly websites. I enjoy transforming ideas into intuitive interfaces that look great and work smoothly across different devices. </p>

<p> Beyond writing code, I'm committed to continuous learning and improving my development workflow. I use tools such as <span class="highlight">Git, VS Code, and ESLint</span> to write organized, maintainable code and follow good development practices. </p>

<div class="about-details">

<div class="detail-card"> <span class="detail-icon" aria-hidden="true">📍</span> <div> <h3>Location</h3> <p>Kenya</p> </div> </div>

<div class="detail-card"> <span class="detail-icon" aria-hidden="true">💻</span> <div> <h3>Specialization</h3> <p>Frontend Development</p> </div> </div>

<div class="detail-card"> <span class="detail-icon" aria-hidden="true">🌱</span> <div> <h3>Mindset</h3> <p>Always Learning</p> </div> </div>

</div> </div>

</div> </section>

</body> </html>
