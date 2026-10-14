<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Me | Washington Otieno</title>
  <style>
    /* ===== CSS Variables & Design Tokens ===== */
    :root {
      --primary: #0066ff;
      --primary-hover: #0052cc;
      --primary-light: rgba(0, 102, 255, 0.08);
      --text-main: #1e293b;
      --text-muted: #64748b;
      --bg-body: #f8fafc;
      --bg-card: #ffffff;
      --border-color: #e2e8f0;
      --radius-lg: 20px;
      --radius-md: 12px;
      --shadow-subtle: 0 10px 30px -5px rgba(0, 0, 0, 0.05);
      --shadow-hover: 0 12px 25px -5px rgba(0, 102, 255, 0.12);
      --transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
    }

    /* ===== General Reset ===== */
    *, *::before, *::after {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      background: var(--bg-body);
      color: var(--text-main);
      line-height: 1.7;
      -webkit-font-smoothing: antialiased;
    }

    /* ===== About Section ===== */
    #about {
      padding: 90px 20px;
    }

    .about-container {
      max-width: 980px;
      margin: 0 auto;
    }

    /* ===== Section Header ===== */
    .about-heading {
      text-align: center;
      margin-bottom: 48px;
    }

    .section-label {
      display: inline-block;
      margin-bottom: 12px;
      padding: 6px 14px;
      background: var(--primary-light);
      color: var(--primary);
      font-size: 0.8rem;
      font-weight: 700;
      letter-spacing: 2px;
      text-transform: uppercase;
      border-radius: 20px;
    }

    .about-title {
      font-size: clamp(2.2rem, 5vw, 3.2rem);
      font-weight: 800;
      line-height: 1.25;
      letter-spacing: -1px;
      color: #0f172a;
    }

    .about-title span {
      background: linear-gradient(135deg, var(--primary) 0%, #00d2ff 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .about-subtitle {
      max-width: 620px;
      margin: 16px auto 0;
      font-size: 1.1rem;
      color: var(--text-muted);
    }

    /* ===== Main Card Content ===== */
    .about-content {
      padding: clamp(28px, 5vw, 48px);
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      border-top: 5px solid var(--primary);
      border-radius: var(--radius-lg);
      box-shadow: var(--shadow-subtle);
    }

    .about-content p {
      margin-bottom: 20px;
      font-size: 1.05rem;
      color: #334155;
    }

    .about-content .intro {
      color: #0f172a;
      font-size: 1.2rem;
      font-weight: 600;
      line-height: 1.8;
    }

    .highlight {
      color: var(--primary);
      font-weight: 700;
    }

    /* ===== Information Grid ===== */
    .about-details {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      margin-top: 36px;
      padding-top: 32px;
      border-top: 1px solid var(--border-color);
    }

    .detail-card {
      display: flex;
      align-items: flex-start;
      gap: 16px;
      padding: 20px;
      background: #fafbfc;
      border: 1px solid var(--border-color);
      border-radius: var(--radius-md);
      transition: var(--transition);
    }

    .detail-card:hover {
      transform: translateY(-4px);
      background: var(--bg-card);
      border-color: var(--primary);
      box-shadow: var(--shadow-hover);
    }

    .detail-icon {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 42px;
      height: 42px;
      background: var(--primary-light);
      color: var(--primary);
      border-radius: 10px;
      flex-shrink: 0;
    }

    .detail-icon svg {
      width: 22px;
      height: 22px;
      fill: currentColor;
    }

    .detail-card h3 {
      margin-bottom: 4px;
      color: #0f172a;
      font-size: 0.95rem;
      font-weight: 700;
    }

    .detail-card p {
      margin: 0;
      color: var(--text-muted);
      font-size: 0.9rem;
      line-height: 1.5;
      overflow-wrap: anywhere;
    }

    /* ===== Mobile & Responsiveness ===== */
    @media (max-width: 640px) {
      #about {
        padding: 60px 16px;
      }
      .about-content {
        padding: 24px;
      }
      .detail-card {
        padding: 16px;
      }
    }

    /* ===== Accessibility (Motion) ===== */
    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after {
        transition: none !important;
        transform: none !important;
      }
    }
  </style>
</head>
<body>

  <section id="about">
    <div class="about-container">
      
      <!-- Section Header -->
      <div class="about-heading">
        <span class="section-label">Get To Know Me</span>
        <h1 class="about-title">Hi, I'm <span>Washington Otieno</span></h1>
        <p class="about-subtitle">Data Analyst & Technical Solutions Specialist transforming complex business data into actionable strategies.</p>
      </div>

      <!-- Main About Card -->
      <div class="about-content">
        <p class="intro">
          I am a results-driven <span class="highlight">Data Analyst</span> with a core technical stack spanning <span class="highlight">Python, SQL, Power BI, and Econometric Modeling</span>.
        </p>
        <p>
          I bridge the gap between complex datasets and decisive strategic choices. Whether querying relational databases, building end-to-end Pandas processing pipelines, running statsmodels regressions, or designing interactive dashboards, I deliver end-to-end analytical solutions across diverse business contexts.
        </p>

        <!-- Details Grid -->
        <div class="about-details">
          
          <!-- Card 1 -->
          <div class="detail-card">
            <div class="detail-icon" aria-hidden="true">
              <svg viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/></svg>
            </div>
            <div>
              <h3>Core Specialization</h3>
              <p>Data Wrangling, SQL Analytics, Business Intelligence & Predictive Modeling</p>
            </div>
          </div>

          <!-- Card 2 -->
          <div class="detail-card">
            <div class="detail-icon" aria-hidden="true">
              <svg viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-5 14H7v-2h7v2zm3-4H7v-2h10v2zm0-4H7V7h10v2z"/></svg>
            </div>
            <div>
              <h3>Technical Stack</h3>
              <p>Python (Pandas, Statsmodels), SQL (SQLite/PostgreSQL), Power BI & Tableau</p>
            </div>
          </div>

          <!-- Card 3 -->
          <div class="detail-card">
            <div class="detail-icon" aria-hidden="true">
              <svg viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
            </div>
            <div>
              <h3>Location</h3>
              <p>Kenya (Available for Global Remote Operations)</p>
            </div>
          </div>

        </div>
      </div>

    </div>
  </section>

</body>
</html>
