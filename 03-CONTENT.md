# CONTENT — every word, slide by slide

> **This is the copy. Set it, do not rewrite it.** Checked line by line against the filed application
> and against BOI's language rules. Changing a word can change what the application means.
> The reasoning behind the narrative is in `00-THE-MYSPORTIA-STORY.md` — read that first.
> The presenter's script for every slide is in `05-PRESENTER-SCRIPT.md` — it shows where the emphasis
> falls, but **it is spoken text and never appears on a slide.**

**22 slides. Landscape 16:9, 1920 × 1080.**

The portal specifies the order of its own required contents: items 2–6 land on slides 12–18 and
item 7 (the team) on slide 20, in the portal's own order. Slides 1–11 are the setup the portal does
not prescribe, and they are where the story does its work.

### The three acts

| | Slides | |
|---|---|---|
| **I — The opportunity** | 2–8 | Why this exists. The problem, the founding insight, what MySportia is |
| **II — The build** | 9–18 | What was built, what this project builds, and why the order matters |
| **III — Thailand's return** | 19–22 | Team, investment, what the country gets |

---

## 1 · Cover

```
MySportia
National sports and activity infrastructure for Thailand
```
Footer block:
```
Education AI Group Co., Ltd.
September 2026
```
The word **Thailand** takes Tech Teal. Nothing else on this slide is green except the foot rule.

---

## 2 · Section opener — Act I

```
The opportunity
```
Eyebrow: `ACT I — WHY THIS EXISTS`

---

## 3 · The problem

Three statements. Numbers dominant, set large, one under another. This is the strongest evidence in
the document; give it room.

```
75%          of Thai adults are highly sedentary, sitting more than seven hours a day
3 in 4       stop playing sport entirely after leaving education
```
Then, set apart after a short green rule, as the conclusion rather than a fourth statistic:
```
The reason is not lack of interest. It is lack of access.
```
No icons. No illustration. The numbers are the design.

---

## 4 · Where it started

A quieter slide. The founding moment, told as a short story, not a bullet list.

```
Sport is everywhere in education. Then it stops.

It once took over two hours of phone calls to organise a single game of paintball
— a venue with no online booking, a group to coordinate, and no way to see
whether anything was available.

A flight, a hotel or a car can be booked in ninety seconds.

Sport is one of the last major consumer categories with no unified way in.
```

---

## 5 · Why access is hard

Four blocks in a four-up grid.

```
Fragmented
Venues run on phone calls, LINE chats, paper schedules and spreadsheets.
Over 60% have no online booking system at all. There is no central place to
discover or book anything.

No one to play with
Having someone at your level to play against is the single biggest predictor
of whether a person keeps participating.

Minority sports are invisible
Climbing, diving, Muay Thai, archery, community leagues — happening across the
country, with no way for the people who would play them to find them.

No visibility for the state
A largely cash sector means no participation data, no sector picture, and tax
revenue that goes uncollected.
```

---

## 6 · Every sport — including the ones nobody builds for

**The icon-wall slide.** A field of the sport pictogram library
(`assets/06-mysportia-brand-book/61-ICONS.svg`, ~110 glyphs) fills the slide — navy glyphs on their
light chips, on the off-white ground, all at one optical size. Over it, one line:

```
Every sport. Every activity. One infrastructure.
```
Caption, small:
```
Once the connective layer exists, the marginal cost of carrying one more sport
is close to zero. The small sports get the same infrastructure as the big ones.
```
This is the minority-sports argument made visible. Let the wall do the talking.

---

## 7 · What MySportia is

One sentence, large, alone. This is the definition the room will quote back.

```
National infrastructure connecting people to the places where they can play —
raising participation in sport and activity, including amateur and minority
sports, by automating the business side so venues can concentrate on
delivering the service.
```
No decoration. A ghosted leaf at most.

---

## 8 · The architecture — two sides, one system

**A diagram earns its place here.** Two columns feeding one platform layer.

```
VENUE SIDE — the engine
Online booking and schedules · payments as a master merchant with Stripe and
Omise (PromptPay, Thai QR, cards) ·
automatic invoices, receipts and VAT · customer database and marketing ·
memberships and packages · automated reminders · resource and staff management

CONSUMER SIDE — the storefront
Find any sport by location, date or type · instant booking and payment ·
peer matchmaking by skill level · create a game, league or tournament ·
rankings, leaderboards and results · your bookings, passes and memberships in
one account, under your control · vetted activities, in Thai and English

The full planned scope — two sides, one system.
```
The closing caption matters: this diagram shows the **full planned scope**, not current status —
slides 12 and 13 divide it into built and to-be-built.

---

## 9 · Section opener — Act II

```
The build
```
Eyebrow: `ACT II — WHAT EXISTS, AND WHAT COMES NEXT`

---

## 10 · ⭐ The order this had to be built in

**The intellectual heart of the deck.** It explains why the company spent a year on the unglamorous
half, and makes the 15/85 split obvious rather than arbitrary. Give it a full slide and let it breathe.

```
The obvious thing to build first was the consumer marketplace.
It could not be built.
```
Then, given weight:
```
The venues were the bottleneck. Notebooks, spreadsheets, phone calls, LINE
messages. No real-time availability, no digital payments, no central system.

You cannot build a marketplace on top of businesses that are not bookable.
```
Then, set as the turn — this is the line to design around:
```
Hotels first got booking systems.
Only then did a booking marketplace become possible.

So the order was inverted, deliberately.
First fix the venues. Then build the thing people actually use.
```

---

## 11 · The three phases

A horizontal three-step diagram. Phases 1 and 2 sit behind; **Phase 3 is visibly the subject.**

```
PHASE 1 — Fix the venues                                          BUILT
One system that runs the business: bookings, schedules, payments,
invoices and VAT, memberships, customers, staff and resources.
Make every venue instantly bookable.

PHASE 2 — The marketplace                            BOOKING LAYER BUILT
Aggregate the digitised venues. One place to find any sport by
location, date or type, with real-time availability and instant
booking, in Thai and English.

PHASE 3 — The lifestyle layer                              THIS PROJECT
Profiles and skill ratings, opponent and partner matching, leagues,
tournaments and national rankings, activity feed and community,
native mobile applications.
```
Beneath, as a single line, the last three words in Tech Teal:
```
Discovery  →  Booking  →  Participation  →  Community  →  Progression
```
Caption:
```
Phases 1 and 2 cover discovery and booking. Phase 3 is participation, community
and progression — the half that determines whether a person is still playing in
a year.
```

---

## 12 · Built and running — live today

*Portal item 2: the functions developed before this application.* **This is the showcase slide — real
product, not mockups.** Use the live screenshots in `assets/07-live-screenshots/` and the production
screens in `assets/04-product-screens/`: the marketplace with the live map, the phone booking flow,
and one venue back-office screen (analytics or calendar). Framed in cards on the off-white ground.

```
Venue management back office — bookings, scheduling, customer records,
staff and reporting
Marketplace listing and booking — live at mysportia.com
Payment infrastructure — master merchant with Stripe and Omise;
PromptPay, Thai QR, cards
```
Status line, given weight:
```
Live at 32 pilot venues in Thailand
```
Caption:
```
Phase 1, and the booking layer of Phase 2 — approximately 15% of the planned
system. The venues are fixed and running.
```

---

## 13 · To be developed — approximately 85%

*Portal item 3.* **The most important content slide in the deck.** Eight functions, numbered,
numerals in Tech Teal.

```
1  Player feed and consumer experience
   A personalised activity feed through which players discover venues, sessions
   and events near them, with social profiles and activity history.

2  Opponent matching
   Matching players to opponents and partners by sport, skill level, location and
   availability, so that a player without a group can still book and play.

3  Leagues, tournaments and rankings
   Creation and running of leagues and tournaments across venues, with fixtures,
   results, standings and a national ranking system by sport.

4  Automated tax reporting to the Revenue Department
   Automated preparation and submission of venue tax reporting directly from
   transaction records, bringing venues into the digital tax system without
   manual filing.

5  Venue hardware integration
   Device firmware, the hardware integration layer and the platform services that
   operate venue access gates, point-of-sale terminals, self-service kiosks and
   QR-based entry and validation.

6  Native mobile applications
   Separate native applications for players and for venue operators, on iOS and
   Android.

7  AI-assisted venue onboarding
   Automated extraction and structuring of a venue's services, schedule and
   pricing so that a venue can be brought onto the platform in hours rather
   than weeks.

8  Multi-tenant backend for national scale
   The platform architecture required to operate across thousands of venues
   nationally, with tenant isolation, regional data handling and operational
   monitoring.
```
Closing line:
```
None of these functions exists in the system today. All will be built in Thailand,
by the company's Thai engineering team, over twelve months.
```

---

## 14 · ⭐ The 15 / 85 split

**One slide, one image. It must land in under two seconds.** Drawing instructions in
`02-DESIGN-SYSTEM.md` §6.2.

```
15%  Built and running        →  Venue back office · marketplace booking · payments
85%  This project             →  Eight new functions · twelve months · in Thailand
```
Set beneath, small:
```
The first half is the plumbing. The second half is the product.
```
Footnote:
```
Completeness measured against full planned product scope.
```

---

## 15 · Why the two halves are one system

```
Every venue that joins brings its existing members with it. They become users of
the marketplace on day one — with no consumer advertising at all.
```
Set apart:
```
This is why the consumer side reaches national scale without national marketing
spend — and why the two halves are one system rather than two products.
```

---

## 16 · Technology

*Portal item 4.* **Awaiting the CTO — and deliberately light.** One clean slide: a structured,
labelled frame with the slots empty, so the stack drops in without redesign. Mark it clearly as
awaiting input so it can never be sent half-filled. No architecture diagrams, no jargon.

```
Languages · Frontend framework · Backend framework · Database ·
Hosting and infrastructure · CI/CD · Monitoring · Mobile (iOS / Android) ·
Device firmware and hardware integration toolchain · AI and automation tooling
```

---

## 17 · The twelve-month development plan

*Portal item 5.* A timeline across four quarters showing when each of the eight functions lands.
Platform and backend foundations early, hardware and mobile mid, leagues and rankings later. Label
the axis in quarters from approval, not calendar months.

Anchor line:
```
Built in Thailand, at the Bangkok development office, by the company's Thai
engineering team.
```

---

## 18 · Customers and revenue

*Portal item 6.*

```
CUSTOMERS
Sports and activity venues in Thailand — Muay Thai gyms, fitness centres, padel
and tennis courts, swimming pools and multi-sport facilities. On the consumer
side, players who discover and book those venues through the marketplace.

REVENUE
A tiered monthly software licence fee, invoiced to the venue. The fee is fixed
within each band according to venue size, and is set independently of the
venue's own revenue.
```

| Band | Monthly licence fee |
|---|---|
| Starter | 1,000 THB |
| Growth | 2,000 THB |
| Professional | 5,000 THB |
| Enterprise | from 10,000 THB |

One line beneath, small, and **once only in the whole deck**:
```
The company also earns payment processing income from venues using its
integrated payments. That income is ordinary non-promoted income, is fully
disclosed, and is taxed normally.
```

---

## 19 · Section opener — Act III

```
Thailand's return
```
Eyebrow: `ACT III — WHO WE ARE, AND WHAT THE COUNTRY GETS`

---

## 20 · The team

*Portal item 7.* **Education AI Group has no employees today.** Every role below is a hire that
happens after approval. State that plainly — it is a strength, because BOI requires the Thai IT
employment to be new employment created after applying.

**Named:**
```
Justin Cohen — Chief Executive Officer, authorised director
MSc Advanced Management, Leeds University. Founding and leading technology,
product and consumer businesses since 2006, including hardware product
development from design through manufacture.

Dmytro Bodlev — Chief Technology Officer
Platform architecture and delivery. Will build and lead the Thai engineering
team in Bangkok.
```
**To be recruited after approval — roles, no names:**
```
Chief Operating Officer   venue operations, customer support, service delivery,
                          venue hardware deployment
Project Manager           delivery planning and coordination across engineering,
                          design and testing
Head of Sales             national venue acquisition and the Thai agent network
```
**Thai engineering team — counts only, none hired yet:**
```
Year 1: 4      Year 2: 8      Year 3: 12
Roles: project management, systems analysis, development, design, testing
Based at the Bangkok development office.
```

---

## 21 · Investment, employment and what Thailand gets

Two halves.

**Left — the commitment:**
```
5.65M THB    total project investment
2,080,000    Thai IT salaries in year one, against BOI's 1,500,000 minimum
12 months    to completion
2 sites      Ko Samui head office · Bangkok development branch, 100 sqm
```
**Right — what Thailand gets:**
```
Higher participation in sport and physical activity, against a measured 75%
sedentary rate

Amateur and minority sports made visible — once the connective layer exists, the
marginal cost of carrying one more sport is close to zero

Venues brought into the digital tax system, through automated reporting to the
Revenue Department, at no cost to the state

Sports tourism, supporting the government's own Amazing Thailand Grand Tourism
and Sports Year campaigns and the National Physical Activity Strategy 2018–2030

Skilled Thai technology employment, and the training that goes with it

Participation data the state has never had — which sports are growing, where,
and among whom
```

---

## 22 · Close

A quiet, confident close. The sport icon field at very low opacity behind. One line, large, with **playing** carrying the Green Gradient:

```
Get Thailand playing.
```
Beneath, small:
```
Education AI Group Co., Ltd.
Registration 0845568020186 · Bo Phut, Ko Samui, Surat Thani
info@educationai.group
```
No thank-you slide, no logo wall.

---

## Optional — if a supporting figure is wanted on the opportunity slides

Only these are approved, and only as stated:
```
2.5 million international tourists take part in sports activities in Thailand,
generating over €423 million

Over 60% of sports venues in Thailand have no online booking system

39 million+ international visitors annually
```
**No other traction figure may appear.** See `04-FACTS.md`.
