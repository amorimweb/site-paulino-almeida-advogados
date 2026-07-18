---
name: Paulino & Almeida Advogados Associados
description: Landing page institucional de advocacia tradicional em Parauapebas, PA (tema wine — desde 2013)
colors:
  ink: "#4a1720"
  accent: "#b58d5a"
  paper: "#f4eee5"
  soft: "#dccbbd"
typography:
  display:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "clamp(64px, 8.7vw, 132px)"
    fontWeight: 500
    letterSpacing: "-0.045em"
  body:
    fontFamily: "DM Sans, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "DM Sans, Arial, sans-serif"
    fontSize: "11px"
    fontWeight: 600
    letterSpacing: "0.22em"
rounded:
  none: "0"
  pill: "100px"
spacing:
  section: "9-14vw"
components:
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "white"
    padding: "17px 22px"
  whatsapp-float:
    backgroundColor: "#1c9d58"
    textColor: "white"
    rounded: "{rounded.pill}"
---

# Design System: Paulino & Almeida Advogados

## 1. Overview

**Creative North Star: "The Institutional Seal"**

Paulino & Almeida runs the **wine** theme variant — the most ceremonial and symmetrical composition in the shared advocacy template, built for a firm whose entire positioning rests on 2013-to-now institutional continuity. Everything is centered: the header logo, the hero copy, the manifest quote. A monumental "P&A" monogram watermark sits behind the manifest section at 32% opacity, functioning like an embossed seal on a founding document. Deep wine-red with a muted gold accent reinforces gravitas without tipping into somber — this is meant to read as an established institution, not a slick modern startup, which is the deliberate opposite move from lighter/warmer variants used by newer or solo-practitioner firms in the same template family.

**Key Characteristics:**
- Full symmetry: centered logo, centered nav gap, centered hero copy and CTA row — no left-aligned asymmetric composition anywhere.
- Giant translucent "P&A" monogram watermark behind the manifest quote — a literal seal-of-institution motif unique to this variant.
- Deep wine ink (#4a1720) with muted antique gold (#b58d5a) — warmer and more traditional than the cooler navy variant, signaling heritage rather than corporate finance.
- Practice-area rows (not a grid of cards) laid out as a numbered list with icon-title-description-arrow columns — reads like a formal table of services, reinforcing institutional order.

## 2. Colors

A deep wine-red and antique-gold pairing — the most traditional, heritage-coded palette in the template family.

### Primary
- **Wine Ink** (#4a1720): Hero background veil, manifest section, about section background — the dominant surface.
- **Antique Gold** (#b58d5a): CTA fill, monogram watermark tint, list numerals — restrained heritage accent, never a bright or modern gold.

### Neutral
- **Warm Paper** (#f4eee5): Light section backgrounds (areas section, contact info panels where applicable).
- **Dusty Rose Soft** (#dccbbd): Dividers between practice-area rows.

### Named Rules
**The Symmetry-Is-Solidity Rule.** Every major composition in this variant is centered. An asymmetric layout (image-left-text-right, or a sidebar) would undercut the "established institution" register this variant exists to deliver.

## 3. Typography

**Display Font:** Playfair Display (with Georgia, serif fallback)
**Body Font:** DM Sans (with Arial fallback)

**Character:** The largest display-type ceiling in the template family (clamp up to 132px) — a deliberate, confident scale befitting a decade-plus institutional history, paired with a quiet, small-scale sans body for readability.

### Hierarchy
- **Display** (500, clamp(64px–132px), centered): Hero headline, the largest and most centered treatment in the whole template family.
- **Headline** (500, clamp(54px–110px)): Section headers, also centered in the manifest section.
- **Body** (400, 18px, line-height 1.65): Paragraph copy.
- **Label** (600, 11px, letter-spacing 0.22em, uppercase): Eyebrows ("DESDE 2013 · PARAUAPEBAS" as the hero kicker — the founding year is treated as a headline-level credential, not a footnote).

### Named Rules
**The Founding-Year-as-Credential Rule.** "Desde 2013" sits in the hero kicker position, the same visual weight class other variants use for a geography or practice-area tag. Longevity is the credential this firm leads with.

## 4. Elevation

Flat, with the WhatsApp float as the sole elevated surface (this firm has a real WhatsApp number configured).

### Shadow Vocabulary
- **Floating-action** (`box-shadow: 0 10px 30px rgba(0,0,0,.19)`): WhatsApp button only.

### Named Rules
**The Flat-By-Default Rule.** No card shadows; practice-area rows separate via hairline borders (`#4a172044`), not elevation.

## 5. Components

### Buttons
- **Shape:** Rectangular, no radius.
- **Primary:** Antique-gold fill, white text, bold uppercase label, centered within the hero's centered action row.

### Practice-Area List (signature component for this variant)
- **Layout:** Single-column list (not a grid), each row a 4-part horizontal grid (numeral · title · description · arrow), separated by hairline borders — reads as a formal, numbered table of services rather than a card gallery.
- **Content:** Trabalho, Civil, Previdenciário, Assessoria Jurídica — four practice areas presented with equal formal weight.

### Monogram Watermark
- **Style:** Giant (`18vw`) translucent (32% opacity) "P&A" letterform centered behind the manifest quote, in the soft dusty-rose tone — a literal embossed-seal motif. This is the variant's most distinctive signature element; reuse this "watermark behind a pull-quote" pattern for any future institutional-credibility moment (awards, years of service, client count) rather than inventing a badge or counter widget.

### Header
- **Style:** Centered layout — brand mark centered, nav links spaced wide on either side rather than clustered right. Unique to this variant among the template family.

## 6. Do's and Don'ts

### Do:
- **Do** keep every major composition centered and symmetrical — this is the variant's entire visual argument for institutional solidity.
- **Do** keep "Desde 2013" and the founders' names visible and prominent; longevity and named leadership are this firm's core credibility signals.
- **Do** use the giant translucent monogram watermark as the one "seal" moment — don't repeat it elsewhere or it loses its weight.
- **Do** respect `prefers-reduced-motion` (CSS-only reveal via `animation-timeline: view()`, no JS dependency).

### Don't:
- **Don't** introduce asymmetric layouts (image-left-text-right split heroes, sidebars) — that visual language belongs to other variants (`navy`, `blue`) and would undercut this one's centered-solidity register.
- **Don't** modernize the palette toward brighter or cooler tones — wine-red and antique gold are the deliberate heritage signal.
- **Don't** replace the numbered practice-area list with a card grid; the formal table-of-services layout is intentional here.
- **Don't** use stock legal-photography clichés — the monogram watermark and centered typography already carry the "established firm" signal without needing generic gavel/handshake imagery.
