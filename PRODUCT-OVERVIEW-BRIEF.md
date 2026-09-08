# BRIEF 2 — Product Overview: Photos & Catalog

> **Job:** rebuild the BOI submission document *"Photos, illustration and/or catalog"* to the same visual standard as the deck.
> **Format:** A4 **landscape**, 6–8 pages, PDF under 5MB.
> Read `DECK-BRIEF.md` first for the brand system — it applies here unchanged.

---

## 1 · What this document has to do

BOI's officer has read the application. This is where they **see** that the product exists.

It is the evidence exhibit: every image is the real production system running at 20 pilot venues, plus the venue hardware. Its entire persuasive weight rests on one impression — *this is built and operating, not a plan.*

**So the design job is credibility, presented beautifully.** Not a brochure, not a mood board. A catalog with the confidence of a product manual from a company that knows what it has made.

The current version is correct but plain: screenshots dropped into boxes with captions underneath. Everything below is about giving that same true content real presence.

---

## 2 · The single biggest change: device framing

Right now screenshots float as bare rectangles. In the Figma work they always sit **inside device frames on a coloured or gradient ground**, which does three things at once — it signals "this is software", it gives the page structure, and it lets a small screenshot command a large area.

Study `assets/09-figma-final/screen-players.png` and `screen-business.png`. Reproduce that treatment:

- **Phone screenshots** → iPhone frame, tilted or straight, on a soft gradient card (lilac, pale blue, or Soft White with a tint)
- **Desktop screenshots** → MacBook frame or a clean browser chrome with the real URL bar showing `mysportia.com`
- **Never more than three screens per page.** One dominant, two supporting. The current page 3 crams six back-office screens into a grid — split it across two pages and let them breathe.

Ready-made device compositions to reuse directly:
`asset-feature-grid.png` · `asset-feature-bookings.png` · `asset-feature-customers.png` · `asset-feature-memberships.png` · `asset-feature-operations.png` · `asset-feature-payments.png`

---

## 3 · Page plan

| Page | Content | Design |
|---|---|---|
| **1 · Cover** | Title, EAG identity, one line: *"Every image is the real system — the production deployment running at 20 pilot venues in Thailand. Nothing is a mock-up."* | Full-bleed hero in the style of `screen-hero-1.png`. Big, quiet, confident. The claim in one sentence, given the whole page |
| **2 · The consumer marketplace** | mysportia.com — search any sport by place, date, time; live map; Thai and English | Desktop browser frame, dominant. Small phone frame overlapping bottom-right showing the same page responsive. Caption strip beneath |
| **3 · The player experience** | Booking a session, the member view, class packs | Three phones in the Figma player-screen idiom, on gradient cards, staggered heights |
| **4 · The venue back office (i)** | Scheduling, bookings, customer records | Laptop frame dominant + two detail crops. Use the real screenshots from `assets/07-live-screenshots/` |
| **5 · The venue back office (ii)** | Finances, analytics, memberships and packages | Same treatment, second spread — do not compress into page 4 |
| **6 · Booking embedded anywhere** | The booking flow; the venue's own website carrying the same live booking | Two-column: flow steps as a journey rail (coloured dots, as in `screen-marketing-distribution.png`), venue site screenshot beside |
| **7 · Venue onboarding** | Services, schedule, pricing structured step by step | Numbered sequence, restrained |
| **8 · The venue hardware** | Kiosks, floor stands, access gates from `assets/05-hardware/` | Product-catalog treatment on white, with spec callouts. **Must carry the manufacturer's note "Not include pos software"** — this is the evidence that the software layer is EAG's own |

Pages 4/5 and 6/7 may merge if the design is stronger for it, but never at the cost of cramming.

---

## 4 · Craft notes

**Captions carry the argument.** Each is one plain sentence saying what the officer is looking at — "Scheduling — the week at a glance." Set in Inter 9–10pt, warm grey, directly beneath its image. Never floating loose.

**One accent per page, maximum.** Pink for the single phrase that matters. Everything else is navy and grey.

**The hardware page is not a slide.** It's a product catalog page — white ground, generous margins, spec text in a tidy column. Think supplier datasheet designed properly.

**Footer on every page:** thin gradient rule, `Education AI Group Co., Ltd.` left, page number right.

**Closing line, page 8 foot, small:** *"All software imagery is the production system as deployed on 20 August 2026 and operated since."*

---

## 5 · Hard rules

- **20 pilot venues.** Never any other figure.
- Banned everywhere: `Exsportia` · `Israel` · `MVP` · `mock-up` used of our own product · `enhance` / `improve` / `optimise` / `expand` / `refine`
- Hardware supplier is **SHENZHEN CARAV ELECTRONICS CO., LTD** — name it exactly
- Every screenshot must be a **real** screen. If an image would need faking, cut the claim instead
- ⚠️ The `09-figma-final` assets carry investor-world numbers (34 venues, 162M GTV). **Take the composition and craft. Never the numbers.**

---

## 6 · Assets

| Need | Where |
|---|---|
| Live production screens | `assets/07-live-screenshots/` |
| Player and venue app screens | `assets/04-product-screens/` |
| Kiosks, stands, gates | `assets/05-hardware/` |
| Device-frame compositions to copy | `assets/09-figma-final/screen-players.png`, `screen-business.png`, `asset-feature-*.png` |
| Brand marks | `assets/01-eag-brand-book/`, `assets/03-mysportia-logos/` |
| Type and colour tokens | `assets/09-figma-final/DESIGN-TOKENS.json` |

Full file list with URLs: `ASSET-INDEX.md`.

Output A4 landscape PDF, fonts embedded. If a page cannot be made excellent with real material, say so rather than filling it.
