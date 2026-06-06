---
tags:
  - Web
  - HTML
  - Static-Site
Creation: 2026-06-05
Date: 2026-06-05
Ref: "[[Dev]]"
Type: Doc.Dev
Index: true
---

# _www

Personal static website. Handcrafted HTML with inline CSS/JS, hosted on GitHub Pages with custom domain.

## Stack

| Component   | Technology              |
|:------------|:------------------------|
| **Type**    | Static HTML             |
| **CSS**     | Inline (CSS variables)  |
| **JS**      | Vanilla (inline)        |
| **Host**    | GitHub Pages            |
| **Domain**  | alissoneloi.com         |

## Folder Structure

```
_www/
├── index.html          # Main personal website (27KB)
├── rabbit.html         # 404 page - jumping bunny animation (42KB)
├── CNAME               # Custom domain: alissoneloi.com
├── .git/
├── .gitattributes
└── .gitignore
```

## Pages

| File          | Description                                           |
|:--------------|:----------------------------------------------------- |
| `index.html`  | Personal site - "A. Eloi - IT & Business Specialist"  |
| `rabbit.html` | 404 Not Found page with jumping bunny animation       |

## Design

| Element     | Details                           |
|:------------|:----------------------------------|
| **Palette** | Orange (#feab12) + Blue (#0693e3) |
| **Style**   | Modern, minimalist, animated CSS  |
| **Features**| CSS variables, fade-up animations |

## Git

| Config       | Value                                  |
|:-------------|:---------------------------------------|
| **Remote**   | GitHub Pages (check `git remote -v`)   |
| **Branch**   | main                                   |

## Notes

- Single-file HTML (no external CSS/JS)
- CNAME configured for custom domain
- Rabbit page: cute 404 error page with animation

---

```dataviewjs
// Related Notes;
dv.view("Scripts/FooterRelated")
```
