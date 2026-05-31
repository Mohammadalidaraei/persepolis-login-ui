# 🏛️ Persepolis Login UI

A cinematic, single-file login page inspired by the ancient **Achaemenid Persian Empire** — built with pure HTML, CSS, and vanilla JavaScript. No frameworks. No dependencies.

![Persian Empire](https://img.shields.io/badge/Aesthetic-Ancient%20Persian-C9A84C?style=flat-square&labelColor=0E0C0A)
![Tech](https://img.shields.io/badge/Stack-HTML%20%2F%20CSS%20%2F%20JS-gold?style=flat-square&labelColor=0E0C0A)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square&labelColor=0E0C0A)

---

## ✨ Features

- **Winged Faravahar** — the sacred Achaemenid symbol rendered in SVG with glowing gold gradients
- **Achaemenid Griffin carvings** etched on the sides of the login card
- **Lotus flower motifs** — authentic Persepolis decorative dividers
- **Persian column silhouettes** flanking the background
- **Animated torch sconces** with flickering flame effect (pure CSS)
- **Ambient gold dust particles** floating upward throughout the scene
- **Cinematic stone texture** — dark charcoal base with layered noise grain
- **Staggered entrance animations** — Faravahar descends, card rises, fields slide in sequentially
- **Golden focus interactions** — input fields glow on focus with sweeping underline animation
- **Hexagonal CTA button** — echoing ancient Persian shield geometry
- Fully **responsive** and **single-file** — zero external dependencies beyond Google Fonts

---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| `--gold` | `#C9A84C` | Primary accent, borders |
| `--gold-bright` | `#F0C060` | Glow, highlights, button |
| `--charcoal` | `#0E0C0A` | Base background |
| `--stone-dark` | `#1A1612` | Card background |
| `--cream` | `#F5ECD0` | Input text |

**Typography:**
- `Cinzel Decorative` — titles and CTA (imperial, ancient feel)
- `Cinzel` — labels and metadata (refined, legible)
- `EB Garamond` — body and placeholders (classical serif)

---

## 🚀 Usage

No build step. No package manager. Just open the file.

```bash
git clone https://github.com/YOUR_USERNAME/persepolis-login-ui.git
cd persepolis-login-ui
open index.html
```

Or serve locally:

```bash
npx serve .
# then visit http://localhost:3000
```

---

## 📁 Structure

```
persepolis-login-ui/
└── index.html      # Everything — HTML, CSS, JS in one file
└── README.md
```

---

## 🛠️ Customization

All design tokens are CSS variables at the top of the `<style>` block. To change the color palette, edit the `:root` section:

```css
:root {
  --gold:        #C9A84C;
  --charcoal:    #0E0C0A;
  /* ... */
}
```

To connect to a real backend, replace the `handleEnter()` function in the `<script>` block with your own `fetch()` or form submission logic.

---

## 📜 License

MIT — free to use, modify, and distribute.

---

> *"I am Darius, the Great King, King of Kings."*
> — Inscription at Persepolis, 6th century BCE

