# Konrad Chan — Portfolio

Modern recreation of Konrad Chan's motion design / creative direction portfolio as a single-page PWA.

**Live:** https://djayku.github.io/konrad

## Identity (real, from konradchan.com)
- Motion Designer · Creative Director · Music Producer
- Hong Kong based, originally from / studied University of Manitoba
- 6 albums/EPs + hundreds of tracks since age 9
- Tools: Premiere Pro, After Effects, Photoshop, Lightroom, Illustrator, Logic Pro X
- Clients: Calvin Klein, Adobe, Marriott, Empire Tailors, Craftissimo, Rosie Posie, Kitty Wong, Sam Wong, Victor Cheng
- Instagram: @konradjchan
- Vimeo: @konradjchan

## Design language
- Pure black + signal red (`#FF3D00`) + warm bone
- Display: DM Serif Display (titles), Instrument Serif (italic accents)
- Sans: Inter
- Mono: JetBrains Mono (metadata)
- Custom orange cursor that becomes "▶ Play" on video tiles
- Asymmetric 12-col bento with mixed aspect ratios
- Generative noise overlay (4% opacity, mix-blend overlay)
- Loading screen, scroll-reveal animations, project case-study modals

## Sections
- Loading screen → Hero → Marquee → Asymmetric work grid (8 projects) → Reel frame → Client wall → About → Approach → Recognition → Testimonial → Contact → Footer

## Tech
- Single-file HTML, no build step
- PWA via manifest + service worker
- Google Fonts only
- All 8 case studies wired to clickable modals