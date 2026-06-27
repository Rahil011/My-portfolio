# Rahil Khan — Portfolio Website

A modern, responsive portfolio website for **Rahil Khan**, PHP Full Stack Developer.

Live demo: *(deploy using instructions below)*

## Features

- Dark luxury theme with gold accents
- Fully responsive (mobile, tablet, desktop)
- Smooth scroll animations & interactive timeline
- Profile photo hero section
- Downloadable resume (PDF)
- Contact form (opens email client)
- Links to [GitHub](https://github.com/Rahil011) & [LinkedIn](https://www.linkedin.com/in/rahil-khan-678278213)

## Project Structure

```
NewPortfolio/
├── index.html          # Main page
├── styles.css          # All styles
├── script.js           # Animations & interactions
├── assets/
│   ├── profile.png     # Profile photo
│   └── RahilKhan_Resume.pdf
└── README.md
```

## Preview Locally

Open `index.html` in your browser, or run a local server:

```bash
cd NewPortfolio
python3 -m http.server 8080
```

Then visit: http://localhost:8080

---

## Free Hosting on GitHub Pages

Follow these steps to host your portfolio **for free** at `https://rahil011.github.io/portfolio/` (or any repo name you choose).

### Step 1 — Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `portfolio` (or `rahil-khan-portfolio`)
3. Set visibility to **Public**
4. Click **Create repository**

### Step 2 — Push Your Code

```bash
cd /Users/rahil/NewPortfolio

git init
git add .
git commit -m "Add updated portfolio website"
git branch -M main
git remote add origin https://github.com/Rahil011/portfolio.git
git push -u origin main
```

> Replace `Rahil011/portfolio` with your actual GitHub username and repo name.

### Step 3 — Enable GitHub Pages

1. Open your repo on GitHub
2. Go to **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main` → Folder: `/ (root)`
5. Click **Save**

Your site will be live in 1–2 minutes at:
**`https://rahil011.github.io/portfolio/`**

### Step 4 — Link Portfolio on Your GitHub Profile

1. Go to [github.com/Rahil011](https://github.com/Rahil011)
2. Click **Edit profile**
3. In the **Website** field, paste your GitHub Pages URL:
   ```
   https://rahil011.github.io/portfolio/
   ```
4. Update your **Bio** to something like:
   ```
   PHP Full Stack Developer | Building secure, scalable web apps
   ```
5. Click **Save**

### Step 5 — Pin This Repository

On your GitHub profile, go to the **Repositories** tab → **Customize your pins** → pin your `portfolio` repo so visitors see it first.

---

## Replace Your Old Portfolio

You have two options:

| Option | URL Result |
|--------|-----------|
| **New repo** (`portfolio`) | `rahil011.github.io/portfolio/` |
| **Replace old repo** (`My-Portfolio`) | `rahil011.github.io/My-Portfolio/` (keeps same URL) |

To keep your existing URL, push to the old repo instead:

```bash
git remote add origin https://github.com/Rahil011/My-Portfolio.git
git push -u origin main --force
```

> Only use `--force` if you want to completely replace the old portfolio files.

---

## Update Resume

Replace `assets/RahilKhan_Resume.pdf` with your latest resume, then:

```bash
git add assets/RahilKhan_Resume.pdf
git commit -m "Update resume"
git push
```

GitHub Pages redeploys automatically on every push.

---

## Other Free Hosting Options

| Platform | URL | Notes |
|----------|-----|-------|
| [GitHub Pages](https://pages.github.com/) | `username.github.io/repo` | Best for dev portfolios, free forever |
| [Netlify](https://www.netlify.com/) | `yoursite.netlify.app` | Drag & drop deploy, free tier |
| [Vercel](https://vercel.com/) | `yoursite.vercel.app` | Great for static sites |
| [Cloudflare Pages](https://pages.cloudflare.com/) | `yoursite.pages.dev` | Fast CDN, free tier |

---

## Customization

- **Colors**: Edit CSS variables at the top of `styles.css` (`--accent`, `--bg`, etc.)
- **Content**: Update text directly in `index.html`
- **Projects**: Add/remove cards in the `#projects` section
- **Contact email**: Search for `rahil4356@gmail.com` across all files

---

## License

© Rahil Khan. All rights reserved.
