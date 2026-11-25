# Portfolio

Personal portfolio website of Pacôme Ahoussinou — software and web developer, Cotonou, Benin.

**Live:** https://ahoussinoupacome123-lang.github.io/portfolio/

## Files

| File | What it is |
|---|---|
| `index.html` | The site. Open it in a browser, or serve this folder from any static host. |
| `pacome-portfolio.html` | The page without the outer HTML shell. `index.html` is built from it. |
| `cv-source.html` | Source for the CV PDF (A4, one page). |
| `pacome-ahoussinou-cv.pdf` | The CV the site links to. |
| `og.jpg` | The preview card shown when the link is shared. |

## Editing

Nearly all the content lives in the `SITE` object near the bottom of `pacome-portfolio.html`:
name, role, email, links, projects, certificates, skills, experience and education. The terminal
section reads the same object, so adding a project updates the list, the preview cards and the
`projects` command at once.

After editing `pacome-portfolio.html`, rebuild `index.html` so the `<head>` metadata stays in place.
The two branches are kept in sync: `main` holds the source, `gh-pages` is what GitHub Pages serves.
