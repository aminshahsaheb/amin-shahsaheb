from pathlib import Path
import zipfile

base = Path("/mnt/data/amin-shahsaheb-final")
assets = base / "assets"
assets.mkdir(parents=True, exist_ok=True)

hero = r'''<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="520" viewBox="0 0 1600 520">
<defs>
  <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#07090b"/><stop offset=".55" stop-color="#0b1010"/><stop offset="1" stop-color="#07110d"/></linearGradient>
  <radialGradient id="halo" cx="78%" cy="50%" r="45%"><stop offset="0" stop-color="#34d399" stop-opacity=".18"/><stop offset=".5" stop-color="#34d399" stop-opacity=".05"/><stop offset="1" stop-color="#34d399" stop-opacity="0"/></radialGradient>
  <linearGradient id="fade" x1="0" x2="1"><stop stop-color="#6ee7b7" stop-opacity="0"/><stop offset=".5" stop-color="#6ee7b7" stop-opacity=".58"/><stop offset="1" stop-color="#6ee7b7" stop-opacity="0"/></linearGradient>
  <filter id="blur"><feGaussianBlur stdDeviation="12"/></filter>
</defs>
<rect width="1600" height="520" rx="34" fill="url(#bg)"/>
<rect width="1600" height="520" rx="34" fill="url(#halo)"/>

<g stroke="#b8efd4" stroke-opacity=".045">
  <path d="M70 90H1530M70 170H1530M70 250H1530M70 330H1530M70 410H1530"/>
  <path d="M160 45V475M320 45V475M480 45V475M640 45V475M800 45V475M960 45V475M1120 45V475M1280 45V475M1440 45V475"/>
</g>

<text x="90" y="145" fill="#f4f8f6" font-family="Inter,Segoe UI,Arial,sans-serif" font-size="56" font-weight="700" letter-spacing="1.3">AMIN SHAHSÂHEB</text>
<text x="94" y="188" fill="#8de8bd" font-family="Inter,Segoe UI,Arial,sans-serif" font-size="17" font-weight="600" letter-spacing="5.2">BUSINESS • TECHNOLOGY • MARKETS</text>
<text x="94" y="246" fill="#cbd8d2" font-family="Inter,Segoe UI,Arial,sans-serif" font-size="20">Building businesses, digital products, brands,</text>
<text x="94" y="277" fill="#cbd8d2" font-family="Inter,Segoe UI,Arial,sans-serif" font-size="20">and practical systems at the edge of technology and AI.</text>
<rect x="94" y="316" width="290" height="2" fill="url(#fade)"/>
<text x="94" y="349" fill="#709080" font-family="ui-monospace,SFMono-Regular,Menlo,monospace" font-size="12" letter-spacing="2.2">BUSINESS / MARKETS / TECHNOLOGY / AI</text>

<g transform="translate(1210 252)">
  <circle r="146" fill="none" stroke="#8be9ba" stroke-opacity=".1"/>
  <circle r="112" fill="none" stroke="#8be9ba" stroke-opacity=".15"/>
  <circle r="76" fill="none" stroke="#8be9ba" stroke-opacity=".22" stroke-width="1.5"/>
  <path d="M-145 0H145M0-145V145" stroke="#8be9ba" stroke-opacity=".06"/>
  <path d="M-105-70C-58-121,10-111,43-65C75-20,58 34,8 62C-40 88,-90 59,-103 13C-110-14,-115-45,-105-70Z" fill="none" stroke="#9aefc7" stroke-opacity=".64" stroke-width="2"/>
  <path d="M-25-107C39-88,84-27,74 28C63 80,5 105,-47 79C-91 57,-107 7,-89-35" fill="none" stroke="#9aefc7" stroke-opacity=".26" stroke-width="1.5"/>
  <circle r="7" fill="#b9f7db"/>
  <circle r="28" fill="#34d399" opacity=".10" filter="url(#blur)"/>
  <circle cx="-103" cy="-70" r="3" fill="#b3f4d3"/><circle cx="74" cy="28" r="3" fill="#b3f4d3"/>
</g>

<path d="M984 397L1044 365L1092 377L1144 326L1197 349L1246 304L1285 318L1332 265L1384 281L1432 232" fill="none" stroke="#8beab9" stroke-opacity=".42" stroke-width="2"/>
<g fill="#b9f5d8"><circle cx="1044" cy="365" r="2.5"/><circle cx="1144" cy="326" r="2.5"/><circle cx="1246" cy="304" r="2.5"/><circle cx="1332" cy="265" r="2.5"/><circle cx="1432" cy="232" r="2.5"/></g>

<path d="M88 434H1512" stroke="url(#fade)"/>
<text x="94" y="464" fill="#61776c" font-family="Inter,Segoe UI,Arial,sans-serif" font-size="11" letter-spacing="3.1">SELECTED WORK • PROJECTS • SYSTEMS • CONTINUITY</text>
</svg>'''

readme = r'''<div align="center">

<img src="assets/hero.svg" alt="Amin Shahsaheb — Business • Technology • Markets" width="100%">

<p>
  <a href="https://biokart.ir/amin-shahsaheb">Business Card</a> ·
  <a href="https://github.com/aminshahsaheb">GitHub</a> ·
  <a href="https://www.instagram.com/Amin_shahsaheb">Instagram</a> ·
  <a href="https://wa.me/989198818465">WhatsApp</a>
</p>

<p><strong>Business • Technology • Markets</strong></p>
<p><em>Building businesses, digital products, brands, and practical systems at the edge of technology and AI.</em></p>

</div>

---

## ◆ About

I work across **business development, financial markets, technology, digital products, branding, and sales**.

My approach is practical: turn useful ideas into **products, brands, systems, and real-world projects**.

## ◈ Focus

| Area | Focus |
| --- | --- |
| **Business** | Development, strategy, marketing & sales |
| **Markets** | Research, analysis & systematic thinking |
| **Technology** | Digital products, software & technical projects |
| **Brand** | Visual identity, positioning & design |
| **AI** | Human–AI systems, continuity & emerging products |

## ◇ Selected Projects

### **[Fanus — Living Seal](https://fanus1.netlify.app/)**

A project exploring the intersection of **AI, memory, continuity, and human–AI relationships**.

**Explore:** [Fanus](https://fanus1.netlify.app/) · [Fanus Demo](https://fanus-presence.vercel.app/)

### **[BioKart](https://biokart.ir/amin-shahsaheb)**

Work across **marketing, sales, business development, and digital presence**.

## ⚙ What I Do

- Business development & consulting
- Financial market analysis
- Digital product development
- Branding & visual identity
- Marketing & sales

## ▣ Technology Background

Experience across **software, hardware, mobile technology, digital products, and online projects**.

## ◎ Current Direction

```text
BUSINESS
   ×
TECHNOLOGY
   ×
AI
   ×
MARKETS
