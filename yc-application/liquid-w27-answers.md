# Liquid: YC Winter 2027 application answers (v2, post partner review)

Deadline: 2 November 2026, 8pm PT. Decisions by 11 December.

This is the submit-ready draft after six partner-persona reviews (see `partner-review.md`). Square brackets are the only facts left to fill; the checklist at the end lists every one. Nothing in brackets should survive to the form.

---

## FOUNDERS

### Who writes code, or does other technical work on your product? Was any of it done by a non-founder? Please explain.

I do, with Claude Code. Everything that exists was built by me: the Liquid Note, the cap-auction rulebook and the simulator that tested it, the free grant decoder, and a clickable prototype of all five participant flows (the employee who sells, the buyer, the company, the existing investor, our broker). No non-founder has written code.

I am not an engineer. At DueDil and Rho I specified the product and shipped it with engineers I hired. The production system here is a regulated settlement and auction platform and I will not build that alone; see the cofounder answer. During the batch, settlement runs on a registered broker-dealer partner's licence so the first auction can clear without us building regulated infrastructure in-house.

### Are you looking for a cofounder?

Yes. I need one of two people: an engineer who has built brokerage, settlement or exchange systems, or an operator who has run a broker-dealer. [Name], who ran the broker-dealer function at Acorns, is [committed to join as cofounder / in conversation about joining as cofounder]. I am also talking to [n] engineers I have worked with before, including [name]. I will not take someone I have not worked with to tick the box.

### Founder video (1 minute). Script.

I'm Damian. I co-founded DueDil, the private-company data layer in Europe; Founders Pledge, the standard document founders sign at formation, which has had $13.6 billion pledged through it; and Rho, the business bank for startups. I've been illiquid through all of it.

Liquid is a short standard document a company signs once at formation. It says its shares may be sold, twice a year, in a sealed auction, on terms nobody has to negotiate again. SAFEs standardized money in. Liquid standardizes equity out.

Only about 200 companies out of a $9.4 trillion universe can trade today. Every marketplace that tried to fix this went after those 200 names. We're getting every company to sign one thing instead. [n] founders have signed so far.

---

## COMPANY

### Company name

Liquid

### Describe what your company does in 50 characters or less.

The SAFE for selling private startup shares.

(43 characters. Alternatives: "Startup equity that can actually be sold"; "Standard consent and auctions for private shares".)

### Company URL, if any

[fill in, or leave blank]

### Please provide a link to the product, if any.

[Live URL of the 11 October prototype. Host index.html and app.js on a static site before submitting.]

### What is your company going to make? Please describe your product and what it does or will do.

Liquid is a standard document plus the market that runs on it.

The document is the Liquid Note. A company signs it once at formation, for free. It grants transfer consent in advance and pre-wires the right of first refusal and co-sale for everyone who signs it. It obligates nothing: nobody has to sell, the company never has to open a window, and the company never names a price. The right travels with the shares through option exercise, SAFE conversion, splits and recaps. There are no numbers, fees or methodology in it, because the SAFE's lesson is that a standard you can redline is not a standard. The honest limit: it binds the company and the people who sign it. A Series A lead who never signed it can rewrite transfer restrictions in the investor rights agreement, and getting leads to carry the note forward is the hard part of the business.

The market is two sealed-bid auctions a year, on the same calendar for every company. A seller names the cash they want and the lowest valuation cap they will accept. A buyer names their cash and the highest cap they will pay. Each company's auction clears at the cap where the most cash changes hands. The seller gets cash in 72 hours. The buyer's share count is set by the company's next funding round, up to the cap they bid, so the auction publishes a ceiling, not a price, and the company's investors still price the round. We coordinate with the company's 409A appraiser rather than pretend they will not look at the cap. If there is no round within two years, the shares transfer at the auction cap. The buyer holds the risk in between; if the company dies first, the pledged shares are worthless and the seller keeps the cash, and the bid screen says so.

Before any auction, our agents read the company's books and a licensed appraiser signs the numbers buyers bid on. If those numbers restate by more than 10% within 90 days, we refund the buyer up to [cap: the fee paid / the 2%]. Every trade routes through a registered broker-dealer. Who sold is never disclosed; that is an enforceable term, not a setting.

Companies pay nothing. Sellers pay 2% on completed sales. Founders get a free tool that tells them when employees want to sell, a $200 a month tier that warrants their numbers so candidates stop discounting the offer, and a $12,000 a year tier that books two dated auctions.

Secondaries are the wedge. A well-run fundraise is already an auction, so the same rails carry primary rounds next. Enough cleared caps across enough companies becomes the first systematic data on what early-stage private equity actually clears at, which 409A providers, fund auditors and LPs currently guess.

### Where do you live now, and where would the company be based after YC?

[Pick one and delete the other.]

Option A: I live in London. The company will be a Delaware C-corp based in San Francisco. I am moving for the batch and staying.

Option B: I live in London. The company will be a Delaware C-corp. I will be in San Francisco for the batch and split time between San Francisco and London after it, with the broker-dealer and engineering team in the US.

### Explain your decision regarding location.

The customers are US venture-backed companies, the rails are US securities law (broker-dealer registration, tender-offer rules, 409A), and the buyers are US funds. The document has to be a Delaware document if it is going to sit inside formation paperwork. The people I need next, securities counsel, a broker-dealer operator and the first buyers, are in San Francisco and New York. [If Option B: My family is in London and I will keep a base there; the company's centre of gravity is the US from day one.]

---

## PROGRESS

### How far along are you?

Pre-launch. No entity, no revenue, no cleared trade.

People: since [date] I have put the Liquid Note in front of [n] founders. [n] said they would sign, [n] in writing. The most common objection was [objection], and the founder I learned most from said: "[quote]." I have talked to [n] buyers about a specific $4m auction on [date]; [n] said they would bid at [x]% below the last round. [n] employees at [n] companies have used the grant decoder. I have met [n] partners at startup law firms; [one firm / name] has agreed to co-draft.

Built: the Liquid Note (eight terms in plain English, reviewed with [name], a secondary-transactions partner at Goodwin); the cap-auction rulebook (v7) and a simulator in which the chosen rule clears at 0.82 of modelled true value against 0.77 for the best alternative; a clickable prototype of all five participant flows; the free grant decoder and the auction interface.

By demo day: 20 signed notes and one cleared auction with third-party bidders, settled on a partner broker-dealer.

### How long have each of you been working on this? How much of that has been full-time? Please explain.

Since [month] 2026, full-time since [month]. The first design artifact is dated 28 August. I have no other operating role. I sit on the board of Web Summit and hold board or advisory seats from previous companies, none of which take more than a few hours a month.

### What tech stack are you using, or planning to use, to build this product? Include AI models and AI coding tools you use.

Today: the prototype is plain HTML and JavaScript; the document and deck pipelines are Python. I build with Claude Code and Claude Opus daily, and ran the auction design through a seven-model panel over six rounds before trusting the simulator.

Planned: TypeScript services on Postgres, with every pledge, bid and settlement in an append-only event log so each clearing can be audited. KYC/AML through [vendor]; settlement cash through [bank or escrow partner]; cap-table reads through [Carta/Pulley API, or manual at first]. The diligence agents that read a company's books before an auction run on Claude via the API, with a licensed appraiser signing every warranted number. Broker-dealer and any ATS filing through a registered partner for the first [n] auctions; our own registration when volume justifies it.

### Are people using your product?

Not yet transacting. [n] founders have read and commented on the Note. [n] employees at [n] companies have used the grant decoder. The first signed notes are [names, or "expected by date"].

### Do you have revenue?

No.

### If you are applying with the same idea as a previous batch, did anything change? If you applied with a different idea, why did you pivot and what did you learn from the last idea?

First application. [Confirm.]

### If you have already participated or committed to participate in an incubator, "accelerator" or "pre-accelerator" program, please tell us about it.

No. [Confirm.]

---

## IDEA

### Why did you pick this idea to work on? Do you have domain expertise in this area? How do you know people need what you're making?

I have already got founders to sign a standard document at formation. Founders Pledge is one page; 2,300 founders in 45 countries have pledged $13.6bn through it and $1.9bn has moved. I know what makes a founder sign something optional at the moment they are thinking about everything else. DueDil built Europe's private-company data layer (exited via FullCircl to nCino), so I know what standing behind a private company's numbers takes. Rho is a business bank for startups, so I know the regulated rails. And I have been illiquid for fifteen years; the one time I sold, it was a bespoke stock transfer agreement that took lawyers [weeks] and cost [amount].

The problem is not in doubt. 16,538 employees sold into tenders in 2025 out of roughly a million on Carta. Only 32% of vested, in-the-money grants get exercised, down from 54% three years earlier, because exercising costs cash and the tax lands the same year. Brett Adcock described offering a senior engineer $15-20m of Series A stock and losing him to $36m of Meta RSUs, "kind of guaranteed cash". Private equity loses to public equity on liquidity, not size. LPs tell their GPs they only believe in DPI now.

What was in doubt is whether founders will sign. I have asked [n]. [n] said yes, [n] in writing. The one I learned most from said: "[quote]." The founder is the blocker, so I sell to the founder first, with a document that costs nothing to sign and makes their equity worth more the day they sign it.

### Who are your competitors? What do you understand about your business that they don't?

Forge, Hiive, Nasdaq Private Market, Carta (CartaX, now dead), and the ghosts of SecondMarket and SharesPost. Robinhood and the synthetic-exposure products are the newest version of the same mistake.

They all went after the same two hundred names, the part of the market that looked most valuable, instead of getting every company to sign one thing. Forge cleared $17bn in twelve years against a $9.4tn universe. Nasdaq Private Market does consent properly but by hand, which is why it only works above Series C at $150,000 to $400,000 an event. SecondMarket skipped consent and Facebook and Twitter shut it down. CartaX used the cap table it was trusted to administer and was dead in three years. Robinhood bypassed consent with synthetic exposure and companies pushed back.

Five locks stand between an employee's shares and cash: consent, information, matching, settlement and demand. Everyone attacked matching and settlement, the cheap two. Nobody has attacked information or standing demand, and consent is only cheap at one moment in a company's life: formation. Ask for it then and it costs nothing. Ask for it at a trade and you are negotiating with a board under pressure, which is why every prior market is discretionary and gets cut first in a downturn. The honest limit: the note binds the company and its option plan, and a Series A lead who never signed it can rewrite transfer restrictions. We start opt-in, publish the sign-through rate, and [status: are asking leads / have one lead on record] whether they would carry it forward.

Two more things. Buyers will not underwrite seed-to-Series-B companies one at a time for $4m. The same calendar for every company lets a buyer bid one formula across a whole batch, which is the only way a fund comes for 800 companies; [n] buyers have told us they would, at [x]% below the last round. And the adverse-selection worry, that only employees who know something sell, is handled structurally rather than wished away: each seller may sell at most 10-20% of vested holdings per window, every company's window is on the same date, who sold is never disclosed, and buyers price off numbers we have verified. Sellers who know something still have an edge; the auction prices it. In the simulator the chosen rule clears at 0.82 of modelled true value, roughly the 25-35% discount restricted-stock studies already find for unverifiable claims.

### How do or will you make money? How much could you make?

Sellers pay 2% of cash cleared (1% above $10m). A median $4m auction is $80,000 to us. Year one is fifteen auctions, about $1.2m. Companies pay nothing to sign. The $200 a month and $12,000 a year tiers are for warranted numbers and dated auctions; the $12,000 is a deposit credited against the 2%, so a company that sells pays 2% and nothing else. 409A providers, fund auditors and LPs pay for the clearing data.

Year three, if it works: 1,200 cleared auctions at a $4m median is $96m of fees on $4.8bn of volume. For scale, Forge cleared $17bn in twelve years, so this is three times Forge's run rate in a segment that has never traded; we get there only if a handful of funds commit to bid a formula across every company on the calendar. Add 800 companies with a booked date that did not clear ($10m), 8,000 keeping their numbers warm ($19m), and clearing data at [$3-5m], and the model is about [$130m].

The ceiling: venture-backed equity turns over 2% of its value a year, about $188bn. Houses manage 4.4%. Listed equities 68%. At housing's rate the market is $414bn a year.

### If you had any other ideas you considered applying with, please list them.

[Fill in honestly, or: None. This is the only thing I have worked on since leaving Rho.]

---

## EQUITY

### Have you formed ANY legal entity yet?

[No. / Yes: Liquid [Inc.], Delaware C-corp, incorporated [date]. Incorporate before submitting if you can; it removes one of the "nothing exists" lines.]

### Have you taken any investment yet?

No.

### Are you currently fundraising?

No. I expect to raise after the batch, once the first auction has cleared.

---

## CURIOUS

### What convinced you to apply to Y Combinator? Did someone encourage you to apply? Have you been to any YC events?

The SAFE. One short, free, standard document changed how every startup raises money by being obviously better, not by being mandatory. Liquid is the same bet on the other side of the cap table. I know YC cannot put an outside document in batch paperwork and I am not asking for that. I will get the first 20 notes signed through my own network whether or not that ever happens; the batch is the fastest place to put the note in front of founders at the one moment consent costs nothing, and to find out why they say no. [Jeff Cruttenden (Acorns) encouraged me to apply after I showed him the note in October.] [YC events attended, or "None."]

### How did you hear about Y Combinator?

[Fill in. E.g. "I've known YC since DueDil in 2011. Several of my co-investors and portfolio founders are alumni, and I signed a YC SAFE as an investor this month."]

### What batch do you want to apply for?

Winter 2027.

---

## Before you submit: every bracket, in order of how much it moves the application

1. **Founder conversations.** The number of founders who have seen the note, said yes, said yes in writing, said no, and the most common objection plus one quote. Every reviewer put this first. Twenty conversations is a fortnight for your network; thirty emails this week with the note attached is the single highest-leverage thing you can do before 2 November.
2. **The cofounder answer.** Name the Acorns operator and their status (cofounder, committed, or in conversation). "Yes [confirm]" reads as undecided.
3. **Buyer calls.** Run them as "these companies are auctioning on [date], would you commit [amount] at [discount]", not as hypotheticals. Three on record changes the demand answer.
4. **Grant decoder usage.** One company where ten employees used it, and what the founder said when told. One data point beats three group chats.
5. **Goodwin's involvement.** Name the partner and what they reviewed; do not overclaim.
6. **Warranty cap.** Decide the formula (fee paid, the 2%, or a fixed amount) and whether an R&W insurer or a reserve stands behind it.
7. **Location.** Option A or B, and delete the other.
8. **Tech stack vendors.** KYC, escrow, cap-table source, broker-dealer partner.
9. **Incorporate** in Delaware if you can before submitting.
10. **Prototype URL**, YC events, how you heard, other ideas, full-time start date, legal fees and weeks on your own secondary sale.

## Claims cut from v1 and why

- "No sale ever needs a signature again" and "existing investors never see a price they didn't set": both contradicted by your own notes (Series A survivability; the cap is visible and 409A will use it). Four of six reviewers caught them.
- "Up to three times more equity": your speaker notes say closer to 2x on the raw Adcock numbers. Replaced with the numbers themselves.
- Apple/Nvidia/SpaceX/Tesla/OpenAI as the adverse-selection answer: survivorship, and every buyer will say so. Replaced with the structural answer (caps, calendar, confidentiality, warranted numbers).
- Index and ETF: an ETF cannot hold this under 40 Act liquidity limits, Destiny Tech100 is the cautionary tale, and it signals year eight when YC wants auction one. Kept as "clearing data" only.
- "$155m year three" with $30m from 400 institutions at $75k: PitchBook-tier revenue on year-three coverage. Model now shows its volume assumption against Forge's lifetime and the data line is cut to $3-5m.
- "Seven engineers after the batch": a hiring plan standing in for a founding team. Replaced by the broker-dealer partner for the batch and the cofounder search.
- "No other room has that": reads as asking YC to be the channel. Replaced with the explicit "I am not asking for batch paperwork."
