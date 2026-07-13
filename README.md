# CHRIS VRAKAS — PERSONAL WEBSITE

> **The future will belong to those non-obvious thinkers who use their wide-ranging powers of interdisciplinary exploration to see connections between multiple, seemingly unrelated domains.**

My personal portfolio and digital stomping ground built from scratch with zero dependencies, zero tracking, and zero compromise. Pure HTML, CSS, and vanilla JavaScript.

**[→ Live Site: chrisvrakas.com](https://chrisvrakas.com)**

---

## 🧠 About

Most personal websites are static brochures. This one is a living document.

I'm a relentlessly curious, lifelong learner — technologist, Bitcoin enthusiast, privacy advocate, and polymathic explorer. I not only differ from others, but I differ from myself from yesterday. This site is the digital expression of that philosophy: ever-evolving, deliberately designed, and built the way I believe software should be built — minimal, fast, and without surveillance.

No WordPress. No analytics. No cookies. No bloat. Just code and ideas.

---

## ✨ Features

- **6 Pages** — Index, Whoami, Principles, Resources, Connect, Privacy Policy
- **189 Principles** — Core convictions, passions, and standards across 5 categories
- **600+ Curated Resources** — Software, books, films, podcasts, and bookmarks
- **Terminal Aesthetic** — Monospace typography, dark theme, intentional design
- **Vanilla Stack** — No frameworks, no dependencies, pure HTML/CSS/JS
- **Fully Responsive** — Desktop, tablet, and mobile
- **Privacy-First** — No analytics, no cookies, no third-party trackers
- **Self-Hosted Fonts** — Sometype Mono loaded locally, not from Google Fonts
- **PGP Contact** — Because encryption should be the default

---

## 🎨 Design Philosophy

### Zero Bloat
Every byte is intentional:
- Sometype Mono throughout — monospace because clarity > decoration
- `#1a1a1a` background, `#ddc18a` text, `#ff3333` accent — that's the palette
- No JavaScript libraries — if vanilla JS can't do it, it doesn't belong here

### Privacy as Aesthetic
The design reflects the philosophy:
- No external font calls (Google Fonts tracks users)
- No CDN except Font Awesome for social icons
- No tracking pixels hiding in the markup
- The Privacy Policy page isn't legal boilerplate — it's a manifesto

### Copyleft, Not Copyright
> *"When everyone copyrights, copyleft."*

This project is open source because information wants to be free. If something here helps you build something better, that's the point.

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup, no divitis
- **CSS3** — Flexbox layout, CSS custom properties, responsive breakpoints
- **Vanilla JavaScript** — Hamburger menu, scroll behavior, nothing more
- **GitHub Pages** — Static hosting, push to deploy
- **Cloudflare** — CDN, DNS, and SSL (set to Custom mode — see below)
- **Sometype Mono** — Self-hosted variable font

### ⚠️ Cloudflare SSL Note
SSL/TLS mode must remain on **Custom** (not Automatic, not Full Strict). Full Strict causes Error 526 with GitHub Pages. If the site ever goes down with a 526, check this setting first.

---

## 📂 Project Structure

```
chrisvrakas.github.io/
├── index.html              # Landing page — hero, preface, quotes
├── whoami.html             # About / bio page
├── principles.html         # 189 principles across 5 categories
├── resources.html          # 600+ curated tools, books, films, podcasts, bookmarks
├── connect.html            # Contact page with PGP key
├── privacy.html            # Privacy policy (not legal boilerplate — a manifesto)
├── robots.txt              # SEO: search engine instructions
├── sitemap.xml             # SEO: site structure for indexing
├── favicon.ico             # Classic favicon
├── favicon-16x16.png       # Small favicon
├── favicon-32x32.png       # Standard favicon
├── apple-touch-icon.png    # iOS home screen icon
├── android-chrome-192x192.png
├── android-chrome-512x512.png
└── assets/
    ├── fonts/              # Sometype Mono (Regular, Medium, Bold — self-hosted)
    ├── images/             # All graphics: hero images, logos, arrows, banners
    ├── notes/              # PRINCIPLES.pdf — original source document
    └── pgp/                # PGP public key
```

---

## 📐 Principles Page

`principles.html` — 189 hand-curated principles organized across 5 sections:

| Section | Count | Description |
|---|---|---|
| ETHOS | 44 | Paradox, truth hierarchy, Da Vinci framework, mental models, first principles |
| RELATIONSHIPS | 21 | What I value in others, communication, vulnerability, decentralization |
| CONDUCT | 47 | Daily habits, attire, silence, privacy, cryptography, logic, code |
| PROFESSIONAL | 54 | Work, speed, failure, competition, mental models, investing |
| AVOID | 26 | Comparison, resentment, politics, social media, assumptions |

Each section opens with a highlighted `CONCEPT → CONCEPT → CONCEPT` block. Every principle has a hover-activated deep-link anchor. The ETHOS section features a custom Da Vinci banner graphic and the full 7-principle Da Vinci framework from Michael J. Gelb's *How to Think Like Leonardo da Vinci*.

**[→ Browse principles as markdown](principles/)**

---

## 📚 Resources Page

The resources page (`resources.html`) is mirrored as a standalone GitHub repository for discoverability in the open-source ecosystem:

**[→ awesome-polymathic-resource-stack](https://github.com/chrisvrakas/awesome-polymathic-resource-stack)**

600+ hand-picked resources organized across:
- **SOFTWARE** — Privacy tools, security, crypto wallets, CLI, AI/LLMs, dev tools
- **BOOKS** — 150+ across Bitcoin, cypherpunk, hacking, business, philosophy, true crime
- **MOVIES** — Curated films worth your time
- **PODCASTS** — Signal over noise
- **BOOKMARKS** — The web's non-obvious bangers

---

## 🎨 Color Palette

```css
--background:  #1a1a1a   /* Near-black */
--text:        #ddc18a   /* Warm tan / gold */
--accent:      #ff3333   /* Red — links, headings, highlights */
--font:        'Sometype Mono', monospace
```

---

## 📄 License

**When everyone copyrights, copyleft.**

This project is open source and available under the [MIT License](LICENSE.md) — fork it, modify it, learn from it. Just give credit where it's due.

---

## 🙏 Acknowledgments

- **Sometype Mono** — The only font this site will ever need
- **GitHub Pages** — Free static hosting that just works
- **Cloudflare** — DNS, CDN, and SSL done right
- Every philosopher, hacker, and contrarian who proved that independent thinking compounds

---

## 📬 Contact

**Chris Vrakas**

- Website: [chrisvrakas.com](https://chrisvrakas.com)
- GitHub: [@chrisvrakas](https://github.com/chrisvrakas)
- X: [@chris_vrakas](https://x.com/chris_vrakas)
- Medium: [@chrisvrakas](https://medium.com/@chrisvrakas)
- PGP: [freedom@chrisvrakas.com](mailto:freedom@chrisvrakas.com)

---

## ⚡ Fast Facts

- **Zero external dependencies** — no npm, no webpack, no build step
- **Zero tracking** — no Google Analytics, no cookies, no fingerprinting
- **Zero JavaScript frameworks** — vanilla all the way down
- **100% HTML** — GitHub says so, and GitHub doesn't lie

---

<div align="center">

**"No man ever steps in the same river twice, for it's not the same river and he's not the same man."**  
— Heraclitus

**[Visit chrisvrakas.com →](https://chrisvrakas.com)**

</div>
