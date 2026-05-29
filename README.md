# 🚀 Rajneesh Chauhan — Data Scientist Portfolio

A production-grade, single-file portfolio website for a Data Scientist & MLOps Engineer. Built with pure HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies. Deploy anywhere in under 2 minutes.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🎨 **Dark DS Aesthetic** | Terminal-inspired design with cyan accents, grid background, and noise overlay |
| ⚙️ **Admin Panel** | Edit hero text, project links, resume URLs, certifications, and contact info live |
| 📄 **Resume Section** | View + Download buttons, LinkedIn, GitHub, and Kaggle profile links |
| 🏆 **Certifications** | Add/remove certs with names, issuers, dates, icons, and direct links |
| 🔗 **GitHub Project Links** | All 3 projects linked directly to your repos |
| 📊 **Live Metrics** | ROC-AUC, precision, RAG faithfulness displayed as hero stats |
| 💾 **Persistent Admin Edits** | Changes saved to `localStorage` — survive page refresh |
| 🖱️ **Scroll Animations** | Fade-in on scroll for all major sections |
| 📱 **Responsive** | Mobile-friendly layout |

---

## 📁 Project Structure

```
portfolio/
├── portfolio.html          # Main portfolio file (everything in one file)
├── best_DS_resume.pdf      # Your resume PDF (place in same folder)
└── README.md               # This file
```

> **Keep your resume PDF** named `best_DS_resume.pdf` in the same folder, OR update the links via the Admin Panel.

---

## ⚙️ Admin Panel Guide

Click the **⚙ Admin** button in the top-right navbar.

### Tabs:

**Hero** — Edit your name, title, and summary paragraph.

**Projects** — Update GitHub repo URLs and project titles for all 3 projects.

**Certifications** — Add new certificates:
1. Enter the certificate name, issuer, date, and emoji icon.
2. Paste a **public URL** to the certificate (Google Drive, LinkedIn, Dropbox, etc.).
3. Click **Add Certificate** — it renders immediately on the page.

**Resume Links** — Paste your hosted resume URLs:
- View URL → opens PDF in browser
- Download URL → triggers download
- LinkedIn profile URL

**Contact** — Update email, phone, location, GitHub, Kaggle links.

---

## 📤 How to Add Your Certificates

1. Upload your certificate PDF/image to **Google Drive**
2. Right-click → **Get link** → set to **Anyone with the link**
3. Copy the link and paste it in **Admin Panel → Certifications → Certificate URL**

For a direct download link from Google Drive, use:
```
https://drive.google.com/uc?export=download&id=YOUR_FILE_ID
```

---

## 🌐 Free Forever Deployment Options

### Option 1: GitHub Pages (Recommended — 100% Free Forever)

```bash
# 1. Create a new GitHub repo named: yourusername.github.io
#    e.g. Codex610.github.io

# 2. Clone it and add your files
git clone https://github.com/Codex610/ds-portfolio
cd Codex610.github.io

# 3. Copy your portfolio files here
cp /path/to/portfolio.html index.html
cp /path/to/best_DS_resume.pdf .

# 4. Push to GitHub
git add .
git commit -m "🚀 Launch portfolio"
git push origin main
```

Your portfolio is live at: `https://Codex610.github.io`

> ✅ Free | Custom domain support | Automatic HTTPS | Forever free

---

### Option 2: Netlify Drop (Easiest — No Account Needed)

1. Go to **https://app.netlify.com/drop**
2. Drag and drop your `portfolio.html` + `Best-DS.pdf` folder
3. Done — you get a live URL instantly like `https://abc123.netlify.app`

To keep it permanently: create a free Netlify account and claim the site.

> ✅ Free | Custom domain | HTTPS | 100GB bandwidth/month

---

### Option 3: Vercel

```bash
npm install -g vercel
cd your-portfolio-folder
vercel
```

Follow prompts → get a URL like `https://portfolio.vercel.app`

> ✅ Free | Fastest CDN | Custom domain | Instant deploys

---

### Option 4: Cloudflare Pages

1. Push your files to a GitHub repo
2. Go to **https://pages.cloudflare.com**
3. Connect your GitHub repo → deploy

> ✅ Free | Global CDN | Custom domain | Unlimited bandwidth

---

## 🔗 Resume PDF Hosting (for the Admin Panel links)

Once deployed on GitHub Pages, your resume is accessible at:
```
https://Codex610.github.io/best_DS_resume.pdf
```

Use this as your View and Download URL in the Admin Panel.

---

## 🛠️ Customization Cheatsheet

| Want to change | Where |
|---|---|
| Name, title, summary | Admin Panel → Hero |
| Project GitHub links | Admin Panel → Projects |
| Certificate details | Admin Panel → Certifications |
| Resume PDF link | Admin Panel → Resume Links |
| Contact info | Admin Panel → Contact |
| Colors | Edit `:root` CSS variables in `<style>` |
| Metrics (ROC-AUC etc.) | Edit `.hero-metrics` section in HTML |
| Skills | Edit `.skills-grid` section in HTML |

---

## 🎨 Color Palette

| Variable | Color | Use |
|---|---|---|
| `--bg` | `#05080f` | Page background |
| `--surface` | `#0c1120` | Card backgrounds |
| `--accent` | `#00e5ff` | Cyan highlights, links |
| `--accent2` | `#7c3aed` | Purple accents |
| `--accent3` | `#f59e0b` | Amber dates/badges |
| `--green` | `#10b981` | Metric badges |

---

## 📬 Contact

**Rajneesh Chauhan**
- Email: rajnishchauhan912556@gmail.com
- GitHub: [@Codex610](https://github.com/Codex610)
- Kaggle: [@rajneesh08032004](https://kaggle.com/rajneesh08032004)
- LeetCode: [@rajNish_001](https://leetcode.com/u/rajNish_001)

---

*Built with precision. Deployed with purpose.* 🚀
