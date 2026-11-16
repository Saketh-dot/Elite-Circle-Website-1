# Elite Circle website (merged build)

Open `index.html` in a browser. Pages use hash links (#home, #about, #services, #portfolio, #plans, #contact). Fonts (Cormorant Garamond, Montserrat) load from Google Fonts, so an internet connection is needed.

## Contents
- `index.html` - whole site (HTML, CSS, JS). Content is in the `R` object, prices in `T`, portfolio in `PC`, images in `IM`.
- `assets/logos/` - primary (light), black-theme (dark mode), navy-cover (footer). Raster crops from the Brand Book PDF: get vector masters from your designer.
- `assets/images/` - 23 concept images (AI-generated, tagged "Concept image").

## What is in this build
- Immersive layer: scroll progress bar, parallax hero with 4-image crossfade, word-by-word text reveal, interactive service list, pinned horizontal gallery, scroll-lit process steps, lightbox with arrow keys, budget tabs, page transitions, cursor ring and magnetic buttons (desktop). Motion switches off for "reduce motion".
- From v4: announcement bar, hero call-back form, WhatsApp buttons (floating on desktop, bottom bar on mobile), event-type ticker, quote band, price cards with "Recommended" markers, event-type chips on the enquiry form, mobile menu, detailed portfolio cards and sample testimonials.

- Inner pages (About, Services, Portfolio, Budget plans, Contact) have full-bleed parallax heroes. Services uses stacking panels, Portfolio a featured case plus a testimonial carousel, Budget plans sticky segment tabs and an animated 40-40-20 payment bar, Contact a sticky image panel with a 3-step form.

## Brand changes made while merging
- Dropped the dotted ring graphic (guidelines: do not redraw the round-table symbol), the green WhatsApp button, terracotta bars and pulsing buttons (terracotta stays a small accent), and the shrinking header logo (full logo must stay at least 120 px wide).

## Replace before launch
- WhatsApp number (wa.me/911234567890) and phone 1234567890, email, social links, working hours.
- Portfolio shows four illustrative case studies (tagged "Illustrative"), not real client work. Replace with real events, photos and permitted quotes as you deliver them, then remove the tags and the note at the top of the page.
- Images are AI concept images; replace with real event photos. 
- "Free planning call with every enquiry" and "Get a free call back": confirm you will honour these.
- Forms are front-end mocks and send nothing yet. EC monogram favicon, privacy and terms pages not built.
