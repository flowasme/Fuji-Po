# Fuji-Po

> **Echoes of Japan’s golden eras, curated for your space.**

Fuji-Po is a static art and poster showcase inspired by Japanese visual culture, vintage design, and timeless cultural imagery. The experience presents curated poster collections through a warm, editorial-style interface that blends a mountain-inspired hero section, responsive layouts, custom typography, and image-led browsing.[1]

**[View the live site][2]** · **[Browse the source repository][1]**

## Project Snapshot

| Area | Details |
| --- | --- |
| Project type | Static front-end website and visual gallery |
| Primary technologies | HTML5 and CSS3 |
| Content focus | Japanese paintings, modern art, calligraphy, and Van Gogh-inspired posters |
| Layout approach | Responsive flexbox-based sections with media queries |
| Typography | General Sans and Erode Variable font families |
| Styling direction | Navy, charcoal, and warm cream palette with editorial typography |
| Deployment | Publicly accessible through the project’s hosted site [2] |
| Author | Mehdi FERHAT |

## The Experience

Fuji-Po opens with a hero section that introduces the site as a curated gateway to vintage finds and cultural treasures from Japan. Visitors can then move through themed poster collections presented as image cards, each paired with actions for learning more or downloading a digital copy.

The visual language is deliberately nostalgic but contemporary. Large display typography, soft translucent overlays, a sticky header, generous spacing, and a restrained color palette give the page the character of a digital exhibition or poster archive rather than a conventional storefront.

## Collection Map

| Collection | Purpose | Presentation |
| --- | --- | --- |
| **Old-Era Japanese Paintings** | Showcases vintage Japanese-inspired painting and poster artwork. | Multi-column image-card gallery |
| **Modern Art & Calligraphy** | Presents contemporary poster designs and calligraphic artwork. | Responsive poster-card gallery |
| **Van Gogh Portraits & Flower Collection** | Groups portrait and floral poster artwork into a dedicated visual section. | Multi-column collection layout |

## Interface Highlights

* **Sticky navigation header:** Keeps the brand mark, search field, navigation links, and menu control visible while browsing.
* **Responsive presentation:** Uses flexible layouts and viewport-aware typography to adapt the page across screen sizes.
* **Hero calls to action:** Provides `Shop Now` and `Explore Collections` entry points in the opening section.
* **Poster cards:** Displays artwork with `Learn More` and `Download Digital Copy` controls.
* **Scroll-to-top control:** Includes an anchored return link for quickly moving back to the top of the page.
* **Custom visual identity:** Uses locally bundled fonts, themed UI icons, a favicon, and curated image assets.

## Repository Anatomy

```text
Fuji-Po/
├── fonts/              # Local font files used by the stylesheet
├── images/             # Logo, interface icons, favicon, and poster artwork
├── style/
│   └── style.css       # Layout, typography, colors, and responsive rules
├── .gitattributes
├── index.html           # Main page markup
└── README.md
```

The project intentionally keeps its implementation lightweight. The page is built from a single HTML entry point and a central stylesheet, while the `images/` and `fonts/` directories provide the visual assets required by the experience.[1]

## Run It Locally

Because Fuji-Po is a static website, no package installation or build step is required for a basic local preview.

### 1. Clone the repository

```bash
git clone https://github.com/flowasme/Fuji-Po.git
cd Fuji-Po
```

### 2. Start a local web server

Using Python:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser. Serving the project through a local web server is recommended so that relative font and image paths behave consistently.

## Design System

| Element | Implementation |
| --- | --- |
| Main color | Deep navy `#003353` |
| Secondary color | Charcoal `#222625` |
| Background accent | Warm cream `#FBF3E2` |
| Primary typeface | General Sans |
| Display typeface | Erode Variable |
| Motion detail | Smooth scrolling and subtle button scale on hover |
| Responsive strategy | Flexbox layouts, fluid typography, and viewport-specific media queries |

## Current Implementation Notes

Fuji-Po is currently best understood as a polished static front-end prototype. The page structure and visual presentation are implemented, but several controls are still placeholders in the current source.[1]

The search field is displayed in the header, but no search or filtering logic is included. Likewise, `Shop Now`, `Explore Collections`, `Learn More`, and `Download Digital Copy` are rendered as interface controls without connected application behavior. The navigation links currently use placeholder anchors, and the menu icon does not have a JavaScript interaction attached. These areas provide a clear foundation for future functionality such as collection filtering, poster detail views, downloads, and responsive menu expansion.

## Possible Next Steps

A natural next iteration could connect each poster card to metadata and a detail view, implement client-side search across titles and categories, and attach the download buttons to the appropriate digital assets. The project could also benefit from semantic navigation targets, accessible labels for icon-only controls, keyboard-friendly interactions, and a populated footer with contact or attribution information.

## Author

**Mehdi FERHAT**
