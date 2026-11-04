# sethuastro.github.io

Source for my academic homepage, **https://sethuastro.github.io**.

I'm Sethulekshmi Beena, an astrophysics researcher with an MSc in Astrophysics (Distinction) from the University of Hertfordshire. The site summarises my research on the cold molecular gas in the z = 4.425 submillimetre galaxy SGP 38326, my open-source code CMB-Decoupling, and my background.

## How it's built

A single static page, `index.html`, written in plain HTML, CSS and a small amount of JavaScript. There is no framework and no build step. GitHub Pages serves it directly from the `main` branch.

- Font: IBM Plex Sans, from Google Fonts.
- Light and dark themes follow the system setting, through CSS colour tokens.
- `images/headshot.jpg`: profile photo.
- `images/visibility_function.png`: copied from [CMB_Decoupling](https://github.com/sethuastro/CMB_Decoupling) (`figures/visibility_function.png`).
- The [CI] spectrum in the Research section is drawn as an SVG by the inline script. It is a schematic profile, not data.

## Previewing locally

Open `index.html` in a browser, or run:

```
python -m http.server
```

and then visit http://localhost:8000.
