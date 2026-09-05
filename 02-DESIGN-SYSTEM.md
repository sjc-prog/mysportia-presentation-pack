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
most persuasive marks in the document. Set them at 96–160pt in Satoshi 600 and let them carry whole
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
| **Education AI Group** | Every slide's chrome: ground, header, footer, foot rule, page number, headline colour, all typography, section dividers, charts | Is never reduced to a small logo in the corner of a MySportia-branded page |
| **MySportia** | Only what sits inside the frame: product screenshots, the product wordmark where the product is named | Never sets the slide background, never supplies a headline colour, never replaces the EAG header |

**The test.** Flick through at speed. It must read as one Education AI Group document that contains a
product — not as two brands taking turns.

**One permitted exception.** A product-showcase slide may run a full-bleed MySportia navy panel
*provided* the EAG header, footer and page number stay on top of it in the reverse treatment. That is
the frame holding, not the frame being replaced.

---

# Part three — Education AI Group, the parent system

## 3.1 Colour

| Role | Name | Hex |
|---|---|---|
| Accent | **Green** | `#6FBC8F` |
| Accent light | **Mint** | `#A7E3C1` |
| Accent deep | **Deep Green** | `#2E6B53` |
| Text / dark ground | **Navy** | `#111827` |
| Rule / border | **Light Grey** | `#E6EAE7` |
| Page ground | **Off White** | `#F7F8F7` |
| Secondary text | — | `#5A6270` |
| Tertiary text | — | `#9AA1AC` |

**Ratio: ~70% off-white ground, ~20% navy type, ~10% green.**

**There is no cyan and there are no gradients.** If any older brief said "green-to-cyan", it was wrong
and is withdrawn. The ground is Off White `#F7F8F7`, never pure white.

## 3.2 Typography

**Satoshi** for headings and key communication. **Inter** for body and supporting.
Fallback if Satoshi is unavailable: General Sans, then Inter at tighter tracking. **Never a serif,
never a geometric display face.**

| Element | Size | Weight | Tracking | Colour |
|---|---|---|---|---|
| Section opener | 72pt | Satoshi 600 | −2% | White on Navy |
| Slide title | 40pt | Satoshi 600 | −1% | Navy |
| Eyebrow above title | 11pt | Inter 600, UPPERCASE | +12% | Deep Green |
| Hero number | 96–160pt | Satoshi 600 | −3% | Navy, unit in Green |
| Sub-head / lead-in | 22pt | Satoshi 500 | −0.5% | Navy |
| Body | 16pt | Inter 400 | 0 | `#5A6270` |
| List item title | 17pt | Inter 600 | 0 | Navy |
| Table | 14pt | Inter 400 | 0 | Navy |
| Caption / source | 11pt | Inter 400 | 0 | `#9AA1AC` |

Body line-height **1.55**. Headline line-height **1.12**. Measure: **never wider than 72 characters.**

## 3.3 The signature typographic move

Headlines run Navy and the **final phrase drops to Green**. The brand's own line does exactly this:

> Intelligent. Trusted. Simple. **Future-ready.**

Use it on the cover and on section openers. **Once per spread at most** — it stops working when every
headline does it.

## 3.4 Grid and layout

- Canvas **1920 × 1080**. Outer margin **96px** all sides; **112px** on the cover.
- **12 columns**, 24px gutters. Two-up content sits 6/6 with a full gutter; asymmetric splits use 7/5.
- **8px baseline grid.** Everything snaps. Consistent vertical rhythm is most of what makes a deck feel
  professionally set.
- Title block sits at a fixed height on every content slide so titles do not jump between slides.
- Content starts at a consistent y across the deck. Slides that break the grid should break it
  deliberately and completely — a hero-number slide, a full-bleed panel — never by a few pixels.

## 3.5 Page furniture — on every slide

Taken from the letterhead, document cover and presentation-slide specimens on brand-book page 05.

1. **Green foot rule.** Solid `#6FBC8F`, full width of the bottom edge, **6px**. This is the strongest
   single carrier of the identity — it is on the letterhead, the cover and the email signature.
   **Every slide. No exceptions, including the dark ones.**
2. **Header.** EAG horizontal logo top-left, 32px high. Right-hand slot: `BOI 8.1.1 · EDUCATION AI GROUP`
   in 10pt Inter, `#9AA1AC`, uppercase, wide-tracked.
3. **Page number.** Top-right or bottom-right, Inter 11pt, format `04 | 16` with the separator in
   Green — the brand book numbers its own pages this way.
4. **Ghosted leaf watermark.** The leaf icon at **3–6% opacity**, large, bleeding off one corner.
   **One per slide maximum, and never behind a table, a chart, or a screenshot.** Use it on the cover,
   the section openers and the definition slide. Not on dense slides.

## 3.6 Logo rules

Clear space on all four sides equal to the cap height of the "E" in the wordmark. Minimum 120px
digital. Never alter proportions, colours or elements. Reverse lockup (white wordmark, green leaf) on
Navy or on photography. Files in `assets/02-eag-logos/`.

## 3.7 Components

- **Cards** — Off White or white, `#E6EAE7` 1px border, **16px radius**, very soft shadow
  (`0 1px 2px rgba(17,24,39,0.04), 0 8px 24px rgba(17,24,39,0.05)`), **32px internal padding**.
- **Numbered list items** — the numeral in Green, Satoshi 600, hung in the left margin so the text
  block stays flush. Do not use bullet dots anywhere in this deck.
- **Icons** — thin single-weight line, open forms, often inside a circular outline. Never filled,
  never duotone. Reference set on brand-book page 05.
- **Rounded forms throughout.** Nothing sharp-cornered.

## 3.8 Section openers

Navy `#111827` ground, reverse logo, 72pt white title with the final word in Green, eyebrow in Mint,
large ghosted leaf. **Green foot rule stays.** Three of them: *The opportunity* · *The project* ·
*Thailand's return*.

---

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
licence for Averta**, so if it is unavailable use the EAG stack (Satoshi / Inter) rather than
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
- **The navy** — MySportia `#233247` and EAG `#111827` read as one family. Where they meet, use EAG's
  `#111827` for type and let `#233247` live inside product imagery.

# Part five — charts and tables

- Off-white ground, `#E6EAE7` gridlines at 1px, **no chart borders, no 3D, no shadows on data.**
- Series order: `#6FBC8F` → `#2E6B53` → `#A7E3C1` → `#111827` → `#9AA1AC`.
- **Label directly on the data.** A legend is a failure to design the chart.
- Currency right-aligned, Inter tabular numerals, **THB stated once in the column header**, not in
  every cell.
- **Negative numbers in parentheses, in Navy — never in red.** The Year 1 loss is deliberate and
  correct; red editorialises against our own case.
- Every chart carries an 11pt basis note beneath it in `#9AA1AC`.
- Tables: no vertical rules, no zebra fill. A 1px `#E6EAE7` rule under the header and between rows,
  and 20px row padding. Let the whitespace do the separating.

---

# Part six — the two set pieces

These two slides carry the document. Give them the most time.

## 6.1 The problem slide (slide 3)

Three statements stacked, each with a dominant number hung left and the sentence set beside it in
22pt. `75%` and `3 in 4` at ~140pt. Then the turn — *"The reason is not lack of interest. It is lack
of access."* — set at 28pt in Navy, separated by clear space and a short Green rule, so it reads as
the conclusion rather than a fourth statistic.

No icons. No illustration. The numbers are the design.

## 6.2 The 15 / 85 slide (slide 11)

**This is the emotional centre and the reviewer's actual decision.** It must land in under two seconds.

The approach that works: **one horizontal bar across the full content width**, split 15/85.
- The 15% segment in **Mint `#A7E3C1`**, labelled *Built and running*.
- The 85% segment in **Green `#6FBC8F`**, labelled *This project*.
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

- [ ] Green foot rule on **every** slide, including dark ones
- [ ] EAG logo top-left on every slide; page number `nn | 16` with a Green separator
- [ ] No cyan, no gradients, no pure white ground
- [ ] Satoshi headings, Inter body — no serif anywhere
- [ ] Every number matches `04-FACTS.md` exactly
- [ ] Year 1 loss in parentheses, in Navy, not red
- [ ] No banned word anywhere, **including in captions, chart labels and slide notes**
- [ ] MySportia pink appears only inside screenshots and the wordmark
- [ ] Real screenshots used; no invented UI
- [ ] Technology slide clearly marked as awaiting the CTO
- [ ] Nobody is named except Justin Cohen and Dmytro Bodlev
- [ ] No bullet dots; numerals hung in Green
- [ ] Slide 9 ("the order this had to be built in") reads as the turn of the argument, not as filler
- [ ] Read it once at 25% zoom — the shape of each slide should be legible with no text at all
- [ ] Full-quality export, and the final file size stated on delivery
- [ ] The sport icon library has been used at least once — it is the strongest visual asset available
