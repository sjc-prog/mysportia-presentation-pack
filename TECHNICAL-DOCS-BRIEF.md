# BRIEF 5 — The three technical documents

> **Job:** rebuild **three** related exhibits in one consistent house style.
> **Format:** A4 **landscape**, PDF under 5MB each. Deliver as three separate files.
> Read `DECK-BRIEF.md` first for the brand system — it applies here unchanged.
>
> ⚠️ **Set the page size to landscape at export.** Every document so far has come back as landscape artwork on portrait pages with no rotation flag, so each page opened sideways and had to be repaired.

| # | Document | Pages |
|---|---|---|
| **A** | Software Development Details | 4–5 |
| **B** | Technology Appendix | 2–3 |
| **C** | Machinery Schedule | 2–3 |

---

## 1 · What these three do together

These are the officer's proof that **real engineering happens here** — that this is a software company with a codebase, a process and a plan, not a business idea with a developer attached.

They are read by someone technical, or by someone who will pass them to someone technical. They must be **precise, systematic and unembellished**. Where the deck persuades, these three *demonstrate*.

**The house style for all three: engineering documentation, beautifully set.** Think a well-made technical specification — clear hierarchy, tables that are genuinely readable, no decoration that isn't carrying information. Restraint is the point.

All three currently contain the right content in plain layouts. Nothing needs rewriting; the job is structure and legibility.

---

## 2 · Shared design system for the set

- **A common cover treatment** so the three read as a matched set: kicker `SUPPLEMENTARY ATTACHMENT · ACTIVITY 8.1.1`, document title, one-line description, EAG identity.
- **Tables are the primary visual element.** Make them excellent: generous row padding, a tint on alternate rows or a hairline between them, left-aligned text, right-aligned figures, tabular numerals throughout. Never let a table look like a spreadsheet dump.
- **Numbered sections** with the number set large in pale blue as a structural marker.
- **One pink accent per page**, and only on the single fact that matters most.
- **No photography. No device mockups.** Diagrams only where they carry meaning.
- **Footer every page:** thin gradient rule, `Education AI Group Co., Ltd.` left, page number right.

---

## 3 · Document A — Software Development Details

The most important of the three. It is the direct answer to *"what exactly are you developing?"*

**Page 1 — Cover + project type**
Cover, then section 1: **Type (c)** — further development on pre-existing software developed by the company itself. Give this its own clear block; it is the classification the whole application rests on. The pre-existing software is EAG's own work, built in Thailand between September 2025 and August 2026, and is the stated baseline.

**Page 2 — The baseline (what exists today, ~15%)**
The three components in production since 20 August 2026, running at **20 pilot venues**: venue management back office · marketplace listing and booking · payment infrastructure. Set as three clean cards. State plainly that it is open for inspection.

**Page 3 — The eight functions to be developed (~85%)**
The centrepiece. A numbered table of all eight, each with its description:

1. Player feed and consumer experience
2. Opponent matching
3. Leagues, tournaments and rankings
4. Automated tax reporting to the Revenue Department
5. Venue hardware integration
6. Native mobile applications
7. AI-assisted venue onboarding
8. Multi-tenant backend for national scale

Make the numerals structural — large, pale, in the left column. **Every one of these is new; none exists in the system today.** Say so.

**Page 4 — Development process and the twelve-month plan**
The full SDLC carried out in Thailand: modeling · requirement analysis · design · development and implementation · program and system testing · deployment · configuration and change management · related professional training. Set as a horizontal process rail.

Then the plan as four quarters (Q1–Q4) with what each delivers. Rail or four-column grid, matching the deck's twelve-month slide.

**Page 5 — Customers and revenue**
Licence bands: Starter **1,000** · Growth **2,000** · Professional **5,000** · Enterprise **from 10,000** THB per month. Plus the disclosure line, which must be kept exactly in substance: the company also earns payment processing income from venues using its integrated payments; that income is ordinary non-promoted income, fully disclosed, and taxed normally.

---

## 4 · Document B — Technology Appendix

Short, dense, and the most purely technical thing in the pack. It should look like it was compiled by engineers — because it was, from the production codebase.

**Page 1 — The production system today**
A specification table: Languages · Front end · Back end · Data · Payments · Accounting · Monitoring · CI/CD · Mobile · AI tooling. Set as label/value rows with the technology names in a monospace or tabular face so they read as a manifest.

Payments row reads: **Master-merchant integrations with Omise and Stripe** — PromptPay, Thai QR, cards. *(Not PayPal — corrected 8 September.)*

**Page 2 — Extension under this project**
What is added for the new functions: React Native, device firmware and hardware integration toolchain, Revenue Department reporting, multi-tenant architecture.

**Page 3 — Tools by development stage**
The eight-stage table (modeling → related professional training) with the tools used at each. This maps directly onto BOI's own SDLC framing, so it should be the cleanest table in the pack. Note the ISO/IEC 29110 certification programme in the training row.

Footer note: *compiled from the production codebase, September 2026.*

---

## 5 · Document C — Machinery Schedule

A procurement document. It should look like a purchase schedule from a company that knows its supply chain.

**Page 1 — The schedule**
Supplier: **SHENZHEN CARAV ELECTRONICS CO., LTD**, Shenzhen, China — country of origin PRC (China). One kiosk per venue, fifty venues.

The costing table, with figures right-aligned and totals emphasised:

| Line | Unit USD | Qty | USD |
|---|---:|---:|---:|
| Self-service kiosk, 21.5" Android 11 (RK3568) | 453.00 | 50 | 22,650 |
| Floor stand | 88.00 | 50 | 4,400 |
| Access gate / turnstile | 332.50 | 50 | 16,625 |
| **Goods subtotal, EXW Shenzhen** | | | **43,675** |
| Freight, export clearance and marine insurance (~8%) | | | ~3,494 |
| **CIF Thailand** | | | **~47,169** |

Then: at 32.92 THB/USD → **≈ 1,552,800 THB — 1.55 Million Baht.**

**Page 2 — Why CIF, and the point that matters**
Tab 4.5 requires CIF; the Carav quotations are EXW, which excludes freight, clearance and insurance. Import duty and VAT are excluded from CIF.

Then the argument worth setting as a callout — the manufacturer's own specification says **"Not include pos software"**. That is documentary evidence from the supplier that **the software layer is not purchased; it is EAG's own**, which is the subject of this application.

Also state: the equipment is deployed to venues, not sold or given to them. EAG retains title and depreciates the assets.

---

## 6 · Hard rules — all three documents

- **20 pilot venues** · **15% / 85%** · **eight** new functions · **twelve months** · fleet **1.55M THB** at FX **32.92** · hardware total **2.06M** · turnstile **$332.50**
- Licence bands **1,000 / 2,000 / 5,000 / from 10,000** THB per month
- **Payment partners are Stripe and Omise.** Not PayPal — it was wrongly named in an earlier draft and has been corrected across the pack. Do not reintroduce it.
- Supplier named exactly: **SHENZHEN CARAV ELECTRONICS CO., LTD**
- Banned: `Exsportia` · `Israel` · `IP transfer` / `assignment` · `commission` · `MVP` · `enhance` / `improve` / `optimise` / `expand` / `refine` — BOI reads the last group as "not new development", which would undermine the type (c) classification
- Do not add any claim not in this brief
- ⚠️ `assets/09-figma-final` carries investor-world numbers. **Composition yes, numbers never.**

---

## 7 · Assets

| Need | Where |
|---|---|
| Process / journey rails | `assets/09-figma-final/screen-marketing-distribution.png` |
| Card and table treatments | `assets/09-figma-final/asset-card-lg.png`, `Card-Statistic-Highlight_*.png` |
| Hardware imagery (Document C only, sparingly) | `assets/05-hardware/` |
| EAG identity | `assets/01-eag-brand-book/`, `assets/10-eag-brand/` |
| Type and colour tokens | `assets/09-figma-final/DESIGN-TOKENS.json` |

Full file list with URLs: `ASSET-INDEX.md`.
