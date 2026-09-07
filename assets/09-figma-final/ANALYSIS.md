# Figma "Final" — Investor Pitch 2025-2026 (captured 2026-09-07)

Source: figma.com file `bYHIxf9wctphcGyXBM6Esl` (Exsportia Company team), page "Priority: Investor Landing Page", areas labeled **Final**.
Exports here: `Final-section-full.png` (8033×18080 @1x — heroes + full layout) · `Final-frame-main.png` (5596×15254 @1x — the approved long-scroll landing).

## Design language (what makes it good — use everywhere)
- **MySportia brand carried hard**: X-mark built from pink/amber/green pills + navy, athlete photography cut out over the mark; lowercase `mysportia` wordmark
- **Black-and-white typographic slabs** with ONE accent color per statement (pink); huge confident headlines ("We close venues in the field. **We onboard them in an hour.**")
- **Stat quads**: 4 big-number cards in a row (30 visited · 25 piloted · 5 qualified · 5 retained) with tiny captions
- **Journey rails**: colored-dot step timelines (Landing→Book→Demo→Intake→Onboarding→LIVE), "From advert to live venue in 7 days"
- **Real UI mockups everywhere**: iPhone frames for player app (Discover/Book/Pay/Play, Feed, Profile, Find Opponents, Leagues, Teams), MacBook for venue back office; gradient lilac cards behind devices
- **Dark callout boxes** with green mono-label headers (BUSINESS MODEL CALLOUT / STICKINESS BOX)
- **Left rail navigation** of the narrative: Vision · Players · Venues & Businesses · Trainers & Coaches · Competition · Ecosystem diagram · Business model · Partners · Financials · Marketing & Distribution · Team · Vision & Expansion · Funding ask & Contact
- Hub-and-spoke competition diagram (mysportia core vs fragmented single-sport apps; "$200M+ raised across fragmented single-sport tools")
- Founder quote card (gradient): "We're not changing behaviour. We're removing barriers."
- Team cards (photo, role in accent, "Owns:", "Why it matters:") + geography strip (Koh Samui/Bangkok · Lviv)
- Closing rhythm: phased roadmap (Thailand proof → SEA 18-month window → Global), $10.5M→$3.3B GTV ladder, funding ask block ($1M–$1.5M seed), Book-a-call + Data-room + Apply form, footer

## Key content facts (INVESTOR world — ⚠️ NOT the BOI story)
34 live venues · ~10 cities · 162M THB cumulative GTV · 94% YoY · $750K self-funded · 400,000 players stat · 22,150 trainers · 5% per transaction, no subscriptions · team includes Lviv/Ukraine R&D · timeline from 2021.
**Never mix these numbers into BOI documents (BOI: 20 pilot venues, licence-fee model, 17 Sep 2025 company, 15/85).** Two separate worlds by design.

## Next step (agreed with Justin)
Assemble a Claude Design asset pack from these exports (crop heroes, phone mockups, stat cards, diagrams as individual assets) + a slide-by-slide brief in this design language, then run Claude Design to rebuild the presentation(s).

## Asset pack — EXTRACTED 2026-09-07 via Figma Dev Mode MCP (124 files in `assets/`)
- **11 full screens** at 1440px design width: 3 hero variants, Vision, Players, Business, Trainers, Financials/Model, Marketing & Distribution, Founders, Vision & Expansion
- **Components**: Nav rail, stat cards, feature cards (bookings/customers/memberships/operations/payments/marketplace), card instances, title blocks
- **Diagrams**: competition hub-spoke, feature grid, ecosystem pieces
- **Photography & imagery**: athlete photos, AI-generated hero images, team photos/profiles, phone mockups, payment-method logo strip
- **`DESIGN-TOKENS.json`**: full variable defs — type system is **Helvetica Neue** (Hero 72/80 Bold · H1 54/60 · H2 44/52 · Subheading 20/26 Medium · Body M 18/26) with Helvetica Now Display for H4; grey ramp #191919/#333333
- **`structure-final-section.json` / `structure-final-frame.json`**: complete node trees with IDs — any asset can be re-pulled at any size via the local MCP (`http://127.0.0.1:3845/mcp`) while Figma desktop is open
