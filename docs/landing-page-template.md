# Content Workshop Landing Page Template

**Source page:** https://contentworkshop.com/ai-landing-page-with-form/ (AI Studio)
**Created:** October 28, 2026 · **Updated:** October 28, 2026 (labeling conventions added; FAQ answers shortened to 15–35 words)

**How to use this:** Copy the **Copy draft skeleton** into a new doc, follow the **Labeling conventions**, and fill every slot. Length targets come from the AI Studio page, so a filled page fits the existing layout without design changes. Each section's fields are fixed by the page design: keep the counts (3 hero benefits, 3 pillars, 4 steps, 4 outcomes, 4 testimonials). If you need a different count, check with design first. The AI Studio copy is kept below as a worked example.

**Before drafting:** fill the **Page Brief**. Landing pages lean toward the blog rules in `content-workshop-blog-writer-instructions.md` and `content-workshop-editorial-addendum.md`, but don't follow all of them strictly. See **Style Notes** for the three tiers.

---

## Page Brief

| Field | Answer |
|---|---|
| Offer / service line | [e.g., AI Studio, Content Strategy, AI Marketing Course] |
| Primary audience | [Role + company type, e.g., B2B cybersecurity marketing leaders] |
| Core pain (one sentence) | [What's broken for them today] |
| Promised outcome (one sentence) | [What changes after working with CW] |
| Form CTA / conversion goal | [e.g., book an intro call] |
| Proof asset | [Case study client + link] |
| Testimonials (4) | [Names, titles, companies: verified against source] |
| Target keyword (if SEO matters) | [Exact phrase, exact word order] |
| Page URL slug | [/service-landing-page/] |

---

## Template

### Labeling conventions

Copy drafts use the same labels on every page, so designers and developers can scan them quickly:

| Element | How to write it |
|---|---|
| Doc title | `# [Page Name] — Copy Draft` |
| Source lines (under title) | Italic: *Based on: landing-page-template.md \| Source: [brief / source docs]* and *Structure based on - [reference page URL]* |
| Layout section, no on-page heading | H2 in bold caps: **HERO**, **FORM**, **TICKER**, **VALUE PILLARS**, **FOOTER** |
| Section with an on-page heading | H2 with the label: **H2:** [heading text] |
| FAQ section | H2: **SECTION: FAQ**, then **H2:** [heading] as a line inside it |
| Fields | Inline bold label, then the copy: **H1:** … / **Subhead:** … / **Body:** … |
| Lists | Bold label on its own line, then bullets: **Bullets:** / **Features:** |
| Form fields | One line, pipe-separated: **Fields:** Full Name \| Email \| … |
| Buttons and links | **CTA button:** [label] - *[where it links]* |
| Notes for design/dev | Italic, in parentheses or on their own line: *(links to form with Tier 1 pre-selected)* |
| Steps | 3-column table: number \| step name \| description |
| Boxes / cards in a row | 2-column table **Title** \| **Body**, with the note *These are boxes in order from left to right, one for each row* |
| Pricing tiers | H3 per tier, with **Snapshot:** / **Price:** / **Opens with:** / **Features:** / **CTA button:** |
| FAQ | 2-column table **Q** \| **A** |
| Placeholders | `[PRICE]`, `[BETA_QUOTE_1]`: caps in brackets |
| Copy not from a source | Italic flag after it: *[INFERRED — verify]* or *[CONFIRM before publish]* |
| Global sections | **FOOTER** with *(global — no copy needed)* |
| Notes, open items, style check | Last section: **DRAFT NOTES** with *(not page copy)* |

Length targets below are in italic notes. They're for the writer and get deleted from the final draft.

### Copy draft skeleton

Copy everything inside the block below into a new doc and fill every slot. Drop or add sections to match the page, and flag layout changes in DRAFT NOTES.

```markdown
# [Page Name] — Copy Draft

*Based on: landing-page-template.md | Source: [brief / source docs]*
*Structure based on - [reference page URL]*

## HERO

**Eyebrow:** [3–5 words]
**H1:** [5–8 words, ≤40 characters]
*Alternates: [option 2] / [option 3]*
**Subhead:** [1–2 sentences, 20–25 words: name the pain, then introduce the offer]
**Bullets:**
- [8–12 words]
- [8–12 words]
- [8–12 words]
**CTA button:** [1–3 words] - *[links to]*
**Scroll cue:** [label] ⬇️ - *[anchor link to section]*

## FORM

*[Purpose and placement, e.g., sits in the hero's right column]*
**Form title:** [6–10 words]
**Fields:** Company | Full Name | Title | Email | CAPTCHA
*[Which fields are required]*
**Submit button:** [1–3 words]
**Confirmation message:** [1 sentence]

## TICKER

*Scrolling marquee. Enter once; the site loops it.*
**Phrases:** [2–5 words] • [ ] • [ ] • [ ] • [ ] • [ ] • [ ] •
*(7 phrases. Reuse the eyebrow and one section heading so the ticker echoes the page.)*

## VALUE PILLARS

*These are boxes in order from left to right, one for each row*

| **Title** | **Body** |
| --- | --- |
| [3–5 words: approach] | [2 short paragraphs, 45–80 words total] |
| [3–5 words: what we deliver] | [45–80 words] |
| [3–5 words: who we are] | [45–80 words] |

**CTA button:** [label] - *[links to]*

## **H2:** [Process heading, 5–9 words]

| | | |
| --- | --- | --- |
| 1 | [1-word verb] | [1–2 sentences, 15–22 words] |
| 2 | [1-word verb] | [15–22 words] |
| 3 | [1-word verb] | [15–22 words] |
| 4 | [1-word verb] | [15–22 words] |

**CTA button:** [label] - *[links to]*

## **H2:** [Case study heading, 6–10 words]

*(Or pricing: see the Pricing variant below)*
**Client:** [Verified company name] - *links to [client work URL]*
**Challenge:** [2 sentences, 40–50 words]
**Result:** [2 sentences, 40–50 words]

*These are boxes in order from left to right, one for each row*

| **Title** | **Body** |
| --- | --- |
| [3–5 words] | [25–35 words: lead with a hard number if one exists] |
| [3–5 words] | [25–35 words] |
| [3–5 words] | [25–35 words] |
| [3–5 words] | [25–35 words] |

**CTA button:** View Case Study - *links to [case study URL]*
*(Every number must come from the published case study, unrounded.)*

## **H2:** [Testimonials heading] *(default: What Our Clients Say About Us)*

*Carousel, 4 slides. Quotes run verbatim. Best-matching quote in slide 1 or 2.*

| **Slide** | **Quote** | **Name / Title, Company** |
| --- | --- | --- |
| 1 | [30–80 words] | [Name] / [Title], [Company] |
| 2 | [ ] | [ ] |
| 3 | [ ] | [ ] |
| 4 | [ ] | [ ] |

## SECTION: FAQ

**H2:** [FAQ heading] *(default: Have questions?)*
**Side button:** Contact Us - *links to /contact/*

| **Q** | **A** |
| --- | --- |
| [Biggest objection] | [15–35 words] |
| [ ] | [ ] |

*(8–12 questions: objections first, then how it works, then logistics. Answers 15–35 words: answer first, one supporting fact, no restating the question. Every term the page introduces gets an FAQ.)*

## FOOTER

*(global — no copy needed)*

## SEO

*(not visible on page)*
**Meta title:** [≤60 characters] *([N] characters)*
**Meta description:** [140–155 characters] *([N] characters)*
**URL slug:** /[2–5-words]/
**Keywords:** "[primary]" ([where it appears]) · "[secondary]" ([where it appears])

## DRAFT NOTES

*(not page copy)*
**Layout changes from the template (check with design):**
- [Change]
**Open before publish:**
- [ ] [Item]
**Style check:**
- Negative-setup lines: [count, and which]
- Banned clichés: [count]
- Em dashes: [count]
- H1 / meta title / meta description: [character counts]
```

### Pricing variant

Use in place of the case study when the page sells tiers or products. Example: the AI Marketing Course page.

```markdown
## **H2:** [Pricing heading, e.g., Choose Your Path]

*[Number of cards, order left to right, which one is featured]*
**Subline:** [1 sentence]

### [Tier / Product Name]

**Tagline:** [1 sentence]
**Snapshot:** [level or specs · key differentiator]
**Price:** [PRICE]
**Opens with:** [what this tier adds over the one before it; omit on the first tier]
**Features:**
- [Feature]
**CTA button:** [label] *(links to [checkout / form with this tier pre-selected])*

**Fine print:** [billing terms, what's not included]
```

---

## Worked Example: AI Studio (as published)

**Hero.** Eyebrow: Tame the marketing chaos · H1: The Smartest AI Is Built Around You · Subhead: Scattered AI pilots aren't moving the needle. Our AI Studio helps build an ecosystem that matches how your team actually works.
Benefits: By tackling the tedium, you'll have more room for creativity. / Get ahead of the marketing rat race and craft a seamless process. / Set your vision, scale your efforts without increasing headcount.

**Form.** Heading: Let's chat about building your AI ecosystem.

**Ticker.** More breathing room • Less tedium • Flawless flows • Evolve from pilots to playbooks • Transformation is designed • Human-AI-Human • Tame the marketing chaos •

**Pillars.**
- *A Problem-First Approach.* Before any model is trained or workflow designed, our AI Studio team works to understand the real barriers holding your marketing performance back. / This clarity shapes everything we build, from intuitive content systems to insightful analytics tools, so your team can work faster, think deeper, and spend more time on winning creative strategies.
- *Custom-Built Tools & Systems.* If it's built for everyone, it's built for no-one. Such is true for AI tools and agents. / Every project we deliver is made from scratch to address your challenges and accommodate your tool stack. This makes intervention minimal, adoption seamless, and scale a certainty.
- *A Team Who Gets Your Team.* We're a marketing team first, AI engineers second. The systems we build were born from the same pressures, deadlines, and goals our clients face every day. / We started experimenting with AI to solve our own problems. That work gave us a front-row view of how AI can remove friction in marketing processes to make life easier and drive results.

**Process.** Successful Transformation Isn't Forced. It's Designed.
Assess: We'll identify the friction points holding you back. Together, we'll imagine what your world should look like. · Pilot: We'll pick one use case to tackle first. In doing so, we'll discern a repeatable process for success and expansion. · Build: Our team of engineers and experts will build the custom GPTs, AI agents, and playbooks to unlock your true flow. · Support: Through workshops and office hours, we'll make sure your whole team makes the transition to a new way of working.

**Case study.** What We've Built — And How Our Clients Build With It · Client: Palo Alto Networks · Outcomes: Reclaimed Time at Scale (~21.66 hours/month saved per team member) · Dramatic Efficiency Gains (200+ hours/year per product manager) · Leadership in AI Adoption · Reduced Tedium, Increased Impact.

**Testimonials.** Jennifer Tullman-Botzer (Head of Content, Cyolo) · David Moulton (Director of Content and Thought Leadership, Palo Alto Networks) · Gianna Whitver (Co-Founder & CEO, Cybersecurity Marketing Society) · Catherine Schultz (Senior Director of Content and Communication, Keyfactor).

**FAQ (12).** Does implementing AI mean replacing our creative team? · What is the "Human-AI-Human" workflow mentioned in your methodology? · How do you ensure AI outputs stay on brand? · Do you teach prompt engineering? · What formats does the training take? · What are "Custom AI Agents" and "Gems"? · Which AI platforms do you support? · Can these agents handle complex tasks like content repurposing? · What happens if our AI tools need updates? · What kind of support do we get after the initial training? · Can AI help with strategic planning and research? · How do you identify which processes to automate?

---

## Style Notes

**Policy:** landing pages don't follow every strict blog rule, but they lean that way where possible. Short, punchy copy can earn an exception. An exception should be a choice made on purpose, not a habit. Rules fall into three tiers.

### Tier 1: Always apply (no exceptions)

Factual and mechanical rules. These protect accuracy, not style.

- **Name verification** (addendum Rule 2): client names, testimonial names/titles, and internal product names (AI Studio, Gems, etc.) checked against the source.
- **Stats match the source exactly**: no rounding or restating.
- **Testimonials used exactly as approved.**
- **Exact keyword word order** (addendum Rule 1), if the page targets a keyword.
- **Em dashes set closed** (`word—word`), never spaced.

### Tier 2: Default, bend when it earns it

Follow these unless breaking one makes a specific line clearly stronger. Limit: **one exception per category per page.**

| Rule | Landing page version |
|---|---|
| Banned clichés | Avoid. One is allowed only if it is the clearest phrasing and you can't find a fresh alternative. Never in the H1. |
| Negative-setup construction ("isn't X, it's Y") | One per page, either in a heading or the body. On a landing page it can work as a section-heading hook. |
| Em dash count (≤3) | Same ceiling. |
| Shortening pass (addendum Rule 5) | Always run it on the H1, section headings, and meta title. |
| "Silent" / "quiet" tell-words | Same as blogs: flag on use. |

### Tier 3: Blog-only (doesn't apply)

Word count targets, intro structure, the rule converting full-sentence bullets to H3 + paragraph pairs, the internal-linking rules, and the blog outline template. The layout in this template takes their place.

### AI Studio page, measured against this policy

| Pattern | Where | Verdict |
|---|---|---|
| "Isn't Forced. It's Designed." | Process heading | Acceptable: the page's one negative-setup exception, and the line works as a hook |
| "built for everyone, it's built for no-one" | Pillar 2 | Over the limit, because the process heading already uses the one allowed. Rework on reuse. |
| "moving the needle" | Hero subhead | Rework: a banned cliché, high on the page; a fresher line is available |
| "seamless" (×2) | Benefit 2, Pillar 2 | Rework: one would be the max, and both have easy replacements |
| "unlock your true flow" | Process: Build | Rework: close to "unlock success" |
| Spaced em dash ("Built — And") | Case study heading | Fix: Tier 1 rule; set as "Built—And" or use a colon |

---

## Pre-Publish Checklist

- [ ] Every slot filled; only intentional placeholders (e.g., `[PRICE]`) remain, and each is listed in DRAFT NOTES
- [ ] Draft follows the labeling conventions; every *[INFERRED]* flag resolved
- [ ] Section counts match the layout: 3 benefits, 7 ticker phrases, 3 pillars, 4 steps, 4 outcomes, 4 testimonials, 8–12 FAQs
- [ ] FAQ answers 15–35 words each
- [ ] H1 ≤40 characters; meta title ≤60; meta description 140–155
- [ ] Every stat matches the published case study exactly
- [ ] Every testimonial name, title, and company verified; quotes used exactly as approved
- [ ] Every term introduced on the page is defined in the FAQ
- [ ] All CTA links resolve (Contact, client work page, case study)
- [ ] Tier 1 rules all pass (names, stats, quotes, keyword order, closed em dashes)
- [ ] Find-pass for banned clichés and negative-setup constructions: at most one exception per category, never a cliché in the H1
- [ ] Em dashes ≤3
