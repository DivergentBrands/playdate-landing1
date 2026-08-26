# Playdate™ — Brand Guidelines (One-Pager)

> Nature's gentlest clean for little hands.
> A water-based hypochlorous acid spray for baby & kids, by **Divergent Brands LLC**.

**Brand asset:** `./brand-assets/playdate-label-design.png` (8 oz label — source of truth for color & type)

---

## 1. Brand Essence

**Positioning:** The warm alternative in a category built on fear. Every other bottle shouts about germs; Playdate is a gentle cosmetic cleanser you feel *good* reaching for a dozen times a day.

- **One line:** Nature's gentlest clean for little hands.
- **Promise:** Three simple ingredients. Nothing to sting, nothing to decode.
- **Feeling:** Calm, tender, honest, quietly premium — never clinical, never alarmist.
- **Audience anchor:** the research-every-label parent ("Jessica") who reads the back of the bottle in the aisle.

**Voice — warm over fear**

| Do | Don't |
|---|---|
| "Sticky hands happen. Meet their gentlest clean." | "Kills 99.9% of germs on contact." |
| "Gentle enough for the softest skin." | "Protect your baby from dangerous bacteria." |
| "Three ingredients. That's the whole list." | "Hospital-grade disinfecting power." |
| Plain, tender, specific | Fear-driven, clinical, hype |

---

## 2. Color Palette

Derived directly from the label. Warm, muted, gender-neutral.

### Primary

| Token | Hex | Role |
|---|---|---|
| **Terracotta Clay** | `#C4856A` | "play" wordmark, top rule, primary line-icons, CTAs |
| **Clay Deep** | `#9C5A43` | "baby" wordmark, headings on cream, deep accents |
| **Sage** | `#8AAB8E` | "date" wordmark, pill fills, bottom rule, secondary icons |
| **Sage Deep** | `#6E9174` | eyebrows, links, hover states, small text on cream |

### Neutrals & Grounds

| Token | Hex | Role |
|---|---|---|
| **Cream Blush** | `#FDF6F0` | Primary background / base |
| **Blush** | `#FBEDE7` | Label field & alternating section background |
| **Warm Sand** | `#F6E9DF` | Cards, callout blocks, alt sections |
| **Ink** | `#3F3A34` | Body copy, tagline |
| **Ink Soft** | `#8B7F74` | Captions, muted labels |
| **Hairline** | `rgba(63,58,52,0.12)` | Thin dividers (as on the label) |

**Ratio rule:** ~70% cream/blush ground, ~20% clay + sage accents, ~10% ink. Let the warm ground breathe — whitespace is part of the brand.

---

## 3. Typography

Two families, pulled from the packaging.

| Role | Typeface | Weights | Usage |
|---|---|---|---|
| **Display** | **Cormorant Garamond** (serif) | 500 / 600 / 700 + italic | Wordmark, headlines, taglines, "baby & kids!" |
| **Utility** | **Montserrat** (sans-serif) | 400 / 500 / 600 / 700 | Pills, badges, eyebrows, buttons, body, data |

**Signature treatments**
- **Badges / eyebrows:** Montserrat 600–700, ALL CAPS, letter-spacing `0.14em`–`0.22em` (e.g. `HYPOCHLOROUS ACID SPRAY`, `DERMATOLOGICALLY TESTED`).
- **Taglines & flourishes:** Cormorant Garamond *italic* (e.g. *"Nature's gentlest clean for little hands"*, *"& kids!"*).
- **Headlines:** Cormorant Garamond 600, tight leading (~1.05), generous size.

```html
<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;0,700;1,500;1,600&family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">
```

---

## 4. Logo / Wordmark

- **Two-tone lockup:** `play` in **Terracotta Clay `#C4856A`** + `date` in **Sage `#8AAB8E`**, set in Cormorant Garamond ~600, no space between the words.
- **Trademark:** use **™** (superscript Montserrat), **not ®**, until USPTO registration resolves.
  - ⚠️ *The current label art shows `®` — update to `™` before print/launch.*
- **Clear space:** keep at least the cap-height of the "p" clear on all sides.
- **Minimum size:** ~90px wide on screen / 18mm in print for legibility of the two-tone.
- **Don'ts:** don't recolor, add a third color, add drop shadows, condense, or place on busy photography without a soft scrim.
- **Icon / favicon:** two overlapping circles (concept D) as the primary mark; serif lowercase **"p"** as the small-size fallback.

---

## 5. Iconography & Components

Match the label's system exactly.

- **Line icons:** thin-stroke (~1.5px), single-color, inside a thin circle. Clay or sage stroke, never filled. (infants & toddlers / non-toxic / alcohol-free set.)
- **Pills:** fully rounded (`border-radius: 100px`), sage or clay fill, cream text, uppercase Montserrat — the hero device from the label.
- **Cards / callouts:** large corner radius (`20–24px`), Warm Sand or Blush fill, soft or no shadow.
- **Dividers:** hairline rules with the ✦ sparkle flourish for emphasis, as on the label.
- **Buttons:** pill-shaped, Clay fill / cream text; ghost = clay outline on cream.

---

## 6. Web / Landing-Page Layout

**Direction:** borrow Nara Organics' structure — a warm lifestyle hero, **soft rounded "bubble" callouts** stacked as a guided story, benefit-forward copy over **alternating warm section grounds**, generous whitespace, everything rounded and friendly. Then dress it in Playdate's clay/sage/cream and Cormorant + Montserrat.

**Section flow (top → bottom):**
1. **Hero** — lifestyle photo (real little hands, warm light) + two-tone wordmark + sage `HYPOCHLOROUS ACID SPRAY` pill + Cormorant headline + one CTA.
2. **Trust bar** — the approved-claim chips on a Clay Deep strip.
3. **"Get to know Playdate"** — Nara-style stacked **rounded bubble callouts** walking through the story (gentle → transparent → multi-use).
4. **Three-ingredient transparency block** — Warm Sand card, big `0%` alcohol callout.
5. **Benefit cards** — 2×2 rounded cards on a Sage ground (no bleach smell / won't leak / kind to skin / nothing to decode).
6. **Multi-use icon row** — thin-line circle icons (hands · faces · toys · on-the-go).
7. **Founder note** — centered, Cormorant, warm-over-fear mission.
8. **Founding 100 CTA** — Clay ground, email capture.
9. **FAQ** — Cormorant summaries, "Is this a sanitizer? No." up top.
10. **Footer** — wordmark + **tag chips** (Nara-style: `#GENTLE  #ALCOHOL-FREE  #SENSITIVE-SKIN  #HOCL`) + compliance disclaimer.

**Imagery:** real babies/kids and little hands in natural, warmly-lit settings (not studio-white, not clinical). Soft focus, cream/earth tones. Avoid germ/danger imagery entirely.

---

## 7. Design Tokens (paste into your CSS)

```css
:root {
  /* Brand */
  --clay:        #C4856A;
  --clay-deep:   #9C5A43;
  --sage:        #8AAB8E;
  --sage-deep:   #6E9174;

  /* Grounds & neutrals */
  --cream:       #FDF6F0;
  --blush:       #FBEDE7;
  --sand:        #F6E9DF;
  --ink:         #3F3A34;
  --ink-soft:    #8B7F74;
  --hairline:    rgba(63,58,52,0.12);

  /* Type */
  --font-display: 'Cormorant Garamond', Georgia, serif;
  --font-utility: 'Montserrat', system-ui, sans-serif;

  /* Shape */
  --radius-card: 22px;
  --radius-pill: 100px;
}
```

---

## 8. Compliance Guardrails (non-negotiable)

Playdate has **no EPA registration** and is positioned as a **cosmetic cleanser** — copy and design must stay inside this lane on the label, site, and ads.

**✅ Approved claim set**
Alcohol-Free · Hypoallergenic · Dermatologically Tested · Suitable for Sensitive Skin · Non-Toxic · HOCl Formula · Water-Based · gently cleanses / wipes away dirt.

**⛔ Never use**
- "sanitizer," "sanitize," "disinfect," "disinfectant," "antimicrobial," "antibacterial"
- "kills 99.9%," "kills germs/bacteria/viruses," "kills norovirus," "protects from illness"
- treat/heal claims (eczema, diaper rash, pink eye, acne, cuts) — these are drug claims
- "Pediatrician Approved," "Infant & Toddler Approved," "0+ months," "newborn safe"
- **®** on the mark (use **™** until registered)

**Standing disclaimer (footer/label):** *Playdate™ is a cosmetic hand & surface cleanser — not a hand sanitizer, disinfectant, or drug — and is not intended to diagnose, treat, cure, or prevent any disease. Always wash with soap and water; Playdate is a gentle extra for when soap and water aren't available. Keep out of reach of children; for use by an adult.*

---

*© 2026 Divergent Brands LLC · Playdate™ (registration pending). Keep this file in the repo root or `/brand-assets`.*
