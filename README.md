# Learning Roadmap

Personal PWA for Japanese, finance/project-finance/modelling, and Excel fluency.

The product is deliberately simple: open it and immediately see **what to study next, which exact resource to use, how long to spend, and whether you're ahead or behind**.

- Japanese target: 4 hours/week
- Finance + modelling target: 4 hours/week
- Excel is folded into the finance track
- No streaks, points, badges or gamification
- One-tap “Done & advance” from the Today screen
- Exact current resource + quick links
- Weekly and cumulative ahead/behind tracking
- Adaptive suggested session length when behind
- Curriculum/resource roadmap
- Local-only study history with export/import backup
- Installable on iPhone from Safari

## GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.

If GitHub Pages is not available while this repository is private on your plan, make this repository public and repeat the Pages step.

## iPhone installation

Open the published Pages URL in Safari → Share / Page Menu → **Add to Home Screen** → **Open as Web App** → Add.

## Privacy

Study logs and completed curriculum tasks are saved in browser `localStorage`. They are not committed to GitHub. Use **Log → Export** periodically.

## App structure

- `index.html` — semantic app shell
- `styles.css` — responsive/mobile-first visual system
- `data.js` — Japanese, finance, Excel curricula and approved resource stack
- `app.js` — recommendation, progress, persistence and logging logic
- `manifest.webmanifest` — standalone PWA configuration
- `sw.js` — offline caching / update behaviour

No build tools or dependencies are required.