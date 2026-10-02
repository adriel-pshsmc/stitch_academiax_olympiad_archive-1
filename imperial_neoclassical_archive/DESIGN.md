---
name: Imperial Neoclassical Archive
colors:
  surface: '#f6fafe'
  surface-dim: '#d6dade'
  surface-bright: '#f6fafe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4f8'
  surface-container: '#eaeef2'
  surface-container-high: '#e4e9ed'
  surface-container-highest: '#dfe3e7'
  on-surface: '#171c1f'
  on-surface-variant: '#44474d'
  inverse-surface: '#2c3134'
  inverse-on-surface: '#edf1f5'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#505f7c'
  primary: '#000513'
  on-primary: '#ffffff'
  primary-container: '#0e1e38'
  on-primary-container: '#7786a5'
  inverse-primary: '#b8c7e9'
  secondary: '#b80938'
  on-secondary: '#ffffff'
  secondary-container: '#db2e4e'
  on-secondary-container: '#fffbff'
  tertiary: '#080400'
  on-tertiary: '#ffffff'
  tertiary-container: '#291c00'
  on-tertiary-container: '#a8800b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#b8c7e9'
  on-primary-fixed: '#0b1b35'
  on-primary-fixed-variant: '#384763'
  secondary-fixed: '#ffdadb'
  secondary-fixed-dim: '#ffb2b7'
  on-secondary-fixed: '#40000d'
  on-secondary-fixed-variant: '#920029'
  tertiary-fixed: '#ffdf9c'
  tertiary-fixed-dim: '#f0c04f'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5b4300'
  background: '#f6fafe'
  on-background: '#171c1f'
  surface-variant: '#dfe3e7'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  title-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  title-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-badge:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system synthesizes the rigorous utilitarianism of French national open-access research repositories (such as HAL and INRIA) with the architectural gravity and typographic decorum of French Empire Neoclassicism. The personality is monumental, intellectually rigorous, and uncompromisingly precise. It targets academic researchers, state archivists, domain reviewers, and international research consortiums who require high-density metadata indexing alongside institutional gravitas.

The visual style blends institutional minimalism with Neoclassical formalism:
- **Structural Monumentality:** Symmetrical layouts, disciplined hairline borders, and dense tabular alignment reminiscent of the *Imprimerie Nationale* and formal academic cartularies.
- **Academic Functionalism:** Razor-sharp data density, explicit persistent identifiers, strict hierarchical categorization, and zero-radius structural framing.
- **Imperial Accents:** Restrained antique gold rules, crimson review seals, and formal Latinate section headers counterbalanced by cold, utilitarian monospaced indices.

## Colors

The palette establishes an authoritarian, scholarly hierarchy rooted in high-contrast archival parchment and state regalia:

- **Primary (`#0e1e38` / `#0b132b`):** Deep Imperial Navy. Applied to primary structural headers, document anchors, top-level navigation, and dominant typography. Evokes the authority of state academies and archival ledgers.
- **Secondary (`#be123c` / `#991b1b`):** INRIA Crimson. Reserved for critical peer-review statuses, direct actions (e.g., "Deposit Manuscript", "Withdraw"), active filter facets, and live research embargo warnings.
- **Tertiary (`#b48a1a` / `#d4af37`):** Gilded Antique Gold. Utilized strictly for distinguished scholarly markers: Grand Prix laurels, Olympiad badges, authenticated open-access seals, and archival accession numbers.
- **Neutral (`#ffffff`, `#f8fafc`, `#f1f5f9`, `#334155`):** Crisp archival vellum tones. Pure white (`#ffffff`) serves as the base paper surface, `#f8fafc` as the underlying canvas, and `#f1f5f9` (subtle vellum tint) as structural metadata panels and facet containers. Slate `#334155` provides medium-contrast metadata copy, while `#0f172a` serves as primary body copy.

## Typography

The typographic hierarchy implements a deliberate dichotomy:
1. **The Humanist Imperium (Display & Headings):** `Playfair Display` provides neoclassical authority, invoking historical cartularies and scholarly gazettes. Used exclusively for monument headers, paper titles, archive section divisions, and institutional insignia.
2. **The Rationalist Modern (Body & Structural Metadata):** `Inter` provides neutral, high-legibility typographic utility for long-form abstracts, author affiliations, bibliographic notes, and control interfaces.
3. **The Persistent Registry (Identifiers & Systems):** `JetBrains Mono` handles persistent academic identifiers (`AXI-2026-XXXX`), DOI cords, timestamps, checksums, and dataset byte dimensions. All numerical indices in tabular facets default to tabular numerals.

## Layout & Spacing

The archive operates on a strict 12-column asymmetric fluid grid structured around archival reading mechanics:
- **Desktop (>=1280px):** 12-column layout with a 3-column fixed-density facet panel on the left (280px-340px) and a 9-column main reading and registry pane. Gutters are fixed at `1.5rem` (`24px`), with outer canvas margins of `2rem` (`32px`). Maximum content boundary caps at `1600px` to maintain strict optical scan lines.
- **Tablet (768px - 1279px):** 8-column layout. The facet panel collapses into a persistent top filtering tray or expandable off-canvas folio. Gutters transition to `1rem` (`16px`).
- **Mobile (<768px):** 4-column layout. Gutters compress to `0.75rem` (`12px`) and section margins compress to `1rem` (`16px`). Record metadata cards unstack into strict vertical dossiers.

Vertical rhythms are disciplined around an 8px baseline grid (using 4px increments strictly for inline badge padding and compact metadata rows).

## Elevation & Depth

This design system rejects deep blur-based skeuomorphism and floating shadows in favor of **Crisp Neoclassical Planarity** and **Low-Contrast Structural Linework**:

- **Borders over Shadows:** Depth is produced through hairline bounding boxes (`1px solid #cbd5e1`) and inset panel offsets rather than drop shadows.
- **Surface Elevation via Tonal Tiers:**
  - Base Document Canvas: `#f8fafc`
  - Elevated Card Panels & Paper Folios: `#ffffff` with a crisp `1px solid #e2e8f0` structural rule.
  - Recessed Index Trays & Facet Panels: `#f1f5f9` (vellum tint) with an internal separation line (`#cbd5e1`).
  - Active/Hover States: No floating Z-height change; instead, surfaces gain an immediate `1px solid #0e1e38` accent rule or an antique gold trim (`#b48a1a`).
- **Diplomatic Seals & Overlays:** Modals and contextual drawer panels employ a heavy scrim (`#0b132b` at 60% opacity) combined with an antique gold top-edge rule (2px `#d4af37`), eschewing diffuse shadows for an austere, architectural presence.

## Shapes

The shape system is strictly **Sharp (0px radius)** throughout the entire component ecosystem. 

All cards, buttons, badges, input controls, chips, and modal sheets terminate in razor-sharp 90-degree angles. This zero-radius mandate mirrors classical stone tablets, printed gazettes, and official legal dossiers. Corner radii are forbidden; hierarchy and interaction feedback are communicated strictly through border-weight modifications, inverted tonal fills, and gilded accent marks.

## Components

### Buttons
- **Primary Imperial Button:** Rectangular, sharp corners. Background: `#0e1e38`; text: `#ffffff` in `Inter` medium; border: `1px solid #0e1e38`. On hover, transitions to background `#be123c` (INRIA Crimson) and border `#be123c`.
- **Secondary / Archival Outline Button:** Background: `#ffffff`; text: `#0e1e38`; border: `1px solid #0e1e38`. On hover: `#f1f5f9` surface with `1px solid #0e1e38`.
- **Solemn Action Button (Deposit / Publish):** Background: `#be123c`; text: `#ffffff`; border: `1px solid #991b1b`. On hover: `#991b1b`.
- **Pedestal / Laurel Button:** Background: `#ffffff`; text: `#b48a1a`; border: `1px solid #b48a1a`. Padding: `0.5rem 1rem`.

### Badges & Institutional Seals
- **Accession Identifier Badge:** Monospace font (`JetBrains Mono`), uppercase. Background: `#f1f5f9`; text: `#0e1e38`; border: `1px solid #cbd5e1`; padding: `2px 6px`. Format: `[AXI-2026-9812]`.
- **Olympiad / Laurel Seal:** Compact institutional badge. Background: `#fefce8`; text: `#b48a1a`; border: `1px solid #d4af37`. Prefixed with a Unicode laurel wreath or classical star marker.
- **Peer-Review State Badge:** Validated status (`#f0fdf4` / border `#86efac` / text `#166534`), In Review status (`#fffbeb` / border `#fde68a` / text `#92400e`), Retracted/Embargoed (`#fef2f2` / border `#fca5a5` / text `#991b1b`).

### High-Density Facets & Filter Trees
- **Facet Container:** Flush `#f1f5f9` background, zero border radius, bordered on the right by `1px solid #cbd5e1`.
- **Facet Headers:** `Inter` 11px uppercase bold, tracking `0.08em`, colored `#334155`. Accompanied by a discrete gold underline indicator.
- **Facet Item:** High-density vertical rows (28px height), displaying taxonomy classification, subject domain, and exact record counts aligned right in `JetBrains Mono` muted (`#64748b`).

### Academic Record Cards
- **Structure:** Flat `#ffffff` card, framed with `1px solid #e2e8f0`. Left border features a 3px accent stroke: deep navy by default, crimson for priority preprints, antique gold for prize-winning monographs.
- **Header Row:** Displays persistent ID (`JetBrains Mono`), publication date, and peer-review certification status badge.
- **Title:** `Playfair Display` 18px bold, `#0e1e38`. Hover transitions to `#be123c`.
- **Metadata Matrix:** Dense 2-column inline list of authors, primary laboratory affiliation, and HAL/INRIA domain nodes.

### Inputs & Search Fields
- **Search Bar (Omnibox Archive Query):** Sharp rectangle, `#ffffff` surface, `1px solid #94a3b8`. Focus state introduces a double-line optical illusion via `outline: 2px solid #0e1e38; outline-offset: 1px`. Left-aligned magnifier icon paired with an archival dropdown filter.
- **Checkboxes & Radios:** Strictly square (0px radius). Unchecked: `#ffffff` with `1.5px solid #64748b`. Checked: `#0e1e38` with an inset white square check marker.

### Tabular Bibliographies
- **Data Tables:** Alternating rows of `#ffffff` and `#f8fafc`. Table headers in `#0e1e38` background with `#ffffff` serif text (`Playfair Display`, 13px uppercase). Border collapses with `1px solid #e2e8f0`.