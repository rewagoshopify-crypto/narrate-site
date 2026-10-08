# Narrate website

Single-file static site (`index.html`). No build step.

## Push to GitHub
```
git init
git add .
git commit -m "Initial Narrate site"
git branch -M main
git remote add origin https://github.com/<your-username>/narrate-site.git
git push -u origin main
```

## Deploy to Vercel
Import the GitHub repo at vercel.com/new. Framework preset: Other. Leave build command and output directory empty. Deploy.
