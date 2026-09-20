<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Purushottam Kudale | Java Full-Stack Developer</title>
<meta name="description" content="Purushottam Kudale - Java Full-Stack Developer & SDE. GitHub Portfolio layout.">
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
  --font: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif;
  --mono: ui-monospace, SFMono-Regular, "SF Mono", Menlo, Consolas, monospace;
}
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg: #0D1117; --bg-soft: #151B23; --text: #E6EDF3; --muted: #9198A1; --border: #3D444D; --link: #4493F8;
  }
}
:root[data-theme="dark"] {
  --bg: #0D1117; --bg-soft: #151B23; --text: #E6EDF3; --muted: #9198A1; --border: #3D444D; --link: #4493F8;
}
*, *::before, *::after { box-sizing: border-box; }
html { scroll-behavior: smooth; scroll-padding-top: 4rem; }
body { margin: 0; background: var(--bg); color: var(--text); font-family: var(--font); font-size: 1rem; line-height: 1.6; -webkit-font-smoothing: antialiased; }
a { color: var(--link); }
:focus-visible { outline: 3px solid var(--link); outline-offset: 2px; border-radius: 4px; }
.wrap { max-width: 54rem; margin: 0 auto; padding: 0 1.25rem; }
p { margin: 0; }
ul { margin: 0; padding: 0; list-style: none; }
hr { border: 0; border-top: 1px solid var(--border); margin: 2rem 0; }
.text-center { text-align: center; }

/* top bar */
.bar { border-bottom: 1px solid var(--border); background: var(--bg); position: sticky; top: 0; z-index: 5; }
.bar .wrap { display: flex; align-items: center; justify-content: space-between; gap: 1rem; min-height: 3.25rem; flex-wrap: wrap; padding-top: 0.4rem; padding-bottom: 0.4rem; }
.bar nav { display: flex; gap: 1.1rem; flex-wrap: wrap; align-items: center; font-size: 0.95rem; }
.bar nav a { color: var(--muted); text-decoration: none; }
.bar nav a:hover { color: var(--text); text-decoration: underline; }
.themebtn { font: inherit; font-size: 0.9rem; color: var(--text); background: var(--bg-soft); border: 1px solid var(--border); border-radius: 6px; padding: 0.25rem 0.75rem; cursor: pointer; }
.themebtn:hover { border-color: var(--muted); }

/* hero */
.hero { text-align: center; padding: 2.5rem 0 1rem; }
.hero h1 { font-size: clamp(1.8rem, 4.5vw, 2.5rem); margin: 0 0 0.5rem; line-height: 1.2; }
.hero h3 { color: var(--muted); font-size: 1.2rem; font-weight: 500; margin: 0 0 1.2rem; }
.badge-group { display: flex; flex-wrap: wrap; gap: 0.4rem; justify-content: center; margin-top: 0.5rem; margin-bottom: 1rem; }
.badge-group img { vertical-align: middle; height: 28px; }

/* sections */
section.sec { padding-top: 1rem; }
h2.sh { font-size: 1.4rem; margin: 0 0 1rem; line-height: 1.25; }
h3.sub { font-size: 1.1rem; margin: 1.2rem 0 0.5rem; font-weight: 600; }
.about p { margin-bottom: 0.9rem; }
.emojilist { display: grid; gap: 0.45rem; margin-top: 0.5rem; }
.emojilist li { display: grid; grid-template-columns: 1.75rem minmax(0, 1fr); }

/* experience */
.job { margin-top: 1.4rem; }
.job h3 { font-size: 1.15rem; margin: 0; line-height: 1.3; }
.job .org { font-weight: 700; margin-top: 0.2rem; }
code.date { font-family: var(--mono); font-size: 0.85rem; background: var(--bg-soft); border: 1px solid var(--border); border-radius: 6px; padding: 0.1rem 0.4rem; }
.job ul { margin-top: 0.6rem; padding-left: 1.25rem; list-style: disc; display: grid; gap: 0.3rem; }

/* project table matching Markdown table */
.project-table { width: 100%; border-collapse: collapse; margin-top: 1rem; }
.project-table td { border: 1px solid var(--border); padding: 1.2rem; vertical-align: top; background: var(--bg-soft); }
.project-table h3 { margin: 0 0 0.4rem; font-size: 1.15rem; }
.project-table .tech { font-weight: 600; margin-bottom: 0.6rem; color: var(--muted); }
.project-table .feat { list-style: none; padding: 0; margin: 0.8rem 0; display: grid; gap: 0.3rem; }
.project-table .feat li { display: grid; grid-template-columns: 1.5rem minmax(0, 1fr); }
.code-inline { font-family: var(--mono); background: var(--bg); border: 1px solid var(--border); padding: 0.15rem 0.4rem; border-radius: 4px; font-size: 0.85rem; display: inline-block; margin: 0.2rem 0.1rem; }

/* ascii box */
pre.ascii-box { background: var(--bg-soft); border: 1px solid var(--border); border-radius: 6px; padding: 1rem; font-family: var(--mono); font-size: 0.85rem; line-height: 1.4; overflow-x: auto; color: var(--text); }

footer { text-align: center; padding: 2rem 0 3rem; color: var(--muted); }
footer h3 { margin: 0 0 0.4rem; color: var(--text); }

@media (max-width: 640px) {
  .project-table, .project-table tbody, .project-table tr, .project-table td { display: block; width: 100%; }
  .project-table td[colspan="2"] { width: 100%; }
}
</style>
</head>
<body>

<div class="bar">
  <div class="wrap">
    <nav aria-label="Main">
      <a href="#about">About Me</a>
      <a href="#stack">Tech Stack</a>
      <a href="#experience">Experience</a>
      <a href="#projects">Projects</a>
      <a href="#goals">Career Goals</a>
      <a href="#connect">Connect</a>
    </nav>
    <button type="button" class="themebtn" id="themebtn">Dark mode</button>
  </div>
</div>

<main class="wrap">

  <header class="hero" id="top">
    <h1>👋 Hi, I'm <strong>Purushottam Kudale</strong></h1>
    <h3>🚀 Java Full-Stack Developer | Software Development Engineer</h3>
    
    <div class="badge-group">
      <a href="https://www.linkedin.com/in/purushottam-kudale/" target="_blank" rel="noopener">
        <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
      </a>
      <a href="mailto:purushottamkudale0@gmail.com">
        <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
      </a>
      <a href="https://github.com/purushottamkudale" target="_blank" rel="noopener">
        <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
      </a>
    </div>
  </header>

  <hr />

  <section class="sec about" id="about">
    <h2 class="sh">👨‍💻 About Me</h2>
    <p>I'm a <strong>Java Full-Stack Developer</strong> and Computer Science engineering graduate passionate about building scalable, user-focused software applications.</p>
    <p>I enjoy working across the complete development lifecycle — from designing REST APIs and backend services to building responsive React interfaces and managing databases.</p>
    
    <ul class="emojilist">
      <li><span>🎓</span><span><strong>B.E. in Information Science & Engineering</strong> — SDM Institute of Technology, Ujire</span></li>
      <li><span>💻</span><span>Strong foundation in <strong>Java, Spring Boot, REST APIs, React.js, Node.js, and SQL</strong></span></li>
      <li><span>🌐</span><span>Experience building <strong>full-stack web applications</strong></span></li>
      <li><span>🤖</span><span>Interested in <strong>AI-assisted software development and prompt engineering</strong></span></li>
      <li><span>🐳</span><span>Currently strengthening my <strong>Linux, Docker & DevOps</strong> skills</span></li>
      <li><span>🔧</span><span>Comfortable with <strong>Git, GitHub, Maven, MySQL & MongoDB</strong></span></li>
      <li><span>🎯</span><span>Open to <strong>Java Full-Stack Developer / SDE opportunities</strong></span></li>
      <li><span>📍</span><span>Interested in opportunities in <strong>Bengaluru, Pune, Hyderabad & Remote</strong></span></li>
    </ul>
  </section>

  <hr />

  <section class="sec" id="stack">
    <h2 class="sh">🛠️ Tech Stack</h2>

    <h3 class="sub">💻 Languages</h3>
    <div class="badge-group" style="justify-content: flex-start;">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
    </div>

    <h3 class="sub">⚙️ Backend</h3>
    <div class="badge-group" style="justify-content: flex-start;">
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
      <img src="https://img.shields.io/badge/Spring%20Core-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Core" />
      <img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Data JPA" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
      <img src="https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white" alt="JSP" />
      <img src="https://img.shields.io/badge/Servlets-007396?style=for-the-badge&logo=java&logoColor=white" alt="Servlets" />
    </div>

    <h3 class="sub">🎨 Frontend</h3>
    <div class="badge-group" style="justify-content: flex-start;">
      <img src="https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React.js" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
      <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
    </div>

    <h3 class="sub">🗄️ Databases</h3>
    <div class="badge-group" style="justify-content: flex-start;">
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    </div>

    <h3 class="sub">🚀 Tools & DevOps</h3>
    <div class="badge-group" style="justify-content: flex-start;">
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
      <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
    </div>

    <h3 class="sub">🤖 AI Development Tools</h3>
    <div class="badge-group" style="justify-content: flex-start;">
      <img src="https://img.shields.io/badge/GitHub%20Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white" alt="GitHub Copilot" />
      <img src="https://img.shields.io/badge/Claude%20AI-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude AI" />
    </div>
  </section>

  <hr />

  <section class="sec" id="experience">
    <h2 class="sh">💼 Experience</h2>

    <div class="job">
      <h3>🟢 Java Full-Stack Development Intern</h3>
      <p class="org">Pentagon Space</p>
      <code class="date">Feb 2025 – Nov 2025</code>
      <ul>
        <li>Developed responsive web modules using <strong>Java, Spring Boot, JSP, Servlets, and MySQL</strong></li>
        <li>Built reusable frontend components using <strong>React.js, HTML5, and Tailwind CSS</strong></li>
        <li>Worked with <strong>RESTful APIs and database-driven applications</strong></li>
        <li>Used <strong>Git & GitHub</strong> for source control, collaboration, and pull requests</li>
        <li>Followed <strong>Agile/Scrum</strong> development practices</li>
        <li>Used AI-assisted development workflows for debugging and code optimization</li>
      </ul>
    </div>

    <div class="job">
      <h3>🔵 Full Stack Web Development Intern</h3>
      <p class="org">Edureka</p>
      <code class="date">Oct 2023 – Nov 2023</code>
      <ul>
        <li>Developed an <strong>Employee Database Management System</strong></li>
        <li>Applied SQL, RDBMS, normalization, joins, indexing, and relational database concepts</li>
        <li>Created responsive interfaces using <strong>HTML5, CSS3, and JavaScript</strong></li>
        <li>Worked with multi-table SQL queries for data retrieval and reporting</li>
      </ul>
    </div>
  </section>

  <hr />

  <section class="sec" id="projects">
    <h2 class="sh">🚀 Featured Projects</h2>

    <table class="project-table">
      <tr>
        <td width="50%">
          <h3>🎓 Campus Connect</h3>
          <p class="tech">MERN Stack</p>
          <p>A full-stack campus platform designed to connect students and simplify campus activities.</p>
          
          <p style="margin-top:0.6rem; font-weight:bold;">Features</p>
          <ul class="feat">
            <li><span>📅</span><span>Event scheduling</span></li>
            <li><span>🔔</span><span>Notifications</span></li>
            <li><span>💬</span><span>Discussion forums</span></li>
            <li><span>📊</span><span>Dynamic React dashboard</span></li>
            <li><span>🔐</span><span>User authentication</span></li>
          </ul>

          <p><strong>Tech:</strong> MongoDB · Express.js · React.js · Node.js</p>

          <p style="margin-top: 1rem;">
            <a href="https://github.com/purushottamkudale/Campus-Connect" target="_blank" rel="noopener">
              <img src="https://img.shields.io/badge/View%20Project-181717?style=for-the-badge&logo=github&logoColor=white" alt="View Project" />
            </a>
          </p>
        </td>

        <td width="50%">
          <h3>🏋️ Gym Management System</h3>
          <p class="tech">PHP · MySQL · Bootstrap</p>
          <p>A web-based system for managing gym operations and member information.</p>
          
          <p style="margin-top:0.6rem; font-weight:bold;">Features</p>
          <ul class="feat">
            <li><span>👤</span><span>Member management</span></li>
            <li><span>💳</span><span>Payment tracking</span></li>
            <li><span>📋</span><span>Membership lifecycle</span></li>
            <li><span>🗄️</span><span>Relational database design</span></li>
            <li><span>🔐</span><span>Secure data handling</span></li>
          </ul>

          <p><strong>Tech:</strong> PHP · MySQL · Bootstrap · CSS</p>

          <p style="margin-top: 1rem;">
            <a href="https://github.com/purushottamkudale/GYM-management-System" target="_blank" rel="noopener">
              <img src="https://img.shields.io/badge/View%20Project-181717?style=for-the-badge&logo=github&logoColor=white" alt="View Project" />
            </a>
          </p>
        </td>
      </tr>

      <tr>
        <td colspan="2">
          <h3>☕ Spring Boot Enterprise Applications</h3>
          <p class="tech">Java · Spring Boot · Spring Core · Spring Data JPA · Maven</p>
          <p>Developed enterprise-style applications using modern Spring architecture and best practices.</p>
          
          <p style="margin-top: 0.8rem;"><strong>Key Concepts</strong></p>
          <div style="margin-top:0.3rem;">
            <span class="code-inline">IoC</span>
            <span class="code-inline">Dependency Injection</span>
            <span class="code-inline">REST APIs</span>
            <span class="code-inline">JPA</span>
            <span class="code-inline">Hibernate</span>
            <span class="code-inline">Maven</span>
            <span class="code-inline">Annotation-based Configuration</span>
          </div>
        </td>
      </tr>
    </table>
  </section>

  <hr />

  <section class="sec" id="goals">
    <h2 class="sh">🎯 Career Goals</h2>

    <pre class="ascii-box">
┌─────────────────────────────────────────────────────────┐
│                                                         │
│   🚀 Build scalable production-ready applications       │
│                                                         │
│   ☕ Become an expert Java & Spring Boot Developer      │
│                                                         │
│   ⚛️ Build modern full-stack applications               │
│                                                         │
│   🐳 Master Docker, CI/CD & DevOps                      │
│                                                         │
│   ☁️ Expand my Cloud & AWS knowledge                    │
│                                                         │
│   🤖 Integrate AI into modern software development     │
│                                                         │
└─────────────────────────────────────────────────────────┘
    </pre>
  </section>

  <hr />

  <section class="sec text-center" id="connect">
    <h2 class="sh" style="border: 0; margin-bottom: 0.5rem;">🤝 Let's Connect</h2>

    <p style="color: var(--muted); margin-bottom: 1rem;">I'm always interested in connecting with developers, recruiters, and technology enthusiasts.</p>

    <h3>💼 Open to Java Full-Stack / SDE Opportunities</h3>

    <div class="badge-group" style="margin-top: 1.5rem;">
      <a href="mailto:purushottamkudale0@gmail.com">
        <img src="https://img.shields.io/badge/%F0%9F%93%A7%20Email-purushottamkudale0%40gmail.com-EA4335?style=for-the-badge" alt="Email" />
      </a>
      <a href="https://www.linkedin.com/in/purushottam-kudale/" target="_blank" rel="noopener">
        <img src="https://img.shields.io/badge/LinkedIn-Purushottam%20Kudale-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
      </a>
      <a href="https://github.com/purushottamkudale" target="_blank" rel="noopener">
        <img src="https://img.shields.io/badge/GitHub-purushottamkudale-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
      </a>
    </div>

    <p style="margin-top: 1.5rem; font-weight: 600;">⭐ If you find my projects interesting, consider giving them a star!</p>

    <p style="margin-top: 1.5rem;">
      <img src="https://komarev.com/ghpvc/?username=purushottamkudale&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
    </p>
  </section>

  <hr />

</main>

<footer>
  <h3>💻 <em>"Code. Learn. Build. Repeat."</em></h3>
  <div>&copy; 2026 Purushottam Kudale</div>
</footer>

<script>
(function () {
  var root = document.documentElement;
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
    syncLabel();
  }
})();
</script>
</body>
</html>
