# My first website

A first static HTML/CSS exercise with three stream pages and technology links.

[Português (Brasil)](README.pt-BR.md)

## Idea and process

Source reviewed on 2026-10-01. Educational walkthrough based on Code Institute material. No dated planning notes, wireframes or personal design diary were found in the reviewed files. This records the implemented exercise, not original product history.

## Architecture and design

index.html links to HTML5/CSS3 resources and external Wikimedia images. stream-two.html and stream-three.html contain headings and short text. css/style.css defines dark navigation, floated cards and image sizes; it references Oswald without loading the font. There is no JavaScript app, API or database in the reviewed structure.

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/`. External fonts/icons/images need network access. The preview was not run during this update; no current public deployment was verified.

## Testing and limitations

No automated suite was found in the reviewed root listing. Browser/manual checks were not run. All three pages have a stylesheet link missing its closing >; the first card uses lass instead of class. Validate HTML before relying on the layout. Check inter-page navigation, external image loading, narrow widths, keyboard focus and new-tab link safety. External logos/images retain their rights.

## Snapshots

No application screenshot was verified or added. Future dated files under `docs/assets/` should show actual desktop/mobile states, without personal form data. Add links only after files exist; never invent a working-state capture.

## Credits and licensing

Code Institute walkthrough/template material, libraries and assets retain their original rights. No new license is applied. The original README remains below as historical source, not current setup advice.

---

## Original README

# My very first website

Welcome! [Code Institute](https://codeinstitute.net)
