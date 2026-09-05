# Presenter's script — MySportia, slide by slide

> Written for Justin Cohen, first person, spoken English. **None of this text appears on any slide.**
> Each entry is 30–90 seconds. Deliver it like a story, not a report — the deck holds the numbers so
> the voice doesn't have to.
>
> The register throughout, from the company's own brand voice: **inevitable, not promotional.**
> You are not selling. You are describing something that obviously had to exist, built in the only
> order it could have been built in.
>
> *Delivery notes are in italics. Words in bold are the ones to lean on.*
>
> **This file is the canonical rehearsal text.** The script blocks on the published brief mirror it;
> edit here first.

---

## 1 · Cover

Good morning, and thank you for the time.

What I'm going to show you today is not an app, and it's not a booking website. It's
**infrastructure** — national infrastructure for sport and activity in Thailand.

My name is Justin Cohen. I'm the Chief Executive of Education AI Group, and MySportia is what we
build. I'll show you why it exists, what's already running today, and what we're building next.

*Pause. Advance.*

---

## 2 · Act I opener — The opportunity

Everything we've built follows from one problem. So let me start there — with two numbers.

---

## 3 · The problem

Over **seventy-five percent** of Thai adults are highly sedentary. Sitting more than seven hours a
day.

And **three out of four people** stop playing sport — entirely — after they leave education.

*Pause. Let the numbers sit.*

Three in four. And here's the part that matters: it is **not** because people stop wanting to play.
Nobody falls out of love with football at twenty-two. Nobody decides swimming isn't for them the day
they get a job.

They stop because **access breaks down**. That's the problem. And access is a problem you can
actually fix.

---

## 4 · Where it started

*The slide holds the story — don't re-read it. Make it personal:*

That slide is my own afternoon. It once took me **over two hours on the phone** to organise one game
of paintball. One game. A venue with no online booking, a group of friends to coordinate, no way to
see what was available.

And I can book a flight in ninety seconds. A hotel in ninety seconds.

Sport is one of the **last major categories of modern life with no unified way in**. Travel has one.
Transport has one. Sport doesn't. That gap is why three in four people stop playing — and it's the
exact moment this idea started.

---

## 5 · Why access is hard

So why is it so hard? Four reasons, and they compound.

The sector is **fragmented** — venues run on phone calls, LINE chats, paper diaries and spreadsheets.
There is no central place to find or book anything.

People have **no one to play with** — and having someone at your level is the single biggest
predictor of whether you keep going. Not motivation. Not equipment. A person.

The smaller sports are **invisible** — I'll show you that in a second.

And because so much of the sector runs on cash, the **state can't see it** — no participation data,
no sector picture, and tax that never gets collected.

---

## 6 · Every sport — including the ones nobody builds for

*Gesture at the wall. Give the room a moment to scan it.*

Look at this for a moment. Climbing. Diving. Archery. Muay Thai.

Every one of these is happening somewhere in Thailand **right now** — and almost none of it can be
found by the people who would play it. These sports are not unpopular. They are **invisible**.

And here's what infrastructure changes: once the connective layer exists, adding one more sport
costs almost nothing. Which means for the first time, the small sports get **the same infrastructure
as the big ones**. No one builds dedicated software for the archery community. Infrastructure
carries them anyway, at no extra cost.

---

## 7 · What MySportia is

So here is what MySportia is, in one sentence.

*Read it from the slide, slowly. Do not paraphrase it. Mark the breaths and rehearse this line more
than any other: "National infrastructure / connecting people to the places where they can play —
(breath) — raising participation in sport and activity — including amateur and minority sports —
(breath) — by automating the business side / so venues can concentrate on delivering the service."*

**National infrastructure connecting people to the places where they can play — raising
participation in sport and activity, including amateur and minority sports, by automating the
business side so venues can concentrate on delivering the service.**

That's the whole company. Everything else I show you today is just this sentence, built.

---

## 8 · The architecture — two sides, one system

It has two sides, and they're one system.

The **venue side is the engine**. It runs the business — bookings, schedules, payments through
PromptPay and Thai QR and cards, automatic invoices and receipts and VAT, memberships, customer
records, staff. Everything a venue owner currently does by hand at eleven o'clock at night.

The **consumer side is the storefront**. Find any sport, by place, date or type. Book it and pay in
a few taps. Find someone at your level to play against. And the person gets **control** — their
bookings, their passes, their memberships, in one account in their pocket, instead of a paper card
behind a counter. In Thai and in English.

One system. The engine makes the storefront possible — and that's the next part of the story.

---

## 9 · Act II opener — The build

So how do you actually build this?

The honest answer is: **in the wrong order — deliberately.** Let me explain.

---

## 10 · The order this had to be built in

The obvious thing to build first is the marketplace. That's the exciting half. That's what everyone
wants to build.

**It could not be built.** We know, because that's where we started.

The venues were the bottleneck. Notebooks. Spreadsheets. Phone calls. LINE messages. No real-time
availability, no digital payments, no system. And you **cannot build a marketplace on top of
businesses that are not bookable**. There is nothing to connect to.

There's a precedent for this, and it's a good one. **Hotels first got booking systems. Only then did
a booking marketplace become possible.** The extranet came before Booking.com. Always does.

So we inverted the order, deliberately. **First fix the venues. Then build the thing people actually
use.** We spent our first year on the unglamorous half — and it's the only reason the rest of this
presentation is possible.

---

## 11 · The three phases

That gives you the three phases — and tells you exactly where we are.

**Phase one: fix the venues.** One system that runs the whole business and makes every venue
instantly bookable. **Built.**

**Phase two: the marketplace.** Aggregate those venues into one place where anyone can find and book
any sport, in Thai and English. **Built.**

**Phase three: the lifestyle layer.** Profiles and skill ratings. Matching you to an opponent at
your level. Leagues, tournaments, national rankings. Community. Native mobile apps. **That is this
project.**

Discovery. Booking. **Participation. Community. Progression.** The first two get someone to one
session. The last three decide whether they're **still playing in a year** — they're what turns the
three-in-four around.

---

## 12 · Built and running — live today

Now — everything on this slide is **live**. This is not a concept and these are not mockups.

*Point to the screens.*

This is the marketplace, live at mysportia.com — real venues on a real map. This is the booking flow
on a phone — pick a trainer, pick a time, pay. And this is the back office a venue manager sees
every morning.

It's running today at **thirty-two pilot venues in Thailand**, taking real bookings and real
payments, right now.

And underneath it sits real payment infrastructure: we operate as a **master merchant with Stripe
and with Omise**. That means a new venue is taking digital payments in hours, not weeks — the rails
are already built to scale.

Measured against the full product we've planned, this is roughly **fifteen percent** of it. The
venues are fixed. The plumbing works. Which is exactly what makes the next slide possible.

---

## 13 · What a venue gets

So what does a venue actually get? Four things.

**More revenue** — the marketplace brings customers they could never reach, and empty slots start to fill.

**Zero admin** — bookings, payments, reminders, invoices, VAT — it runs itself. Staff coach instead of doing paperwork.

**Their own brand** — their storefront, their customer relationships. We stay in the background.

And **the numbers to grow** — which classes fill, who comes back, what earns.

That's why venues join. And it's why they stay.

---

## 14 · What a player gets

And the player?

**Everything in one place** — any sport, any venue, live availability. **Booked and paid in seconds** — PromptPay, Thai QR, a card. **Control** — bookings, passes, memberships in one account in their pocket.

And with this project: **someone to play with** — matched to their level, with leagues and rankings to play for.

That's what turns one booking into a habit.

---

## 15 · To be developed — the eight functions

This is what we build next. Eight functions — and **none of them exists in the system today**.

*Lift the pace through the list; slow down only on the three bolded items.*

A player feed, so people discover what's near them. **Opponent matching** — sport, skill level,
location, availability — so a person without a group can still play. Leagues, tournaments and
national rankings, so there's something to play for. **Automated tax reporting** — the venue's
returns prepared from its own transaction records and submitted through the Revenue Department's
digital channels, so a venue enters the tax system without doing the paperwork. Venue hardware —
access gates, kiosks, point of sale, QR entry. Native mobile apps for players and venue operators.
AI-assisted onboarding, so a venue joins in hours, not weeks. And the **backend for national
scale** — thousands of venues, not thirty-two.

All of it built **in Thailand, by our Thai engineering team, in twelve months**.

---

## 16 · The 15 / 85 split

One picture, so the proportions are clear.

*Gesture at the bar. Then the line — slowly:*

The fifteen percent is what we've shown you — built, running, taking payments. The eighty-five
percent is this project.

**The first half is the plumbing. The second half is the product.**

---

## 17 · Why the two halves are one system

One more thing about how this grows, because it's the part people miss.

**Every venue that joins brings its members with it.** The gym signs on Monday — and by Tuesday its
whole membership is on the marketplace. And we spent nothing on consumer advertising to make that
happen. **Zero.**

That's why the consumer side reaches national scale **without national marketing spend**. The supply
side carries its own demand in with it. And it's why this is one system, not two products.

---

## 18 · One infrastructure. Many industries.

One more thing about the infrastructure, because it's worth seeing where this goes.

Nothing in the venue engine is sport-specific. Bookings, schedules, master-merchant payments, memberships, automatic accounting, tax reporting — **every service business in Thailand needs the same machine.**

MySportia is the live proof, in sport. And within the group, the same model is already built for other industries — **Kizzem** for venue and service booking generally, **PetFlow HQ** for pet care. More follow.

This application funds the sports platform. But the infrastructure it completes is **a model Thailand keeps** — built once, here.

---

## 19 · Technology

I won't take you deep into the technology today — the full stack is documented for anyone who wants
it, and our Chief Technology Officer will happily go as deep as you like.

What matters in this room is simpler: it's a modern cloud platform, it already runs in production,
it already handles real payments — and everything new gets **built in Thailand, in Bangkok, by the
Thai team we're hiring**.

---

## 20 · The twelve-month plan

The build runs twelve months, in four quarters.

Foundations first — the backend for scale and the core consumer experience. Then hardware
integration and the mobile applications through the middle of the year. Leagues, rankings and the
community layer complete it.

One team, one office in Bangkok, one deadline. At the end of it: **a system ready to operate at
national scale**.

---

## 21 · Customers and revenue

Who pays, and how. It's deliberately simple.

Our customers are **sports and activity venues in Thailand** — Muay Thai gyms, fitness centres,
padel and tennis courts, pools, multi-sport facilities. And on the other side, the players who book
them.

Venues pay a **tiered monthly software licence** — a fixed fee by venue size, from a thousand baht a
month for the smallest to ten thousand and up for the largest. Fixed means fixed: it does not move
with the venue's own revenue. A venue always knows exactly what the software costs.

There's also payment processing income when venues use our integrated payments — ordinary income,
fully disclosed, taxed normally. But the **licence is the business**.

---

## 22 · Act III opener — Thailand's return

Last act. Who's building this — and what Thailand gets back.

---

## 23 · The Thailand dividend

Let me spell out what this means for Thailand, because it's bigger than sport.

When a venue runs on MySportia, its **whole revenue runs through one system**. Every booking, every payment, recorded as it happens. Accounts produced automatically — invoices, receipts, VAT — without a bookkeeper.

And under this project, filing itself: returns prepared from the venue's own records, **submitted through the Revenue Department's digital channels.**

Today most of this sector is cash. Revenue goes unrecorded, tax goes uncollected. A connected venue is a **visible** venue — and we don't just make them visible, we make them **bigger**: new customers from the marketplace, automated operations, more revenue to declare.

**A bigger, cleaner tax base — at no cost to the state.**

---

## 24 · The team

Education AI Group has **no employees today** — and that's deliberate. Every role you see here is a
job we create after approval. This project doesn't shift existing jobs around; it creates new ones.

I lead the company. My background is twenty years of building technology, product and consumer
businesses — including taking hardware from design through manufacture.

**Dmytro Bodlev** is our Chief Technology Officer. He architected the platform you saw running —
and after approval, he builds and leads the Thai engineering team in Bangkok. Everything running
today was built by the founding team; the roles on this slide are the new employment that takes a
working pilot to national infrastructure.

Around us: a Chief Operating Officer, a Project Manager, and a Head of Sales — and the Thai
engineering team itself: **four engineers in year one, eight in year two, twelve in year three.**
Project management, systems analysis, development, design, testing. All new hires. All in Bangkok.

---

## 25 · Investment, employment and what Thailand gets

The commitment: **five — point six five — million baht** of investment. Thai IT salaries of **just
over two million baht in year one** — the requirement is one and a half; the exact figure is on the
slide. Twelve months to
completion. Two sites — Ko Samui and Bangkok.

And the return — because this is the reason the project deserves promotion:

**Participation goes up**, against that seventy-five percent sedentary rate. **The small sports
become visible** — carried by the infrastructure at no extra cost. **The tax dividend** — you've
just seen how that works. It supports
the government's own sports tourism campaigns and the National Physical Activity Strategy. It
creates **skilled Thai technology employment**. And it produces something Thailand has never had:
**real participation data** — which sports are growing, where, and among whom.

---

## 26 · Close

Three in four people stop playing. Not because they want to — because nothing connects them to the
places where they could.

We've spent a year building the half nobody sees. Now we build the half everyone will use.

*Pause.*

**Get Thailand playing.**

Thank you. I'm happy to take questions — and if you'd like, the live system is a phone away.

---

## If they only remember three things

1. **Three in four stop playing — from lack of access, not interest.** Access is fixable.
2. **First fix the venues, then build what people use.** The 15% is the plumbing, running live at 32
   venues; the 85% is the product, built in Thailand in twelve months.
3. **Thailand gets participation, visibility for small sports, tax transparency, data and skilled
   jobs** — infrastructure the state never had to build.

## Questions to expect, and the one-line anchors

| Likely question | Anchor |
|---|---|
| "Is this just a booking app?" | No — booking is phase two, and it's done. This project is participation: matching, leagues, rankings, community. The half that changes behaviour |
| "What exists today?" | Roughly 15% of the planned system, live at 32 pilot venues, taking real bookings and payments. Happy to show it now |
| "Who builds it?" | Our Thai engineering team in Bangkok — four, then eight, then twelve. All new employment created after approval |
| "How do you make money?" | A fixed monthly software licence by venue size. It never moves with the venue's revenue |
| "Why will venues join?" | Because the system runs their whole business — and every venue that joins brings its members in with it |
| "What does the state get?" | Automated reporting to the Revenue Department, participation data, and a sector moving from cash to digital — at no cost to the state |
| "Whose figures are the 75% and the 3 in 4?" | Independent published research, not ours — the citations travel with the application pack |
| "Who built what exists today?" | The founding team. The roles on the team slide are the new employment that takes a working pilot to national infrastructure |
