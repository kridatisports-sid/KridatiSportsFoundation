# Kridati Sports Foundation — Website

**Live at:** `https://[your-username].github.io/kridati/` (after setup)

---

## Files

```
kridati-site/
├── index.html       ← Main website
├── 404.html         ← Custom 404 page
├── KRIDATI_SPORTS.png  ← Your logo (add this file!)
└── README.md
```

---

## Deploying to GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) → **New repository**
2. Name it `kridati` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload Files
1. On the repository page, click **Add file → Upload files**
2. Upload all files from this folder: `index.html`, `404.html`, `KRIDATI_SPORTS.png`, `README.md`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repository **Settings** tab
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch → **/ (root)** folder
5. Click **Save**

Your site will be live in ~60 seconds at:
`https://[your-github-username].github.io/kridati/`

---

## Before Going Live — Checklist

- [ ] Add your logo file `KRIDATI_SPORTS.png` to the repo (or remove logo references — the site already falls back to styled text)
- [ ] Update phone number in the Contact section (search `+91 XXXXX XXXXX`)
- [ ] Update CIN number when registered (search `CIN: [To be updated]`)
- [ ] Replace placeholder emails (`info@kridati.org`, `partnerships@kridati.org`) with your real addresses
- [ ] Add real social media links in the footer (search `href="#"` inside `.footer-socials`)
- [ ] Update copyright year if needed

---

## Custom Domain (Optional)

If you have a domain like `kridati.org`:
1. In GitHub Pages settings, enter your domain under **Custom domain**
2. Add a `CNAME` file to the repo root containing just: `kridati.org`
3. Update your domain's DNS with your registrar:
   - A records pointing to GitHub's IPs: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Or a CNAME record: `www → [your-username].github.io`

---

## Contact Form Note

The contact form uses a `mailto:` link (opens the user's email client). This works without a backend server and is ideal for static GitHub Pages hosting. When ready to upgrade to a real form backend, services like [Formspree](https://formspree.io) or [Netlify Forms](https://www.netlify.com/products/forms/) integrate easily with this codebase.
