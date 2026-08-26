# Playdate™ Landing Page — Revision Spec

**How to use this:** Paste this whole file into Claude Code (or hand to a developer) as the task. It edits the **existing** landing page build. Work top to bottom — the compliance items are launch blockers and come first. Copy strings are written as `FIND` → `REPLACE` so they map to what's on the page now. Keep the existing design, layout, colors, and type; only change what's specified here.

> Compliance note: Playdate has no EPA registration and is positioned as a cosmetic cleanser, so nothing on the page may claim or imply it kills germs, sanitizes, or disinfects. The edits below preserve that. This is product guidance, not legal advice — run final claim wording past the regulatory contact before launch.

---

## Priority 1 — Compliance blockers (do these first)

### 1.1 Reframe the comparison table (highest risk on the page)
The table currently compares Playdate *to a sanitizer*, which implies Playdate does a sanitizer's job. Keep the table, rows, and styling exactly as-is. Change only the heading and the column label so we're contrasting against alcohol-based sprays, not the sanitizer category.

- Section eyebrow: keep `THE DIFFERENCE`.
- **FIND** (section title): `How Playdate compares to a typical hand sanitizer.`
  **REPLACE:** `What makes Playdate different from a conventional hand spray.`
- **FIND** (table column header): `Typical Sanitizer`
  **REPLACE:** `Alcohol-Based Sprays`
- Leave all four rows unchanged (Alcohol content, Scent, Stings little hands, Ingredient list).

### 1.2 Fix or remove the "62 of 100 claimed" progress bar
If the counter is hardcoded, it's fabricated scarcity (an FTC deception risk) and looks bad if it never moves.
- **Preferred:** wire `X of 100 claimed` / `Y left` and the bar width to the real signup count from the email/reservation backend.
- **If it can't be made real before launch:** remove the progress bar entirely. The genuine scarcity line (`Only 100 spots at $12.99`) is enough on its own.

### 1.3 Make the founder quote truthful
The "OUR WHY" quote is attributed to `Sarah, The Playdate Founder`. Attributed endorsements must be real.
- If the founder is not named Sarah, replace with the real founder's name/title, **or** change attribution to something non-personal like `— The Playdate team`.
- Do not keep a fictional named person.

---

## Priority 2 — Missing pain points (new copy to add)

### 2.1 Add a new section: "What is hypochlorous acid?" (customer education)
**Placement:** Add as a brand-new full-width section directly **below** the `Nature's gentlest clean. None of the harsh chemicals.` block and **above** the `One bottle, everywhere little hands go.` section.

**Purpose:** Turn "what even is this?" into confidence. This is where we sell that HOCl is safe, natural, and familiar — and it doubles as the answer to the unspoken "does gentle actually work?" worry, using credibility instead of efficacy. Keep it strictly cosmetic: no kill / sanitize / disinfect / antimicrobial / "fights germs" wording.

**Styling:** Match the existing sections — small sage eyebrow, centered Cormorant headline, then a row of the same rounded cards used elsewhere on the page. Set it on an alternating warm ground (Warm Sand `#F6E9DF` or Blush) so it reads as its own moment. *Optional visual:* a simple thin-line diagram — `Purified Water  +  Salt  +  a tiny electric charge  →  Hypochlorous Acid` — in the label's icon style.

**Copy:**

Eyebrow: `THE SCIENCE, SIMPLY`

Headline: `So, what is hypochlorous acid?`

Intro paragraph:
> It sounds like a chemistry lesson, but hypochlorous acid (HOCl) is one of the simplest, gentlest cleansers there is. It's made from just three things found in nature — purified water, a pinch of salt, and a tiny electric charge. No harsh solvents, no synthetic fragrance, nothing you'd need to look up.

Four cards:

- **Card 1 — Your body already knows it**
  > Here's what surprises most parents: your own body naturally makes hypochlorous acid. It isn't a foreign chemical being sprayed onto your child's skin — it's a molecule your body already recognizes.

- **Card 2 — Trusted for over a century**
  > HOCl isn't a trend. It's been relied on in wound care, eye care, and food handling for more than a hundred years — long before it ever reached baby care. We simply made a version gentle enough for everyday little hands.

- **Card 3 — Gentle by its nature**
  > Alcohol-free, fragrance-free, and pH-friendly — so there's nothing to sting, dry, or irritate, even on the most sensitive skin. And none of that harsh bleach smell; just a light, clean freshness.

- **Card 4 — Nothing left behind**
  > A quick mist gently cleanses and wipes away everyday dirt and grime, then simply breaks back down into its simple parts. No sticky residue, no rinsing, nothing lingering on little hands.

Optional closing line (centered, under the cards):
> Simple ingredients, a gentle clean, and a name that stops sounding scary the moment you understand it.

### 2.2 Add a leak-proof / travel line — a top-3 category complaint we currently ignore
"Arrived open," "leaked in my diaper bag," and "sprayer stopped working" are constant in this category. We have a real edge (leak-resistant, metal-free sprayer) and aren't using it. Add near the **"bottle in a diaper bag"** photo in the "One bottle, everywhere little hands go" section (as a caption or short supporting line):

> Built to travel — a leak-resistant cap that won't soak your wipes, sealed and freshness-dated so it arrives ready to use.

### 2.3 Add an ingestion / mouthing reassurance — the biggest purchase driver, currently underplayed
We say "non-toxic" but never tie it to the specific fear (babies put hands straight in their mouths). Add this as a short callout, ideally in or just below the hero, or in the "Yes, you can have both" section:

> Made for the age when everything ends up in a mouth. Alcohol-free and non-toxic, so a spray before snack time is one less thing to second-guess.

### 2.4 Name the daycare / on-the-go occasions — the #1 purchase trigger, currently absent
Occasions are not efficacy claims, so we can name them freely. Add this line to the **"One bottle, everywhere little hands go"** section as a subhead or supporting sentence under the four photo cards:

> For daycare drop-off, the playground, the grocery cart, and every sticky moment in between.

### 2.5 Add a shelf-life FAQ — pre-empts a real HOCl objection
Parents who know HOCl know it can degrade over time. Add a new accordion item to the **"Good to know"** FAQ (place after "Does it smell like bleach?"):

- **Q:** `How long does it last?`
- **A:** `Hypochlorous acid is freshest when it's made in small, sealed batches — which is exactly how we bottle it. Each bottle is freshness-dated, and because we pre-fill every size (including travel), you're never decanting it into another container where it can lose its gentleness. Use within the date on the bottle for the best experience.`

---

## Priority 3 — Copy tightening

### 3.1 Tighten the white-blood-cell line (drifts toward implied germ-fighting)
In the **FULL TRANSPARENCY / "Three ingredients"** body copy:
- **FIND:** `Hypochlorous acid is the same gentle molecule your own white blood cells make to help keep you clean.`
- **REPLACE:** `Hypochlorous acid is the same molecule your own body already makes.`
- Leave the surrounding sentences ("Water, hypochlorous acid, and salt." / "There is nothing else in the bottle...") unchanged.

### 3.2 Add a risk-reversal line to the founding offer
Founding buyers are doing us a favor by giving feedback — make yes frictionless. Add under the **FOUNDING 100** reservation form, near the existing "No payment is collected today" fine print:

> Not for you? We'll refund it — no bottle to return.

---

## Do NOT change
- Hero headline `For moms who read the ingredient label.` (keep as-is — no parents/moms swap).
- The overall layout, section order, palette, fonts, rounded-card styling, and the "Is this a sanitizer? No." FAQ answer (that answer is correct and important — leave it).
- The approved claim chips (Alcohol Free, Non Toxic, Dermatologically Tested, Water Based, Hypoallergenic, Suitable for Sensitive Skin).

---

## Post-edit compliance checklist (verify before shipping)
- [ ] No instance of "sanitizer," "sanitize," "disinfect," "disinfectant," "antimicrobial," "antibacterial," "kills," "99.9%," or "germs" describing what the product *does* (the word "germs" is fine only in the "every other bottle shouts about germs" critique).
- [ ] Comparison table contrasts against "Alcohol-Based Sprays," not a sanitizer.
- [ ] Progress counter is real or removed.
- [ ] Founder attribution is truthful.
- [ ] No treat/heal claims (eczema, diaper rash, pink eye, etc.) anywhere.
