
# Netflix-style Portfolio

This repository contains a static, Netflix-style portfolio landing page (single-file `index.html`) for Gunjan Deshpande.

Live site
---------

The site is published via GitHub Pages and is available here:

https://gunjan-d.github.io/Netflix-port/

How to publish on GitHub (if you need to re-publish):

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

Notes:
- `index.html` uses an inline stylesheet and script. If you want to split CSS/JS into separate files, move styles and scripts into `styles.css` and `script.js` and update `index.html` accordingly.
- Large media files (e.g., `hiring.mp4`) are not included. Add them to the repo if you want a video hero.
  /////////////////////////////////////////////////
