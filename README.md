<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Nitin Rawat — LinkedIn Profile</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: #f3f2ef; color: #000; }
  .container { max-width: 740px; margin: 32px auto; padding: 0 16px 64px; }

  /* CARD */
  .card { background: #fff; border-radius: 10px; border: 1px solid #e0e0e0; margin-bottom: 12px; overflow: hidden; }

  /* HERO */
  .hero-banner { height: 120px; background: linear-gradient(135deg, #0a66c2, #004182); }
  .hero-body { padding: 0 24px 20px; position: relative; }
  .avatar { width: 88px; height: 88px; border-radius: 50%; background: #0a66c2; border: 4px solid #fff; display: flex; align-items: center; justify-content: center; font-size: 28px; font-weight: 700; color: #fff; margin-top: -44px; margin-bottom: 12px; }
  .hero-name { font-size: 22px; font-weight: 700; color: #000; margin-bottom: 4px; }
  .hero-headline { font-size: 14px; color: #333; line-height: 1.5; margin-bottom: 6px; }
  .hero-location { font-size: 13px; color: #0a66c2; margin-bottom: 14px; }
  .btn-row { display: flex; gap: 8px; flex-wrap: wrap; }
  .btn-primary { background: #0a66c2; color: #fff; border: none; padding: 8px 20px; border-radius: 20px; font-size: 13px; font-weight: 600; cursor: pointer; }
  .btn-secondary { background: #fff; color: #0a66c2; border: 1.5px solid #0a66c2; padding: 7px 20px; border-radius: 20px; font-size: 13px; font-weight: 600; cursor: pointer; }
  .open-badge { display: inline-block; background: #daf0e3; color: #057642; font-size: 12px; font-weight: 600; padding: 4px 12px; border-radius: 4px; margin-top: 10px; }

  /* SECTION COMMON */
  .section { padding: 20px 24px; }
  .section + .section { border-top: 1px solid #e0e0e0; }
  .section-title { font-size: 18px; font-weight: 700; margin-bottom: 16px; color: #000; }

  /* ABOUT */
  .about-text { font-size: 14px; line-height: 1.75; color: #333; white-space: pre-line; }
  .stack-row { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 14px; }
  .tag { font-size: 12px; padding: 4px 10px; border-radius: 14px; font-weight: 500; }
  .tag-blue { background: #dce6f0; color: #004182; }
  .tag-green { background: #daf0e3; color: #057642; }
  .tag-purple { background: #ede9f8; color: #5f3dc4; }

  /* EXPERIENCE */
  .exp-item { display: flex; gap: 14px; margin-bottom: 22px; }
  .exp-item:last-child { margin-bottom: 0; }
  .exp-dot-col { display: flex; flex-direction: column; align-items: center; padding-top: 4px; }
  .exp-dot { width: 12px; height: 12px; border-radius: 50%; flex-shrink: 0; }
  .exp-line { width: 2px; flex: 1; background: #e0e0e0; margin-top: 4px; }
  .exp-role { font-size: 15px; font-weight: 700; color: #000; margin-bottom: 2px; }
  .exp-company { font-size: 13px; color: #555; margin-bottom: 10px; }
  .exp-bullets { list-style: none; padding: 0; }
  .exp-bullets li { font-size: 13px; color: #333; line-height: 1.65; padding: 3px 0 3px 16px; position: relative; }
  .exp-bullets li::before { content: "▸"; position: absolute; left: 0; color: #0a66c2; }
  .metric { color: #057642; font-weight: 700; }

  /* SKILLS */
  .skills-grid { display: flex; flex-wrap: wrap; gap: 8px; }
  .skill-pill { font-size: 13px; padding: 6px 14px; border-radius: 20px; border: 1.5px solid #c9d4de; color: #333; background: #f9f9f9; font-weight: 500; }
  .skill-pill:hover { background: #eef3f8; border-color: #0a66c2; color: #0a66c2; cursor: default; }
  .skill-pill.learning { border-color: #9b7fe8; color: #5f3dc4; background: #f5f0ff; }

  /* FEATURED */
  .featured-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap: 12px; }
  .feat-card { border: 1.5px solid #e0e0e0; border-radius: 8px; overflow: hidden; }
  .feat-thumb { height: 70px; display: flex; align-items: center; justify-content: center; font-size: 28px; }
  .feat-body { padding: 10px 12px; }
  .feat-title { font-size: 13px; font-weight: 700; color: #000; margin-bottom: 4px; }
  .feat-sub { font-size: 12px; color: #555; line-height: 1.5; }

  /* CONNECT */
  .connect-box { background: #eef3f8; border-radius: 8px; padding: 16px 20px; }
  .connect-label { font-size: 12px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.06em; color: #555; margin-bottom: 8px; }
  .connect-text { font-size: 13px; color: #333; line-height: 1.7; font-style: italic; }
  .copy-btn { margin-top: 10px; background: #0a66c2; color: #fff; border: none; padding: 7px 16px; border-radius: 16px; font-size: 12px; font-weight: 600; cursor: pointer; }
  .copy-btn:hover { background: #004182; }

  /* DIVIDER LABEL */
  .divider-label { font-size: 11px; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; color: #888; margin-bottom: 12px; }

  @media (max-width: 520px) {
    .hero-name { font-size: 18px; }
    .featured-grid { grid-template-columns: 1fr 1fr; }
  }
</style>
</head>
<body>
<div class="container">

  <!-- HERO CARD -->
  <div class="card">
    <div class="hero-banner"></div>
    <div class="hero-body">
      <div class="avatar">NR</div>
      <div class="hero-name">Nitin Rawat</div>
      <div class="hero-headline">Data Analyst &amp; BI Engineer | ETL Pipelines · Tableau · Power BI · SQL · Python · AWS<br>Turning Raw Data into Business Decisions</div>
      <div class="hero-location">📍 Delhi, India · nitinrawat2502@gmail.com</div>
      <div class="open-badge">✅ Open to Work — Data Analyst · BI Engineer · Analytics Engineer</div>
      <div class="btn-row" style="margin-top:14px;">
        <button class="btn-primary">Connect</button>
        <button class="btn-secondary">Message</button>
      </div>
    </div>
  </div>

  <!-- ABOUT -->
  <div class="card">
    <div class="section">
      <div class="section-title">About</div>
      <div class="about-text">I build the plumbing that keeps data clean, moving, and meaningful — so teams can stop guessing and start deciding.

With 3+ years across BI, data engineering, and performance analytics, I've shipped end-to-end ETL pipelines on AWS, cut manual reporting effort by <span class="metric">80%</span>, and built dashboards that became the single source of truth for cross-functional teams.

My work spans the full data stack — ingestion, transformation, modelling, and visualisation. From raw CSVs to Tableau dashboards, live Plotly Dash apps, and star schemas on Databricks, I build things that hold up in production.

I've operated across AI ventures, staffing, and performance marketing, which means I translate fast between messy business questions and precise analytical answers.

Currently levelling up in Cloud Data Engineering and AI-powered Analytics (LangChain, Hugging Face, TensorFlow).</div>
      <div class="stack-row">
        <span class="tag tag-blue">Python</span>
        <span class="tag tag-blue">SQL</span>
        <span class="tag tag-blue">Tableau</span>
        <span class="tag tag-blue">Power BI</span>
        <span class="tag tag-blue">AWS</span>
        <span class="tag tag-blue">Databricks</span>
        <span class="tag tag-green">↓ 80% manual effort</span>
        <span class="tag tag-green">↑ 30% data accuracy</span>
        <span class="tag tag-purple">LangChain — learning</span>
      </div>
    </div>
  </div>

  <!-- EXPERIENCE -->
  <div class="card">
    <div class="section">
      <div class="section-title">Experience</div>

      <div class="exp-item">
        <div class="exp-dot-col">
          <div class="exp-dot" style="background:#0a66c2;"></div>
          <div class="exp-line"></div>
        </div>
        <div>
          <div class="exp-role">Data Analyst</div>
          <div class="exp-company">LoQal AI Ventures · Delhi · Full-time</div>
          <ul class="exp-bullets">
            <li>Architected end-to-end ETL pipelines on <strong>AWS S3 + Lambda</strong>, fully automating cloud data ingestion across multiple sources</li>
            <li>Cut manual reporting effort by <span class="metric">80%</span> through containerised, scheduled workflows built with Docker and Git</li>
            <li>Deployed real-time dashboards in Tableau, Power BI, and Plotly Dash — giving stakeholders live access to business metrics</li>
            <li>Managed full data deployment lifecycle on AWS, delivering a scalable, production-grade analytics layer</li>
          </ul>
        </div>
      </div>

      <div class="exp-item">
        <div class="exp-dot-col">
          <div class="exp-dot" style="background:#057642;"></div>
          <div class="exp-line"></div>
        </div>
        <div>
          <div class="exp-role">Data Analyst</div>
          <div class="exp-company">Elon Staffing · Gurugram · Full-time</div>
          <ul class="exp-bullets">
            <li>Built a unified reporting layer integrating <span class="metric">5+ disparate databases</span> into a single SQL + Python ETL workflow</li>
            <li>Improved data accuracy by <span class="metric">30%</span> through systematic cleaning and validation using Pandas, NumPy, and Seaborn</li>
            <li>Designed KPI dashboards in Tableau and Power BI that accelerated cross-department decision-making by <span class="metric">20%</span></li>
            <li>Automated recurring reports with Excel VBA and pivot tables, cutting generation time by <span class="metric">50%</span></li>
          </ul>
        </div>
      </div>

      <div class="exp-item">
        <div class="exp-dot-col">
          <div class="exp-dot" style="background:#c37d16;"></div>
        </div>
        <div>
          <div class="exp-role">MIS Intelligence Analyst</div>
          <div class="exp-company">AdByteHub · Gurugram · Full-time</div>
          <ul class="exp-bullets">
            <li>Delivered campaign analytics across CTR, CPC, and ROAS — giving leadership clear visibility into marketing ROI</li>
            <li>Built structured revenue and ROI reports in Power BI consumed directly by senior stakeholders for strategic decisions</li>
            <li>Maintained clean, consistent datasets with Python + SQL, ensuring accuracy across all performance reporting cycles</li>
            <li>Tracked real-time campaign performance via Power BI dashboards used for day-to-day spend optimisation</li>
          </ul>
        </div>
      </div>

    </div>
  </div>

  <!-- SKILLS -->
  <div class="card">
    <div class="section">
      <div class="section-title">Skills</div>
      <div class="divider-label">Core</div>
      <div class="skills-grid">
        <span class="skill-pill">SQL</span>
        <span class="skill-pill">Python</span>
        <span class="skill-pill">ETL Pipelines</span>
        <span class="skill-pill">Data Modelling</span>
        <span class="skill-pill">Tableau</span>
        <span class="skill-pill">Power BI</span>
        <span class="skill-pill">Plotly Dash</span>
        <span class="skill-pill">AWS S3</span>
        <span class="skill-pill">AWS Lambda</span>
        <span class="skill-pill">PySpark</span>
        <span class="skill-pill">Databricks</span>
        <span class="skill-pill">Docker</span>
        <span class="skill-pill">Pandas</span>
        <span class="skill-pill">NumPy</span>
        <span class="skill-pill">Seaborn</span>
        <span class="skill-pill">Scikit-learn</span>
        <span class="skill-pill">Excel VBA</span>
        <span class="skill-pill">Git</span>
        <span class="skill-pill">Apache Superset</span>
      </div>
      <div class="divider-label" style="margin-top:16px;">Actively learning</div>
      <div class="skills-grid">
        <span class="skill-pill learning">LangChain</span>
        <span class="skill-pill learning">Hugging Face</span>
        <span class="skill-pill learning">TensorFlow</span>
        <span class="skill-pill learning">PyTorch</span>
        <span class="skill-pill learning">Cloud Data Engineering</span>
      </div>
    </div>
  </div>

  <!-- FEATURED -->
  <div class="card">
    <div class="section">
      <div class="section-title">Featured</div>
      <div class="featured-grid">
        <div class="feat-card">
          <div class="feat-thumb" style="background:#dce6f0;">🏭</div>
          <div class="feat-body">
            <div class="feat-title">FMCG Sales Analytics Platform</div>
            <div class="feat-sub">Medallion pipeline — Databricks + AWS S3 + PySpark + Tableau</div>
          </div>
        </div>
        <div class="feat-card">
          <div class="feat-thumb" style="background:#daf0e3;">👥</div>
          <div class="feat-body">
            <div class="feat-title">HR Analytics Dashboard</div>
            <div class="feat-sub">8,900+ records · 20+ visuals · LOD expressions — Tableau Public</div>
          </div>
        </div>
        <div class="feat-card">
          <div class="feat-thumb" style="background:#fff4e0;">💰</div>
          <div class="feat-body">
            <div class="feat-title">Product Price Dynamics</div>
            <div class="feat-sub">EDA + Power BI on pricing patterns — Python + Seaborn</div>
          </div>
        </div>
        <div class="feat-card">
          <div class="feat-thumb" style="background:#ede9f8;">✍️</div>
          <div class="feat-body">
            <div class="feat-title">Post idea: 5 lessons from building ETL pipelines on AWS</div>
            <div class="feat-sub">Thought leadership — drives recruiter reach organically</div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- CONNECTION MESSAGE -->
  <div class="card">
    <div class="section">
      <div class="section-title">Connection request message</div>
      <div class="connect-box">
        <div class="connect-label">Short · 300 char limit</div>
        <div class="connect-text" id="connect-msg">Hi [Name], I came across your profile and love what [Company] is building in the data space. I'm a Data Analyst with 3+ years in ETL pipelines, Tableau, and AWS — currently exploring new opportunities. Would be great to connect!</div>
        <button class="copy-btn" onclick="copyMsg()">Copy message</button>
      </div>
    </div>
  </div>

</div>

<script>
  function copyMsg() {
    const text = document.getElementById('connect-msg').innerText;
    navigator.clipboard.writeText(text).then(() => {
      const btn = document.querySelector('.copy-btn');
      btn.textContent = 'Copied!';
      setTimeout(() => btn.textContent = 'Copy message', 2000);
    });
  }
</script>
</body>
</html>
