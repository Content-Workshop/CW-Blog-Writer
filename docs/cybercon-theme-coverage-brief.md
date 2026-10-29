# CyberCon Theme Coverage: Second-Brand Brief

**Purpose:** Run the CyberCon content-gap analysis for a second brand. The event, the sessions and the six problems are already settled (included below). The new work is checking **this brand's** blog against those problems and proposing the few posts that would close its real gaps.

**Origin:** Built and refined on the Content Workshop run (October 2026). The lessons from that run are written into the rules below, so a new chat doesn't need to repeat the false starts.

---

## How to use this

Paste this whole file into a new chat, then fill in the **Inputs** section. The assistant should run the process end to end without asking questions that the inputs already answer.

---

## Inputs (fill these in)

| Input | Value |
|---|---|
| Brand | `[e.g., Chatter]` |
| Blog listing URL | `[e.g., https://example.com/blog/]` |
| Services / studios / offerings page(s) | `[URL(s)]` |
| Editorial docs for this brand (voice, style rules), if any | `[paths or "none"]` |
| Who the output is for | `[e.g., David]` |
| Recency cutoff for counting a post as coverage | `[default: published 2025 or later]` |
| Max new posts | `[default: 3, plus 1 optional]` |

If the brand's audience or offerings aren't clear from the offerings page, say so plainly and state the assumption you're working from. Don't invent services.

---

## The goal (read this first)

**Theme-level coverage, not one-to-one coverage.** We want a clear point of view on each major problem attendees will be talking about. We do **not** need a post for every session, and we do **not** want a session-by-session coverage map in the deliverable.

**Don't plan updates to old posts.** Recommend an update only if it's really important *and* the post is newer than the recency cutoff. The default is no updates.

---

## Process

### Step 1: Inventory the blog
- Crawl **every** page of the blog listing, following the pagination to the last page. Record each post's title, URL, publish date and headings.
- Expect rate limiting (HTTP 429). Fetch pages one at a time with a short delay, retry anything that comes back as an error page, and check that every page returned real content.
- Read the offerings / studios pages so ideas can be tied to real services.
- Download the post bodies and run a full-text keyword search per theme. Read the most relevant posts in full, and say how many you actually read.

### Step 2: Use the six CyberCon problems
- Start from the six problems in **The event** section below. They're brand-neutral; only the verdicts change per brand.
- Keep the problem names as written, so the two brands' pages can be compared side by side.
- If this brand's offerings make a cluster of sessions matter that the six problems only touch in passing (for example, creators and community), you may split it out as a seventh problem. Say why in one line.
- The full session list is in the appendix if you need to check where a session belongs.

### Step 3: Give each problem a verdict
Use only posts newer than the recency cutoff as evidence of coverage.

| Verdict | Meaning |
|---|---|
| **Covered** | We already have a recent post with a clear point of view on this problem. Action: none, or promote the existing post around the event. |
| **Partly covered** | We address part of the problem, but the part people will be asking about is missing. Action: one new post. |
| **Not ours** | Outside the brand's audience or offerings. Action: none. Say why in one line. |

### Step 4: Propose new posts (only for Partly covered problems)
- **At most one post per Partly covered problem**, up to the max in Inputs. If a second idea serves the same problem, mark it **Optional**.
- For each post include:
  - **Working title** (run a shortening pass; no "it's not X, it's Y" construction in titles)
  - **Claim**: one sentence, stated as something a reader could disagree with
  - **Why now**: which sessions raise it and why the event timing matters
  - **Supports**: which studio or offering, named as it appears on the brand's site
  - **For**: the specific reader
  - **Outline**: 4–5 bullets
  - **Risk**: what a skeptical reader or the stakeholder would push back on
- Prefer ideas where the brand has firsthand material (its own process, data or client work) over ideas anyone could write.

---

## Deliverable

A single shareable page (HTML artifact), structured like this:

1. **Header**: a one-sentence answer ("The event comes down to N problems. We cover X, Y isn't ours, Z need a new post."), plus small status chips.
2. **One card per problem**, in this order:
   - What attendees will be asking (2–3 sentences)
   - Example sessions that raise it (4–6, not the full list)
   - What we already have (recent posts only, linked, with dates)
   - A one-line verdict
   - **The new post details nested inside the card** for Partly covered problems. Otherwise, a one-line action.
3. **Method footer**: what was crawled, how many posts, the recency cutoff, and how many posts were read in full.

Do **not** include a session-by-session map, a status filter, or an updates table unless one is asked for. Keep the session-level reasoning in the chat in case someone asks why a problem got its verdict.

In the chat reply, give a short summary table of problems → verdict → action, and the link.

---

## Writing rules for the page and post ideas
- Be direct and specific. No filler, hype or banned clichés ("game-changer," "move the needle," "leverage," "harness the power of").
- Use at most one "it's not X, it's Y" construction across the whole page, and none in titles or headings.
- Use em dashes sparingly, set closed (`word—word`).
- Verify every post title, URL and date against the crawl. Verify offering names against the brand's site.
- Say what you know and what you inferred. If coverage depth was judged from headings and keywords rather than a full read, say so.
- If the brand has its own editorial docs, load them first. They override these rules where they conflict.

---

## The event: CyberCon (cybersecurity marketing conference)

87 sessions across workshops, the main program, the CyberCMO Summit and the CEO Summit. AI runs through four of the six problems.

| # | Problem | What attendees will be asking | Example sessions |
|---|---|---|---|
| 1 | Everyone sounds the same | How to stand out when AI pushes every vendor toward the same message and every booth says "AI-powered." | Resist Comfort (keynote) · Where AI Belongs in Your Positioning · Signal vs. Noise · The Death of Feature Marketing · Kill the AI Tells · Everything Is Important and Nothing Stands Out |
| 2 | Making AI part of how the team works | How to encode brand standards into AI, keep them current, and restructure the team around it. | Claude Beginner and Intermediate Workshops · Living Messaging System (panel) · Product Marketing OS with Claude · Spokespeople GPTs · Hi, I'm Claudia! · The Human Side of Transformation |
| 3 | Getting found when buyers ask AI | How to show up in AI answers and measure it. | Do This, Not That: How to Win at AI Search (runs twice) · Orchestrating Outcomes · We Spent $100K Testing OpenAI Ads · When Visibility Isn't Enough |
| 4 | Buyers trust proof and peers more than vendors | How to earn credibility with research, customer proof, docs, community and creators. | Nobody Read Your Threat Report · The Cybersecurity Newsroom · Proof Over Positioning · UGC and Community Marketing · Brand vs Creator · Buyers Read the Docs · Make Them Laugh, Then Make Them Buy |
| 5 | Proving marketing drives revenue | How to show what events, swag and demand programs return under budget pressure. | When Creativity Meets Revenue · Beyond Events · Weaponizing Swag · Every Event Is a Content Studio · Marketing Leaders Roundtables · Building a Brand-Led Demand Gen Engine |
| 6 | Specialized GTM and running the marketing org | Federal and critical-infrastructure selling, ABM and paid-media mechanics, PLG, investor views, CMO operating cadence. | FedRAMP 20x GTM · Federal Cybersecurity Purchasing · Real-Time ABM · Run Your Marketing Department Like a Business · The VC Perspective |

---

## Reference: the Content Workshop outcome

Use this for **scale** and to **avoid duplicates**, not as this brand's answers. Verdicts depend on each brand's own blog and offerings.

| Problem | CW verdict | CW action |
|---|---|---|
| 1. Everyone sounds the same | Partly covered | New post: *Demote AI in Your Positioning* (optional second: *Count Your AI Tells*) |
| 2. Making AI part of how the team works | Partly covered | New post: *Your Messaging Belongs in a Repo* |
| 3. Getting found when buyers ask AI | Covered | Promote existing post |
| 4. Buyers trust proof and peers | Covered | None |
| 5. Proving marketing drives revenue | Partly covered | New post: *Plan the Content Before You Book the Booth* |
| 6. Specialized GTM and running the org | Not ours | None |

Result: 3 new posts plus 1 optional, and no updates. Aim for the same small scale. If this brand partly covers the same problem as CW, choose an angle that doesn't overlap the CW post.

---

## Appendix: full CyberCon session list

**Workshops**
- Claude Beginner Workshop: hands-on intro to Claude for everyday marketing work (research, campaign planning, content, messaging). No AI background needed.
- Claude Intermediate Workshop: building Claude Skills and turning repeat cyber-marketing tasks into reusable workflows.
- Points for Creativity: A Roller Derby Workshop: a creative reset using roller-derby naming as a stand-in for branding; teams remix stale jargon into a brand concept and tagline.
- Workshop: Business Networking Pickup Lines: drills on cold in-person connections, finding the right person in the room, qualifying contacts.

**Main program**
- Resist Comfort (keynote): discomfort as a competitive edge now that AI makes everyone's work sound alike; seeking criticism and pushing past safe ideas.
- Nobody Read Your Threat Report: survey design, defensible metrics, segmentation, mining existing telemetry.
- Embed Analyst Interactions in Your Marketing Roadmap: ongoing analyst engagement to inform launches and messaging.
- FedRAMP 20x GTM: positioning "continuous validation" honestly, with narrative, content blueprint, ABM and assets.
- Behind the Booth: where AI helps field marketing scale and prove impact, and where human judgment leads.
- Where AI Belongs in Your Positioning: positioning as a startup-style hypothesis; companies that got AI messaging right and wrong.
- Make Them Laugh, Then Make Them Buy: irony, parody and self-deprecation building trust with skeptical B2B buyers.
- Our Messaging Was Outdated… So We Built a Living Messaging System (panel): messaging in a Claude skill stored in GitHub, Slack-submitted updates, AI-drafted revisions; what worked and broke.
- 3 AI Tactics That Make Your Whole Company Think Marketing Runs on Magic: three no-code AI tactics, each launchable in under three hours.
- Kill the AI Tells: live teardown of security copy and a repeatable method for fixing telltale AI patterns.
- The State of Federal Cybersecurity Purchasing: agency priorities, budgets, procurement, aligning outreach.
- From Scrappy to Serious (fireside): when and how to mature a startup brand, funding it, executive buy-in.
- The PLG Playbook for Early Stage Cyber Marketers: scaling to 3,000 customers with PLG and blending it with sales-led growth.
- Securing Water Infrastructure: threats to municipal water systems and selling to utilities.
- AI-Driven Security as a Competitive Advantage (panel): agentic AI in SOCs, customer trust, executive risk narratives in regulated industries.
- When Creativity Meets Revenue: designing events, booths and experiences that feed pipeline, and measuring them.
- A Time to Scale: marketing across cultures in EMEA, APAC and the Americas.
- From Slop to Story: a shared AI system for consistent brand voice, plus an AI marketing maturity model.
- Read the Room: interactive game show with audience phone voting on cyber marketing trends.
- Proof Over Positioning: documented operational results from public-sector and nonprofit clients as positioning.
- Go, Kill, Return, and Go Again: SAS origin story as a model for growth teams and weekly sprints.
- From Cost Center to Growth Engine: tying alliances, events and marketing to revenue and RevOps (MSSP, Microsoft partners).
- Behind the Rebrand: executive alignment, timelines, scope creep, red flags in agency contracts.
- Architecting Unique First-Party Signals: first-party signals across paid, content and launches for signal-based GTM.
- Do This, Not That. How to Win at AI Search (runs twice): what to start and stop doing to show up in AI answers; checking what AI says about your brand.
- From Social Media to CMO (panel): social roles as preparation for marketing leadership.
- Consensus Architecture: mapping a buying committee, finding content gaps per stakeholder, champion material.
- One Guitar. One CISO. Your Questions.: informal Q&A with a CISO on what drives buying decisions.
- The Marketing Operating System: KPI-driven roadmaps and quarterly marketing reviews.
- CISO Series Game Show: audience-participation game show.

**CyberCMO Summit**
- Crack the Case: AI-powered win/loss analysis that changed targeting, messaging and enablement.
- Cybersecurity Marketing: Where Everything Is Important and Nothing Stands Out (speed session): simplifying messaging, sales/CS alignment, using AI without sounding generic.
- The Death of Feature Marketing: agentic AI buyers weigh trust and governance; PMMs as category architects.
- Future of the Cybersecurity Marketing Society: organizers on the Society's direction.
- Spokespeople GPTs (speed session): custom GPTs trained on brand voice for drafts, talking points, FAQs; humans keep the final say.
- Cybersecurity Songs (speed session): live performance.
- How to Build a Threat Research Content Engine: threat research into narratives press, buyers and sales use; CTF activations at Black Hat and DEF CON.
- Real-Time ABM for the CISO Who Never Fills Out a Form: real-time account ID and automated ad spend in Salesforce; privacy guardrails.
- Run Your Marketing Department Like a Business: CMO-turned-CRO operating cadences and accountability.
- Marketing Leaders Roundtables: budget pressure, capacity, proving impact, sales alignment.
- Beyond Events (panel): field marketing from running events to contributing revenue.
- Hi, I'm Claudia! (speed session): an AI trained on one executive's standards to triage decisions and draft feedback.
- Orchestrating Outcomes: deals that start with a risk event, run through AI search and peer advice, and stall at procurement.
- From Influence to Income (panel): cyber creators building audiences and revenue.
- How to Crack the Market and Gain Momentum as a Startup (speed session): owning a focused "narrative wedge."
- How I Hacked the RSA Innovation Sandbox Application (speed session).
- We Spent $100K Testing OpenAI Ads So You Don't Have To: five lessons from ChatGPT ad testing.
- Inside the Cybersecurity Buying Journey: 2027 (panel): research from 500 decision-makers.
- When Visibility Isn't Enough (panel): third-party validation and trusted voices turned into pipeline.
- The Human Side of Transformation (panel): restructuring teams and roles for AI.
- Two Worlds, Two CISOs: a vendor CISO and a traditional-enterprise CISO react to vendor marketing.
- Building a Brand-Led Demand Gen Engine: connecting brand, PMM, field and demand gen to pipeline.
- Signal vs. Noise: The CMO Playbook for Standing Out in Cyber (panel).
- Brand vs Creator: Most Common Influencer Marketing Mistakes.
- Roundtable: AI Use Cases: making AI use cases repeatable and measurable.
- Keeping the Brand Alive After the Deal Closes: avoiding brand dilution after an acquisition.
- The Cybersecurity Newsroom: an in-house research and PR newsroom instead of paid media.
- How to Win Over Sales: earning sales' trust so PMM content gets used.
- CMO Wins and Fails: applying AI across marketing during a rebrand, stack change and platform shift.
- 5 Moves to Strengthen Demand Performance in 30 Days.
- Demand Generation Maturity Model.
- When Buyers Don't Believe Your Marketing, They Read the Docs: documentation as a pre-sale trust channel; a five-part Docs Trust Audit.
- Weaponizing Swag in the GTM Lifecycle: tying branded items to goals and tracking them in the CRM.
- Beyond Amplification: influencers as creative and strategic partners.
- CyberMarketing Benchmarks: reading benchmarks by company stage and GTM model.
- The Ultimate Lead Magnet: publishing a book in-house on a shoestring.
- Product Marketing Roundtables.
- Closing CyberCMO Summit Conversation.

**CEO Summit and other sessions**
- Social Engineering 101 (keynote): how con artists use trust, urgency and authority.
- MQLs, Memes and Building a Growth Team: metrics, hiring and culture.
- Zero to Flagship: campaign architecture behind 96% engagement in one quarter.
- Selling Cybersecurity to Everyone: messaging for governments, enterprises, boards and investors.
- Maximizing Executive Relationships (panel): customer advocacy when your best customers must stay anonymous.
- AI-Powered Partner Enablement: an AI agent inside partners' tools, multilingual, assessing prospect security posture.
- UGC and Community Marketing: a 4M-user community grown through UGC and peer recommendations.
- The Human MOAT (workshop): personal branding on mastery, originality, authenticity and trust.
- The VC Perspective: how investors judge GTM strategy and repeatable growth.
- How to Build a Product Marketing Operating System with Claude: pillars, minimum skills, sharing with a team.
- Before You Can Afford Gartner: a lightweight founder AR playbook.
- Every Event Is a Content Studio (speed session): one event into weeks of organic content, and measuring reach.
- Customer Marketing as a Growth Engine: advocacy, community and lifecycle.
- Failure Modes in Go-to-Market: fuzzy positioning, loose ICPs, a diagnostic checklist.
- They Don't Trust Your Sales Team (Yet): community-led growth tied to pipeline.
