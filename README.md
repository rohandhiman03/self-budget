# Rohan's Budget App

Personal daily budget tracker — installable on iPhone as a home screen app.

## Deploy to GitHub Pages (5 steps)

1. Create a new repo on GitHub (any name, e.g. `budget`)
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "init"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. In your repo → **Settings → Pages → Source → GitHub Actions**
4. The workflow auto-runs and deploys ✅
5. Your app URL: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Add to iPhone Home Screen

1. Open the app URL in **Safari** on your iPhone
2. Tap the **Share** button (box with arrow)
3. Scroll down → tap **"Add to Home Screen"**
4. Tap **Add** — done! Opens full-screen like a native app.

## Run locally

```bash
npm install
npm run dev
```

## Data

All expenses are stored in your browser's `localStorage` — private to your device, no server involved.
