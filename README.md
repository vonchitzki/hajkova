# Marketa Hajkova

Static site for the fashion designer Marketa Hajkova. The homepage is `index.html`: a self-contained page (inline CSS and JS, Bebas Neue from Google Fonts, Helvetica from the system) with no build step. Open it in a browser or serve the folder.

Homepage structure: fixed hairline navigation (pages, logotype, Instagram icon), full-bleed monochrome hero with the name across the bottom edge, Svatební and Kolekce plates, a "Media" logo strip, a horizontally scrolling gallery of press images directly under it, a contact form, and a footer.

The three exploratory options that led to this page are kept in `options/` (runway, lookbook, atelier) for reference and can be deleted.

## Placeholders to replace before launch

- **Photography**: every image is an Unsplash stock URL marked with an HTML comment. Replace with the designer's own photographs (hero: a photo that crops well to landscape and portrait; plates: 4:5; gallery: 4:5).
- **Media logos**: `assets/media/*.svg` are public-domain wordmarks downloaded from Wikimedia Commons (Vogue, Elle, Harper's Bazaar, Marie Claire, Cosmopolitan, Glamour). They are layout placeholders, not confirmed features. Replace with the real press list; keep each logo as a monochrome SVG around 30px tall.
- **Gallery captions**: each caption names the outlet the image appeared in; set them from the real press images.
- **Instagram link**: all Instagram links point to `#`.
- **Page links**: Domů, O mně and the section links point to `#`; wire them to the real pages.
- **Contact form**: static markup only. Connect `action` to a form handler before launch.
- **Copy**: Czech draft copy; review with the designer. The `lang` attribute and centralized labels make an English version straightforward.
