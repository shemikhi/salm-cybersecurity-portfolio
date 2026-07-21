# Salm Bashemakh — Cybersecurity Portfolio

A dark, terminal-inspired cybersecurity portfolio built for expansion. Add new writeups, blog posts, and projects anytime by following the structure below.

## 🚀 Quick Start

```bash
# Open directly in browser
open index.html

# Or serve locally
python3 -m http.server 8000
# Visit http://localhost:8000
```

## 📁 File Structure

```
portfolio/
├── index.html                  # Main portfolio page
├── assets/
│   ├── style.css              # All styles (shared across all pages)
│   └── main.js                # Matrix rain + scroll reveal + nav (shared)
├── writeups/                   # CTF writeups & lab walkthroughs
│   ├── ad-attack-detection-lab.html
│   ├── aws-cloud-security-lab.html
│   ├── kerberoasting-detection-splunk.html
│   ├── dcsync-detection.html
│   └── aws-iam-misconfigurations.html
└── blog/                       # Security blog posts
    ├── soc-analyst-mindset.html
    ├── mitre-attack-blue-team.html
    └── home-lab-guide.html
```

## 📝 Adding New Content

### Add a New Writeup

1. Create a new `.html` file in `writeups/`
2. Copy the template from any existing writeup
3. Update the title, date, tags, and content
4. Add a card to `index.html` in the `#writeups` section:

```html
<a href="writeups/your-new-writeup.html" class="blog-card">
  <div class="date">2025-08-01</div>
  <h3>Your Writeup Title</h3>
  <p>Brief description of the writeup...</p>
  <div class="tags">
    <span class="tag">Tag1</span>
    <span class="tag">Tag2</span>
  </div>
</a>
```

### Add a New Blog Post

1. Create a new `.html` file in `blog/`
2. Use the same template structure as existing blog posts
3. Add a card to `index.html` in the `#blog` section

### Add a New Project

1. Create a project detail page in `writeups/` (or a new `projects/` folder)
2. Link it from the Projects grid in `index.html`
3. Optionally add a thumbnail image in `assets/images/`

## 🎨 Customization

- **Colors:** Edit CSS variables in `assets/style.css` `:root`
- **Fonts:** Already loaded from Google Fonts (JetBrains Mono + Orbitron)
- **Animations:** All pure CSS/JS — no build step needed
- **Matrix rain:** Configurable in `assets/main.js`

## 📄 License

Personal use only.
