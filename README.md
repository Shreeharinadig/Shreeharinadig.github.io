# Shree Hari Nadig B M — Portfolio

Personal portfolio site for recruiters. Single static page, hosted free on GitHub Pages.

- Live: https://shreeharinadig.github.io
- Repo: https://github.com/Shreeharinadig/Shreeharinadig.github.io
- Pages source: `main` branch, repo root

## Structure

One self-contained `index.html`: inline CSS and JS, no build step, no framework. The only external load is Google Fonts (Bricolage Grotesque, IBM Plex Sans, IBM Plex Mono).

- Slide-in drawer (hamburger, top left) with table of contents, GitHub and LinkedIn links, and theme switch
- Sections: Overview, About, Experience, Projects, Skills, Education, Contact
- Light and dark theme via CSS tokens in `:root`, following `prefers-color-scheme` with a manual toggle (`data-theme`)
- JS extras: reading-progress bar, scroll-spy, count-up metrics, card spotlight, canvas network background. All motion is disabled under `prefers-reduced-motion`.

## Run locally

Open `index.html` in a browser. No install or build needed.

## Update and deploy

```powershell
git add index.html
git commit -m "Update portfolio"
git push origin main
```

GitHub Pages refreshes 1–2 minutes after a push. Hard refresh (Ctrl+F5) to bypass cache.

