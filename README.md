# JIANG Xiantao — Academic Homepage

Personal academic website hosted on GitHub Pages.

**URL:** https://XTjiang111.github.io

## Structure

```
├── index.html          # Main page (name, profile, pubs, teaching)
├── css/style.css       # Stylesheet (colors, fonts, layout)
├── js/main.js          # Scripts (scroll, interactions)
└── README.md
```

## Update Guide

### Common edits

| Task | Where to edit |
|------|---------------|
| Change name / title / email / links | `index.html` → `hero-contact` / hero section |
| Add / remove publication | `index.html` → `#publications`, copy or delete a `.pub-item` block |
| Update research interests | `index.html` → `#research` section |
| Modify teaching entries | `index.html` → `#teaching` section |
| Change colors / fonts / spacing | `css/style.css` |
| Replace avatar photo | Place a photo file (e.g. `avatar.jpg`) in project root, then replace `<div class="avatar-placeholder">` with `<img src="avatar.jpg" class="avatar-img">` |

## Local Development

Open `index.html` in your browser, or serve with any static file server:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

## Deployment

Push to the `main` branch of `XTjiang111/XTjiang111.github.io`.
GitHub Pages will automatically deploy from the `main` branch.