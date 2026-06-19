# USSF — United States of Sheep Fart 🐑

The official web portal for **USSF**, a Minecraft survival nation built around its capital, **Neoveil Jade City (NJC)**.

> "A living capital where the modern city rises above ancient medieval roots — its streets, towers, and alleys all shaped by the hands and lives of its people."

## 🌐 Live Site

This is a static single-page site — no build step, no dependencies. Just open `index.html` in a browser, or host it for free with [GitHub Pages](https://pages.github.com/):

1. Go to **Settings → Pages** on this repo
2. Set source to your main branch, root folder
3. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

## 🏙️ What's Inside

- **About NJC** — the capital city, its name, and its districts
- **Cities** — NJC, Santorini (2nd capital), Iceland, with the in-game world map
- **Highways** — the route from the airport through NJC to the territories
- **Golden Jade Veilend Bridge** — the landmark crossing over the Jade River
- **The Colosseum** — NJC's ancient landmark
- **Metro & Rail Guide** — full transit diagram for all 3 metro lines + long-distance trains
- **Slut Town** — the capital's nightlife district

## 📁 Structure

```
.
├── index.html        # the entire site
└── assets/            # in-game screenshots used throughout the site
    ├── colosseum.png
    ├── bridge.png
    ├── map.png
    ├── downtown.png
    ├── medieval.png
    ├── skyline.png
    └── slut_town.png
```

## ✏️ Editing

Everything lives in one file — `index.html` — with all CSS inline in a single `<style>` block. Each section is commented (`<!-- ===== SECTION ===== -->`) so you can find and edit content directly without touching layout code.

To swap an image, just replace the file in `assets/` with the same filename, or update the `src=` path in `index.html`.

---

Built by Nithil & Jenny.
