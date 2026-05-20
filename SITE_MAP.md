# Site Map

**Figma File Key**: `pIy3GsWgljWwePaNXi3S2S`
**Source URL**: `https://www.figma.com/design/pIy3GsWgljWwePaNXi3S2S/vaultix?node-id=1-11798`
**Container Max-Width**: `1440px`
**Framework**: Astro

## Pages

### Page: Home (Welcome)
Node ID: `5:30703`

#### Sections

| Section | Node ID | Component | Background | Notes |
|---------|---------|-----------|------------|-------|
| Hero (incl. Navbar) | `1:11799` | `Hero.astro` | `#050505` (dark) | Full-width; Navbar inside at y=24; decorative border lines; 2-col image+text |
| CTA | `1:11858` | `CTA.astro` | `#141414` (gray) | Centered header+buttons; polygon decorative shapes; chart widget |
| Footer | `3:3570` | `Footer.astro` | `#050505` (dark) | 4-col nav grid + Stay Updated + image watermark |

## Shared Components
| Component | Node ID | Description |
|-----------|---------|-------------|
| Navbar | `3:122` | Logo (Vaultix icon + text) + nav menu (dark pill) + CTA button |
| Button (Primary) | `3:561` | Yellow (#fdff22) bg, dark text, uppercase, 14px bold |
| Button (Secondary) | `3:613` | Semi-transparent bg, white text, uppercase, 14px bold |

## Assets
| File | Type | Used In |
|------|------|---------|
| `/assets/images/hero-person.png` | PNG 1031×1011 | Hero — person photo |
| `/assets/images/logo-icon.svg` | SVG | Navbar logo mark |
| `/assets/images/footer-logo-icon.svg` | SVG | Footer logo mark |
| `/assets/images/footer-main-image.png` | PNG | Footer image column (bg layer 1) |
| `/assets/images/footer-main-image2.png` | PNG | Footer image column (bg layer 2) |
| `/assets/images/cta-polygon1.svg` | SVG | CTA decorative hexagon outline 1 |
| `/assets/images/cta-polygon2.svg` | SVG | CTA decorative hexagon outline 2 |
| `/assets/images/cta-polygon3.svg` | SVG | CTA decorative hexagon outline 3 |
| `/assets/images/cta-polygon4.svg` | SVG | CTA decorative rotated polygon |

## Design Tokens
- **Ideal frame width**: 1440px (`--size-container-ideal: 1440`)
- **Container padding (desktop)**: 9.75em (156px) — aligns with decorative border lines
- **Nav padding (desktop)**: 11em (176px) — wider gutter for navbar
- **Font**: Geist Mono (400, 700, 900) via Google Fonts
- **Primary accent**: `#fdff22`
- **Borders**: `#343434`
