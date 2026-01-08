# Shake N' Swirl Website

Static website for Shake N' Swirl — Home, Menu, About, Contact, responsive hamburger nav, and shared footer.

## Structure
- index.html — Home
- menu.html — Menu (includes full in-store menu, corrected Frozen Yogurt, and a Delivery Platform Menu section)
- about.html — About page with story and reviews
- contact.html — Contact page with address, hours, phone, and map embed
- assets/css/styles.css — Styles
- assets/js/main.js — Hamburger menu + smooth scroll
- assets/images/logo.jpg — Placeholder; replace with the real logo file

## Quick Start
Open `index.html` directly in your browser, or run a lightweight local server:

### Python (if installed)
```bash
python -m http.server 5500
# then visit http://localhost:5500/index.html
```

### PowerShell (Windows-only alternative)
```powershell
Start-Process msedge index.html
```

## Edit Notes
- Replace `assets/images/logo.jpg` with the actual logo image.
- Update hours or pricing as needed; Delivery pricing is under the collapsible section in `menu.html`.
- Social links: Instagram and TikTok are wired. Order Online goes to Toast.

## Accessibility
- Keyboard-accessible mobile menu toggle (`aria-expanded`).
- Semantic headings and alt text for images.
