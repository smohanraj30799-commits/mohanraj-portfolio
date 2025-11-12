<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mohanraj S — Data Analyst</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#06b6d4;--glass:rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial;color:#e6eef6;background:linear-gradient(180deg,#071126 0%, #07182a 100%)}
    .container{max-width:980px;margin:32px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;margin-bottom:20px}
    .brand{display:flex;gap:14px;align-items:center}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;color:#021018;font-weight:700}
    h1{margin:0;font-size:22px}
    p.lead{margin:6px 0 0;color:var(--muted);font-size:14px}
    nav a{color:var(--muted);text-decoration:none;margin-left:16px;font-weight:600}

    .card{background:var(--card);border-radius:14px;padding:20px;margin-bottom:18px;box-shadow:0 6px 18px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    .grid{display:grid;grid-template-columns:1fr 340px;gap:18px}
    .hero{display:flex;flex-direction:column;gap:12px}
    .hero h2{margin:0;font-size:20px}
    .buttons{display:flex;gap:12px}
    .btn{padding:10px 14px;border-radius:10px;border:0;background:linear-gradient(90deg,var(--accent),#7c3aed);color:#021018;font-weight:700;cursor:pointer}
    .outline{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted);font-weight:600}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .skill{background:var(--glass);padding:8px 10px;border-radius:999px;font-size:13px;color:var(--muted)}

    .project-list{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
    .project{padding:12px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.01),rgba(255,255,255,0.00));border:1px solid rgba(255,255,255,0.02)}
    .project h4{margin:0 0 6px}
    footer{margin-top:18px;color:var(--muted);font-size:13px;display:flex;justify-content:space-between;align-items:center}

    /* responsive */
    @media (max-width:900px){.grid{grid-template-columns:1fr}.project-list{grid-template-columns:1fr}.logo{width:48px;height:48px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">MR</div>
        <div>
          <h1>Mohanraj S</h1>
          <p class="lead">Data Analyst • Python | SQL | Power BI</p>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <div class="grid">
        <section>
          <div class="card hero">
            <h2>Hi — I'm Mohanraj</h2>
            <p class="lead">Analytically driven and detail-oriented graduate with a strong foundation in statistical analysis, data cleaning, and dashboard creation. I love turning data into clear insights.</p>
            <div class="buttons">
              <a class="btn" href="#projects">See projects</a>
              <a class="btn outline" href="#contact">Hire / Contact</a>
            </div>

            <div style="margin-top:12px">
              <h3 style="margin:0 0 8px">Skills</h3>
              <div class="skills">
                <div class="skill">Python</div>
                <div class="skill">Pandas</div>
                <div class="skill">SQL</div>
                <div class="skill">Power BI</div>
                <div class="skill">Excel</div>
                <div class="skill">Data Cleaning</div>
              </div>
            </div>
          </div>

          <div id="projects" class="card">
            <h3 style="margin-top:0">Selected projects</h3>
            <div class="project-list">
              <div class="project">
                <h4>Sales Dashboard</h4>
                <p class="lead" style="margin:0 0 8px">Interactive Power BI dashboard showing monthly sales, cohort analysis and KPI tracking.</p>
                <small class="lead">Tools: Power BI, SQL</small>
              </div>
              <div class="project">
                <h4>Customer Churn Model</h4>
                <p class="lead" style="margin:0 0 8px">Built a churn prediction model and data pipeline to score customers weekly.</p>
                <small class="lead">Tools: Python, scikit-learn, Pandas</small>
              </div>
              <div class="project">
                <h4>Web Scraper + ETL</h4>
                <p class="lead" style="margin:0 0 8px">Automated data collection from public sites and loaded cleaned data to a SQLite DB.</p>
                <small class="lead">Tools: Python, BeautifulSoup, SQLite</small>
              </div>
              <div class="project">
                <h4>Resume & Interview Prep</h4>
                <p class="lead" style="margin:0 0 8px">Resume creation and targeted interview Q&A for data roles.</p>
                <small class="lead">Tools: Excel, Google Sheets</small>
              </div>
            </div>
          </div>
        </section>

        <aside>
          <div class="card">
            <h3 style="margin-top:0">Contact</h3>
            <p class="lead">Email: <a href="mailto:your.email@example.com" style="color:var(--accent);text-decoration:none">your.email@example.com</a></p>
            <p class="lead">Location: India</p>
            <p style="margin-top:10px">Download: <a href="#" style="color:var(--accent)">Resume (PDF)</a></p>
            <div style="margin-top:12px">
              <h4 style="margin:0 0 8px">Social</h4>
              <p style="margin:0"><a href="#" style="text-decoration:none;color:var(--muted)">LinkedIn</a> • <a href="#" style="text-decoration:none;color:var(--muted)">GitHub</a></p>
            </div>
          </div>

          <div class="card">
            <h4 style="margin-top:0">About</h4>
            <p class="lead">I create clear dashboards and reproducible data pipelines. Currently learning advanced Python and ML techniques to deliver more predictive insights.</p>
          </div>

          <div id="contact" class="card">
            <h4 style="margin-top:0">Leave a message</h4>
            <form onsubmit="alert('This is a demo. Replace with your form endpoint or use mailto.');return false;">
              <div style="margin-bottom:8px"><input placeholder="Your name" style="width:100%;padding:9px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit"/></div>
              <div style="margin-bottom:8px"><input placeholder="Email" style="width:100%;padding:9px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit"/></div>
              <div style="margin-bottom:8px"><textarea placeholder="Message" style="width:100%;padding:9px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit" rows="4"></textarea></div>
              <button class="btn" type="submit">Send</button>
            </form>
          </div>
        </aside>
      </div>

      <footer>
        <div>© <span id="year"></span> Mohanraj S</div>
        <div>Built with ❤️ • Single-file portfolio</div>
      </footer>
    </main>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
