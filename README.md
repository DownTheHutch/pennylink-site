# PennyLink Pre-launch Site

This is a minimal, fast, static landing page for PennyLink (`pennylink.app`).

## Quick Start (Local)
Open `index.html` in your browser.

## Deploy Options

### A) GitHub Pages + Namecheap (recommended free setup)
1. Create a new GitHub repo (e.g., `pennylink-site`) and push these files.
2. In GitHub: Settings → Pages → Deploy from `main` branch `/` (root).
3. In Namecheap: Domain List → `pennylink.app` → Advanced DNS → add a CNAME record for `www` to `<your-username>.github.io` and set an A record to GitHub Pages IPs (or use the CNAME only with `www`).
4. (Optional) Enforce HTTPS in GitHub Pages.

### B) Netlify (one-click CI deploy)
1. Drag-and-drop this folder into app.netlify.com or connect your GitHub repo.
2. Set `pennylink.app` as a custom domain in Netlify and update DNS in Namecheap.

### C) Vercel
1. `npm i -g vercel` then `vercel` in this folder, or connect via dashboard.
2. Assign `pennylink.app` as custom domain; update DNS in Namecheap.

## Hook up the form
Replace the `form`'s `action="#"` in `index.html` with your email provider's embed or post URL (Mailchimp/ConvertKit/Brevo). You can also swap in their full HTML embed block.

## Basic SEO
- Title + meta description set
- Open Graph + Twitter card image at `assets/og-image.png`
- Mobile-friendly, fast, no heavy JS

