# balaak.github.io

Personal site of **Bala Kumaran**, a product and UI designer working AI-native.

**Live:** https://balaak.github.io
**LinkedIn:** https://www.linkedin.com/in/balakumaranux/

---

## The Stack, Vol.01

A breakdown of six beautifully animated UI component libraries for building landing pages, and which ones your AI editor can install for you through MCP.

| # | Library | MCP |
|---|---------|-----|
| 01 | [Skiper UI](https://skiper-ui.com) | via shadcn MCP |
| 02 | [Vengeance UI](https://www.vengenceui.com) | via shadcn MCP |
| 03 | [Animmaster Lib](https://animmasterlib.dev) | none |
| 04 | [Fancy Components](https://fancycomponents.dev) | none |
| 05 | [React Bits](https://reactbits.dev) | ships its own MCP |
| 06 | [SmoothUI](https://smoothui.dev) | via shadcn MCP |

## How it's built

A single static page, no framework:

- Background video under an 88% overlay (tune with the `--overlay` CSS variable)
- **GSAP** + ScrollTrigger for the load choreography and scroll motion
- Magnetic 3D tilt cards with an iridescent glow
- Bento grid, and sticky stacked scroll-cards
- Type: **Clash Display** (headings) + **Inter** (body)

## Structure

```
index.html            the page
assets/bg.mp4         background video (compressed for web)
assets/bg-poster.jpg  first-frame poster
assets/01-06-*.png    library screenshots
```

## Local preview

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

---

Crafted carefully by **Blake Genesis**.
