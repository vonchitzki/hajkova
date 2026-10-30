---
name: Marketa Hajkova
description: A fashion-show opening on a lookbook body; a fixed grayscale triptych the page slides over, white ground, black ink, one hairline, beige mats around every photograph, and four faces with one job each (Bebas Neue logotype, Pinyon Script titles, Cormorant Garamond reading, Jost tracked caps for chrome). Nothing is bold.
colors:
  white: "#ffffff"
  paper: "#f5f4f1"
  mat: "#ebe8e4"
  black: "#111111"
  ink: "#1a1a1a"
  text-soft: "#3a3a3a"
  grey: "#6a6a6a"
  line: "#e2e0dc"
  line-field: "#cfcdc8"
typography:
  brand:
    fontFamily: "Bebas Neue, Oswald, Arial Narrow, sans-serif"
    fontSize: "26px"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0"
  headline:
    fontFamily: "Pinyon Script, Great Vibes, cursive"
    fontSize: "clamp(40px, 3.6vw, 52px)"
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: "0"
  headline-contact:
    fontFamily: "Pinyon Script, Great Vibes, cursive"
    fontSize: "clamp(44px, 4vw, 58px)"
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: "0"
  menu:
    fontFamily: "Pinyon Script, Great Vibes, cursive"
    fontSize: "44px"
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: "0"
  title:
    fontFamily: "Pinyon Script, Great Vibes, cursive"
    fontSize: "36px"
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: "0"
  body:
    fontFamily: "Cormorant Garamond, Cormorant, Garamond, Times New Roman, serif"
    fontSize: "18px"
    fontWeight: 500
    lineHeight: 1.45
    letterSpacing: "0.02em"
  label:
    fontFamily: "Jost, Futura PT, Futura, Helvetica Neue, Arial, sans-serif"
    fontSize: "11px"
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: "0.2em"
rounded:
  none: "0"
  circle: "50%"
spacing:
  hairline: "1px"
  mat: "clamp(7px, .8vw, 12px)"
  field-gap: "8px"
  gallery-gap: "16px"
  title-gap: "22px"
  nav-gap: "30px"
  form-gap: "30px"
  bar: "53px"
  gutter: "clamp(20px, 4vw, 64px)"
  gallery-top: "clamp(56px, 7vw, 110px)"
  section: "clamp(80px, 11vw, 170px)"
  contact: "clamp(90px, 12vw, 180px)"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    typography: "{typography.label}"
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
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0 0 4px 0"
  input-hairline:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: "4px 0 10px 0"
  nav-bar:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    height: "{spacing.bar}"
  menu-sheet:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.menu}"
  mat:
    backgroundColor: "{colors.mat}"
    rounded: "{rounded.none}"
    padding: "{spacing.mat}"
  caption-below-image:
    backgroundColor: "transparent"
    textColor: "{colors.grey}"
    typography: "{typography.label}"
    padding: "14px 0 0 0"
  footer:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.grey}"
    typography: "{typography.label}"
    padding: "56px 0 32px"
---

# Design System: Marketa Hajkova

## Overview

**Creative North Star: "The Show Title on a Lookbook"**

The homepage opens like a fashion show and continues like a lookbook. The first viewport is a grayscale triptych of three portrait photographs, fixed in place, each panel turning to a second photograph in turn; the only words on it are the white bar along its bottom edge, where the designer's name sits as a condensed Bebas Neue logotype between four small links. On scroll the bar rises with the page, which slides up over the still photographs and covers them. Everything after is quiet white plates in beige mats, one hairline band of press logos, a scroll row of matted gallery frames, a centered form and a paper-grey footer. Chrome is small, tracked caps so the photographs carry the page; density is deliberately low, one image and one title per plate.

The world is white ground and black ink with a single hairline weight between them, and a beige mat around every photograph below the hero. Four faces, each with one job: Bebas Neue sets the name; Pinyon Script sets every section title and the mobile menu; Cormorant Garamond 500 sets everything that is read; Jost sets every piece of chrome at 11px uppercase, tracked 0.2em. Nothing is bold. These are free Google stand-ins for the reference site's licensed faces (Shelley Script, Nicolas Cochin EF, ITC Kabel) and can be swapped for the licensed originals without changing the roles. There are no boxes, no shadows and no radius anywhere except the two circular gallery arrows. The hero photographs are forced to grayscale; plates and gallery frames keep muted colour (saturation 0.6) so the work reads as photographed, not as a filter.

Of the user's pinned palette (white, black, beige, grey) beige lands as Mat (#ebe8e4), the passe-partout around every plate and gallery photograph, and as Paper (#f5f4f1), the footer ground and the well behind a loading photograph. Rejected on evidence: the centered-logo card stack, colour accents, ornament.

**Key Characteristics:**
- White ground, black ink, one hairline (1px); Mat frames every photograph below the hero, Paper holds the footer and the image wells.
- Four faces, one job each: Bebas Neue for the name, Pinyon Script for titles and the mobile menu, Cormorant Garamond 500 for reading text, Jost 11px caps at 0.2em for chrome. Weight 400 or 500 only.
- Fixed grayscale hero triptych the page and nav slide up over; plate and gallery photographs at 60% saturation in a 4:5 frame inside a Mat.
- The only curve is the 44px circular gallery arrow; every other edge is square.
- One easing curve (cubic-bezier(.19,1,.22,1)), slow entrances, every animation behind prefers-reduced-motion.

## Colors

An achromatic palette with two warm off-whites: white and paper as grounds, mat as the frame around photographs, black and ink as type and fill, two greys for secondary text, two hairline tints.

### Primary
- **Ink** (#1a1a1a): body text, every title on white, the nav text and logotype, the burger lines, the submit button fill, the focused field edge, the caret, the footer logotype. The working black of the page.
- **White** (#ffffff): the page ground, the nav bar, the mobile menu sheet, the submit label; also the text colour of a selection.

### Neutral
- **Mat** (#ebe8e4): the passe-partout around every plate and gallery photograph. The beige of the pinned palette; it only ever frames a photograph.
- **Paper** (#f5f4f1): the footer ground and the well behind every plate and gallery photograph while it loads (inside the Mat). It is a ground, never a card.
- **Black** (#111111): the hero backdrop behind the triptych, the selection highlight and the submit hover fill.
- **Text soft** (#3a3a3a): paragraph text beside a plate and in the contact intro, one step lighter than Ink so titles lead.
- **Grey** (#6a6a6a): secondary text on white: the Media heading, the gallery counter, gallery captions, field labels, footer text and links at rest.
- **Line** (#e2e0dc): the hairline on white: Media band rules, gallery arrow rings, footer rule; also the faint "MH" monogram on the mobile menu sheet.
- **Line field** (#cfcdc8): the resting underline of every form field; it darkens to Ink on focus.

### Named Rules
**The One Hairline Rule.** Every rule, divider, ring, underline and burger line is 1px. On white it is Line; under a field it is Line field; a link underline is currentColor. No 2px rules, no borders around boxes, no hairline under the nav.

**The Passe-Partout Rule.** Every photograph below the hero sits in a Mat: padding clamp(7px, .8vw, 12px) of #ebe8e4 around the 4:5 image, square, no shadow, no border. Captions sit below the Mat, never inside it or over the photograph. The hero is the one unmatted image.

**The Paper Is a Ground Rule.** Paper fills the footer edge to edge and the well behind a photograph inside its Mat. It is never a panel, card or chip on white.

**The Monochrome Hero Rule.** The hero photographs are `filter: grayscale(1) contrast(1.02)`; every other photograph is `filter: saturate(.6)`. Any image replacing a placeholder inherits the filter of its slot.

## Typography

**Logotype Font:** Bebas Neue (with Oswald, Arial Narrow, sans-serif; Google Fonts), the name only
**Title Font:** Pinyon Script (with Great Vibes, cursive; Google Fonts), section titles and mobile menu links
**Body Font:** Cormorant Garamond 500 (with Cormorant, Garamond, Times New Roman, serif; Google Fonts), reading and input text
**Label Font:** Jost 400 (with Futura PT, Futura, Helvetica Neue, Arial, sans-serif; Google Fonts), all chrome

**Character:** Four faces, each with one job and no overlap. The condensed Bebas Neue caps (kept from the first build by user decision) are a wordmark, not a type style: they set "Marketa Hajkova" in the nav and footer and the "MH" monogram on the mobile menu, and nothing else. The formal script carries meaning at the top of each section: plate, gallery, Media and contact titles, and the five links of the open mobile menu. The Garalde sets every sentence that is read, at 18px/1.45, weight 500, tracked 0.02em. Every small functional word (nav links, plate links, counter, captions, field labels, the submit, the footer) is the geometric sans at 11px, uppercase, tracked 0.2em: one size, one tracking, one class (`.caps`). Hierarchy comes from face, not weight; nothing in the build is bold or italic. These four are free stand-ins for the reference's licensed Shelley Script, Nicolas Cochin EF and ITC Kabel.

### Hierarchy
- **Brand** (Bebas Neue 400, uppercase, line-height 1, letter-spacing 0): the nav logotype at 26px with 2px top padding (22px below 860px) and the footer logotype at 24px in Ink. The same face sets the "MH" monogram on the mobile menu sheet at 56px, letter-spacing 0, in Line.
- **Headline** (Pinyon Script 400, clamp(40px, 3.6vw, 52px), 1.15, 0): plate titles ("Svatební", "Kolekce") and the gallery title ("Galerie"); 22px to the paragraph beneath a plate. Plates are fixed at 40px below 860px.
- **Headline contact** (Pinyon Script 400, clamp(44px, 4vw, 58px), 1.15, 0): the contact title ("Napište mi"), 20px above the intro.
- **Menu** (Pinyon Script 400, 44px, 1.15): the five links of the open mobile menu, centered, 6px apart, 8px side padding.
- **Title** (Pinyon Script 400, 36px, Grey, centered): the Media band heading.
- **Body** (Cormorant Garamond 500, 18px, 1.45, 0.02em): paragraphs at max 34ch beside a plate and 40ch in contact, both in Text soft and centered; form input and textarea text is the same face, weight and size in Ink (`font: inherit`).
- **Label** (Jost 400, 11px, 1.2, 0.2em, uppercase): nav links, plate links, the gallery counter (tabular numerals), gallery captions, field labels, the submit label, the "MENU" label on the mobile sheet, and all footer text and links.

### Named Rules
**The One Face, One Job Rule.** Bebas Neue sets the name, Pinyon Script sets titles and the mobile menu, Cormorant Garamond sets reading and input text, Jost caps set chrome. A face never takes another face's job: no script label, no caps title, no Garamond button.

**The Logotype Only Rule.** Bebas Neue sets "Marketa Hajkova" (and its "MH" monogram) and nothing else. It is never used for a section title, a label, a button or a menu link; a new surface that needs a title sets it in the script.

**The Script Title Rule.** Every section title is Pinyon Script 400 at letter-spacing 0 and line-height 1.15, set all lowercase via text-transform (user decision 2026-10-30; the source copy keeps its capitals), never uppercase, never tracked. The mobile menu links keep their capitals. Plates and gallery are clamp(40px, 3.6vw, 52px), contact clamp(44px, 4vw, 58px), the Media heading 36px in Grey, the mobile menu 44px.

**The Nothing Bold Rule.** No element is set heavier than 500; Cormorant is 500, every other face 400. Emphasis comes from face and size, not weight.

**The One Chrome Size Rule.** All chrome is Jost 11px uppercase at 0.2em, line-height 1.2. A new label, button or caption takes the `.caps` style as is rather than a size or tracking of its own.

## Layout

One fluid gutter (clamp(20px, 4vw, 64px)) frames every section; there is no max-width container except the contact column (560px, centered). Plates sit on a 12-column grid with the gutter as column gap: the matted image takes columns 2 to 6 and the text columns 8 to 11, vertically centered and centered in its column (title, paragraph and link); the alternate plate mirrors (image 7 to 11, text 2 to 5). Column 1 and column 12 stay empty, so plates are inset one column from the gutter.

Vertical rhythm is one fluid section step, clamp(80px, 11vw, 170px): above the first plate, between plates and above the Media band. The gallery sits clamp(56px, 7vw, 110px) below Media; contact has clamp(90px, 12vw, 180px) above and clamp(90px, 12vw, 170px) below. Inside a section the steps are fixed: 22px title-to-paragraph (20px in contact), 32px paragraph-to-link, 30px between form fields, 8px label-to-input, 54px intro-to-form, 8px form-to-submit.

The hero is fixed to the top of the viewport at calc(100svh - 53px) (min 480px), a three-column grid of equal portrait panels on Black. A transparent spacer (`.lift`) of the same height sits in flow beneath it, followed by the 53px nav bar, so on load the bar sits on the bottom edge of the first viewport; on scroll the bar and the page (main and footer, White and Paper, z-index 1) rise over the still triptych, and the bar sticks at the top (position: sticky, top 0). Once the spacer leaves the viewport the hero is set to visibility: hidden. The Media band is inset by the gutter, ruled top and bottom, and runs a 44s linear marquee of a duplicated logo list. The gallery is a scroll-snap row (x mandatory) of matted frames min(72vw, 380px) wide with a 16px gap, padded by the gutter, scrollbar hidden; the counter and arrows sit in the header beside the title. The footer is a 12-column grid: logotype 1 to 4, page links 5 to 8, Instagram and contact link 9 to 12, legal line beneath a hairline.

**One breakpoint, 860px.** Below it: the nav is a fixed 53px bar at the top with a burger left, the logotype centered at 22px and Instagram right; the hero becomes a normal block under the bar showing only the middle panel, and the spacer is removed; the menu opens as a full-screen white sheet; plates collapse to blocks with the text 34px under the image and titles fixed at 40px; the footer grid becomes two columns with the logotype full width.

## Elevation & Depth

No shadows. The page is flat; depth comes from one move: the white page is a layer that slides up over the fixed hero (hero z-index 0, main and footer z-index 1, nav 20, mobile sheet 19 so the bar stays above it). There are no scrims, gradients or overlays on the photographs; with no text over the hero, none are needed. The nav is solid White, not translucent or frosted. The Mat separates a photograph from the white ground by tone, not by shadow.

### Named Rules
**The No-Shadow Rule.** `box-shadow`, `drop-shadow` and `backdrop-filter` do not appear in the build and are not to be introduced. Separation comes from a hairline, from the Mat, from Paper, or from the page sliding over the hero.

**The Clean Hero Rule.** Nothing is laid over the hero photographs: no text, no scrim, no gradient. The name lives on the bar beneath them; the h1 is visually hidden.

## Shapes

Everything is square except one element. Radius is 0 on every box, mat, input (`border-radius: 0` is set explicitly) and button; the gallery arrows are 44px circles (`border-radius: 50%`) ringed by a Line hairline, the only curve in the system. Photographs are clipped to 4:5 with `object-fit: cover` inside their Mat in plates and gallery frames; hero panels cover their column at 50% 25%, 50% 30% and 50% 35%. Borders are single-edge hairlines (field bottom, link bottom, Media band top and bottom, footer legal top), never a full box. Icons are line art at 1.2 to 1.3 stroke: the Instagram glyph (17px in the nav, 16px in the footer), the 16x12 gallery arrows, and the three-line burger (24px lines, 1px, 7px apart).

## Components

### Buttons
- **Shape:** square (0 radius), except the circular gallery arrows.
- **Primary (submit):** Ink fill, White label in Label type (Jost 400, 11px, 0.2em, uppercase, line-height 1), 20px padding all round, full width of the 560px form column, 8px above it. The only filled button in the build.
- **Hover / Focus:** fill goes to Black over 0.3s; focus is the global 1px currentColor outline at 4px offset.
- **Gallery arrows:** 44px circle with a 1px Line ring around a 16x12 line arrow; the ring darkens to Ink on hover over 0.3s; 30% opacity when disabled at either end.
- **Burger (≤860px):** 44px hit area at the left of the bar, three 24px by 1px lines 7px apart. Open, the middle line clears and the outer two meet and rotate to an X (±45deg), in two 0.25s phases; the label "Menu" is visually hidden; aria-expanded tracks the state.

### Links
- **Underline link** (the call-to-action under each plate): Label type, 1px currentColor bottom border 4px below the text; hover fades to 50% opacity over 0.3s.
- **Nav link:** Label type, 6px vertical padding; hover and the current page draw a 1px text underline at 5px offset. No animation on the underline.
- **Footer link:** Label type in Grey; hover turns it Ink with a text underline at 4px offset.

### Cards / Containers
There are no cards. A plate is a figure in a Mat (clamp(7px, .8vw, 12px) of #ebe8e4 around a 4:5 photo on a Paper well, 60% saturation), with its title, paragraph and link centered in the opposite grid columns. Gallery frames are the same matted photograph at min(72vw, 380px) with a Grey Label caption 14px below the Mat. Nothing is placed over a plate or frame photograph.

### Inputs / Fields
- **Style:** transparent, no side or top borders, a 1px Line field bottom edge, Ink text in Body type (Cormorant Garamond 500, 18px), 4px top / 10px bottom padding; label above in Grey Label type, 8px gap. Labels and fields are left-aligned inside the centered contact column.
- **Focus:** the outline is suppressed and the bottom edge turns Ink over 0.3s.
- **Textarea:** vertical resize only, 110px minimum.

### Navigation
- **Desktop:** a 53px White bar placed directly under the hero; sticky at top 0, so it sits on the bottom edge of the first viewport on load, rises with the page and then sticks. Grid 1fr auto 1fr, padded by the gutter: Svatební and Kolekce left; the Bebas Neue logotype centered at 26px; O mně and Kontakt right with the Instagram icon (17px in a 40px hit area) after them; 30px between items. Links are Label type in Ink with a 1px underline at 5px offset on hover and for the current page. No hairline under the bar.
- **Mobile (≤860px):** the bar is fixed at the top, grid 44px 1fr 44px: burger left, logotype centered at 22px, Instagram right. The menu is a full-screen White sheet (`.sheet`, data-open) under the bar: a small "MENU" Label above five links (Domů, Svatební, Kolekce, O mně, Kontakt) centered in Menu type (Pinyon Script 44px), and the "MH" monogram in Bebas Neue 56px, Line, centered 5% from the bottom. The sheet fades in over 0.45s and the links rise 10px and fade in over 0.6s, staggered 0.04s each. Body scroll is locked while open; a link tap, Escape (focus returns to the burger) or widening past 860px closes it.

### Hero Triptych (signature)
Three equal portrait panels on Black, fixed, calc(100svh - 53px) tall (min 480px), every photograph `grayscale(1) contrast(1.02)` with no overlay. Each panel holds two photographs; the second crossfades in and out on a 21s loop (hidden to 38%, shown 46% to 88%, hidden from 96%), the second and third panels offset by 7s and 14s, so one panel is turning at a time. Under reduced motion the second photographs are hidden and the triptych is static. Below 860px it is a normal block under the fixed bar showing only the middle panel.

### Logotype (signature)
"Marketa Hajkova" in Bebas Neue 400 uppercase at letter-spacing 0 and line-height 1, the one use of the logotype face besides its monogram. It lives on the bar: 26px centered in the nav (22px below 860px), 24px in the footer in Ink on Paper. It never appears over a photograph. The "MH" monogram on the mobile menu sheet is the same face at 64px in Line, decorative and aria-hidden.

### Media Band (signature)
A gutter-inset band ruled top and bottom in Line, 36px above and 40px below, headed "Media" in Title type (Pinyon Script 36px) in Grey, centered, 26px above the track. Logos are SVG wordmarks rendered through `filter: grayscale(1)` at 78% opacity, clamp(22px, 2.2vw, 30px) tall, with clamp(32px, 4.5vw, 80px) of air each side, running in a 44s linear marquee of a duplicated list, paused on hover; each logo goes to full opacity on hover. Under reduced motion the duplicate list is hidden and the band becomes a plain horizontal scroll. The logos shipped are public-domain placeholders, not the designer's press list.

### Gallery (signature)
A header (Headline title left, counter and two circular arrows right, baseline-aligned, gutter-inset, 28px above the track) over a scroll-snap row of matted 4:5 frames with a 16px gap. Arrows scroll by one frame; arrow keys do the same when the track is focused (tabindex 0); the counter reads "n / 8" in tabular numerals and the arrows disable at either end.

### Motion
One easing, cubic-bezier(.19,1,.22,1). The hero panels crossfade on a staggered 21s loop. The mobile sheet fades over 0.45s and its links lift 10px in a 0.04s stagger over 0.6s; the burger morphs to an X in two 0.25s phases. Plates and the contact block rise 14px and fade in over 1s when 15% visible, once. Hovers fade over 0.3s. Every animation and transition sits behind `prefers-reduced-motion: no-preference` or has a `reduce` fallback; smooth scroll is disabled under reduce.

### Focus and Selection
Global `:focus-visible` is a 1px currentColor outline at 4px offset. Form fields replace it with the darkening underline. Selection is White on Black; the caret is Ink. Anchored sections scroll to 53px below the top (`scroll-margin-top: var(--bar)`) so the bar never covers a title.

## Do's and Don'ts

### Do:
- **Do** set the name "Marketa Hajkova", and only the name, in Bebas Neue 400 uppercase at letter-spacing 0: 26px centered in the nav (22px mobile), 24px in the footer.
- **Do** set every section title in Pinyon Script 400 at letter-spacing 0 and line-height 1.15, all lowercase: clamp(40px, 3.6vw, 52px) for plates and gallery (40px below 860px), clamp(44px, 4vw, 58px) for contact.
- **Do** keep reading text at Cormorant Garamond 500, 18px/1.45, 0.02em (max 34 to 40ch), and every piece of chrome at Jost 400, 11px, uppercase, 0.2em.
- **Do** run the hero photographs through `filter: grayscale(1) contrast(1.02)` and every other photograph through `filter: saturate(.6)`, cropped 4:5 inside a Mat.
- **Do** frame every photograph below the hero in a square Mat of clamp(7px, .8vw, 12px), with its caption below the Mat.
- **Do** draw every divider, ring and field edge as a 1px hairline (Line on white, Line field under inputs).
- **Do** use the one easing curve for every transition and give every animation a reduced-motion path.
- **Do** keep Paper to grounds: the footer and the image well.

### Don't:
- **Don't** introduce a hue. The palette is white, paper, mat, black, ink and grey; no accent.
- **Don't** add shadows, backdrop blur, borders around boxes, or any radius other than the circular gallery arrows.
- **Don't** place text, a scrim or a gradient over the hero photographs.
- **Don't** place a dark or paper card, panel or chip on the white ground.
- **Don't** use Bebas Neue for anything but the name and its monogram, or Pinyon Script for anything but titles and the mobile menu.
- **Don't** set anything bold, set a title in uppercase or tracked, or give a piece of chrome its own size or tracking.
- **Don't** add a second filled button; the submit is the only fill. Other actions are underlined links or circular line arrows.
- **Don't** put a max-width container around sections; the gutter is the frame, and only the contact column is capped (560px).
- **Don't** present the Unsplash photographs or the Wikimedia Commons logos as brand assets; both are placeholders listed for replacement.
