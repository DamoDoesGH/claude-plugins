# Liquid: YC Winter 2027 application answers (v3)

Deadline 2 November 2026, 8pm PT. Brackets are facts to fill; nothing in brackets goes on the form.

Calibration used for v3: accepted applications average about 110 words for "what will you make", 70 for "how far along", 160 for "why this idea" (shizune.co archive of 30 accepted applications). Reddit r/ycombinator and r/startups: under 120 words, ideally a sentence, no buzzwords, no exaggeration. YC's own guide: the point in the first sentence, matter-of-fact, "like X but for Y", name the obstacle and your theory for it. Structure throughout: problem, then solution, then the one number that proves it.

---

## FOUNDERS

**Who writes code, or does other technical work on your product? Was any of it done by a non-founder?**

Me, with Claude Code. I built the Liquid Note, the auction rulebook and simulator, the grant decoder, and a clickable prototype of all five participant flows. No non-founder has written code. I am not an engineer; at DueDil and Rho I specified the product and shipped it with engineers I hired. The first auction clears on a partner broker-dealer's rails, so the batch does not depend on building regulated infrastructure.

**Are you looking for a cofounder?**

Yes: an engineer who has built brokerage or settlement systems, or an operator who has run a broker-dealer. [Name], who ran the broker-dealer function at Acorns, is [committed / in conversation]. I will not take someone I have not worked with to tick the box.

**Founder video (1 minute)**

I'm Damian. I co-founded DueDil, Europe's private-company data layer; Founders Pledge, the document founders sign at formation that has $13.6bn pledged through it; and Rho, the business bank for startups. I've been illiquid through all of it.

Only about 200 companies trade in a $9.4 trillion market, because every sale needs a signature from someone with no reason to give it. Everyone who tried to fix this went after those 200 names.

Liquid is one short document a company signs at formation that says its shares may be sold, twice a year, in a sealed auction. SAFEs standardized money in. Liquid standardizes equity out. [n] founders have signed.

---

## COMPANY

**Company name**

Liquid

**Describe what your company does in 50 characters or less.**

The SAFE for selling private startup shares.

**Company URL, if any**

[URL or blank]

**Please provide a link to the product, if any.**

[Prototype URL]

**What is your company going to make? Please describe your product and what it does or will do.**

Only about 200 companies trade in a $9.4tn market, because every sale needs the company's consent and every marketplace asked for it one trade at a time.

Liquid is a standard document plus the market that runs on it. The Liquid Note is signed once at formation, free, and grants transfer consent in advance. Nobody has to sell; the company never sets a price. It is the SAFE for money going out.

Twice a year, every signed company auctions on the same day. Sellers name the cash they want and the lowest valuation cap they'll take; buyers the reverse. Cash in 72 hours; the next round sets the share price, up to the cap. We warrant the numbers, a registered broker-dealer settles. Companies pay nothing. Sellers pay 2%.

**Where do you live now, and where would the company be based after YC?**

London / San Francisco. [Confirm.]

**Explain your decision regarding location.**

The companies, the securities law and the buyers are American. The note has to be a Delaware document to sit inside formation paperwork. [One line on family or London base if you are keeping one.]

---

## PROGRESS

**How far along are you?**

Pre-launch, no entity. [n] founders have seen the note; [n] said yes, [n] in writing; the main objection was [objection]. [n] buyers said they would bid on a $4m auction at [x]% below the last round. [n] employees at [n] companies have used the grant decoder.

Built: the Note (eight terms, reviewed with [name] at Goodwin), the cap-auction rulebook and simulator (clears at 0.82 of true value vs 0.77 for the best alternative), a prototype of all five participant flows, the grant decoder. Target for demo day: 20 signed notes, one cleared auction.

**How long have each of you been working on this? How much of that has been full-time?**

Since [month] 2026, full-time since [month]. No other operating role; board seats take a few hours a month.

**What tech stack are you using, or planning to use? Include AI models and AI coding tools you use.**

Now: HTML/JS prototype, Python pipelines, built with Claude Code and Claude Opus; auction design stress-tested by a seven-model panel before the simulator. Planned: TypeScript on Postgres with an append-only ledger of pledges, bids and settlements; KYC via [vendor]; escrow via [partner]; diligence agents on Claude with a licensed appraiser signing every warranted number; broker-dealer and ATS via a registered partner until volume justifies our own.

**Are people using your product?**

Not yet transacting. [n] founders have read the note; [n] employees have used the grant decoder.

**Do you have revenue?**

No.

**If you are applying with the same idea as a previous batch, did anything change?**

First application.

**Prior incubator or accelerator?**

No.

---

## IDEA

**Why did you pick this idea to work on? Do you have domain expertise? How do you know people need what you're making?**

I have already got founders to sign a standard document at formation: Founders Pledge, one page, 2,300 founders, $13.6bn pledged. DueDil built Europe's private-company data layer (exited to nCino). Rho is the business bank for startups. Fifteen years illiquid myself; my one sale cost [amount] in legal fees.

Illiquidity hurts everyone. Founders overpay in equity to beat liquid RSUs: Brett Adcock offered an engineer $15-20m of Series A stock and lost him to $36m at Meta, "kind of guaranteed cash". Employees hold lottery tickets: 16,538 sold into tenders in 2025 out of a million on Carta. LPs only believe in DPI now.

Founders are the blocker, so I sell to founders first. [n] of [n] asked have said yes.

**Who are your competitors? What do you understand about your business that they don't?**

Forge, Hiive, Nasdaq Private Market, Carta, and the ghosts of SecondMarket and SharesPost.

They all went after the same two hundred names instead of getting every company to sign one thing. SecondMarket skipped consent; Facebook shut it down. Forge solved matching, not consent: $17bn in twelve years against $9.4tn. Carta was administrator and broker at once; dead in three years. Nasdaq does consent by hand at $150-400k an event, so only above Series C.

Five locks: consent, information, matching, settlement, demand. Everyone attacked the cheap two. Consent is only cheap at formation. Demand follows supply: a fund that would never come for one company comes for 800 on one day.

Honest limit: a Series A lead who never signed can rewrite transfer restrictions. We start opt-in and publish the sign-through rate.

**How do or will you make money? How much could you make?**

Sellers pay 2% of cash cleared; a median $4m auction is $80k. Companies pay nothing to sign; $200/month warrants their numbers, $12k/year books two auctions and is credited against the 2%. Year one: 15 auctions, about $1.2m. Year three: 1,200 auctions, $96m, plus about $30m from booked dates, warm numbers and clearing data. Venture-backed equity turns over 2% a year ($188bn); houses 4.4%; at housing's rate the market is $414bn.

**Other ideas you considered applying with?**

[None / list.]

---

## EQUITY

**Have you formed any legal entity yet?**

[No. / Liquid Inc., Delaware, incorporated [date].]

**Have you taken any investment yet?**

No.

**Are you currently fundraising?**

No. After the batch, once the first auction has cleared.

---

## CURIOUS

**What convinced you to apply to Y Combinator? Did someone encourage you? Have you been to any YC events?**

The SAFE: one free standard document became the default by being obviously better, not mandatory. Liquid is the same bet on the other side of the cap table. I'm not asking for batch paperwork; I'll get the first 20 signatures myself. The batch is where founders are at formation, and the fastest place to learn why they say no. [Jeff Cruttenden (Acorns) encouraged me.] [Events, or none.]

**How did you hear about Y Combinator?**

[E.g. Known it since DueDil in 2011; signed a YC SAFE as an investor this month.]

**Batch**

Winter 2027.

---

## Fill before submitting, in order of impact

1. Founder conversations: asked / yes / yes in writing / main objection. Thirty emails with the note attached this week.
2. Cofounder: name the Acorns operator and their status.
3. Buyer calls on a dated first auction, not a hypothetical.
4. Grant decoder: one company, how many employees, what the founder said.
5. Goodwin partner's name; warranty cap; location; vendors; incorporate if you can; prototype URL; legal fees on your own sale.
