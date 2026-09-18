# Nirali Narayan — Portfolio Website

A single-page, responsive portfolio. Plain HTML + CSS (no build step), so it
hosts on GitHub Pages for free in a few minutes.

## Files

```
index.html        ← the whole page (all sections + a little JavaScript)
style.css         ← all styling
assets/nirali.jpg ← your hero photo
README.md         ← this file
```

## Preview it on your computer first

Just double-click `index.html` — it opens in your browser. That's it.

---

## Put it online with GitHub Pages (free)

### Option A — no command line (easiest)

1. Go to https://github.com and sign in (your username is `niraliabhani18`).
2. Click **New** to create a repository.
   - **For a site at `https://niraliabhani18.github.io`**: name the repo exactly
     `niraliabhani18.github.io`.
   - **For a project site** like `https://niraliabhani18.github.io/portfolio`:
     name it anything, e.g. `portfolio`.
   - Keep it **Public**. Don't add a README (you already have one). Click **Create**.
3. On the new repo page, click **uploading an existing file**.
4. Drag in `index.html`, `style.css`, **and the `assets` folder** (with `nirali.jpg`
   inside it). Click **Commit changes**.
5. Go to **Settings → Pages** (left sidebar).
6. Under **Build and deployment → Source**, pick **Deploy from a branch**.
   Set branch to **main** and folder to **/ (root)**. Click **Save**.
7. Wait ~1–2 minutes, refresh the Pages settings, and your live link appears at
   the top. Done.

### Option B — with Git (command line)

```bash
cd portfolio
git init
git add .
git commit -m "Portfolio site"
git branch -M main
# replace REPO with your repo name (or niraliabhani18.github.io)
git remote add origin https://github.com/niraliabhani18/REPO.git
git push -u origin main
```

Then do steps 5–7 above to turn on Pages.

---

## Things to update (quick edits in `index.html`)

Open `index.html` in any text editor (Notepad, VS Code) and search for these:

- **Testimonials** — the three quote cards are **placeholders**. Find the
  "TESTIMONIALS" section and paste your real LinkedIn recommendations
  (name, role, and the quote). There's a reminder note in the page; delete it
  when finished.
- **Photo** — to swap your hero image, replace `assets/nirali.jpg` with a new
  square photo of the same name.
- **Links** — LinkedIn, GitHub, YouTube, email and phone all live near the top
  (hero) and bottom (contact). I used `linkedin.com/in/niraliabhani92` (from your
  latest branding doc). Your earlier résumé listed `linkedin.com/in/niraliabhani`
  — please confirm which one is your live profile and fix both spots if needed.

## Custom domain (optional)

If you buy a domain (e.g. `niralinarayan.com`), add it under
**Settings → Pages → Custom domain**, then point your domain's DNS to GitHub.
GitHub's guide: https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site

---

Design: deep-teal + persimmon editorial theme on warm paper, with a magazine-style
"contents" numbering — a nod to your writing, speaking and photography. Fully
responsive, keyboard-accessible, and it respects reduced-motion settings.
