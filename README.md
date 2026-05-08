# UKG Time Tracker — Reveal.js Slide Deck

A self-contained **Reveal.js 4** slide deck presenting the **UKG Web Time Tracker** project — a cloud-hosted employee time tracking platform with USB fingerprint authentication and multi-location support.

---

## 🚀 How to Open

No server or build step required.

1. **Clone or download** this repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows — just double-click index.html, or:
start index.html
```

> The deck loads Reveal.js, Font Awesome, and highlight.js from CDN.  
> An internet connection is required on first load. Once cached by the browser it works offline.

---

## 🎞️ Slides (15 total)

| # | Title |
|---|-------|
| 1 | Title Slide |
| 2 | What Are We Building? |
| 3 | The Big Picture — Architecture |
| 4 | The Tech Stack |
| 5 | Why Electron? |
| 6 | Fingerprint Auth (Privacy-First) |
| 7 | Multi-Location Clock-In |
| 8 | Permission Models |
| 9 | Timezone Handling |
| 10 | Database Design |
| 11 | Admin Dashboard |
| 12 | Edge Cases Handled |
| 13 | Project Folder Structure |
| 14 | Build Roadmap (10 Weeks) |
| 15 | Summary & Next Steps |

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` / `Space` | Next slide / fragment |
| `←` | Previous slide / fragment |
| `↑` / `↓` | Navigate vertical slides (if any) |
| `F` | Enter fullscreen |
| `S` | Open speaker notes window |
| `ESC` or `O` | Toggle slide overview |
| `B` | Pause / blackout screen |
| `?` | Show all keyboard shortcuts |

---

## 🖼️ Design

| Token | Value |
|-------|-------|
| Background | `#0a0e1a` (deep dark navy) |
| Headings | `#00C2FF` (cyan) |
| Body text | `#e8eaf6` |
| Cards | `background #111827`, `border #1e3a5f` |
| Success | `#00e676` |
| Danger | `#ff5252` |
| Warning | `#ffab40` |

CDN dependencies:

- **Reveal.js 4** — `https://cdn.jsdelivr.net/npm/reveal.js@4/`
- **Font Awesome 6** — `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/`
- **highlight.js** (Monokai theme) — bundled with Reveal.js 4

---

## 📁 Repository Structure

```
ukg-timetracker-slides/
├── index.html   ← The complete slide deck (open this)
└── README.md    ← You are here
```

---

## 📝 License

MIT
