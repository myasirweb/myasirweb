
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:'Segoe UI',system-ui,sans-serif;background:#0d1117;color:#e6edf3}
.wrap{background:#0d1117;min-height:100vh;padding:0}
.hero{background:linear-gradient(135deg,#0f2027 0%,#203a43 50%,#2c5364 100%);padding:48px 32px 40px;text-align:center;position:relative;overflow:hidden}
.hero::before{content:'';position:absolute;top:-60px;right:-60px;width:260px;height:260px;border-radius:50%;background:rgba(88,166,255,0.07)}
.hero::after{content:'';position:absolute;bottom:-40px;left:-40px;width:180px;height:180px;border-radius:50%;background:rgba(88,166,255,0.05)}
.hero-name{font-size:46px;font-weight:700;color:#fff;letter-spacing:-1px;margin-bottom:8px}
.hero-title{font-size:15px;color:#89CFF0;letter-spacing:2px;font-weight:400;margin-bottom:20px;text-transform:uppercase}
.hero-typing{font-family:'Courier New',monospace;font-size:14px;color:#58A6FF;margin-bottom:24px;min-height:22px}
.badges{display:flex;gap:8px;justify-content:center;flex-wrap:wrap}
.badge{padding:7px 16px;border-radius:6px;font-size:12px;font-weight:600;text-decoration:none;display:flex;align-items:center;gap:6px}
.badge-li{background:#0A66C2;color:#fff}
.badge-gm{background:#EA4335;color:#fff}
.badge-po{background:#238636;color:#fff}
.badge-gh{background:#21262d;color:#e6edf3;border:1px solid #30363d}
.section{padding:28px 28px 0}
.sec-title{font-size:13px;font-weight:600;color:#58A6FF;text-transform:uppercase;letter-spacing:1.5px;margin-bottom:18px;display:flex;align-items:center;gap:8px}
.sec-title::after{content:'';flex:1;height:1px;background:linear-gradient(to right,#21262d,transparent)}
.about-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:28px}
.about-item{background:#161b22;border:1px solid #21262d;border-radius:10px;padding:14px 16px;display:flex;align-items:flex-start;gap:10px}
.about-icon{font-size:18px;width:28px;text-align:center;flex-shrink:0;margin-top:1px}
.about-text{font-size:13px;color:#8b949e;line-height:1.5}
.about-text strong{color:#e6edf3;font-weight:600}
.stat-row{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:28px}
.stat-card{background:#161b22;border:1px solid #21262d;border-radius:10px;padding:16px 12px;text-align:center}
.stat-num{font-size:26px;font-weight:700;color:#58A6FF;line-height:1}
.stat-label{font-size:11px;color:#8b949e;margin-top:4px;line-height:1.3}
.skills-grid{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:28px}
.skill-pill{background:#161b22;border:1px solid #30363d;border-radius:20px;padding:5px 13px;font-size:12px;color:#8b949e;display:flex;align-items:center;gap:5px}
.skill-pill.hot{border-color:#58A6FF40;color:#58A6FF;background:#0d2137}
.skill-dot{width:6px;height:6px;border-radius:50%;background:#58A6FF;flex-shrink:0}
.proj-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:28px}
.proj-card{background:#161b22;border:1px solid #21262d;border-radius:10px;padding:16px;transition:border-color 0.2s}
.proj-card:hover{border-color:#58A6FF60}
.proj-name{font-size:14px;font-weight:600;color:#58A6FF;margin-bottom:4px}
.proj-desc{font-size:12px;color:#8b949e;margin-bottom:10px;line-height:1.5}
.proj-tags{display:flex;flex-wrap:wrap;gap:5px}
.tag{background:#0d2137;color:#58A6FF;font-size:10px;padding:2px 8px;border-radius:4px;border:1px solid #58A6FF30}
.note{background:#161b22;border:1px solid #21262d;border-left:3px solid #58A6FF;border-radius:0 8px 8px 0;padding:12px 16px;font-size:13px;color:#8b949e;margin-bottom:28px}
.note span{color:#58A6FF;font-weight:600}
.connect-box{background:linear-gradient(135deg,#0f2027,#203a43);border:1px solid #21262d;border-radius:12px;padding:24px;text-align:center;margin:0 28px 28px}
.connect-title{font-size:16px;font-weight:600;color:#e6edf3;margin-bottom:6px}
.connect-sub{font-size:13px;color:#8b949e;margin-bottom:16px}
.connect-btns{display:flex;gap:8px;justify-content:center;flex-wrap:wrap}
.quote{font-size:13px;color:#8b949e;font-style:italic;margin-top:14px}
.footer-wave{background:linear-gradient(135deg,#2c5364,#203a43,#0f2027);height:60px;border-radius:0 0 8px 8px;display:flex;align-items:center;justify-content:center}
.footer-text{font-size:11px;color:#58A6FF60;letter-spacing:1px}
</style>

<div class="wrap">
  <div class="hero">
    <div class="hero-name">Muhammad Yasir</div>
    <div class="hero-title">Frontend Engineer &nbsp;·&nbsp; React &nbsp;·&nbsp; Next.js &nbsp;·&nbsp; Full Stack MERN</div>
    <div class="hero-typing" id="typing"></div>
    <div class="badges">
      <span class="badge badge-li">🔗 LinkedIn</span>
      <span class="badge badge-gm">✉️ Gmail</span>
      <span class="badge badge-po">🌐 Portfolio</span>
      <span class="badge badge-gh">🐙 GitHub</span>
    </div>
  </div>

  <div class="section">
    <div class="sec-title">About me</div>
    <div class="about-grid">
      <div class="about-item"><div class="about-icon">🚀</div><div class="about-text"><strong>3+ years</strong> building production-grade websites & web apps</div></div>
      <div class="about-item"><div class="about-icon">🌐</div><div class="about-text"><strong>50+ projects</strong> delivered solo, end-to-end</div></div>
      <div class="about-item"><div class="about-icon">⚙️</div><div class="about-text"><strong>Full Stack</strong> capable — UI to API to Database (MERN)</div></div>
      <div class="about-item"><div class="about-icon">🌍</div><div class="about-text">Worked with <strong>international clients</strong> remotely</div></div>
      <div class="about-item"><div class="about-icon">🧩</div><div class="about-text">Clean architecture, <strong>reusable component systems</strong></div></div>
      <div class="about-item"><div class="about-icon">📬</div><div class="about-text"><strong>Open to remote</strong> frontend / full stack roles</div></div>
    </div>
  </div>

  <div class="section">
    <div class="sec-title">Impact numbers</div>
    <div class="stat-row">
      <div class="stat-card"><div class="stat-num">50+</div><div class="stat-label">Websites & apps delivered</div></div>
      <div class="stat-card"><div class="stat-num">20+</div><div class="stat-label">Reusable UI components</div></div>
      <div class="stat-card"><div class="stat-num">3+</div><div class="stat-label">Years in production</div></div>
      <div class="stat-card"><div class="stat-num">90+</div><div class="stat-label">Lighthouse score avg</div></div>
    </div>
  </div>

  <div class="section">
    <div class="sec-title">Tech stack</div>
    <div class="skills-grid">
      <div class="skill-pill hot"><div class="skill-dot"></div>React.js</div>
      <div class="skill-pill hot"><div class="skill-dot"></div>Next.js</div>
      <div class="skill-pill hot"><div class="skill-dot"></div>Redux Toolkit</div>
      <div class="skill-pill hot"><div class="skill-dot"></div>RTK Query</div>
      <div class="skill-pill">JavaScript ES6+</div>
      <div class="skill-pill">TypeScript</div>
      <div class="skill-pill">Tailwind CSS</div>
      <div class="skill-pill">Ant Design</div>
      <div class="skill-pill">Bootstrap</div>
      <div class="skill-pill">HTML5 / CSS3</div>
      <div class="skill-pill hot"><div class="skill-dot"></div>Node.js</div>
      <div class="skill-pill hot"><div class="skill-dot"></div>Express.js</div>
      <div class="skill-pill hot"><div class="skill-dot"></div>MongoDB</div>
      <div class="skill-pill">REST APIs</div>
      <div class="skill-pill">Git / GitHub</div>
      <div class="skill-pill">Vercel</div>
      <div class="skill-pill">Figma</div>
      <div class="skill-pill">WordPress</div>
    </div>
  </div>

  <div class="section">
    <div class="sec-title">Featured projects</div>
    <div class="note"><span>💡 More full stack products actively being built & uploaded — stay tuned</span></div>
    <div class="proj-grid">
      <div class="proj-card">
        <div class="proj-name">🛒 MERN E-Commerce — Watches</div>
        <div class="proj-desc">Full stack web application with cart, secure auth & admin dashboard</div>
        <div class="proj-tags"><span class="tag">MongoDB</span><span class="tag">Express</span><span class="tag">React</span><span class="tag">Node.js</span></div>
      </div>
      <div class="proj-card">
        <div class="proj-name">💼 Blue Rock Capital</div>
        <div class="proj-desc">Investment firm web app — SEO optimized, high performance</div>
        <div class="proj-tags"><span class="tag">Next.js</span><span class="tag">TypeScript</span><span class="tag">Tailwind</span></div>
      </div>
      <div class="proj-card">
        <div class="proj-name">⚖️ SAJ Legal</div>
        <div class="proj-desc">Law firm website — solo client delivery, on-page SEO</div>
        <div class="proj-tags"><span class="tag">Next.js</span><span class="tag">JavaScript</span><span class="tag">SEO</span></div>
      </div>
      <div class="proj-card">
        <div class="proj-name">🌐 Personal Portfolio</div>
        <div class="proj-desc">Showcasing work — fast, SEO-first, Next.js powered</div>
        <div class="proj-tags"><span class="tag">Next.js</span><span class="tag">TypeScript</span><span class="tag">Tailwind</span></div>
      </div>
    </div>
  </div>

  <div class="connect-box">
    <div class="connect-title">Available for Remote Opportunities</div>
    <div class="connect-sub">Frontend / Full Stack · Responding within 24 hours</div>
    <div class="connect-btns">
      <span class="badge badge-li">🔗 Connect on LinkedIn</span>
      <span class="badge badge-gm">✉️ Send an Email</span>
      <span class="badge badge-po">🌐 View Portfolio</span>
    </div>
    <div class="quote">"I don't just write code — I build products that work."</div>
  </div>

  <div class="footer-wave"><div class="footer-text">MUHAMMAD YASIR · FRONTEND ENGINEER · OPEN TO REMOTE</div></div>
</div>

<script>
const lines = [
  "⚛️  React.js · Next.js · Full Stack MERN",
  "🌐  50+ Websites & Web Applications Delivered",
  "🔥  Building Scalable Products from Scratch",
  "🌍  Open to Remote Opportunities Worldwide"
];
let li = 0, ci = 0, del = false;
const el = document.getElementById('typing');
function type() {
  if (!del) {
    el.textContent = lines[li].substring(0, ci++);
    if (ci > lines[li].length) { del = true; setTimeout(type, 1800); return; }
  } else {
    el.textContent = lines[li].substring(0, ci--);
    if (ci < 0) { del = false; li = (li+1) % lines.length; ci = 0; setTimeout(type, 400); return; }
  }
  setTimeout(type, del ? 30 : 55);
}
type();
</script>
