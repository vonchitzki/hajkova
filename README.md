# Marketa Hajkova

Static site for the fashion designer Marketa Hajkova. The homepage is `index.html`: a self-contained page (inline CSS and JS, fonts from Google Fonts: Bebas Neue for the logotype, Pinyon Script for titles, Cormorant Garamond for text, Jost for labels) with no build step. Open it in a browser or serve the folder.

Homepage structure (hero, fonts, image mats and navigation modelled on alexandragrecco.com): a fixed monochrome triptych hero that the page slides over, a navigation bar (pages, logotype, Instagram icon) that starts at the bottom of the first screen and sticks to the top, with a full-screen script menu on mobile, Svatební and Kolekce plates, a "Media" logo strip, a horizontally scrolling gallery of press images directly under it, a contact form, and a footer.

The three exploratory options that led to this page are kept in `options/` (runway, lookbook, atelier) for reference and can be deleted.

## Placeholders to replace before launch

- **Photography**: every image is an Unsplash stock URL marked with an HTML comment. Replace with the designer's own photographs (hero: six portrait photographs, two per panel, the middle panel's first photo is the one shown on mobile; plates: 4:5; gallery: 4:5).
- **Media logos**: `assets/media/*.svg` are public-domain wordmarks downloaded from Wikimedia Commons (Vogue, Elle, Harper's Bazaar, Marie Claire, Cosmopolitan, Glamour). They are layout placeholders, not confirmed features. Replace with the real press list; keep each logo as a monochrome SVG around 30px tall.
- **Gallery captions**: each caption names the outlet the image appeared in; set them from the real press images.
- **Instagram link**: all Instagram links point to `#`.
- **Page links**: Domů, O mně and the section links point to `#`; wire them to the real pages.
- **Contact form**: static markup only. Connect `action` to a form handler before launch.
- **Fonts**: the reference site's faces (ITC Kabel, Nicolas Cochin, Shelley Script) are commercial; the Google Fonts above are free stand-ins. License the originals if wanted. The logotype stays in Bebas Neue by choice.
- **Copy**: Czech draft copy; review with the designer. The `lang` attribute and centralized labels make an English version straightforward.
