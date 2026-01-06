# Personal Website — Starter

This is a minimal, accessible static personal website.

Preview locally:
- Using Python (quick): `python3 -m http.server 8000` then open http://localhost:8000
- Or use VS Code Live Server / any static file server.

Customize:
- Edit `index.html` to add your name, bio, projects, and links.
- Edit `styles.css` to tweak colors, fonts, and layout.
- Replace social links and mailto in `index.html`.

Deploy options:

1) GitHub Pages (simple)
- Create a new GitHub repository (or use an existing one).
- Push the files to the `main` branch:
  ```
  git init
  git add .
  git commit -m "Initial site"
  git branch -M main
  git remote add origin https://github.com/OWNER/REPO.git
  git push -u origin main
  ```
- In your repository on GitHub go to Settings → Pages and set:
  - Source: Branch → `main` and folder → `/ (root)` (or `/docs` if you prefer).
- After a minute, your site will be published at `https://OWNER.github.io/REPO` (or the repository's Pages URL shown in Settings).

2) Vercel (recommended for automatic deploys)
- Go to https://vercel.com, sign in with GitHub, import your repository, and deploy. Vercel will automatically build and serve this static site.
- Optionally install the Vercel CLI: `npm i -g vercel` and run `vercel` from the project folder.

Custom domain:
- Add your domain in Pages or Vercel dashboard and follow their instructions to add the DNS records.

Next steps:
- If you'd like I can:
  - personalize the content (fill in your name, bio, projects),
  - add an About page and blog support,
  - convert to a generator (Next.js/Hugo) or add analytics,
  - push the files for you after you create the empty repo (tell me when it's ready).
