# Rohan Mayekar Portfolio

A static website: one `index.html` plus images. No build step, no framework.

## What's in this folder

- `index.html`: the whole site (all text, styles and scripts)
- `photo.jpg`: your photo at the top
- `logos/`: Kiddopia, Azent and upGrad logos
- `certs/`: the four certificate images

Keep these files together in the same folder structure.

## Host it (pick one)

**Netlify Drop (fastest, about 2 minutes)**
1. Unzip this folder.
2. Go to app.netlify.com/drop and sign in with a personal email.
3. Drag the unzipped folder onto the page. You get a live link straight away.
4. Optional: Site settings → Domain management to add your own domain.

**GitHub Pages (best if you'll edit often)**
1. Create a GitHub account with a personal email, then a new public repository (for example `portfolio`).
2. Click "Add file" → "Upload files" and drag in everything from this folder.
3. Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`. Save.
4. Your site appears at `https://<username>.github.io/portfolio/` within a minute or two.

**Vercel**
1. Sign up with a personal email at vercel.com.
2. Import the GitHub repository from option 2, or install the Vercel CLI and run `vercel` in this folder.

## Edit it later

**Small text changes:** open `index.html` in any text editor (VS Code, or even Notepad / TextEdit in plain-text mode). Use Find to locate the exact text, change it and save. Then:
- Netlify Drop: drag the folder onto your site's Deploys page again.
- GitHub Pages: open `index.html` on GitHub, click the pencil icon, paste your change, commit. The site updates in a minute.

**Swap an image:** replace the file with a new one of the same name (for example a new `photo.jpg`) and re-upload.

**Bigger changes:** upload this zip to Claude on your personal account and describe what you want changed.

Where things live in `index.html`:
- Intro and name: the `<header class="nb-hero">` block near the top of `<body>`
- Jobs: `<section id="jobs">`
- Case studies and certificates: `<section id="case-studies">` (full case-study text is in a script near the bottom, in `var D={...}`)
- Recommendations: `<section id="recommendations">` (full texts are in the second `var D={...}` script)
- Awards, Skills, Contact: `<section id="awards">`, `<section id="skills">`, `<section id="contact">`
