# ivorjuechtern.de

The website of Ivor Jüchtern UG, in German (top level) and English (`/english/`).

## How it works

- `content/` – articles as Markdown, one file per language
  (`de-<address>.md`, `en-<address>.md`), images next to them in `images/`.
- `templates/` – page templates, `style.css`, fonts, images and the fixed
  texts per language (`templates/texts/de.json`, `en.json`).
- `generate.js` – runs [generator.js](https://github.com/dahoum/generator.js)
  (version pinned in `package-lock.json`).
- `public/` – the built site. It is **not** in the repository: statichost.eu
  builds it on every deploy (see `statichost.yml`).

## Building locally

```
npm ci
npm run build
```

Then open `public/index.html`, or serve the folder, for example with
`python3 -m http.server --directory public`.
