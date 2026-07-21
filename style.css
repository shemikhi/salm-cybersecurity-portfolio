/* ========== SALM BASEHEMAKH — CYBER PORTFOLIO ========== */
:root {
  --bg: #0a0a0f;
  --bg-card: #11111a;
  --bg-hover: #1a1a2e;
  --neon-green: #00ff41;
  --neon-cyan: #00f0ff;
  --neon-red: #ff0040;
  --neon-amber: #ffaa00;
  --neon-purple: #b829dd;
  --text: #e0e0e0;
  --text-dim: #888899;
  --border: #222233;
}

* { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  background: var(--bg);
  color: var(--text);
  font-family: 'JetBrains Mono', monospace;
  overflow-x: hidden;
  line-height: 1.6;
}

/* CRT Scanline */
.crt::before {
  content: '';
  position: fixed;
  top: 0; left: 0; right: 0; bottom: 0;
  background: repeating-linear-gradient(
    0deg, rgba(0,0,0,0.15), rgba(0,0,0,0.15) 1px,
    transparent 1px, transparent 2px
  );
  pointer-events: none;
  z-index: 9999;
  opacity: 0.4;
}

/* Glitch */
.glitch {
  position: relative;
  font-family: 'Orbitron', sans-serif;
  font-weight: 900;
  letter-spacing: 2px;
}
.glitch::before, .glitch::after {
  content: attr(data-text);
  position: absolute;
  top: 0; left: 0; width: 100%; height: 100%;
}
.glitch::before {
  left: 2px;
  text-shadow: -2px 0 var(--neon-red);
  clip: rect(24px, 550px, 90px, 0);
  animation: glitch-anim 3s infinite linear alternate-reverse;
}
.glitch::after {
  left: -2px;
  text-shadow: -2px 0 var(--neon-cyan);
  clip: rect(85px, 550px, 140px, 0);
  animation: glitch-anim2 2.5s infinite linear alternate-reverse;
}
@keyframes glitch-anim {
  0% { clip: rect(10px, 9999px, 30px, 0); }
  20% { clip: rect(80px, 9999px, 100px, 0); }
  40% { clip: rect(10px, 9999px, 50px, 0); }
  60% { clip: rect(40px, 9999px, 80px, 0); }
  80% { clip: rect(20px, 9999px, 60px, 0); }
  100% { clip: rect(70px, 9999px, 90px, 0); }
}
@keyframes glitch-anim2 {
  0% { clip: rect(60px, 9999px, 80px, 0); }
  20% { clip: rect(10px, 9999px, 30px, 0); }
  40% { clip: rect(50px, 9999px, 70px, 0); }
  60% { clip: rect(30px, 9999px, 50px, 0); }
  80% { clip: rect(90px, 9999px, 100px, 0); }
  100% { clip: rect(20px, 9999px, 40px, 0); }
}

/* Typewriter */
.typewriter {
  overflow: hidden;
  white-space: nowrap;
  border-right: 2px solid var(--neon-green);
  animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
  display: inline-block;
}
@keyframes typing { from { width: 0 } to { width: 100% } }
@keyframes blink-caret { 50% { border-color: transparent } }

/* Matrix Canvas */
#matrix-canvas {
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  opacity: 0.08;
  pointer-events: none;
}

/* Layout */
.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 24px;
  position: relative;
  z-index: 1;
}

/* Nav */
.nav {
  position: fixed;
  top: 0; left: 0; right: 0;
  background: rgba(10,10,15,0.92);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid var(--border);
  z-index: 100;
  padding: 12px 24px;
  display: flex;
  justify-content: center;
  gap: 24px;
  flex-wrap: wrap;
}
.nav a {
  color: var(--text-dim);
  text-decoration: none;
  font-size: 12px;
  transition: color 0.3s;
}
.nav a:hover, .nav a.active { color: var(--neon-green); }

/* Hero */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  position: relative;
  padding: 80px 20px 40px;
}
.hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: rgba(0,255,65,0.08);
  border: 1px solid var(--neon-green);
  color: var(--neon-green);
  padding: 6px 16px;
  border-radius: 4px;
  font-size: 12px;
  margin-bottom: 24px;
}
.hero-badge .dot {
  width: 8px; height: 8px;
  background: var(--neon-green);
  border-radius: 50%;
  animation: pulse 2s infinite;
}
@keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.3; } }

.hero h1 {
  font-size: clamp(2.5rem, 8vw, 5rem);
  margin: 0 0 16px 0;
  color: var(--neon-green);
  text-shadow: 0 0 20px rgba(0,255,65,0.3);
}
.hero .subtitle {
  font-size: clamp(1rem, 3vw, 1.4rem);
  color: var(--text-dim);
  margin-bottom: 8px;
}
.hero .location {
  color: var(--neon-cyan);
  font-size: 14px;
  margin-bottom: 32px;
}

/* Terminal Box */
.terminal-box {
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 20px 24px;
  max-width: 600px;
  width: 100%;
  text-align: left;
  margin-top: 20px;
  box-shadow: 0 0 30px rgba(0,240,255,0.05);
}
.terminal-header {
  display: flex;
  gap: 6px;
  margin-bottom: 12px;
}
.terminal-header span {
  width: 12px; height: 12px;
  border-radius: 50%;
}
.t-red { background: var(--neon-red); }
.t-amber { background: var(--neon-amber); }
.t-green { background: var(--neon-green); }
.terminal-body {
  font-size: 13px;
  line-height: 1.8;
  color: var(--text);
}
.terminal-body .prompt { color: var(--neon-green); }
.terminal-body .cmd { color: var(--neon-cyan); }
.terminal-body .output { color: var(--text-dim); }
.terminal-body .highlight { color: var(--neon-amber); }

/* Section */
.section {
  padding: 80px 0;
  position: relative;
}
.section-title {
  font-family: 'Orbitron', sans-serif;
  font-size: 28px;
  color: var(--neon-cyan);
  margin-bottom: 40px;
  display: flex;
  align-items: center;
  gap: 12px;
}
.section-title::before {
  content: '>';
  color: var(--neon-green);
}

/* Skills */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
}
.skill-card {
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 20px;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}
.skill-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0;
  width: 3px; height: 100%;
  background: var(--neon-green);
  opacity: 0;
  transition: opacity 0.3s;
}
.skill-card:hover {
  border-color: var(--neon-green);
  transform: translateY(-4px);
  box-shadow: 0 10px 40px rgba(0,255,65,0.08);
}
.skill-card:hover::before { opacity: 1; }
.skill-card h3 {
  font-family: 'Orbitron', sans-serif;
  font-size: 14px;
  color: var(--neon-cyan);
  margin: 0 0 12px 0;
  display: flex;
  align-items: center;
  gap: 8px;
}
.skill-card .tags {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}
.skill-card .tag {
  background: rgba(0,240,255,0.06);
  border: 1px solid rgba(0,240,255,0.15);
  color: var(--text);
  padding: 3px 10px;
  border-radius: 3px;
  font-size: 11px;
}

/* Timeline */
.timeline {
  position: relative;
  padding-left: 30px;
}
.timeline::before {
  content: '';
  position: absolute;
  left: 6px;
  top: 0; bottom: 0;
  width: 2px;
  background: linear-gradient(to bottom, var(--neon-green), var(--neon-cyan), var(--neon-purple));
}
.timeline-item {
  position: relative;
  margin-bottom: 40px;
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 24px;
  transition: all 0.3s;
}
.timeline-item:hover {
  border-color: var(--neon-cyan);
  box-shadow: 0 0 25px rgba(0,240,255,0.06);
}
.timeline-item::before {
  content: '';
  position: absolute;
  left: -28px;
  top: 28px;
  width: 10px; height: 10px;
  background: var(--neon-green);
  border-radius: 50%;
  border: 3px solid var(--bg);
  box-shadow: 0 0 10px var(--neon-green);
}
.timeline-item .date {
  color: var(--neon-amber);
  font-size: 12px;
  margin-bottom: 4px;
}
.timeline-item .role {
  font-family: 'Orbitron', sans-serif;
  font-size: 16px;
  color: var(--neon-cyan);
  margin: 0 0 4px 0;
}
.timeline-item .company {
  color: var(--text-dim);
  font-size: 13px;
  margin-bottom: 12px;
}
.timeline-item ul {
  margin: 0;
  padding-left: 18px;
  color: var(--text);
  font-size: 13px;
  line-height: 1.8;
}
.timeline-item li { margin-bottom: 6px; }
.timeline-item li::marker { color: var(--neon-green); }

/* Projects */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 24px;
}
.project-card {
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 28px;
  position: relative;
  overflow: hidden;
  transition: all 0.3s;
  text-decoration: none;
  color: inherit;
  display: block;
}
.project-card::after {
  content: '';
  position: absolute;
  top: -50%; right: -50%;
  width: 200%; height: 200%;
  background: radial-gradient(circle, rgba(0,255,65,0.03) 0%, transparent 70%);
  opacity: 0;
  transition: opacity 0.3s;
  pointer-events: none;
}
.project-card:hover {
  border-color: var(--neon-purple);
  transform: translateY(-6px);
}
.project-card:hover::after { opacity: 1; }
.project-card .status {
  display: inline-block;
  background: rgba(0,255,65,0.1);
  color: var(--neon-green);
  font-size: 10px;
  padding: 2px 8px;
  border-radius: 3px;
  margin-bottom: 12px;
}
.project-card h3 {
  font-family: 'Orbitron', sans-serif;
  font-size: 16px;
  color: var(--neon-purple);
  margin: 0 0 12px 0;
}
.project-card p {
  font-size: 13px;
  line-height: 1.7;
  color: var(--text-dim);
  margin: 0;
}
.project-card .tech-stack {
  margin-top: 16px;
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}
.project-card .tech {
  background: rgba(184,41,221,0.08);
  border: 1px solid rgba(184,41,221,0.2);
  color: var(--neon-purple);
  padding: 3px 10px;
  border-radius: 3px;
  font-size: 11px;
}

/* Certs */
.certs-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px;
}
.cert-card {
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 20px;
  text-align: center;
  transition: all 0.3s;
  position: relative;
}
.cert-card:hover {
  border-color: var(--neon-amber);
  transform: scale(1.02);
}
.cert-card .cert-icon {
  font-size: 32px;
  margin-bottom: 12px;
}
.cert-card h4 {
  font-family: 'Orbitron', sans-serif;
  font-size: 13px;
  color: var(--neon-amber);
  margin: 0 0 6px 0;
}
.cert-card .issuer {
  font-size: 11px;
  color: var(--text-dim);
}
.cert-card .badge {
  position: absolute;
  top: -1px; right: -1px;
  background: var(--neon-green);
  color: var(--bg);
  font-size: 9px;
  padding: 2px 8px;
  border-radius: 0 8px 0 4px;
  font-weight: bold;
}

/* Contact */
.contact-bar {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 16px;
  margin-top: 32px;
}
.contact-btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: var(--bg-card);
  border: 1px solid var(--border);
  color: var(--text);
  padding: 10px 20px;
  border-radius: 6px;
  text-decoration: none;
  font-size: 13px;
  transition: all 0.3s;
}
.contact-btn:hover {
  border-color: var(--neon-cyan);
  color: var(--neon-cyan);
  box-shadow: 0 0 15px rgba(0,240,255,0.1);
  transform: translateY(-2px);
}

/* Footer */
.footer {
  text-align: center;
  padding: 40px 20px;
  color: var(--text-dim);
  font-size: 12px;
  border-top: 1px solid var(--border);
}

/* Scrollbar */
::-webkit-scrollbar { width: 8px; }
::-webkit-scrollbar-track { background: var(--bg); }
::-webkit-scrollbar-thumb { background: var(--border); border-radius: 4px; }
::-webkit-scrollbar-thumb:hover { background: var(--neon-green); }

/* Fade In */
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.fade-in.visible {
  opacity: 1;
  transform: translateY(0);
}

/* Blog & Writeups */
.blog-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 20px;
}
.blog-card {
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 24px;
  transition: all 0.3s;
  text-decoration: none;
  color: inherit;
  display: block;
}
.blog-card:hover {
  border-color: var(--neon-cyan);
  transform: translateY(-4px);
  box-shadow: 0 10px 40px rgba(0,240,255,0.06);
}
.blog-card .date {
  color: var(--neon-amber);
  font-size: 11px;
  margin-bottom: 8px;
}
.blog-card h3 {
  font-family: 'Orbitron', sans-serif;
  font-size: 15px;
  color: var(--neon-cyan);
  margin: 0 0 8px 0;
}
.blog-card p {
  font-size: 12px;
  color: var(--text-dim);
  line-height: 1.6;
}
.blog-card .tags {
  margin-top: 12px;
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}
.blog-card .tag {
  background: rgba(0,240,255,0.06);
  border: 1px solid rgba(0,240,255,0.15);
  color: var(--text);
  padding: 2px 8px;
  border-radius: 3px;
  font-size: 10px;
}

/* Article Page */
.article-page {
  padding-top: 80px;
  min-height: 100vh;
}
.article-header {
  text-align: center;
  padding: 60px 20px 40px;
}
.article-header h1 {
  font-family: 'Orbitron', sans-serif;
  font-size: clamp(1.5rem, 4vw, 2.5rem);
  color: var(--neon-cyan);
  margin-bottom: 12px;
}
.article-header .meta {
  color: var(--text-dim);
  font-size: 13px;
}
.article-content {
  max-width: 800px;
  margin: 0 auto;
  padding: 0 24px 80px;
  font-size: 14px;
  line-height: 1.9;
  color: var(--text);
}
.article-content h2 {
  font-family: 'Orbitron', sans-serif;
  font-size: 18px;
  color: var(--neon-green);
  margin: 40px 0 16px;
}
.article-content h3 {
  font-family: 'Orbitron', sans-serif;
  font-size: 14px;
  color: var(--neon-amber);
  margin: 24px 0 12px;
}
.article-content p { margin-bottom: 16px; }
.article-content code {
  background: var(--bg-hover);
  border: 1px solid var(--border);
  padding: 2px 6px;
  border-radius: 3px;
  color: var(--neon-green);
  font-size: 12px;
}
.article-content pre {
  background: var(--bg-hover);
  border: 1px solid var(--border);
  border-radius: 6px;
  padding: 16px;
  overflow-x: auto;
  margin: 16px 0;
}
.article-content pre code {
  background: none;
  border: none;
  padding: 0;
  color: var(--text);
}
.article-content ul, .article-content ol {
  margin: 0 0 16px 20px;
  color: var(--text-dim);
}
.article-content li { margin-bottom: 6px; }
.article-content blockquote {
  border-left: 3px solid var(--neon-purple);
  padding-left: 16px;
  margin: 16px 0;
  color: var(--text-dim);
  font-style: italic;
}
.back-btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  color: var(--neon-cyan);
  text-decoration: none;
  font-size: 12px;
  margin-bottom: 20px;
  transition: color 0.3s;
}
.back-btn:hover { color: var(--neon-green); }

/* Responsive */
@media (max-width: 600px) {
  .section { padding: 50px 0; }
  .timeline { padding-left: 20px; }
  .timeline-item::before { left: -18px; }
  .typewriter { white-space: normal; border-right: none; animation: none; }
  .nav { gap: 12px; padding: 10px 12px; }
  .nav a { font-size: 11px; }
}
