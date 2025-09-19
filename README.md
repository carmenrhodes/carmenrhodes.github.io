<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="/Assets/css/custom.css?v=9">

<header class="custom-header full-bleed">
  <nav class="nav-center">
    <a href="/home/" aria-current="page">Home</a>
    <a href="/resume/">Résumé</a>
    <a href="https://github.com/carmenrhodes">GitHub</a>
  </nav>
</header>

<div class="container">

  <div style="display:flex; align-items:center; gap:18px; margin:0 0 18px 0;">
    <img src="/Assets/headshot.jpg" alt="Carmen Rhodes headshot" width="120" style="border-radius:50%; object-fit:cover;">
    <div>
      <p style="margin:0;">
        LaunchCode student learning <strong>Java</strong>, <strong>Spring/Spring Boot</strong>, 
        <strong>JavaScript/React</strong>, <strong>HTML/CSS</strong>, and <strong>MySQL</strong>.<br>
        I’m seeking an entry-level role where I can build, learn fast, and contribute from day one.
      </p>
    </div>
  </div>

  <div class="divider"></div>

  <h2>Skills</h2>
  <div class="tags">
    <span class="tag">Java</span>
    <span class="tag">Spring/Spring Boot</span>
    <span class="tag">JUnit</span>
    <span class="tag">JavaScript/React</span>
    <span class="tag">HTML/CSS</span>
    <span class="tag">MySQL</span>
    <span class="tag">Git/GitHub</span>
  </div>

  <div class="divider"></div>

  <h2>Featured Project — TrackMyStack</h2>
  <div style="background:var(--card); border:1px solid var(--border); border-radius:var(--radius); padding:16px;">
    <img src="/Assets/TrackMyStack.png"
         alt="Screenshot of the TrackMyStack precious-metals inventory app"
         style="width:100%; border-radius:var(--radius); border:1px solid var(--border); margin-bottom:12px;">
    <p>
      TrackMyStack is an inventory app for precious metals. It lets you add, edit, and remove items;
      filter by type or date; and view a streamlined dashboard with total inventory weight and value, quick-add shortcuts,
      and live spot prices.
    </p>
    <p>
      <strong>Live:</strong> <a href="https://trackyourstack.netlify.app/">trackyourstack.netlify.app</a><br>
      <strong>Repo:</strong> <a href="https://github.com/carmenrhodes/LaunchCode-Unit1-Final-Carmen-R">GitHub</a><br>
      <strong>Tech:</strong> JavaScript (React), API integration, HTML, CSS
    </p>
  </div>

  <div class="divider"></div>

  <h2>Connect</h2>
  <div class="quick-actions">
    <a class="btn" href="https://www.linkedin.com/in/carmen-rhodes-a6652214a/">LinkedIn</a>
    <a class="btn" href="https://github.com/carmenrhodes">GitHub</a>
  </div>

  <div class="divider"></div>

</div>

<footer class="custom-footer full-bleed">
  <p>
    © {{ site.time | date: '%Y' }} Carmen Rhodes · 
    <a href="/resume/">Résumé</a> · 
    <a href="https://github.com/carmenrhodes">GitHub</a> · 
    <a href="https://www.linkedin.com/in/carmen-rhodes-a6652214a/">LinkedIn</a>
  </p>
</footer>
