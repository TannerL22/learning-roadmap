# Learning Roadmap

Personal PWA for tracking Japanese study, finance/project-finance/modelling study, and Excel fluency.

- Japanese target: 4 hours/week
- Finance + modelling target: 4 hours/week
- No streaks, points, badges or gamification
- Daily check-ins and notes
- Weekly + cumulative ahead/behind tracking
- Curriculum/resource roadmap
- Local-only study history with export/import backup
- Installable on iPhone from Safari

## GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.

If GitHub Pages is not available while this repository is private on your plan, make this repository public and repeat the Pages step.

## iPhone installation

Open the published Pages URL in Safari → Share / Page Menu → **Add to Home Screen** → **Open as Web App** → Add.

## Privacy

Your study logs and completed curriculum tasks are saved in browser `localStorage`. They are not committed to GitHub. Use **History → Export backup** periodically.

## Editing the curriculum

The curriculum and resource stack are defined near the top of `app.js`:
- `japaneseRoadmap`
- `financeRoadmap`
- `excelRoadmap`
- `resources`

No build tools or dependencies are required.
