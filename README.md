# Culturama

A landing page for a cultural events platform — browse categories (shows, theater, festivals, cinema...), see upcoming events and check an agenda of what's coming next.

Built while practicing HTML/CSS layout (flexbox and grid) at Alura.

## Stack

- HTML5
- CSS3 — flexbox and grid layouts, split into separate stylesheets (`grid.css`, `flex.css`, `style.css`)
- [Meyer reset](https://meyerweb.com/eric/tools/css/reset/) (via CDN) for base styles
- Google Fonts (Fjalla One, Work Sans)

## Running locally

No build step — open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then go to http://localhost:8000.

## Structure

```
index.html
assets/
  style/
    grid.css
    flex.css
    style.css
  img/
```
