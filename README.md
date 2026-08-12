# PDR Pro In — Coming Soon

A dark-themed temporary landing page for **PDR Pro In**, a premium auto repair company based in Kozhikode, Kerala.

## Preview

Single-page "Coming Soon" site featuring:
- Dark premium aesthetic with gold accents
- Responsive, mobile-first design
- Subtle animated background (mesh + grid + noise)
- Floating logo with glow effect
- Contact placeholders (email & phone)
- Zero external dependencies except Google Fonts

## File Structure

```
.
├── index.html          # Main landing page
├── css/
│   └── style.css       # All styles & animations
├── images/
│   └── logo.svg        # PDR Pro In logo
└── README.md           # This file
```

## Hosting Instructions

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on GitHub.
2. Push these files to the `main` branch.
3. Go to **Settings → Pages**.
4. Set source to **Deploy from a branch** → select `main` → `/ (root)`.
5. Your site will be live at `https://<username>.github.io/<repo-name>/`.

### Option 2: Netlify Drop

1. Zip all files.
2. Go to [netlify.com/drop](https://app.netlify.com/drop).
3. Drag & drop the zip. Site is live instantly.

### Option 3: Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this folder and follow prompts.

## Customization

- **Contact Details:** Edit the `mailto:` and `tel:` links in `index.html`.
- **Colors:** Modify CSS variables in `css/style.css` under `:root`.
- **Logo:** Replace `images/logo.svg` with your own (keep the same filename or update the path in `index.html`).

## Credits

- Fonts: [Google Fonts](https://fonts.google.com) (Bebas Neue + Inter)
- Design & Code: Generated for PDR Pro In

---

**Note:** This is a temporary front. Replace it with the full website once development is complete.
