# OceanCode AI — Official Website

Production-ready website for OceanCode AI, an AI development company specializing in Computer Vision, NLP, Deep Learning, and Neural Networks.

---

## 🚀 Deploy to Vercel (3 ways)

### Option 1 — Vercel CLI (recommended)

```bash
# 1. Install Vercel CLI
npm install -g vercel

# 2. Navigate to this project folder
cd oceancode-ai

# 3. Deploy (follow the prompts)
vercel

# 4. Deploy to production
vercel --prod
```

### Option 2 — Drag & Drop (easiest)

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **"Add New Project"**
3. Drag and drop the entire `oceancode-ai` folder onto the upload area
4. Click **"Deploy"** — your site will be live in ~30 seconds

### Option 3 — GitHub Integration (best for ongoing updates)

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → **"Add New Project"**
3. Import your GitHub repo
4. Vercel auto-detects the static site — click **"Deploy"**
5. Every `git push` will auto-deploy going forward

---

## 📁 Project Structure

```
oceancode-ai/
├── index.html      # Complete website (HTML + CSS + JS)
├── vercel.json     # Vercel deployment configuration
└── README.md       # This file
```

---

## ✏️ Customization Checklist

Before going live, update these in `index.html`:

| Item | Search for | Replace with |
|------|-----------|--------------|
| Email | `hello@oceancodeai.com` | Your real email |
| Domain | `www.oceancodeai.com` | Your real domain |
| Stats | `50+`, `30+`, `99%` | Your actual numbers |
| Social links | `href="#"` in footer socials | Your real social URLs |
| Copyright year | `© 2025` | Current year |

---

## 🌐 Custom Domain on Vercel

1. In your Vercel project → **Settings → Domains**
2. Add your domain (e.g. `oceancodeai.com`)
3. Update your DNS records as instructed by Vercel
4. SSL certificate is provisioned automatically (free)

---

## 🛠️ Tech Stack

- Pure HTML5 / CSS3 / Vanilla JS — zero dependencies, zero build step
- Google Fonts: Syne (headings) + DM Sans (body)
- Canvas API for animated particle field
- IntersectionObserver for scroll-triggered animations
- Fully responsive (mobile, tablet, desktop)
