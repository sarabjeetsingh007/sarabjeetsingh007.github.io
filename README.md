# sarabjeetsingh007.github.io

Personal website of Sarabjeet Singh, served by GitHub Pages from the `master` branch.

Plain HTML and CSS, with no build step. The `.nojekyll` file tells GitHub Pages to serve the files as they are.

| Path | What |
|---|---|
| `index.html` | The whole site: about, news, publications, experience, service, software, education, contact |
| `assets/css/site.css` | All styles, including dark mode and phone layout |
| `assets/fonts/` | Inter variable font (SIL Open Font License, see `OFL.txt`) |
| `files/` | Paper PDFs and the CV (`Sarabjeet_Singh_CV.pdf`) |
| `images/profile.jpg` | Photo |
| `life-as-sarab/` | Non-academic page (not linked from the menu) |
| `about/`, `cv/`, `resume/`, `publications/`, `tools/`, `contact/`, `about.html` | Redirects from the old site's URLs |
| `404.html`, `sitemap.xml`, `robots.txt`, `favicon.svg`, `apple-touch-icon.png` | Site plumbing |

## Editing
- **News:** add a `<li>` at the top of the first list in `#news`. Move the oldest visible item into the "older news" list to keep about six visible.
- **Publications:** copy a `<li class="pub">` block. Badge classes: `conf`, `journal`, `gov`, `workshop`, `other`.
- Update "Last updated" in the footer and `lastmod` in `sitemap.xml`.

## Preview locally
```
python3 -m http.server 8000
```
Run this from this folder, then open http://localhost:8000.
