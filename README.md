# Gurufin Design System

**Version:** 1.0 — 2026  
**Sources:** Figma — "Gurufin Brand Guidelines.fig" (2 pages, 21 brand guide frames)

---

## Company Context

**Gurufin** is a specialized financial infrastructure company that combines the efficiency of blockchain technology with the stability and regulatory compliance required for institutional adoption. Founded in 2019, registered in the USA (2023) and Philippines (2025).

**Core Products / Subsidiaries:**
- **Gurufin Chain** — proprietary L1 blockchain
- **GX Stablecoin Network** — stablecoins minted via licensed partner fiat deposits, redeemable at any time
- **Gurufin Station** — (exchange / gateway)
- **Gurufin ITMT** — institutional market technology
- **Gurufin Pay** — payments layer
- **Gurufin Bank** — banking services
- **Gurufin e-Commerce** — e-commerce platform
- **GuruShop / GURU TAB** — consumer products
- **ARIA Labs Inc.** — R&D arm
- **Gurufin Lab Co** — technology labs
- **GNTB National Trust Bank**

The ecosystem has two interconnected pillars: **Gurufin Chain** (the rails) and **GX Stablecoin Network** (the stable value layer). Together these create a closed-loop system for finance, DeFi, and commerce.

Website: [www.gurufin.com](https://www.gurufin.com)  
HQ: 11, Yeoksam-ro 3-gil, Gangnam-gu, Seoul, 9th floor

---

## CONTENT FUNDAMENTALS

**Tone:** Professional, precise, institutional. Confident without arrogance. Technical without jargon overload. The brand communicates "compliance-grade stability" while positioning itself as modern and forward-looking.

**Voice:**
- Third-person for brand / product descriptions ("Gurufin is…")
- Direct imperative for rules/guidelines ("Use the designated version…")
- Avoid hype language — no "revolutionary" or "disruptive"
- Prefer clarity over creativity in copy

**Casing:**
- Section labels and category tags: ALL CAPS (e.g. "BRAND COLOR", "LOGO VARIATION", "APPLICATIONS")
- Headlines: Title Case for section headings, sentence case for body copy
- Product names: always capitalised as proper nouns (Gurufin Chain, GX Stablecoin)

**Emoji:** Not used. Zero emoji in brand materials.

**Numbers:** Use mono font for all prices, IDs, percentages, and code-like data. (e.g. `84.50`, `#0D4689`)

**Example copy:**
> "Programmable rails for modern finance — built to integrate, audited by design, and optimized for real-world operations."
> "Compliance-grade stability."
> "Gurufin is a specialized financial infrastructure that combines the efficiency of blockchain technology with the stability and regulatory compliance required for institutional adoption."

**Links / CTAs:** Signal Blue (`#0048FF`) — one accent per screen only.

---

## VISUAL FOUNDATIONS

### Colors
- **Primary dark background:** `#070F1A` (near-black navy) — used for hero/cover slides
- **Secondary dark:** `#0B1521` — slightly lighter, alternate dark surface
- **Light background (Paper):** `#F5F8FF` — off-white with a cool blue tint; used for content pages
- **Ink (primary text):** `#0A0A0A`
- **Signal Blue (CTA / links):** `#0048FF`
- **Brand Blue (primary accent):** `#0D4689`
- **Sky Blue (highlight/gradient accent):** `#4DA8DD`
- **Neutrals:** `#363E49` → `#5B6B7E` → `#889BB7` → `#C6D4E3` → `#F0F8FF`
- **Success:** `#40BF43` | **Danger:** `#FF2424` | **Warning:** `#FF9822`

**Color rules:** WCAG AA minimum contrast for body text. Logo: black on light, white/inverted PNG on dark. One accent per screen.

### Typography
- **Primary font:** Helvetica Neue (Helvetica) — used for ALL text
  - Headlines/Display: Bold/Heavy (700–800), tight tracking (−0.01 to −0.02em)
  - Body/Lead: Light/Regular (300–400), comfortable line-height
- **Mono font:** Paper Mono / Geist Mono — prices, IDs, code-like data
- **Secondary (limited):** Poppins (Bold 700, small labels), Roboto (data tables)
- **Type scale:** Display 54/58 → H1 40/48 → H2 28/34 → Lead 18/24 → Body 16/24 → Label 12/18

### Backgrounds & Layout
- **Dark pages:** deep navy `#070F1A` with radial gradient orbs in top-left and bottom-right corners (decorative ellipses, blue-to-transparent gradients give depth)
- **Light pages:** `#F5F8FF` flat — clean, no texture
- Cards on light: white (`#FFFFFF`) with `1px solid #DFE0E4` border, `border-radius: 20px`
- Cards on dark: glass effect `rgba(217,217,217,0.1)` bg + `rgba(194,194,194,0.2)` border, `border-radius: 20px`
- Page margin: 100px on all sides (brand guide consistent)

### Logo System
- **Horizontal lockup (white):** for dark backgrounds → `assets/logo-horizontal-white.png`
- **Horizontal lockup (dark):** for light backgrounds → `assets/logo-horizontal-dark.png`
- **Mark only (SVG):** for icon/favicon use → `assets/logo-mark.svg`
- **App icon:** rounded-rectangle format → `assets/app-icon.png`
- **Minimum width:** lockup ≥ 160px, mark-only ≥ 24px. Always use approved SVG/PDF/PNG exports.
- Never redraw the monogram or alter stencil gaps.

### Mascot
- **"The Golden Wing"** — inspired by the Garuda myth. Symbolises speed, protection, and clarity.
- Mood: Protective & trustworthy, Fast & precise, Myth-inspired but modern.
- Asset: `assets/mascot-garuda.png`

### Animation & Motion
- No explicit animation guidelines defined in brand materials.
- Assumed: subtle fades and transforms — functional, not decorative. No bounces or playful motion given the institutional finance context.

### Borders & Radii
- Primary card radius: **20px** (`--radius-lg`)
- Smaller elements: 8–12px
- Full pill: 9999px for tags/badges

### Shadows
- Light mode: subtle drop shadow `0 4px 16px rgba(0,0,0,0.18)`
- Dark glass cards: rely on border opacity, no shadows

### Hover / Interaction States
- Not explicitly defined in brand guide. Recommended: opacity 0.85 on hover for buttons; darken 10% on press.
- Links use Signal Blue `#0048FF`.

### Iconography
No custom icon library defined in brand materials. The brand uses the Gurufin mark/monogram as the primary icon. See `ICONOGRAPHY` section below.

### Color Vibe of Imagery
- Deep navy / dark blue tones dominate
- Cool and professional — no warm filters
- Technical / institutional feeling

---

## ICONOGRAPHY

No third-party icon library is defined in the brand guide. The brand uses:
- **Gurufin mark (SVG):** `assets/logo-mark.svg` — the stencil-gap monogram, used as app icon / avatar
- **App icon PNG:** `assets/app-icon.png` — rounded rect version for iOS/Android
- **Social avatar:** `assets/social-avatar.png`
- **Mascot (Garuda wing):** `assets/mascot-garuda.png`

For UI work, **Lucide Icons** is the recommended substitute (thin stroke, clean geometric style that matches Helvetica's neutrality). Link via CDN: `https://unpkg.com/lucide@latest`.

> ⚠️ No custom icon font or SVG sprite was found in the brand guide. If Gurufin has a proprietary icon set, please provide it for inclusion.

---

## File Index

```
README.md                  ← This file
colors_and_type.css        ← All CSS custom properties (colors, type, spacing, radii, shadows)
SKILL.md                   ← Agent skill definition

assets/
  logo-horizontal-white.png   ← Horizontal wordmark, white (for dark bg)
  logo-horizontal-dark.png    ← Horizontal wordmark, dark (for light bg)
  logo-mark.svg               ← Mark only (SVG, white fill)
  logo-mark-dark.svg          ← Mark only (SVG, dark fill)
  app-icon.png                ← Rounded-rect app icon
  social-avatar.png           ← Social media avatar
  mascot-garuda.png           ← Golden Wing mascot illustration

preview/
  colors-core.html            ← Core brand colors
  colors-neutrals.html        ← Neutral scale
  colors-semantic.html        ← State / semantic colors
  type-scale.html             ← Typography scale specimen
  type-weights.html           ← Font weight specimen
  spacing-tokens.html         ← Spacing & radii tokens
  logo-system.html            ← Logo variations card
  mascot.html                 ← Mascot card
  buttons.html                ← Button components
  cards.html                  ← Card components (light + dark)
  badges.html                 ← Badge / tag components
  form-inputs.html            ← Input field components

ui_kits/
  brand-guide/
    README.md
    index.html               ← Brand guide slides viewer
```
