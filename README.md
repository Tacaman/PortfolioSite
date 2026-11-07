# Diogo Rodrigues — Engineering portfolio

Live site: https://tacaman.github.io/

Original green-and-black palette: https://tacaman.github.io/?theme=classic

Static, bilingual personal portfolio, ready for GitHub Pages. The website is in `dist/` and needs no build or external dependencies.

## Publishing

GitHub Pages: deploy the `dist/` directory through the included Pages workflow. Set Settings → Pages → Source to GitHub Actions. The repository must be public for Pages on GitHub Free.

## Content

The public copy is based on the professional/academic portfolio in Notion and the CV updated on 6 November 2026. `cases.json` is the reference dataset; the page embeds that data for a self-contained static experience. Update both when changing project content.

`Diogo-Rodrigues-CV.pdf` is the current two-page designed CV. The separately labelled ATS PDF is retained from the preceding version.

## Colours and rollback

Blue is the default: `dist/themes/blue.css`, based on the updated CV (#172638, #0070ad, #edf8fc, white).

The original palette is preserved in `dist/themes/green-black.css`. Preview it by adding `?theme=classic` to the site URL. To restore it as the default, change the stylesheet href on `#colour-theme` in `dist/index.html` to `themes/green-black.css`.

The complete pre-change source is also preserved by the tag `reference-green-black-2026-11-06` in the original Sites source repository, at commit `1791763d914afdbbfddd40a40283289b194ebe9b`.

## Maintenance

The diagram selects project filters. Embedded systems and converter control share the controller block; hardware/validation is represented by the feedback path. PT/EN selection is remembered in the browser. No backend, analytics or external data calls are required.
