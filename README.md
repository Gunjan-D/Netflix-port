# Netflix-style Portfolio (Gunjan Deshpande)

This repository contains a static, Netflix-style portfolio landing page (single-file `index.html`) for Gunjan Deshpande.

How to publish on GitHub:

1. Ensure this folder is a git working copy. If not, initialize and add remote:

```powershell
git init
git remote add origin https://github.com/Gunjan-D/Netflix-port
git branch -M main
git add -A
git commit -m "Add Netflix-style portfolio site"
git push -u origin main
```

2. On GitHub, go to the repository Settings → Pages and enable GitHub Pages using the `main` branch and the root folder.

3. The site will be available at `https://Gunjan-D.github.io/Netflix-port/` (may take a minute for GitHub Pages to publish).

Notes:
- `index.html` uses an inline stylesheet and script. If you want to split CSS/JS into separate files, move styles and scripts into `styles.css` and `script.js` and update `index.html` accordingly.
- Large media files (e.g., `hiring.mp4`) are not included. Add them to the repo if you want a video hero.
