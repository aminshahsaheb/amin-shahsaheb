from pathlib import Path
import zipfile

root = Path("/mnt/data/amin-shahsaheb-profile")
assets = root / "assets"
assets.mkdir(parents=True, exist_ok=True)

hero = """<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="360" viewBox="0 0 1200 360" role="img" aria-label="Amin Shahsaheb — Business Technology Markets">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#07090c"/>
      <stop offset="55%" stop-color="#0b1110"/>
      <stop offset="100%" stop-color="#07100d"/>
    </linearGradient>
    <radialGradient id="glow" cx="72%" cy="44%" r="48%">
      <stop offset="0%" stop-color="#6ee7b7" stop-opacity="0.22"/>
      <stop offset="55%" stop-color="#34d399" stop-opacity="0.06"/>
      <stop offset="100%" stop-color="#34d399" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="line" x1="0" x2="1">
      <stop offset="0%" stop-color="#34d399" stop-opacity="0"/>
      <stop offset="50%" stop-color="#6ee7b7" stop-opacity="0.65"/>
      <stop offset="100%" stop-color="#34d399" stop-opacity="0"/>
    </linearGradient>
    <filter id="blur"><feGaussianBlur stdDeviation="18"/></filter>
  </defs>
  <rect width="1200" height="360" rx="28" fill="url(#bg)"/>
  <rect width="1200" height="360" rx="28" fill="url(#glow)"/>
  <g opacity="0.20" stroke="#6ee7b7" stroke-width="1">
    <path d="M60 290 C220 210, 290 305, 420 225 S650 155, 800 215 S1000 300, 1140 170" fill="none"/>
    <path d="M40 325 C230 250, 350 335, 500 265 S740 180, 910 245 S1070 285, 1180 210" fill="none"/>
  </g>
  <circle cx="905" cy="165" r="105" fill="none" stroke="#6ee7b7" stroke-opacity="0.13"/>
  <circle cx="905" cy="165" r="72" fill="none" stroke="#6ee7b7" stroke-opacity="0.18"/>
  <circle cx="905" cy="165" r="6" fill="#a7f3d0"/>
  <g filter="url(#blur)" opacity="0.22"><circle cx="905" cy="165" r="28" fill="#34d399"/></g>
  <path d="M620 286 H1115" stroke="url(#line)" stroke-width="1"/>
  <text x="78" y="110" fill="#f5f7f6" font-family="Inter,Segoe UI,Arial,sans-serif" font-size="44" font-weight="700" letter-spacing="1">AMIN SHAHSÂHEB</text>
  <text x="80" y="154" fill="#a7f3d0" font-family="Inter,Segoe UI,Arial,sans-serif" font-size="19" letter-spacing="4">BUSINESS • TECHNOLOGY • MARKETS</text>
  <text x="80" y="205" fill="#d7e4df" font-family="Inter,Segoe UI,Arial,sans-serif" font-size="17">Building businesses, digital products, brands, and new systems.</text>
  <text x="80" y="255" fill="#7dd3b0" font-family="ui-monospace,SFMono-Regular,Menlo,monospace" font-size="13">FOCUS: BUSINESS / MARKETS / TECHNOLOGY / AI</text>
  <rect x="80" y="286" width="190" height="2" fill="#6ee7b7" opacity="0.75"/>
</svg>
"""

readme = """<div align="center">

<img src="assets/hero.svg" alt="Amin Shahsaheb — Business • Technology • Markets" width="100%">

</div>

<p align="center">
  <a href="https://biokart.ir/amin-shahsaheb"><img src="https://img.shields.io/badge/Business_Card-111827?style=for-the-badge&logo=linktree&logoColor=6ee7b7" alt="Business Card"></a>
  <a href="https://github.com/aminshahsaheb"><img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=ffffff" alt="GitHub"></a>
  <a href="https://www.instagram.com/Amin_shahsaheb"><img src="https://img.shields.io/badge/Instagram-111827?style=for-the-badge&logo=instagram&logoColor=ffffff" alt="Instagram"></a>
  <a href="https://wa.me/989198818465"><img src="https://img.shields.io/badge/WhatsApp-111827?style=for-the-badge&logo=whatsapp&logoColor=6ee7b7" alt="WhatsApp"></a>
</p>

<p align="center">
  <em>Building at the intersection of business, technology, markets, and AI.</em>
</p>

---

## ◆ About

I work across **business development, financial markets, technology, digital products, branding, and sales**.

My focus is on turning ideas into **products, brands, and practical systems** — with current work centered on projects at the intersection of **technology and AI**.

---

## ◈ Focus

| Area | Focus |
|---|---|
| **Business** | Development, strategy, marketing & sales |
| **Markets** | Market research, analysis & systematic thinking |
| **Technology** | Digital products, software & technical projects |
| **Brand** | Logo design, visual identity & positioning |
| **AI** | Human–AI systems, continuity & emerging products |

---

## ◇ Selected Projects

### **[Fanus — Living Seal](https://fanus1.netlify.app/)**

A project at the intersection of **AI, memory, continuity, and human–AI relationships**.

> *Continuity without truth and autonomy is not preservation — it is capture.*

**Explore:** [Fanus](https://fanus1.netlify.app/) · [Fanus Demo](https://fanus-presence.vercel.app/)

### **BioKart**

Work across **marketing, sales, business development, and digital presence**.

**Visit:** [BioKart](https://biokart.ir/amin-shahsaheb)

---

## ⚙ What I Do

- Business development & consulting
- Financial market analysis
- Digital product development
- Branding & visual identity
- Marketing & sales

---

## ▣ Technology Background

Experience across **software, hardware, mobile technology, digital products, and online projects**.

---

## ◎ Current Direction

I am currently focused on building and developing projects that sit between:

`BUSINESS`  ×  `TECHNOLOGY`  ×  `AI`  ×  `MARKETS`

The goal is practical: **build useful things, test them in the real world, and keep improving them.**

---

## ⟡ Connect

<p>
  <a href="https://biokart.ir/amin-shahsaheb">Business Card</a> ·
  <a href="https://www.instagram.com/Amin_shahsaheb">Instagram</a> ·
  <a href="https://wa.me/989198818465">WhatsApp</a> ·
  <a href="https://t.me/Kingsaheb">Telegram</a> ·
  <a href="https://github.com/aminshahsaheb">GitHub</a>
</p>

<p align="center">
  <sub>Best Never Rest</sub>
</p>
"""

(root / "README.md").write_text(readme, encoding="utf-8")
(assets / "hero.svg").write_text(hero, encoding="utf-8")

zip_path = Path("/mnt/data/amin-shahsaheb-profile-ready.zip")
with zipfile.ZipFile(zip_path, "w", zipfile.ZIP_DEFLATED) as z:
    z.write(root / "README.md", "README.md")
    z.write(assets / "hero.svg", "assets/hero.svg")

print(f"Created: {zip_path}")
print(f"Files: {root/'README.md'} and {assets/'hero.svg'}")
