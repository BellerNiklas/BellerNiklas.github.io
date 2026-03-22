# Niklas Beller Website

Personal academic website hosted on GitHub Pages.

Live site: [https://bellerniklas.github.io](https://bellerniklas.github.io)

## Repository Structure

- `index.html` - homepage
- `style.css` - site styling
- `profile.jpg` - portrait used on the homepage
- `cv.pdf` - current CV shown on the site
- `cv.tex` - LaTeX source for the CV

## Local Preview

Open `index.html` directly in a browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Updating Content

- Homepage text and links: edit `index.html`
- Visual styling: edit `style.css`
- CV: replace `cv.pdf` and, if needed, update `cv.tex`
- Profile image: replace `profile.jpg`

## Publishing

```bash
git add index.html style.css cv.pdf cv.tex profile.jpg README.md .gitignore
git commit -m "Update website"
git push
```
