---
name: Marketa Hajkova
description: A fashion-show opening on a lookbook body; white ground, black ink, one hairline, Bebas Neue for the logotype alone and Helvetica Neue for everything else, bold and tight for titles, regular for reading.
colors:
  white: "#ffffff"
  paper: "#f5f4f1"
  black: "#111111"
  ink: "#1a1a1a"
  text-soft: "#3a3a3a"
  grey: "#6a6a6a"
  line: "#e2e0dc"
  line-field: "#cfcdc8"
typography:
  display:
    fontFamily: "Bebas Neue, Oswald, Arial Narrow, sans-serif"
    fontSize: "99px"
    fontWeight: 400
    lineHeight: 0.95
    letterSpacing: "0"
  brand:
    fontFamily: "Bebas Neue, Oswald, Arial Narrow, sans-serif"
    fontSize: "24px"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0"
  headline:
    fontFamily: "Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(32px, 3.4vw, 48px)"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "-0.03em"
  menu:
    fontFamily: "Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "30px"
    fontWeight: 700
    lineHeight: 1.6
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.6
    letterSpacing: "-0.03em"
  body:
    fontFamily: "Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0"
  label:
    fontFamily: "Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0.12em"
  label-tracked:
    fontFamily: "Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.14em"
  label-quiet:
    fontFamily: "Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0.08em"
  caption:
    fontFamily: "Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0.04em"
rounded:
  none: "0"
  circle: "50%"
spacing:
  hairline: "1px"
  field-gap: "8px"
  gallery-gap: "16px"
  title-gap: "20px"
  nav-gap: "28px"
  form-gap: "30px"
  gutter: "clamp(20px, 4vw, 64px)"
  gallery-top: "clamp(56px, 7vw, 110px)"
  section: "clamp(80px, 11vw, 170px)"
  contact: "clamp(90px, 12vw, 180px)"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    typography: "{typography.label-tracked}"
    rounded: "{rounded.none}"
    padding: "20px"
  button-primary-hover:
    backgroundColor: "{colors.black}"
    textColor: "{colors.white}"
  button-arrow:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  link-underline:
    textColor: "{colors.ink}"
    typography: "{typography.label-quiet}"
    rounded: "{rounded.none}"
    padding: "0 0 3px 0"
  input-hairline:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: "4px 0 12px 0"
  nav-over-hero:
    backgroundColor: "transparent"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    height: "64px"
  nav-solid:
    backgroundColor: "rgba(255,255,255,.96)"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    height: "64px"
  plate-figure:
    backgroundColor: "{colors.paper}"
    rounded: "{rounded.none}"
  caption-below-image:
    backgroundColor: "transparent"
    textColor: "{colors.grey}"
    typography: "{typography.caption}"
    padding: "12px 0 0 0"
  footer:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.grey}"
    typography: "{typography.caption}"
    padding: "56px 0 32px"
---

# Design System: Marketa Hajkova

## Overview

**Creative North Star: "The Show Title on a Lookbook"**

The homepage opens like a fashion show and continues like a lookbook. The first viewport is one grayscale photograph with the designer's name set as a condensed logotype dead centre of the frame; everything after it is quiet white plates, one hairline band of press logos, a scroll row of gallery frames, a centered form and a paper-grey footer. Chrome is small, tracked and grey so the photographs carry the page; density is deliberately low, one image and one title per plate.

The world is white ground and black ink with a single hairline weight between them. Bebas Neue is the logotype and nothing else: the hero name, the nav brand, the footer brand. Every other word is Helvetica Neue; section titles are Bold (700) and tight (-0.03em) in sentence case, reading text is Regular (400), and the small chrome is Regular at 12px, tracked. There are no boxes, no shadows and no radius anywhere except the two circular gallery arrows. The hero photograph is forced to grayscale; plates and gallery frames keep muted colour (saturation 0.6) so the work reads as photographed, not as a filter.

Of the user's pinned palette (white, black, beige, grey) beige lands only as Paper (#f5f4f1), the footer ground and the well behind every loading photograph. Rejected on evidence: the centered-logo card stack, colour accents, ornament.

**Key Characteristics:**
- White ground, black ink, one hairline (1px); Paper is the only warm surface and it holds the footer and image wells.
- Bebas Neue 400 uppercase at letter-spacing 0 for the logotype only (hero 99px, nav and footer 24px); Helvetica Neue 700 at -0.03em for every section title, 400 for every paragraph, label and caption.
- Hero photograph grayscale; plate and gallery photographs at 60% saturation in a fixed 4:5 frame.
- The only curve is the 44px circular gallery arrow; every other edge is square.
- One easing curve (cubic-bezier(.19,1,.22,1)), slow entrances, every animation behind prefers-reduced-motion.

## Colors

An achromatic palette with one warm off-white: white and paper as grounds, black and ink as type and fill, two greys for secondary text, two hairline tints.

### Primary
- **Ink** (#1a1a1a): body text, every title on white, the solid nav text, the submit button fill, the focused field edge, the caret, the footer logotype. The working black of the page.
- **White** (#ffffff): the page ground, the nav and logotype over the hero, the submit label; also the text colour of a selection.

### Neutral
- **Paper** (#f5f4f1): the footer ground and the well behind every plate and gallery photograph while it loads. The one warm value; it is a ground, never a card.
- **Black** (#111111): the hero backdrop behind the photograph, the selection highlight and the submit hover fill.
- **Text soft** (#3a3a3a): paragraph text beside a plate and in the contact intro, one step lighter than Ink so titles lead.
- **Grey** (#6a6a6a): secondary text on white: the Media heading, the gallery counter, gallery captions, field labels, every footer link and the footer legal line.
- **Line** (#e2e0dc): the hairline on white: Media band rules, gallery arrow rings, footer rule, mobile menu dividers.
- **Line field** (#cfcdc8): the resting underline of every form field; it darkens to Ink on focus.

### Named Rules
**The One Hairline Rule.** Every rule, divider, ring and field underline is 1px. On white it is Line; under a field it is Line field; over a photograph or in the nav it is currentColor at 35% opacity. No 2px rules, no borders around boxes.

**The Paper Is a Ground Rule.** Paper fills the footer edge to edge and the well behind photographs. It is never a panel, card or chip on white.

**The Monochrome Hero Rule.** The hero photograph is `filter: grayscale(1) contrast(1.02)`; every other photograph is `filter: saturate(.6)`. Any image replacing a placeholder inherits the filter of its slot.

## Typography

**Display Font:** Bebas Neue (with Oswald, Arial Narrow, sans-serif; loaded from Google Fonts), logotype only
**Body Font:** Helvetica Neue (with Helvetica, Arial, sans-serif; system), titles and text

**Character:** The condensed uppercase face is a wordmark, not a type style: it sets the designer's name three times (hero, nav, footer) at letter-spacing 0, regular weight, never bolded or italic, and appears nowhere else. Everything with meaning in it is the grotesk in two voices: Bold at -0.03em for section titles in sentence case, Regular at 16px/1.6 and letter-spacing 0 for reading text. The small chrome (12px) is Regular and tracked open, wider as it gets more button-like (0.04em caption, 0.08em links and labels, 0.12em nav, 0.14em submit). Hierarchy comes from weight and size within one family, with the logotype as the single foreign object.

### Hierarchy
- **Display** (Bebas 400, 99px fixed, 0.95, 0): the hero logotype "Marketa Hajkova" only, centered in the hero both ways (flex, text-align center) inside the gutter. The two words are inline-block spans with 0.1em side padding; below 860px they stack into a column at the same 99px with the padding removed.
- **Brand** (Bebas 400, 24px, 1, 0): the nav logotype (22px below 860px, with 2px top padding to sit on the optical centre) and the footer logotype in Ink.
- **Headline** (Helvetica Neue 700, clamp(32px, 3.4vw, 48px), 1.05, -0.03em, sentence case): plate titles ("Svatební", "Kolekce"), the gallery title ("Galerie") and the contact title ("Napište mi"); 20px to the paragraph beneath a plate, 18px in contact. Fixed at 32px below 860px.
- **Menu** (Helvetica Neue 700, 30px, -0.03em, sentence case): the five links of the open mobile menu, 14px vertical padding, Line dividers.
- **Title** (Helvetica Neue 700, 20px, -0.03em, Grey, centered): the Media band heading, the one small bold title in the build.
- **Body** (400, 16px, 1.6, 0): paragraphs at max 36ch beside a plate (Text soft), 40ch in contact; form input and textarea text is the same face, weight and size in Ink.
- **Label** (400, 12px, 0.12em, uppercase): nav links and the mobile "Menu" / "Zavřít" button.
- **Label tracked** (400, 12px, 0.14em, uppercase, line-height 1): the submit button label.
- **Label quiet** (400, 12px, 0.08em, sentence case): underlined plate links, field labels, the gallery counter (tabular numerals).
- **Caption** (400, 12px, 0.04em): gallery captions in Grey, 12px below the frame. Footer text and links are 12px Grey at normal tracking, with the legal line beneath a hairline.

### Named Rules
**The Logotype Only Rule.** Bebas Neue sets the name "Marketa Hajkova" and nothing else. It is never used for a section title, a label, a button or a menu link; a new surface that needs a title sets it in the grotesk.

**The Bold Tight Title Rule.** Every section title is Helvetica Neue 700 at -0.03em in sentence case, clamp(32px, 3.4vw, 48px) with line-height 1.05. Smaller titles keep the weight and tracking and drop the size (30px menu, 20px Media); nothing else in the build is bold.

**The Title Is the Logotype Rule.** Over the hero the nav logotype is hidden (opacity 0); the display name is the brand. The logotype fades in when the nav turns solid, and is always visible on mobile.

## Layout

One fluid gutter (clamp(20px, 4vw, 64px)) frames every section; there is no max-width container except the contact column (560px, centered). Plates sit on a 12-column grid with the gutter as column gap: the image takes columns 2 to 6 and the text columns 8 to 11, vertically centered; the alternate plate mirrors (image 7 to 11, text 2 to 5). Column 1 and column 12 stay empty, so plates are inset one column from the gutter.

Vertical rhythm is one fluid section step, clamp(80px, 11vw, 170px): above the first plate, between plates and above the Media band. The gallery sits clamp(56px, 7vw, 110px) below Media; contact has clamp(90px, 12vw, 180px) above and clamp(90px, 12vw, 170px) below. Inside a section the steps are fixed: 20px title-to-paragraph (18px in contact), 30px paragraph-to-link, 30px between form fields, 8px label-to-input, 54px intro-to-form, 8px form-to-submit.

The hero is 100svh (min 560px) with the logotype centered in it. The nav is fixed, 64px, white over the hero; once the hero leaves the viewport (IntersectionObserver, -64px root margin) it becomes Ink on 96% white. The Media band is inset by the gutter, ruled top and bottom, and runs a 44s linear marquee of a duplicated logo list. The gallery is a scroll-snap row (x mandatory) of frames min(72vw, 380px) wide with a 16px gap, padded by the gutter, scrollbar hidden; the counter and arrows sit in the header beside the title. The footer is a 12-column grid: logotype 1 to 4, page links 5 to 8, Instagram and contact link 9 to 12, legal line beneath a hairline.

**One breakpoint, 860px.** Below it: the nav drops to 56px with the logotype left at 22px and a "Menu" button right; the open menu fills the viewport below the bar with white and lists the links in the grotesk at 30px bold divided by hairlines; plates collapse to blocks with the text 28px under the image and titles fixed at 32px; the hero name stacks; the footer grid becomes two columns with the logotype full width.

## Elevation & Depth

No shadows. The page is flat: white ground, Paper footer, and photographs are the only things that read as a different layer. Over the hero three gradient scrims keep the chrome and the logotype legible: a top gradient (black 50% to 0 over the top 22%) under the nav; a centre radial vignette (ellipse 55% by 40% at 50% 50%, black 38% to 0) behind the centered name; and a light bottom gradient (black 35% to 0 at 40% up from the bottom edge). Those are the only translucent layers in the build. The solid nav is 96% white, not a frosted panel.

### Named Rules
**The No-Shadow Rule.** `box-shadow`, `drop-shadow` and `backdrop-filter` do not appear in the build and are not to be introduced. Separation comes from a hairline, from Paper, or from a photograph.

## Shapes

Everything is square except one element. Radius is 0 on every box, input (`border-radius: 0` is set explicitly) and button; the gallery arrows are 44px circles (`border-radius: 50%`) ringed by a Line hairline, the only curve in the system. Photographs are clipped to 4:5 with `object-fit: cover` in plates and gallery frames; the hero photo covers the viewport at 50% 30%. Borders are single-edge hairlines (nav bottom, field bottom, link bottom, Media band top and bottom, footer legal top), never a full box. Icons are line art at 1.2 to 1.3 stroke: the Instagram glyph (18px in the nav, 16px in the footer) and the 16x12 gallery arrows.

## Components

### Buttons
- **Shape:** square (0 radius), except the circular gallery arrows.
- **Primary (submit):** Ink fill, White label in Label tracked type (Helvetica Neue 400, 12px, 0.14em, uppercase, line-height 1), 20px padding all round, full width of the 560px form column, 8px above it. The only filled button in the build.
- **Hover / Focus:** fill goes to Black over 0.3s; focus is the global 1px currentColor outline at 4px offset.
- **Gallery arrows:** 44px circle with a 1px Line ring around a 16x12 line arrow; the ring darkens to Ink on hover over 0.3s; 30% opacity when disabled at either end.
- **Mobile "Menu" button:** text only in Label type, 40px tall, 10px side padding; reads "Zavřít" when open.

### Links
- **Underline link** (the call-to-action under each plate): Label quiet type, sentence case, 1px currentColor bottom border 3px below the text; hover fades to 50% opacity over 0.3s.
- **Nav link:** Label type, 4px vertical padding, a 1px underline that draws left to right over 0.35s on hover; the current page keeps it drawn.
- **Footer link:** 12px grotesk in Grey, darkens to Ink on hover.

### Cards / Containers
There are no cards. A plate is a bare figure on a Paper well, 4:5 crop, 60% saturation, with its title, paragraph and link in the opposite grid columns. Gallery frames are the same figure at min(72vw, 380px) with a Grey caption 12px below. Nothing is placed over a plate or frame photograph.

### Inputs / Fields
- **Style:** transparent, no side or top borders, a 1px Line field bottom edge, Ink text in Body type (400, 16px), 4px top / 12px bottom padding; label above in Grey at Label quiet, 8px gap.
- **Focus:** the outline is suppressed and the bottom edge turns Ink over 0.3s.
- **Textarea:** vertical resize only, 110px minimum.

### Navigation
- **Desktop:** fixed, 64px, three-column grid (links left with 28px gap, Bebas logotype at 24px centered and hidden over the hero, Instagram icon right in a 40px hit area). A 1px currentColor hairline at 35% opacity runs along the bottom between the gutters. White on transparent over the hero; Ink on 96% white after it (colour 0.3s, background 0.4s), the logotype fading in over 0.4s.
- **Mobile (≤860px):** 56px, logotype left at 22px and always visible, "Menu" right. Open state (data-open) fills the viewport below the bar with White; links become Menu type (Helvetica Neue 700, 30px, -0.03em, sentence case), 14px vertical padding, Line dividers, the hover underline removed; links close the menu on tap.

### Logotype (signature)
"Marketa Hajkova" in Bebas Neue 400 uppercase at letter-spacing 0, the one use of the display face. In the hero it is 99px at line-height 0.95, centered in the viewport over the vignette, two words side by side with 0.1em of air each (stacked below 860px). In the nav and footer it is 24px at line-height 1 (22px in the mobile nav); the footer brand is Ink on Paper.

### Media Band (signature)
A gutter-inset band ruled top and bottom in Line, 36px above and 40px below, headed "Media" in Title type (Helvetica Neue 700, 20px, -0.03em) in Grey, centered, 30px above the track. Logos are SVG wordmarks rendered through `filter: grayscale(1)` at 78% opacity, clamp(22px, 2.2vw, 30px) tall, with clamp(32px, 4.5vw, 80px) of air each side, running in a 44s linear marquee of a duplicated list, paused on hover; each logo goes to full opacity on hover. Under reduced motion the duplicate list is hidden and the band becomes a plain horizontal scroll. The logos shipped are public-domain placeholders, not the designer's press list.

### Gallery (signature)
A header (Headline title left, counter and two circular arrows right, baseline-aligned, gutter-inset, 28px above the track) over a scroll-snap row of 4:5 frames with a 16px gap. Arrows scroll by one frame; arrow keys do the same when the track is focused (tabindex 0); the counter reads "n / 8" in tabular numerals and the arrows disable at either end.

### Motion
One easing, cubic-bezier(.19,1,.22,1). The hero logotype arrives with a short fade-and-lift: each word from opacity 0 and 18px below to rest over 1.1s, the second word 0.08s after the first. Plates and the contact block rise 14px and fade in over 1s when 15% visible, once. Hovers fade over 0.3s. Every animation and transition sits behind `prefers-reduced-motion: no-preference` or has a `reduce` fallback; smooth scroll is disabled under reduce.

### Focus and Selection
Global `:focus-visible` is a 1px currentColor outline at 4px offset (white over the hero, Ink on white). Form fields replace it with the darkening underline. Selection is White on Black; the caret is Ink.

## Do's and Don'ts

### Do:
- **Do** set the logotype "Marketa Hajkova", and only the logotype, in Bebas Neue 400 uppercase at letter-spacing 0: 99px centered in the hero, 24px in the nav and footer.
- **Do** set every section title in Helvetica Neue 700 at -0.03em, sentence case, clamp(32px, 3.4vw, 48px) with line-height 1.05 (32px below 860px).
- **Do** keep reading text at Helvetica Neue 400, 16px/1.6, letter-spacing 0 (max 36 to 40ch), and the 12px chrome at 400 tracked 0.04em to 0.14em.
- **Do** run the hero photograph through `filter: grayscale(1) contrast(1.02)` and every other photograph through `filter: saturate(.6)`, cropped 4:5 on a Paper well.
- **Do** draw every divider, ring and field edge as a 1px hairline (Line on white, Line field under inputs, currentColor at 35% in the nav).
- **Do** use the one easing curve for every transition and give every animation a reduced-motion path.
- **Do** keep Paper to grounds: the footer and the image well.
- **Do** caption gallery frames in Grey 12px below the image, never over it.

### Don't:
- **Don't** introduce a hue. The palette is white, paper, black, ink and grey; no accent.
- **Don't** add shadows, backdrop blur, borders around boxes, or any radius other than the circular gallery arrows.
- **Don't** place a dark or paper card, panel or chip on the white ground.
- **Don't** use Bebas Neue for anything but the name, and don't track, bold or italicize it.
- **Don't** set a title in uppercase, in a light weight, or at positive tracking; titles are bold, tight and sentence case. Nothing but a title is bold.
- **Don't** add a second filled button; the submit is the only fill. Other actions are underlined links or circular line arrows.
- **Don't** put a max-width container around sections; the gutter is the frame, and only the contact column is capped (560px).
- **Don't** present the Unsplash photographs or the Wikimedia Commons logos as brand assets; both are placeholders listed for replacement.
