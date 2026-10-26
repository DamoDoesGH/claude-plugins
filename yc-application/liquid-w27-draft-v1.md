# Liquid: YC W27 application, draft v1

Pre-review draft. Square brackets mark facts Damian must confirm or fill before submitting. Deadline: 2 November 2026, 8pm PT.

---

## FOUNDERS

### Who writes code, or does other technical work on your product? Was any of it done by a non-founder? Please explain.

I do, with Claude Code. Everything that exists today was built by me: the Liquid Note (the standard document), the cap-auction rulebook and the simulator that tested it, and the clickable prototype covering all five participants (seller, buyer, company, existing investor, our broker). No non-founder has written code. I am not a career engineer. I have founded and run four companies and in two of them the product was a data or financial system I specified and shipped with engineers I hired. The build that matters here is a regulated settlement and auction system, and for that I plan to hire seven engineers after the batch and bring on a broker-dealer operator who ran the function at Acorns.

### Are you looking for a cofounder?

Yes. [Confirm.] Ideally a technical cofounder who has built regulated financial infrastructure (brokerage, settlement, or exchange systems), or an operator who has run a broker-dealer. I would rather go through the batch alone than take the wrong person, but I know YC's view on solo founders and I agree with the reasoning.

### Founder video (1 minute). Suggested script.

I'm Damian. I co-founded DueDil, the private-company data layer in Europe, Founders Pledge, the standard document founders sign at formation that has had $13.6bn pledged through it, and Rho, the business bank for startups. I've been illiquid through all of it. Liquid is a short standard document a company signs once at formation that says its shares may be sold, twice a year, in a sealed auction, on terms it never has to negotiate again. SAFEs standardized money in. Liquid standardizes equity out. Only about 200 companies out of a $9.4 trillion universe can trade today. Every marketplace that tried to fix this went after those 200 names. We're getting every company to sign one thing instead.

---

## COMPANY

### Company name

Liquid

### Describe what your company does in 50 characters or less.

The SAFE for selling private startup shares.

Alternatives (all under 50):
- Startup equity that can actually be sold
- One signature at formation makes startup stock sellable
- Standard consent and auctions for private shares

### Company URL, if any

[none yet / fill in]

### Please provide a link to the product, if any.

[Link to the clickable prototype. Upload the 11 October build (index.html + app.js) to a static host before submitting.]

### What is your company going to make? Please describe your product and what it does or will do.

Liquid is a standard document plus the market that runs on it.

The document is the Liquid Note. A company signs it once at formation, for free, inside its standard paperwork. It grants transfer consent in advance and pre-wires the right of first refusal and co-sale, so no sale ever needs a signature again. It obligates nothing: nobody has to sell, the company never has to open a window, and the company never sets a price. The right travels with the shares through option exercise, SAFE conversion, splits and recaps. There are no numbers, fees or methodology in it, because the SAFE's lesson is that a standard you can redline is not a standard.

The market is two sealed-bid auctions a year, on the same calendar for every company. A seller names the cash they want and the lowest valuation cap they will accept. A buyer names their cash and the highest cap they will pay. Each company's auction clears at the cap where the most cash changes hands. The seller gets cash in 72 hours. The share price is set later by the company's next funding round, up to that cap, so the company's existing investors never see a price they didn't set. Our agents read the books and we warrant the numbers: if the figures restate by more than 10% within 90 days, we pay the buyer. Every trade routes through a registered broker-dealer. Who sold is never disclosed; that is an enforceable term, not a setting.

Companies pay nothing. Sellers pay 2% on completed sales. Before any auction, founders get a free tool that tells them when employees want to sell, a $200 a month tier that warrants their numbers so candidates stop discounting the offer, and a $12,000 a year tier that books two dated auctions.

Secondaries are the wedge. A well-run fundraise is already an auction, so the same rails carry primary rounds next. Thousands of verified prints become the first trustworthy private-company price series, and that benchmark becomes an index anyone can buy.

### Where do you live now, and where would the company be based after YC?

[Confirm.] I live in London. The company will be incorporated in Delaware and based in San Francisco for the batch and after it.

### Explain your decision regarding location.

The customers are US venture-backed companies, the rails are US securities law (broker-dealer registration, 409A, tender-offer rules), and the buyers are US funds. Delaware incorporation is where the standard document has to live if it is going to sit inside formation paperwork. I have run companies in London for fifteen years and the people I need for this one (securities counsel, a broker-dealer operator, buyers) are in San Francisco and New York. [Adjust if you intend to keep a London base.]

---

## PROGRESS

### How far along are you?

Pre-launch. What exists today:

- The Liquid Note, eight terms in plain English, drafted and reviewed with a secondary-transactions partner at Goodwin. [Confirm the extent of Goodwin's involvement.]
- The cap-auction mechanism, specified as a rulebook (v7) and tested in a simulator. The chosen rule clears at 0.82 of true value against 0.77 for the best alternative.
- A clickable prototype of every participant's flow: the employee who sells, the buyer, the company, the existing investor with a board seat, and our broker. Built 11 October, with the first UX passes done.
- The free employee tool (a grant decoder) and the auction interface, built 15 October.
- A revenue model and a founder-facing price list.

What does not exist: a legal entity, a broker-dealer, a customer, or a signed note. The next ninety days are a validation plan with numbers attached: 20 founder conversations with the note in front of them (target 10 verbal yes, 5 in writing), the grant decoder seeded into three batch group chats (target 200 organic users), five meetings with startup-firm partners (target one firm engaged to co-draft), and 10 buyer calls about a concrete $4m hypothetical (target three credible "I would bid at this discount"). [Update with actual results before submitting; every number that has become a result should replace its target.]

### How long have each of you been working on this? How much of that has been full-time? Please explain.

Since [month] 2026, full-time since [month]. [Confirm.] The first design artifact is dated 28 August; the deck is on its 26th revision. I have no other operating role. I sit on the Web Summit board and hold board or advisory seats from previous companies, none of which take more than a few hours a month.

### What tech stack are you using, or planning to use, to build this product? Include AI models and AI coding tools you use.

Today: the prototype is plain HTML and JavaScript; the deck tooling and document pipelines are Python. I build with Claude Code and Claude Opus daily, and used a multi-model panel (seven models, six rounds) to attack the auction design before I trusted the simulator.

Planned: TypeScript services on Postgres, with the ledger of pledges, bids and settlements as an append-only event log so every clearing can be audited. The diligence agents that read a company's books before an auction will run on Claude via the API, with a human appraiser signing off on every warranted number. Broker-dealer, KYC and settlement go through a registered partner first and in-house second. [Confirm or replace with your actual plan.]

### Are people using your product?

No. The prototype has been walked through with [n] founders and [n] buyers; no one has transacted. [Fill in.]

### Do you have revenue?

No.

### If you are applying with the same idea as a previous batch, did anything change? If you applied with a different idea, why did you pivot and what did you learn from the last idea?

First application. [Confirm.]

### If you have already participated or committed to participate in an incubator, "accelerator" or "pre-accelerator" program, please tell us about it.

No. [Confirm.]

---

## IDEA

### Why did you pick this idea to work on? Do you have domain expertise in this area? How do you know people need what you're making?

I have spent my whole career on the three things this needs: private-company data, a document founders sign at formation, and startup financial infrastructure. DueDil built the private-company data layer in Europe and exited to nCino via FullCircl. Founders Pledge is one standard document signed at formation; 2,300 founders in 45 countries have pledged $13.6bn through it and $1.9bn has moved. Rho is a business bank for startups that underwrites startup risk at scale. And I have been illiquid through all of it: fifteen years of paper, and the one time I sold shares it was a bespoke stock transfer agreement negotiated by lawyers for a few hundred thousand dollars.

How I know people need it: 16,538 employees sold into tenders in 2025 out of roughly a million on Carta. Only 32% of vested, in-the-money grants get exercised, down from 54% three years earlier, because exercising costs cash and the tax lands the same year. Founders now give up to three times more equity to win a hire against a public RSU; Brett Adcock described losing an engineer he offered $15-20m of Series A stock to $36m of Meta RSUs, "kind of guaranteed cash". LPs tell their GPs they only believe in DPI now. Every one of those people wants the same thing and none of them can have it, because every sale needs a signature from someone who has no reason to give it.

The founder is the blocker, so I sell to the founder first, with a document that costs nothing to sign and makes their equity worth more the day they sign it. [Replace this paragraph with the real founder-conversation results when they exist: "n of 20 founders said yes, n in writing."]

### Who are your competitors? What do you understand about your business that they don't?

Forge, Hiive, Nasdaq Private Market, Carta (CartaX, now dead), and the ghosts of SecondMarket and SharesPost. Robinhood and the synthetic-exposure products are the newest version of the same mistake.

They all went after the same two hundred names, the part of the market that looked most valuable, instead of getting every company to sign one thing. Forge cleared $17bn in twelve years against a $9.4tn universe. Nasdaq Private Market does consent properly but by hand, which is why it only works above Series C at $150,000 to $400,000 an event. SecondMarket skipped consent and Facebook and Twitter shut it down. CartaX used the cap table it was trusted to administer and was dead in three years. Robinhood bypassed consent with synthetic exposure and companies pushed back.

Five locks stand between an employee's shares and cash: consent, information, matching, settlement and demand. Everyone attacked matching and settlement, the cheap two. Nobody has attacked information or standing demand, and consent is only cheap at one moment in a company's life: formation. Ask for it then and it costs nothing. Ask for it at a trade and you are negotiating with a board under pressure, which is why every prior market is discretionary and gets cut first in a downturn.

Two more things. A private company is not attractive one at a time; it is unbelievably attractive twenty at a time, because most investors want the asset class, not the company. Two auctions a year on one calendar is how you get a fund that would never come for one company to come for 800. And the good companies are not the adverse-selection risk everyone assumes: Apple, Nvidia, SpaceX, Tesla and OpenAI all had a year when they looked like the worst company on the list and were cheapest. The deals worth buying never traded because nothing was standardised.

### How do or will you make money? How much could you make?

Sellers pay 2% on completed auctions (1% above $10m). Companies pay nothing to sign. Founders can pay $200 a month to have their numbers warranted and $12,000 a year to book two dated auctions; the $12,000 is a deposit credited against the 2%, so a company that sells pays 2% and nothing else. Institutions pay for the data and the index.

Year one is fifteen auctions. The year-three model is $155m: 1,200 auctions clearing a median $4m produce $96m; 800 companies with a date booked but no cleared auction, $10m; 8,000 keeping their numbers warm, $19m; 400 institutions at $75,000 for data and index access, $30m. The median is $4m rather than $25m because that is what the companies formation paperwork reaches actually trade; Carta's median seed-to-Series-B tender is $8.5m.

The ceiling: venture-backed equity turns over 2% of its value a year, about $188bn. Houses manage 4.4%. Listed equities 68%. At housing's rate the market is $414bn a year; 2% of that is $8bn in fees before primary rounds or the index.

### If you had any other ideas you considered applying with, please list them.

[Fill in honestly, or state: None. This is the only thing I have worked on since leaving Rho.]

---

## EQUITY

### Have you formed ANY legal entity yet?

No. [Confirm. If you incorporate before submitting, give the Delaware C-corp details.]

### Have you taken any investment yet?

No.

### Are you currently fundraising?

No. After the batch I expect to raise around $3m to fund seven engineers for a year and the broker-dealer build. [Confirm.]

---

## CURIOUS

### What convinced you to apply to Y Combinator? Did someone encourage you to apply? Have you been to any YC events?

The SAFE. YC proved that one short, free, standard document inside batch paperwork can change how every startup in the world raises money, by being obviously better rather than by being mandatory. Liquid is the same bet on the other side of the cap table, and the fastest way to test whether founders will sign it is to put it in front of a few hundred of them at the one moment consent costs nothing. No other room has that. [Name anyone who encouraged you, e.g. Jeff Cruttenden, and any YC events attended.]

### How did you hear about Y Combinator?

[Fill in. E.g. "I've known YC since DueDil in 2011; several of my co-investors and portfolio founders are alumni, and I signed a YC SAFE as an investor this month."]

### What batch do you want to apply for?

Winter 2027.
