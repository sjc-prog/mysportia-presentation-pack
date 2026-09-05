# DESIGN SYSTEM — Education AI Group, with MySportia inside it

> Extracted from the brand book in `assets/01-eag-brand-book/` and from the live product.
> Every value here is measured from a real file, not invented. **This document is authoritative.**

---

# Part one — what beautiful means for this document

The deck is read by **one civil servant deciding whether to grant a tax exemption.** He will read
dozens of these. Beauty here is not decoration; it is the feeling that everything has been considered
and nothing is being hidden. Concretely:

**1 · Space is the luxury signal.** A 96px outer margin on a 1920px slide. If a slide feels full, cut
content rather than shrink type. There is no prize for fitting more on.

**2 · One idea per slide.** The reviewer should be able to say what a slide was about after two
seconds. If two ideas are fighting, split the slide.

**3 · Numbers are the typography.** `75%` · `3 in 4` · `15%` · `85%` · `32` · `5.65M` — these are the
most persuasive marks in the document. Set them at 96–160pt in Poppins 600 and let them carry whole
slides. A large, precisely set number is the single most beautiful thing this deck can do.

**4 · Restraint reads as competence.** Seventy per cent of every slide is off-white ground. Green is a
highlight, never a fill. One accent, three greys, one rule.

**5 · Real evidence, presented with respect.** Ten genuine production screenshots are in
`assets/04-product-screens/`. Frame them properly — a card with a hairline and generous padding, on
the off-white ground. Never a raw floating PNG, never a PowerPoint drop shadow, never a tilted
3D device mockup.

**6 · Rhythm.** Dark navy section openers between the three acts give the deck a pulse and tell the
reviewer where he is. Without them sixteen slides read as a list.

**7 · Nothing that could have come from a template tool.** No gradient meshes, no icon soup, no
stock photography of generic athletes, no bullet points with round dots, no "thank you" slide.

**The failure mode to avoid is an investor deck.** Confident restraint, not energy. If it looks like
it is trying to excite someone, it has missed.

---

# Part two — the brand relationship

**Education AI Group is the mother brand. MySportia is a product inside it.**

This is filed by EAG, on EAG's behalf, to a government reviewer assessing EAG. MySportia appears
*within* the document as the product being built.

| | Owns | Never |
|---|---|---|
| **Education AI Group** | The frame: small logo top-left, page number, gradient foot rule, and the legal identity on cover and close | Never carries the visual weight of the content — it is the holding company, not the subject |
| **MySportia** | The content layer: wordmark on the cover and act openers, the X mark on slides 7 and 12, pink product-accent highlights on product-side slides, phone frames, screenshots and the icon library | Never reduced to a word set in the heading face — the product's own identity must be visible |

**The test.** Flick through at speed. The frame says Education AI Group; everything inside it says
MySportia. If the product's mark never appears, the hierarchy has failed.

**Product panels are encouraged on the showcase slides (12–14):** full-bleed MySportia navy with
phone frames and screenshots, the EAG chrome held on top in reverse. Those slides should feel like
the product's own marketing — confident, modern, alive — inside the group's frame.

---

# Part three — Education AI Group, the parent system

> ⚠️ **Corrected 2026-09-05.** An earlier version of this document specified a sage-green/Satoshi
> system taken from a superseded brand book. **That brand is dead.** The authoritative sources are
> now the files in `assets/01-eag-brand-book/`: the brand board (`06-brand-board-dark.png`), the
> colour palette (`colour-palette.png`) and the four logo lockups. The live educationai.group site
> matches this system.

## 3.1 Colour — the real palette

| Role | Name | Hex |
|---|---|---|
| Primary ink / dark ground | **Deep Navy** | `#0B132B` |
| Accent — energy | **Future Blue** | `#2563FF` |
| Accent — signature | **Tech Teal** | `#00D4C8` |
| Accent — growth | **AI Green** | `#22C55E` |
| Accent — highlight only | **Lime** | `#A3FF12` |
| Light ground | **Soft White** | `#F6F8FA` |
| Secondary text | — | `#475569` |
| Tertiary text / grid | — | `#94A3B8` |
| Card border | — | `#E2E8F0` |

**Gradients are core brand devices — four are defined, no others exist:**

| Gradient | Stops |
|---|---|
| Blue | `#2563FF → #00D4C8` |
| Teal | `#00D4C8 → #22C55E` |
| Green | `#22C55E → #A3FF12` |
| Dark | `#0B132B → #1E293B` |

**Discipline for this document:** the reviewer context still demands restraint. At most **one
gradient element per slide** — normally the foot rule. Gradient text only on the cover and the
section openers. Flat Tech Teal is the working accent everywhere else. Lime is a highlight for
small marks and chart pops, never for text on a light ground (it fails contrast), never a fill for
large areas.

## 3.2 Typography

**Poppins** for headings and key communication — SemiBold (600) for titles, Medium (500) for
sub-heads. **Inter** for body and supporting. Both are the brand's own specified faces; both are on
Google Fonts. Never a serif, never a substitute display face.

| Element | Size | Weight | Tracking | Colour |
|---|---|---|---|---|
| Section opener | 72pt | Poppins 600 | −1% | Soft White on Deep Navy |
| Slide title | 40pt | Poppins 600 | −0.5% | Deep Navy |
| Eyebrow above title | 11pt | Inter 600, UPPERCASE | +12% | Tech Teal |
| Hero number | 96–160pt | Poppins 600 | −2% | Deep Navy, unit in AI Green |
| Sub-head / lead-in | 22pt | Poppins 500 | 0 | Deep Navy |
| Body | 16pt | Inter 400 | 0 | `#475569` |
| List item title | 17pt | Inter 600 | 0 | Deep Navy |
| Table | 14pt | Inter 400 | 0 | Deep Navy |
| Caption / source | 11pt | Inter 400 | 0 | `#94A3B8` |

Body line-height **1.55**. Headline line-height **1.12**. Measure ≤ **72 characters**.

## 3.3 The signature moves

- Headlines run Deep Navy and the **final phrase drops to Tech Teal** — the brand's own tagline
  does exactly this: "Smarter Education. **Stronger Futures.**" Once per spread at most.
- On the cover and section openers only, the key word may carry the **Blue gradient as text fill**
  — the live site sets its lead word this way.
- Brand tone words, from the brand board: **Curious. Calm. Clever. Caring.**

## 3.4 Grid and layout

- Canvas **1920 × 1080**. Outer margin **96px** (112px on the cover). **12 columns**, 24px gutters.
- **8px baseline grid.** Title block at a fixed height on every content slide.
- Light slides on Soft White `#F6F8FA`. The cover and the three section openers run on Deep Navy
  `#0B132B` (the Dark gradient `#0B132B → #1E293B` is permitted as their ground).

## 3.5 Page furniture — on every slide

1. **The gradient foot rule.** A bar across the full width of the bottom edge, **6px**, filled with
   the Blue gradient `#2563FF → #00D4C8`, left to right — this is the document device shown on the
   brand board's own document mock. **Every slide, dark ones included.**
2. **Header.** EAG horizontal logo top-left, 32px high (`logo-horizontal-white-bg.png`; the pale
   reverse on dark slides). Right-hand slot: `MYSPORTIA · EDUCATION AI GROUP` in 10pt Inter,
   `#94A3B8`, uppercase, wide-tracked.
3. **Page number.** Inter 11pt, format `04 | 26`, separator in Tech Teal.
4. **Ghosted leaf watermark.** The gradient leaf (`logo-leaf-icon.png`) at 3–6% opacity, large,
   bleeding off one corner. One per slide maximum; never behind a table, chart or screenshot.

## 3.6 Logo rules

Files in `assets/01-eag-brand-book/`: `logo-horizontal-white-bg.png` (primary),
`logo-stacked-white-bg.png`, `logo-leaf-icon.png` (icon only), `logo-horizontal-pale.png` (reverse,
for dark grounds). Clear space equal to the leaf's own width on all sides; minimum 120px digital;
never redrawn, recoloured or squeezed.

## 3.7 Components

- **Cards** — white on Soft White ground, `#E2E8F0` 1px border, **16px radius**, soft low shadow,
  **32px padding**.
- **Numbered lists** — numeral hung in the left margin in Tech Teal, Poppins 600. **No bullet dots
  anywhere in the deck.**
- **Icons** — thin single-weight line icons in the accent colours, as on the brand board's icon row.
  Never filled, never emoji.
- **Stat chips / status tags** — Deep Navy text on a 10% tint of the relevant accent.

## 3.8 Section openers

Deep Navy ground (Dark gradient permitted), reverse logo, 72pt Soft White title with the final word
in Tech Teal, eyebrow in Tech Teal, large ghosted gradient leaf. Gradient foot rule stays. Three of
them: *The opportunity* · *The build* · *Thailand's return*.

# Part four — MySportia, inside the frame

**The authoritative source is the 73-page MySportia brand book**, now downloaded in full to
`~/Dropbox/BRAND/01-mysportia/brand-book-73pp/`. Key pages are in `assets/06-mysportia-brand-book/`.

## 4.1 The mark

The MySportia mark is an **X formed from a dark navy cross with three rounded bars laid across it —
pink, amber and green, top to bottom.** It is distinctive and it is fixed. Use the supplied files;
never redraw it, never recolour it, never separate the bars from the cross.

The wordmark is set **lowercase — `mysportia`** — in Averta. In body copy the company writes
**"MySportia"**. Both are correct in their place; do not "correct" the lowercase wordmark.

Four lockups exist: mark alone · wordmark alone · horizontal · vertical.

## 4.2 Colour

| Role | Hex | Notes |
|---|---|---|
| **Primary navy** — "mysportia black" | `#233247` | The anchor. Print: PANTONE Black C `#2D2926`, CMYK 65.66.68.82 |
| Dark surface | `#1F2024` | Reversed logo backgrounds |
| **Pink** | `#ED3163` | Gradient `#E01A4F → #F84574` |
| **Amber** | `#FBBB17` | Gradient `#FAAC18 → #F8EE45` |
| **Green** | `#32D882` | Gradient `#04E762 → #21F596` |
| UI navy (newer product) | `#0F1B3D` | The deployed apps |
| App ground · card border | `#F5F6F7` · `#E4E6E9` | |
| Body · muted text | `#697085` · `#A5AAB7` | |

⚠️ **Accessibility, flagged in the company's own brand audit:** the green `#32D882` and the amber
`#FBBB17` both **fail WCAG AA contrast on white for normal text.** Never set body copy in either on a
light ground. Fills, accents and large display type only.

## 4.3 Typography

**Averta** — Bold for headers, Semibold for subheads, Regular for body. **The company holds no web
licence for Averta**, so if it is unavailable use the EAG stack (Poppins / Inter) rather than
substituting a lookalike. MySportia type appears in this deck only inside product screenshots.

## 4.4 The sport icon library

**Roughly 110 sport and activity pictograms**, drawn as navy `#233247` glyphs on light circular chips
— archery, badminton, boxing, climbing, cycling, diving, golf, Muay Thai, padel, pool, running,
surfing, swimming, tennis, yoga and many more. The set is in
`assets/06-mysportia-brand-book/61-ICONS.svg`.

The company's own brand audit calls this **"the single most valuable and most under-used asset the
company owns."** It is perfect for this deck: the argument is that the platform carries *every* sport
including the minority ones, and a wall of 110 pictograms proves that instantly.

**Where to use it:**
- On the **minority sports** point in slide 5 — a grid of the less common icons says it better than a sentence
- As a full-bleed, very low-opacity field behind a section opener
- As small marks in the marketplace or architecture diagram

**How to use it:** navy on the EAG off-white ground, or reversed white on Navy. Do not recolour the
glyphs into EAG green — they are MySportia's, and they read as a product asset inside the EAG frame.
Keep them all at one optical size.

## 4.5 The three design principles, from the brand book

**Deeply simple · Politely disruptive · We love sport.**

And the voice, which the BOI register happens to agree with completely:

> Human, not corporate. Ambitious, not salesy. Confident, not desperate.
> The tone should feel **"inevitable, not promotional."**

## 4.6 How MySportia may appear in an EAG document

- **Screenshots** — inside a bordered card or a flat device frame, on the EAG off-white ground.
- **The wordmark** — where the product is first named. Never larger than the EAG logo on the same page.
- **The pink, amber and green** — only inside a screenshot, on the MySportia mark, or in the icon set.
  **They are not document accent colours.** Never tint an EAG chart pink; never set an EAG headline
  word in MySportia amber.
- **The navies** — MySportia `#233247` and EAG Deep Navy `#0B132B` read as one family. Where they
  meet, use EAG `#0B132B` for type and let `#233247` live inside product imagery.

# Part five — charts and tables

- Soft White ground, `#E2E8F0` gridlines at 1px, **no chart borders, no 3D, no shadows on data.**
- Series order: `#22C55E` → `#00D4C8` → `#2563FF` → `#0B132B` → `#94A3B8`.
- **Label directly on the data.** A legend is a failure to design the chart.
- Currency right-aligned, Inter tabular numerals, **THB stated once in the column header**, not in
  every cell.
- **Negative numbers in parentheses, in Navy — never in red.** The Year 1 loss is deliberate and
  correct; red editorialises against our own case.
- Every chart carries an 11pt basis note beneath it in `#94A3B8`.
- Tables: no vertical rules, no zebra fill. A 1px `#E2E8F0` rule under the header and between rows,
  and 20px row padding. Let the whitespace do the separating.

---

# Part six — the two set pieces

These two slides carry the document. Give them the most time.

## 6.1 The problem slide (slide 3)

Three statements stacked, each with a dominant number hung left and the sentence set beside it in
22pt. `75%` and `3 in 4` at ~140pt. Then the turn — *"The reason is not lack of interest. It is lack
of access."* — set at 28pt in Navy, separated by clear space and a short Tech Teal rule, so it reads as
the conclusion rather than a fourth statistic.

No icons. No illustration. The numbers are the design.

## 6.2 The 15 / 85 slide (slide 11)

**This is the emotional centre and the reviewer's actual decision.** It must land in under two seconds.

The approach that works: **one horizontal bar across the full content width**, split 15/85.
- The 15% segment in **Tech Teal `#00D4C8` at 25% tint**, labelled *Built and running*.
- The 85% segment in the **Teal gradient `#00D4C8 → #22C55E`**, labelled *This project*.
- The numbers set large **above** their segments, not inside them.
- Beneath each segment, its contents in 16pt Inter — three items on the left, the eight functions
  summarised on the right.

The whole point is proportion made visible. Do not draw it as two equal columns, do not use a pie
chart, and do not let the 15% look bigger than it is to be polite. **The 85% is what we are asking to
be promoted; it should dominate the slide, because it dominates the project.**

---

# Part seven — production

**There is no file-size limit on your output. Do not compromise the design to hit one.** Export at
full quality; the client compresses afterwards with a dedicated tool before filing.

- Place screenshots at full resolution. Draw diagrams and charts as vectors.
- Deliver the print-ready PDF **and** the editable source.
- State the final file size on delivery so the client knows how much compression is needed.

*(Background, not a constraint on you: the BOI portal itself caps uploads at 5 MB, which is why the
compression step exists. That is the client's step, not yours.)*

---

# Part eight — checklist before delivering

- [ ] Gradient foot rule (`#2563FF → #00D4C8`) on **every** slide, including dark ones
- [ ] EAG logo top-left on every slide; page number `nn | 26` with a Tech Teal separator
- [ ] Only the four brand gradients, at most one gradient element per slide; ground is Soft White `#F6F8FA`, never pure white
- [ ] Poppins headings, Inter body — no serif anywhere
- [ ] Every number matches `04-FACTS.md` exactly
- [ ] Year 1 loss in parentheses, in Navy, not red
- [ ] No banned word anywhere, **including in captions, chart labels and slide notes**
- [ ] MySportia wordmark on the cover and act openers; the mark on 7 and 12; pink as the product accent on product-side slides only
- [ ] At least half the slides carry an image, diagram or chart; never two consecutive all-text slides
- [ ] Real screenshots used; no invented UI
- [ ] Technology slide clearly marked as awaiting the CTO
- [ ] Nobody is named except Justin Cohen and Dmytro Bodlev
- [ ] No bullet dots; numerals hung in Green
- [ ] Slide 9 ("the order this had to be built in") reads as the turn of the argument, not as filler
- [ ] Read it once at 25% zoom — the shape of each slide should be legible with no text at all
- [ ] Full-quality export, and the final file size stated on delivery
- [ ] The sport icon library used on slides 6 and 26; all ten production screens placed somewhere in the deck
