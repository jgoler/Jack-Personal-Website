# jgoler.github.io

Source for my personal website. Static HTML/CSS, no build step.

- `index.html` — all page content
- `stylesheet.css` — design tokens at the top, then layout
- `images/` — profile photo, paper teasers
- `data/` — CV and bio

## Adding a publication

Copy the commented `<article class="pub">` template inside the Publications section
of `index.html`, fill it in, and place it above the existing entries so the list stays
reverse-chronological.

Teasers can be an `<img>` or a muted looping `<video>`. Keep them around 640px wide
and under ~1 MB so the page stays fast.

## Local preview

```
python3 -m http.server 8000
```

Layout originally adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron_website).
