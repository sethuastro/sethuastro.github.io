# sethuastro.github.io

Source for my academic homepage, **https://sethuastro.github.io**.

I'm Sethulekshmi Beena, an MSc Astrophysics student at the University of Hertfordshire. The site summarises my research on [CI] diagnostics of molecular gas in the z = 4.42 submillimetre galaxy SGP 38326, my computational projects, and my background.

## How it's built

A single static page, `index.html`, written in plain HTML, CSS and a small amount of JavaScript. There is no framework and no build step. GitHub Pages serves it directly from the `main` branch.

- Fonts: Instrument Serif, IBM Plex Sans and IBM Plex Mono, from Google Fonts.
- Light and dark themes follow the system setting, through CSS colour tokens.
- The [CI] spectrum in the header is drawn as an SVG by the inline script. It is a schematic profile, not data.

## Previewing locally

Open `index.html` in a browser, or run:

```
python -m http.server
```

and then visit http://localhost:8000.

