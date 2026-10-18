# Avinash Singh Munda · Portfolio

Static site (HTML, CSS and JS in one file). There is no build step.

## Deploy to Vercel via GitHub
1. Create a new GitHub repository and upload everything in this folder (keep `assets/` beside `index.html`):
   ```
   git init && git add . && git commit -m "Portfolio"
   git branch -M main
   git remote add origin https://github.com/<you>/avinash-portfolio.git
   git push -u origin main
   ```
2. On vercel.com choose **Add New → Project**, then import that repository.
3. Framework Preset: **Other**. Leave the Build Command and Output Directory empty, then click **Deploy**.
4. Optional: add your domain under **Settings → Domains**.

## Edit
- Text and sections: `index.html`
- Portrait: `assets/avinash-bw.jpg`
