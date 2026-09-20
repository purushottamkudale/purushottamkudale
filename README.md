<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Purushottam Kudale, Java Full-Stack Developer</title>
<meta name="description" content="Java full-stack developer and SDE. Spring Boot, React, MySQL. Projects, experience, tech stack and contact details.">
<meta property="og:title" content="Purushottam Kudale, Java Full-Stack Developer">
<meta property="og:description" content="Java Full-Stack Developer and SDE. Open to roles in Bengaluru, Pune, Hyderabad and remote.">
<meta property="og:type" content="website">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ctext y='.9em' font-size='90'%3E%E2%98%95%3C/text%3E%3C/svg%3E">
<script>
try { var t = localStorage.getItem("theme"); if (t) document.documentElement.setAttribute("data-theme", t); } catch (e) {}
</script>
<style>
:root {
  --bg: #FFFFFF;
  --bg-soft: #F6F8FA;
  --text: #1F2328;
  --muted: #59636E;
  --border: #D1D9E0;
  --link: #0969DA;
  --link-ink: #FFFFFF;
  --font: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif;
  --mono: ui-monospace, SFMono-Regular, "SF Mono", Menlo, Consolas, monospace;
}
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg: #0D1117; --bg-soft: #151B23; --text: #E6EDF3; --muted: #9198A1;
    --border: #3D444D; --link: #4493F8; --link-ink: #0D1117;
  }
}
:root[data-theme="dark"] {
  --bg: #0D1117; --bg-soft: #151B23; --text: #E6EDF3; --muted: #9198A1;
  --border: #3D444D; --link: #4493F8; --link-ink: #0D1117;
}
*, *::before, *::after { box-sizing: border-box; }
html { scroll-behavior: smooth; scroll-padding-top: 4rem; }
body { margin: 0; background: var(--bg); color: var(--text); font-family: var(--font); font-size: 1rem; line-height: 1.6; -webkit-font-smoothing: antialiased; }
a { color: var(--link); }
:focus-visible { outline: 3px solid var(--link); outline-offset: 2px; border-radius: 4px; }
.wrap { max-width: 54rem; margin: 0 auto; padding: 0 1.25rem; }
p { margin: 0; }
ul { margin: 0; padding: 0; list-style: none; }
[hidden] { display: none !important; }
.sr { position: absolute; width: 1px; height: 1px; overflow: hidden; clip: rect(0 0 0 0); white-space: nowrap; }

/* top bar */
.bar { border-bottom: 1px solid var(--border); background: var(--bg); position: sticky; top: 0; z-index: 5; }
.bar .wrap { display: flex; align-items: center; justify-content: space-between; gap: 1rem; min-height: 3.25rem; flex-wrap: wrap; padding-top: 0.4rem; padding-bottom: 0.4rem; }
.bar nav { display: flex; gap: 1.1rem; flex-wrap: wrap; align-items: center; font-size: 0.95rem; }
.bar nav a { color: var(--muted); text-decoration: none; }
.bar nav a:hover { color: var(--text); text-decoration: underline; }
.themebtn { font: inherit; font-size: 0.9rem; color: var(--text); background: var(--bg-soft); border: 1px solid var(--border); border-radius: 6px; padding: 0.25rem 0.75rem; cursor: pointer; }
.themebtn:hover { border-color: var(--muted); }

/* badges */
.badge { display: inline-block; padding: 0.28rem 0.7rem; border-radius: 6px; background: var(--c, #444); color: var(--t, #fff); font-size: 0.82rem; font-weight: 600; line-height: 1.4; border: 1px solid rgba(128,128,128,0.35); text-decoration: none; }
.badges { display: flex; flex-wrap: wrap; gap: 0.5rem; }
a.badge.lg, button.badge.lg { padding: 0.6rem 1.05rem; font-size: 0.92rem; }
a.badge:hover, button.badge:hover { filter: brightness(1.12); }
button.badge { font-family: inherit; cursor: pointer; }

/* hero */
.hero { text-align: center; padding: 3.5rem 0 2.5rem; }
.hero h1 { font-size: clamp(1.9rem, 5vw, 2.7rem); line-height: 1.2; margin: 0; letter-spacing: -0.01em; }
.hero h2 { border: 0; margin: 0.9rem 0 0; padding: 0; font-size: clamp(1.1rem, 2.6vw, 1.4rem); font-weight: 600; }
.typed { margin-top: 0.9rem; color: var(--muted); font-family: var(--mono); font-size: 0.95rem; min-height: 1.6em; }
.hero .badges { justify-content: center; margin-top: 1.5rem; }

/* sections */
section.sec { padding-top: 2.25rem; }
h2.sh { font-size: 1.5rem; margin: 0 0 1.1rem; padding-bottom: 0.35rem; border-bottom: 1px solid var(--border); line-height: 1.25; }
h3.sub { font-size: 1.15rem; margin: 1.6rem 0 0.7rem; line-height: 1.3; }
.about p { margin-bottom: 0.9rem; }
.emojilist { display: grid; gap: 0.45rem; margin-top: 0.5rem; }
.emojilist li { display: grid; grid-template-columns: 1.75rem minmax(0, 1fr); }

/* experience */
.job { margin-top: 1.4rem; }
.job h3 { font-size: 1.15rem; margin: 0; line-height: 1.3; }
.job .org { font-weight: 700; margin-top: 0.2rem; }
code.date { font-family: var(--mono); font-size: 0.85rem; background: var(--bg-soft); border: 1px solid var(--border); border-radius: 6px; padding: 0.1rem 0.4rem; }
.job ul { margin-top: 0.6rem; padding-left: 1.25rem; list-style: disc; display: grid; gap: 0.3rem; }

/* projects */
.chips { display: flex; gap: 0.5rem; flex-wrap: wrap; margin-bottom: 1.25rem; }
.chip { font: inherit; font-size: 0.9rem; padding: 0.3rem 0.9rem; border-radius: 999px; border: 1px solid var(--border); background: var(--bg-soft); color: var(--text); cursor: pointer; }
.chip:hover { border-color: var(--muted); }
.chip[aria-pressed="true"] { background: var(--link); border-color: var(--link); color: var(--link-ink); }
.grid { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 1rem; }
.card { border: 1px solid var(--border); background: var(--bg-soft); border-radius: 8px; padding: 1.25rem; display: flex; flex-direction: column; }
.card.wide { grid-column: 1 / -1; }
.card h3 { margin: 0; font-size: 1.2rem; line-height: 1.3; }
.card .kind { font-weight: 700; margin-top: 0.6rem; }
.card .desc { margin-top: 0.3rem; color: var(--muted); }
.card .feat { margin-top: 0.9rem; display: grid; gap: 0.3rem; }
.card .feat li { display: grid; grid-template-columns: 1.6rem minmax(0, 1fr); }
.card .badges { margin-top: 1rem; }
.card .foot { margin-top: auto; padding-top: 1.1rem; display: flex; align-items: center; gap: 0.75rem; flex-wrap: wrap; }
.note { color: var(--muted); font-size: 0.88rem; margin-top: 0.5rem; }

/* goals box */
.goals { border: 1px solid var(--border); background: var(--bg-soft); border-radius: 8px; padding: 1.1rem 1.4rem; font-family: var(--mono); font-size: 0.92rem; display: grid; gap: 0.7rem; }
.goals li { display: grid; grid-template-columns: 1.9rem minmax(0, 1fr); }

/* connect */
.connect { text-align: center; }
.connect .badges { justify-content: center; margin-top: 1.1rem; }
.connect .lead { color: var(--muted); }
.connect h3 { margin: 1.1rem 0 0; font-size: 1.2rem; }
.connect .copyrow { margin-top: 1rem; display: flex; flex-wrap: wrap; gap: 0.6rem; justify-content: center; }
button.copy { font: inherit; font-size: 0.85rem; padding: 0.4rem 0.9rem; border-radius: 6px; border: 1px solid var(--border); background: var(--bg-soft); color: var(--text); cursor: pointer; min-width: 9.5rem; }
button.copy:hover { border-color: var(--muted); }
footer { text-align: center; padding: 2.5rem 0 3rem; color: var(--muted); }
footer em { display: block; margin-bottom: 0.4rem; font-size: 1.05rem; color: var(--text); }

@media (max-width: 640px) {
  .grid { grid-template-columns: minmax(0, 1fr); }
  .bar .wrap { justify-content: center; }
}
@media (prefers-reduced-motion: reduce) { html { scroll-behavior: auto; } }
</style>
</head>
<body>

<div class="bar">
  <div class="wrap">
    <nav aria-label="Main">
      <a href="#about">About</a>
      <a href="#stack">Tech stack</a>
      <a href="#experience">Experience</a>
      <a href="#projects">Projects</a>
      <a href="#connect">Contact</a>
    </nav>
    <button type="button" class="themebtn" id="themebtn">Dark mode</button>
  </div>
</div>

<main class="wrap">

  <header class="hero" id="top">
    <h1><span aria-hidden="true">👋</span> Hi, I'm Purushottam Kudale</h1>
    <h2><span aria-hidden="true">🚀</span> Java Full-Stack Developer | Software Development Engineer</h2>
    <p class="typed" id="typed">Open to roles in Bengaluru, Pune, Hyderabad and remote</p>
    <div class="badges">
      <a class="badge lg" style="--c:#0A66C2" href="https://www.linkedin.com/in/purushottam-kudale/">LinkedIn</a>
      <a class="badge lg" style="--c:#D93025" href="mailto:purushottamkudale0@gmail.com">Email</a>
      <a class="badge lg" style="--c:#181717" href="https://github.com/purushottamkudale">GitHub</a>
      <a class="badge lg" style="--c:#1A7F37" href="tel:+919036836362">Call</a>
      <a class="badge lg" style="--c:var(--link);--t:var(--link-ink)" href="Purushottam_Kudale_Resume.pdf" download>Resume</a>
    </div>
  </header>

  <section class="sec about" id="about">
    <h2 class="sh"><span aria-hidden="true">👨‍💻</span> About me</h2>
    <p>I'm a <strong>Java Full-Stack Developer</strong> and engineering graduate who likes building scalable, user-focused software.</p>
    <p>I enjoy working across the full development lifecycle, from designing REST APIs and backend services to building responsive React interfaces and managing databases.</p>
    <ul class="emojilist">
      <li><span aria-hidden="true">🎓</span><span><strong>B.E. in Information Science and Engineering</strong>, SDM Institute of Technology, Ujire (CGPA 7.46)</span></li>
      <li><span aria-hidden="true">💻</span><span>Strong foundation in <strong>Java, Spring Boot, REST APIs, React.js, Node.js and SQL</strong></span></li>
      <li><span aria-hidden="true">🌐</span><span>Experience building <strong>full-stack web applications</strong></span></li>
      <li><span aria-hidden="true">📊</span><span>Data analytics with <strong>Python, Pandas, NumPy, Excel, SQL and Power BI</strong></span></li>
      <li><span aria-hidden="true">🤖</span><span>Interested in <strong>AI-assisted software development and prompt engineering</strong></span></li>
      <li><span aria-hidden="true">🐳</span><span>Currently strengthening my <strong>Linux, Docker and DevOps</strong> skills</span></li>
      <li><span aria-hidden="true">🔧</span><span>Comfortable with <strong>Git, GitHub, Maven, MySQL and MongoDB</strong></span></li>
      <li><span aria-hidden="true">🎯</span><span>Open to <strong>Java Full-Stack Developer and SDE</strong> opportunities</span></li>
      <li><span aria-hidden="true">📍</span><span>Interested in <strong>Bengaluru, Pune, Hyderabad and remote</strong> roles</span></li>
    </ul>
  </section>

  <section class="sec" id="stack">
    <h2 class="sh"><span aria-hidden="true">🛠️</span> Tech stack</h2>

    <h3 class="sub"><span aria-hidden="true">💻</span> Languages</h3>
    <div class="badges">
      <span class="badge" style="--c:#ED8B00;--t:#000">Java</span>
      <span class="badge" style="--c:#F7DF1E;--t:#000">JavaScript</span>
      <span class="badge" style="--c:#3776AB">Python</span>
      <span class="badge" style="--c:#4479A1">SQL</span>
    </div>

    <h3 class="sub"><span aria-hidden="true">⚙️</span> Backend</h3>
    <div class="badges">
      <span class="badge" style="--c:#6DB33F;--t:#000">Spring Boot</span>
      <span class="badge" style="--c:#6DB33F;--t:#000">Spring Core</span>
      <span class="badge" style="--c:#6DB33F;--t:#000">Spring Security</span>
      <span class="badge" style="--c:#6DB33F;--t:#000">Spring Data JPA</span>
      <span class="badge" style="--c:#59666C">Hibernate</span>
      <span class="badge" style="--c:#339933">Node.js</span>
      <span class="badge" style="--c:#000000">Express.js</span>
      <span class="badge" style="--c:#007396">JSP</span>
      <span class="badge" style="--c:#007396">Servlets</span>
    </div>

    <h3 class="sub"><span aria-hidden="true">🎨</span> Frontend</h3>
    <div class="badges">
      <span class="badge" style="--c:#20232A;--t:#61DAFB">React.js</span>
      <span class="badge" style="--c:#E34F26;--t:#000">HTML5</span>
      <span class="badge" style="--c:#1572B6">CSS3</span>
      <span class="badge" style="--c:#06B6D4;--t:#000">Tailwind CSS</span>
      <span class="badge" style="--c:#7952B3">Bootstrap</span>
      <span class="badge" style="--c:#005F0F">Thymeleaf</span>
    </div>

    <h3 class="sub"><span aria-hidden="true">🗄️</span> Databases</h3>
    <div class="badges">
      <span class="badge" style="--c:#4479A1">MySQL</span>
      <span class="badge" style="--c:#47A248;--t:#000">MongoDB</span>
    </div>

    <h3 class="sub"><span aria-hidden="true">📊</span> Data and analytics</h3>
    <div class="badges">
      <span class="badge" style="--c:#217346">Excel</span>
      <span class="badge" style="--c:#150458">Pandas</span>
      <span class="badge" style="--c:#4D77CF">NumPy</span>
      <span class="badge" style="--c:#11557C">Matplotlib</span>
      <span class="badge" style="--c:#4C72B0">Seaborn</span>
      <span class="badge" style="--c:#F2C811;--t:#000">Power BI</span>
    </div>

    <h3 class="sub"><span aria-hidden="true">🚀</span> Tools and DevOps</h3>
    <div class="badges">
      <span class="badge" style="--c:#F05032;--t:#000">Git</span>
      <span class="badge" style="--c:#181717">GitHub</span>
      <span class="badge" style="--c:#C71A36">Maven</span>
      <span class="badge" style="--c:#2496ED;--t:#000">Docker</span>
      <span class="badge" style="--c:#FCC624;--t:#000">Linux</span>
      <span class="badge" style="--c:#2088FF;--t:#000">GitHub Actions</span>
    </div>

    <h3 class="sub"><span aria-hidden="true">🤖</span> AI development tools</h3>
    <div class="badges">
      <span class="badge" style="--c:#000000">GitHub Copilot</span>
      <span class="badge" style="--c:#D97757;--t:#000">Claude</span>
    </div>
  </section>

  <section class="sec" id="experience">
    <h2 class="sh"><span aria-hidden="true">💼</span> Experience</h2>

    <div class="job">
      <h3><span aria-hidden="true">🟣</span> Data Analytics Intern</h3>
      <p class="org">UV Technocrafts</p>
      <code class="date">Jun 2026 – Sep 2026</code>
      <ul>
        <li>Cleaned and prepared raw datasets using <strong>Excel and Pandas</strong>, fixing missing values, duplicates and inconsistent formats</li>
        <li>Performed exploratory data analysis with <strong>Python, Pandas and NumPy</strong> to find trends, patterns and outliers</li>
        <li>Built charts and visual reports with <strong>Matplotlib and Seaborn</strong> to present findings clearly</li>
        <li>Used <strong>Excel</strong> formulas, pivot tables and summary sheets for reporting and quick analysis</li>
        <li>Turned analysis results into clear summaries and data-backed recommendations for the team</li>
      </ul>
    </div>

    <div class="job">
      <h3><span aria-hidden="true">🟢</span> Java Full-Stack Development Intern</h3>
      <p class="org">Pentagon Space</p>
      <code class="date">Feb 2025 – Nov 2025</code>
      <ul>
        <li>Developed responsive web modules using <strong>Java, Spring Boot, JSP, Servlets and MySQL</strong></li>
        <li>Built reusable frontend components using <strong>React.js, HTML5 and Tailwind CSS</strong></li>
        <li>Worked with <strong>RESTful APIs and database-driven applications</strong></li>
        <li>Used <strong>Git and GitHub</strong> for source control, collaboration and pull requests</li>
        <li>Followed <strong>Agile/Scrum</strong> development practices</li>
        <li>Used AI-assisted development workflows for debugging and code optimization</li>
      </ul>
    </div>

    <div class="job">
      <h3><span aria-hidden="true">🔵</span> Full Stack Web Development Intern</h3>
      <p class="org">Edureka</p>
      <code class="date">Oct 2023 – Nov 2023</code>
      <ul>
        <li>Developed an <strong>Employee Database Management System</strong></li>
        <li>Applied SQL, RDBMS, normalization, joins, indexing and relational database concepts</li>
        <li>Created responsive interfaces using <strong>HTML5, CSS3 and JavaScript</strong></li>
        <li>Worked with multi-table SQL queries for data retrieval and reporting</li>
      </ul>
    </div>
  </section>

  <section class="sec" id="projects">
    <h2 class="sh"><span aria-hidden="true">🚀</span> Featured projects</h2>

    <div class="chips" role="group" aria-label="Filter projects">
      <button type="button" class="chip" data-filter="all" aria-pressed="true">All</button>
      <button type="button" class="chip" data-filter="java" aria-pressed="false">Java and Spring</button>
      <button type="button" class="chip" data-filter="data" aria-pressed="false">Data</button>
      <button type="button" class="chip" data-filter="mern" aria-pressed="false">MERN</button>
      <button type="button" class="chip" data-filter="php" aria-pressed="false">PHP</button>
    </div>

    <div class="grid">
      <article class="card wide" data-tags="java">
        <h3><span aria-hidden="true">💼</span> Job Portal</h3>
        <p class="kind">Spring Boot and React</p>
        <p class="desc">A recruitment platform with three roles. Candidates search jobs and apply with a resume, recruiters post jobs and manage applicants, and admins oversee users and postings.</p>
        <ul class="feat">
          <li><span aria-hidden="true">🔐</span><span>JWT authentication, BCrypt hashing and role-based endpoint access</span></li>
          <li><span aria-hidden="true">🔎</span><span>Job search by keyword, location, job type and minimum salary</span></li>
          <li><span aria-hidden="true">📄</span><span>Resume upload and applicant status updates</span></li>
          <li><span aria-hidden="true">📧</span><span>Email notifications you can switch on in configuration</span></li>
        </ul>
        <div class="badges">
          <span class="badge" style="--c:#ED8B00;--t:#000">Java 17</span>
          <span class="badge" style="--c:#6DB33F;--t:#000">Spring Boot 3</span>
          <span class="badge" style="--c:#6DB33F;--t:#000">Spring Security</span>
          <span class="badge" style="--c:#4479A1">MySQL</span>
          <span class="badge" style="--c:#20232A;--t:#61DAFB">React 18</span>
        </div>
        <div class="foot"><a class="badge lg" style="--c:#181717" href="https://github.com/purushottamkudale/Job-Portal-using-SpringBoot">View project</a></div>
      </article>

      <article class="card" data-tags="java">
        <h3><span aria-hidden="true">🎉</span> IGNITE '26 event website</h3>
        <p class="kind">Spring Boot and Thymeleaf</p>
        <p class="desc">A college fest site rendered by Spring Boot, with content served from MySQL.</p>
        <ul class="feat">
          <li><span aria-hidden="true">🗓️</span><span>Schedule, speakers, FAQ and gallery come from the database</span></li>
          <li><span aria-hidden="true">✅</span><span>Registration with Bean Validation and a duplicate-email check</span></li>
          <li><span aria-hidden="true">🌱</span><span>Database seeded with fest content on first run</span></li>
        </ul>
        <div class="badges">
          <span class="badge" style="--c:#ED8B00;--t:#000">Java 17</span>
          <span class="badge" style="--c:#6DB33F;--t:#000">Spring Boot 3.3</span>
          <span class="badge" style="--c:#005F0F">Thymeleaf</span>
          <span class="badge" style="--c:#4479A1">MySQL</span>
        </div>
        <div class="foot"><a class="badge lg" style="--c:#181717" href="https://github.com/purushottamkudale/Campus-Coneect-using-SpringBoot">View project</a></div>
      </article>

      <article class="card" data-tags="data">
        <h3><span aria-hidden="true">📊</span> E-commerce sales analytics</h3>
        <p class="kind">Python, SQL and Power BI</p>
        <p class="desc">Analysis of 10,000 synthetic orders from 2025.</p>
        <ul class="feat">
          <li><span aria-hidden="true">📈</span><span>Revenue trends, category and region performance, top customers</span></li>
          <li><span aria-hidden="true">🧮</span><span>Ten SQL queries, including window functions and month-over-month growth</span></li>
          <li><span aria-hidden="true">🐍</span><span>Pandas analysis script and Jupyter notebook</span></li>
          <li><span aria-hidden="true">📉</span><span>Power BI dashboard layout guide</span></li>
        </ul>
        <p class="note">The dataset is synthetic and made for learning.</p>
        <div class="badges">
          <span class="badge" style="--c:#3776AB">Python</span>
          <span class="badge" style="--c:#150458">Pandas</span>
          <span class="badge" style="--c:#4479A1">MySQL</span>
          <span class="badge" style="--c:#F2C811;--t:#000">Power BI</span>
        </div>
        <div class="foot"><a class="badge lg" style="--c:#181717" href="https://github.com/purushottamkudale/Ecommerce-Sales-Analytics">View project</a></div>
      </article>

      <article class="card" data-tags="mern">
        <h3><span aria-hidden="true">🎓</span> Campus Connect</h3>
        <p class="kind">MERN stack</p>
        <p class="desc">A full-stack campus platform designed to connect students and simplify campus activities.</p>
        <ul class="feat">
          <li><span aria-hidden="true">📅</span><span>Event scheduling</span></li>
          <li><span aria-hidden="true">🔔</span><span>Notifications</span></li>
          <li><span aria-hidden="true">💬</span><span>Discussion forums</span></li>
          <li><span aria-hidden="true">📊</span><span>Dynamic React dashboard</span></li>
          <li><span aria-hidden="true">🔐</span><span>User authentication</span></li>
        </ul>
        <div class="badges">
          <span class="badge" style="--c:#47A248;--t:#000">MongoDB</span>
          <span class="badge" style="--c:#000000">Express.js</span>
          <span class="badge" style="--c:#20232A;--t:#61DAFB">React.js</span>
          <span class="badge" style="--c:#339933">Node.js</span>
        </div>
        <div class="foot"><a class="badge lg" style="--c:#181717" href="https://github.com/purushottamkudale/Campus-Connect-using-MERN-Stack">View project</a></div>
      </article>

      <article class="card" data-tags="php">
        <h3><span aria-hidden="true">🏋️</span> Gym management system</h3>
        <p class="kind">PHP and MySQL</p>
        <p class="desc">A web-based system for managing gym operations and memberships.</p>
        <ul class="feat">
          <li><span aria-hidden="true">👤</span><span>Separate admin and user registration and login</span></li>
          <li><span aria-hidden="true">📋</span><span>Membership management</span></li>
          <li><span aria-hidden="true">🗄️</span><span>MySQL-backed relational data</span></li>
        </ul>
        <div class="badges">
          <span class="badge" style="--c:#777BB4">PHP</span>
          <span class="badge" style="--c:#4479A1">MySQL</span>
          <span class="badge" style="--c:#F7DF1E;--t:#000">JavaScript</span>
          <span class="badge" style="--c:#1572B6">CSS3</span>
        </div>
        <div class="foot"><a class="badge lg" style="--c:#181717" href="https://github.com/purushottamkudale/GYM-management-System">View project</a></div>
      </article>
    </div>
  </section>

  <section class="sec" id="goals">
    <h2 class="sh"><span aria-hidden="true">🎯</span> Career goals</h2>
    <ul class="goals">
      <li><span aria-hidden="true">🚀</span><span>Build scalable, production-ready applications</span></li>
      <li><span aria-hidden="true">☕</span><span>Become an expert Java and Spring Boot developer</span></li>
      <li><span aria-hidden="true">⚛️</span><span>Build modern full-stack applications</span></li>
      <li><span aria-hidden="true">🐳</span><span>Master Docker, CI/CD and DevOps</span></li>
      <li><span aria-hidden="true">☁️</span><span>Expand my cloud and AWS knowledge</span></li>
      <li><span aria-hidden="true">🤖</span><span>Integrate AI into modern software development</span></li>
    </ul>
  </section>

  <section class="sec connect" id="connect">
    <h2 class="sh"><span aria-hidden="true">🤝</span> Let's connect</h2>
    <p class="lead">I'm always interested in connecting with developers, recruiters and technology enthusiasts.</p>
    <h3><span aria-hidden="true">💼</span> Open to Java Full-Stack and SDE opportunities</h3>
    <div class="badges">
      <a class="badge lg" style="--c:#D93025" href="mailto:purushottamkudale0@gmail.com">purushottamkudale0@gmail.com</a>
      <a class="badge lg" style="--c:#1A7F37" href="tel:+919036836362">+91 90368 36362</a>
    </div>
    <div class="badges">
      <a class="badge lg" style="--c:#0A66C2" href="https://www.linkedin.com/in/purushottam-kudale/">LinkedIn: Purushottam Kudale</a>
      <a class="badge lg" style="--c:#181717" href="https://github.com/purushottamkudale">GitHub: purushottamkudale</a>
    </div>
    <div class="copyrow">
      <button type="button" class="copy" data-copy="purushottamkudale0@gmail.com">Copy email</button>
      <button type="button" class="copy" data-copy="+91 90368 36362">Copy phone</button>
    </div>
    <p class="sr" id="live" role="status" aria-live="polite"></p>
  </section>

</main>

<footer>
  <em>Code. Learn. Build. Repeat.</em>
  <div>&copy; 2026 Purushottam Kudale</div>
</footer>

<script>
(function () {
  var reduced = window.matchMedia("(prefers-reduced-motion: reduce)").matches;
  var root = document.documentElement;

  /* typed intro: cycles through phrases and rests on final location line */
  var typed = document.getElementById("typed");
  var lines = [
    "Building REST APIs with Spring Boot",
    "Building React interfaces",
    "Learning Docker and CI/CD",
    "Open to roles in Bengaluru, Pune, Hyderabad and remote"
  ];
  if (!reduced && typed) {
    var li = 0, ci = 0, deleting = false;
    var tick = function () {
      var full = lines[li];
      if (!deleting) {
        ci += 1;
        typed.textContent = full.slice(0, ci);
        if (ci === full.length) {
          if (li === lines.length - 1) return;
          deleting = true;
          return setTimeout(tick, 1400);
        }
        return setTimeout(tick, 40);
      }
      ci -= 1;
      typed.textContent = full.slice(0, ci);
      if (ci === 0) { 
        deleting = false; 
        li += 1; 
        return setTimeout(tick, 250); 
      }
      setTimeout(tick, 18);
    };
    typed.textContent = "";
    tick();
  }

  /* project filter */
  var chips = document.querySelectorAll(".chip");
  var cards = document.querySelectorAll(".card");
  chips.forEach(function (chip) {
    chip.addEventListener("click", function () {
      var f = chip.getAttribute("data-filter");
      chips.forEach(function (c) { c.setAttribute("aria-pressed", c === chip ? "true" : "false"); });
      var visibleCount = 0;
      cards.forEach(function (card) {
        var tags = (card.getAttribute("data-tags") || "").split(" ");
        var show = f === "all" || tags.indexOf(f) !== -1;
        card.hidden = !show;
        
        /* Reset wide status initially */
        card.classList.remove("wide");
        if (show) visibleCount++;
      });
      
      /* Make top project wide if showing all */
      if (f === "all" && cards.length > 0) {
        cards[0].classList.add("wide");
      }
    });
  });

  /* copy buttons */
  var live = document.getElementById("live");
  function copyText(text) {
    if (navigator.clipboard && window.isSecureContext) {
      return navigator.clipboard.writeText(text);
    }
    return new Promise(function (resolve, reject) {
      var ta = document.createElement("textarea");
      ta.value = text; 
      ta.style.position = "fixed"; 
      ta.style.opacity = "0";
      document.body.appendChild(ta); 
      ta.select();
      try { 
        document.execCommand("copy") ? resolve() : reject(); 
      } catch (e) { 
        reject(e); 
      }
      document.body.removeChild(ta);
    });
  }

  document.querySelectorAll("button.copy").forEach(function (btn) {
    var label = btn.textContent;
    btn.addEventListener("click", function () {
      copyText(btn.getAttribute("data-copy")).then(function () {
        btn.textContent = "Copied";
        if (live) live.textContent = "Copied to clipboard";
      }, function () {
        btn.textContent = "Press Ctrl+C";
      });
      setTimeout(function () { 
        btn.textContent = label; 
        if (live) live.textContent = ""; 
      }, 1600);
    });
  });

  /* theme toggle */
  var themeBtn = document.getElementById("themebtn");
  function effectiveTheme() {
    var t = root.getAttribute("data-theme");
    if (t) return t;
    return window.matchMedia("(prefers-color-scheme: dark)").matches ? "dark" : "light";
  }
  function syncLabel() { 
    if (themeBtn) themeBtn.textContent = effectiveTheme() === "dark" ? "Light mode" : "Dark mode"; 
  }
  if (themeBtn) {
    themeBtn.addEventListener("click", function () {
      var next = effectiveTheme() === "dark" ? "light" : "dark";
      root.setAttribute("data-theme", next);
      try { localStorage.setItem("theme", next); } catch (e) {}
      syncLabel();
    });
  }
  syncLabel();
})();
</script>
</body>
</html>
