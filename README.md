# MKT3039 AS2 — E-Portfolio
**Anh (Jinny) Truong · 25832146 · University of Northampton**

A single-page, dossier-styled companion site for **MKT3039 Digital Marketing — Assignment 2**, analysing Warner Bros. Discovery's *Wizarding World* franchise as a case study in transmedia brand management and digital audience engagement.

Built as a static HTML artefact for direct deployment to GitHub Pages — no build step, no framework, no dependencies beyond the CDN-hosted fonts.

---

## Contents

The portfolio is organised as a **6-file folder stack**. Each tab maps to a section of the written report:

| Tab | Title | Focus |
| --- | --- | --- |
| File 01 | Introduction | Portfolio overview, navigation, and assignment framing |
| File 02 | Ladder of Engagement | Permission-marketing analysis with image-ring evidence |
| File 03 | TikTok Social-Media Zones | Zone-by-zone fit assessment with carousel evidence |
| File 04 | Website Checklist | Structural mimic of harrypotter.com's information architecture |
| File 05 | Trend Analysis | Chronological evidence of franchise-wide trend responses |
| File 06 | Conclusion & References | Synthesis and Harvard-style reference list |

---

## How to publish on GitHub Pages (step by step)

### Step 1 — Create a GitHub account
1. Go to [github.com](https://github.com) and sign up for a free account.
2. Verify your email address.

### Step 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it exactly: `mkt3039-portfolio`
3. Set it to **Public**
4. Tick **Add a README file**
5. Click **Create repository**

### Step 3 — Upload your file
1. Rename `index-2.html` to `index.html` so GitHub Pages serves it at the site root.
2. Inside your new repository, click **Add file** → **Upload files**
3. Drag and drop `index.html` into the upload area
4. Scroll down and click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click **Settings** (top menu of your repo)
2. Scroll down to **Pages** (left sidebar)
3. Under **Branch**, select `main` → folder `/root`
4. Click **Save**

### Step 5 — Get your link
GitHub will show you your live URL — it will look like:
```
https://YOUR-USERNAME.github.io/mkt3039-portfolio/
```
It takes about 1–2 minutes to go live. Refresh if you see a 404.

That's the URL you submit.

---

## Running locally (optional)

No build step, no dependencies. Either:

```bash
open index-2.html
```

…or serve the folder with any static server, e.g.:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/index-2.html
```

---

## Tech stack

- Plain **HTML5** + **CSS** (custom properties, CSS grid, sticky positioning, per-item accordion)
- Vanilla **JavaScript** — no framework, no bundler
- Fonts: **Playfair Display**, **Courier Prime** (Google Fonts), **Computer Modern** (CDN)

---

## Files in this project
- `index.html` (or `index-2.html` before renaming) — the entire portfolio, single-file
- `README.md` — this document

## Notes
- All fonts load from external CDNs — viewing requires an internet connection.
- The portfolio is fully self-contained — no other files needed.
- Third-party screenshots are reproduced for non-commercial academic critique under fair-dealing provisions.

---

## Academic context

- **Unit:** MKT3039 Digital Marketing
- **Assessment:** Assignment 2 — E-Portfolio
- **Referencing style:** Harvard
