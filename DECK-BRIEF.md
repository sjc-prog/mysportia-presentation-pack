# DECK BRIEF — MySportia BOI Project Summary Deck (v2, design upgrade)

> **Read this with `03-CONTENT.md` (every word, slide by slide) and `04-FACTS.md` (the numbers that must never change).**
> This file is the DESIGN instruction. The words are already written and approved — do not rewrite them.
> Target: 26 slides, 16:9 landscape (1920×1080), PDF export under 5MB.

---

## 1 · What this deck is for

A Thailand Board of Investment officer reads this to decide whether Education AI Group Co., Ltd. qualifies for promotion under **activity 8.1.1 — Development of Software, Digital Platform or Digital Content**.

They are not an investor. They are a civil servant checking that a real company with real engineers is doing real software development in Thailand. The deck must feel **credible, specific and built**, never speculative or salesy.

**The tone: quietly confident. Show the system, don't sell the dream.**

---

## 2 · The design bar

The visual standard is set by the MySportia investor landing page in `assets/09-figma-final/`. Study these first:

| Study this | For |
|---|---|
| `screen-hero-1.png` | Hero composition — the X-mark built from pink/amber/green pills with an athlete cut out over it |
| `screen-players.png` | Device mockups on gradient cards, feature grids |
| `screen-business.png` | Dark callout boxes, back-office laptop mockups |
| `screen-trainers.png` | Stat-led openers, card pairs at 408/670 widths |
| `asset-competition-diagram.png` | Hub-and-spoke diagram craft |
| `screen-marketing-distribution.png` | Stat quads, journey rails with coloured dots |

**What makes that work — reproduce all six:**

1. **One idea per slide, stated as a sentence.** Headlines are complete thoughts with a full stop, not labels. "We close venues in the field. **We onboard them in an hour.**" — never "Venue Onboarding".
2. **One accent colour per statement.** The headline is near-black; a single clause is pink. Never two accents competing.
3. **Enormous type contrast.** Hero 72pt against 16pt captions. No mid-sized mush.
4. **Real interface, never icons standing in for product.** Every product claim is evidenced by an actual screen in a device frame.
5. **Generous negative space.** The Figma pages breathe — roughly half of every screen is empty. Resist filling.
6. **Numbers are the hero when numbers are the point.** Stat quads: huge figure, tiny label beneath, thin rule between.

---

## 3 · Brand system — EAG house, MySportia product

The deck is published by **Education AI Group**; the product shown is **MySportia**. EAG owns the frame (logo top-left, page numbers, closing rule); MySportia owns the content.

**Colour**
| Token | Hex | Use |
|---|---|---|
| Deep Navy | `#0B132B` | All headline type, dark panels |
| Future Blue | `#2563FF` | Gradient start, EAG accents |
| Tech Teal | `#00D4C8` | Gradient end, positive states |
| MySportia Pink | `#ED3163` | The accent clause, single per slide |
| Soft White | `#F6F8FA` | Page ground |
| Rule gradient | `linear-gradient(90deg,#2563FF,#00D4C8)` | 4pt bar at the foot of every slide |

**Type** — Poppins for headlines (600/700), Inter for body (400/600). If Poppins is unavailable, Helvetica Neue Bold is the fallback, matching the Figma system in `assets/09-figma-final/DESIGN-TOKENS.json` (Hero 72/80, H1 54/60, H2 44/52, Body 18/26).

**Every slide carries:** EAG logo top-left (22pt tall), page number top-right in `NN | 26` with the current number in pink, act label above the headline in 7.5pt pink letterspaced caps, and the gradient rule across the foot.

---

## 4 · The three acts

| Act | Slides | The argument |
|---|---|---|
| **I — The world** | 1–8 | Sport is everywhere in education, then it stops. Access is the barrier. MySportia is the infrastructure that removes it. |
| **II — The build** | 9–21 | We fixed the venues first because the marketplace is worthless without them. 15% is built; this project funds the 85%. |
| **III — Thailand's return** | 22–26 | Connected revenue, automatic accounting, direct tax filing. A bigger, cleaner tax base at no cost to the state. |

Section openers (slides 2, 9, 22) are full-bleed Deep Navy with the act number in pink, one line of white type, and nothing else.

---

## 5 · Slide-by-slide asset mapping

Words come from `03-CONTENT.md`. Assets below are in `assets/`. Where a Figma asset is named, **reuse the composition and craft — never its old numbers.**

| # | Slide | Design direction & assets |
|---|---|---|
| 1 | Cover | Hero treatment from `09-figma-final/screen-hero-1.png` — X-mark + athlete, lowercase `mysportia` wordmark. Sport-icon watermark field from `06-mysportia-brand-book/61-ICONS.svg` at 6% opacity. Subtitle "National sports and activity infrastructure for Thailand" with *Thailand* in pink |
| 2 | Act I opener | Navy full-bleed |
| 3 | The problem | The 75% stat as a single vast figure, "3 in 4" beneath. Supporting photography from `11-mysportia-brand` |
| 4 | Where it started | School-sport imagery; timeline rail showing sport stopping at graduation |
| 5 | Why access is hard | Four friction cards in the Figma card idiom (`asset-card-lg.png`) |
| 6 | Every sport | The ~110-sport icon field from `61-ICONS.svg` as the whole slide — this is the single most striking visual available. Minority sports called out in pink |
| 7 | What MySportia is | Product hero: phone + laptop mockups from `09-figma-final/asset-feature-grid.png` |
| 8 | The architecture | Two-sided diagram: venue side / player side, one system between. Build in the style of `asset-competition-diagram.png` |
| 9 | Act II opener | Navy full-bleed |
| 10 | ⭐ The order this had to be built in | The argument slide. Sequential rail: venues first → marketplace second. Give it room |
| 11 | The three phases | Three-column progression |
| 12 | Built and running | **Live proof.** Real screenshots from `07-live-screenshots/` in device frames. "Live at 20 pilot venues in Thailand" |
| 13 | What a venue gets | Feature cards from `09-figma-final/asset-feature-bookings/customers/memberships/operations/payments` — these are ready-made and excellent |
| 14 | What a player gets | Player app screens from `04-product-screens/`, laid out like `screen-players.png` (Discover / Book / Pay / Play) |
| 15 | To be developed — 85% | Eight numbered modules. Restrained, systematic, not decorative |
| 16 | ⭐ The 15 / 85 split | Single most important slide for the officer. One bar: 15% built, 85% to build. Nothing else on the page |
| 17 | Why the two halves are one system | Simple connective diagram |
| 18 | One infrastructure. Many industries. | MySportia / Kizzem / PetFlow HQ marks from `08-group-frameworks/`. Note the status chips ("LIVE — 20 PILOT VENUES") in the Figma idiom |
| 19 | Technology | The production stack, ten cards. Already rebuilt — match its current form but upgrade the card craft |
| 20 | Twelve-month plan | Journey rail with coloured dots, as in `screen-marketing-distribution.png`. Four quarters |
| 21 | Customers and revenue | Licence band table (1,000 / 2,000 / 5,000 / from 10,000) with the payment-processing footnote |
| 22 | Act III opener | Navy full-bleed |
| 23 | The Thailand dividend | Four-step chain ending in the dark "growing, visible tax base" card. Already strong — refine craft |
| 24 | The team | Justin and Dmytro. **Use initials (JC / DB), not photographs** — staff headshots are deliberately not in this repo |
| 25 | Investment and what Thailand gets | Stat quad: 5.65M THB · 2,080,000 · 12 months · 2 sites. Figma stat-card treatment |
| 26 | Close | "Get Thailand playing." Full-bleed, EAG logo, quiet |

---

## 6 · Hard rules — a violation fails the deck

**Never appear anywhere:**
`Exsportia` · `Israel` · `IP transfer` / `assignment` · `commission` · `transaction fee` as the business model · `MVP` · `enhance` / `improve` / `optimise` / `expand` / `refine` (BOI reads these as "not new development")

**Numbers that are fixed** (full list in `04-FACTS.md`):
- **20 pilot venues** — never 32, never 33, never 34
- **15% built / 85% to develop**
- **5.65M THB** total investment · **2,080,000** Year 1 Thai IT payroll · **7,330,000** Year 3
- **4 / 8 / 12** Thai engineers across years 1–3
- Company incorporated **17 September 2025**; production **20 August 2026**; trading from **1 September 2026**
- Licence bands **1,000 / 2,000 / 5,000 / from 10,000** THB per month

⚠️ **The `09-figma-final` assets carry investor-world numbers** — 34 venues, 162M GTV, 5% per transaction, a 2021 timeline, Lviv R&D. Those are from a different document for a different audience. **Take the pixels. Never the numbers.**

---

## 7 · Output

26 slides, 1920×1080, exported as PDF. Fonts embedded. Under 5MB after compression, or supply full quality and it will be compressed here.

If a slide cannot be made excellent, say so rather than shipping filler — the previous version shipped a Technology slide reading "AWAITING INPUT" in ten empty boxes, and it reached the submission pack before being caught.
