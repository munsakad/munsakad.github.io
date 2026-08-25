# munsakad.github.io

Personal portfolio site for Dingani Munsaka, built with plain HTML, CSS, and
JavaScript and hosted on [GitHub Pages](https://pages.github.com/).

Live at: https://munsakad.github.io

## Structure

```
index.html       Page structure and content (About, Experience, Projects, Skills, Education, Contact)
styles.css       All styling — layout, colors, responsive rules, dark/light theme
script.js        Mobile nav toggle, dark/light theme toggle, scroll-spy nav, reveal-on-scroll, back-to-top
assets/          Images and resume — see assets/README.md
```

## Local preview

No build step — open `index.html` directly in a browser, or serve the folder
with any static file server (e.g. the VS Code "Live Server" / "Live Preview"
extension) to test with a local URL.

## Before this goes fully live

- [ ] Add your real resume PDF at `assets/resume.pdf` (see `assets/README.md`)
- [ ] Optionally swap `assets/avatar.svg` for a real headshot

## Deploying changes

```bash
git add .
git commit -m "Describe your change"
git push
```

GitHub Pages rebuilds automatically after each push (usually within a minute
or two).
