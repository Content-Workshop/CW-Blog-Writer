---
rubric: article
stage: "Blog / Pillar Page"
reviewer: article-karen
version: 1
appliesTo: Article
---

# Article rubric (blog / pillar page)

Starter draft — open for team feedback. The [Article Karen](article-karen-persona.md) evaluates
each finished `Article` against these via [rubric-qa](rubric-qa.md):
**criterion-level PASS / FAIL / ESCALATE with cited evidence — no holistic score.** Failures become
the `fixList` the Article Writer applies on re-draft.

C1 is brand voice, C2–C6 are craft, C7–C9 are SEO, C10 is AEO, C11 is word count, C12 is sourcing —
the same load-bearing split named in the brief: no agent grades its own homework, and brand voice
is the north star.

## Criteria

### C1 — Sounds like the brand, not a house voice
- **Check:** the draft matches the client CIP's `voiceRules.always`/`never`, `positioning`, and the
  targeted `personas[]` — not a generic marketing-agency voice.
- **Pass when:** a reader who knows the brand would recognize it; no `voiceRules.never` crossed.
- **Fail when:** it reads as generic thought-leader copy, or crosses a stated brand "never."
- **Evidence required:** quote lines vs the CIP's voice rules.

### C2 — Introduction earns attention
- **Check:** opens with tension, a sharp observation, a contrarian angle, a specific problem, a
  consequence, or a real-stakes question — not generic setup language.
- **Pass when:** the opening does one of the above in the brand's voice.
- **Fail when:** it opens with "In today's fast-paced world," "Let's dive in," "It's no secret
  that," or equivalent throat-clearing.
- **Evidence required:** quote the opening lines.

### C3 — Structure and headings
- **Check:** clear H2/H3s, specific and reader-useful (not "Why It Matters" / "Key Benefits" /
  "Final Thoughts"); paragraphs mostly 1–3 sentences; bullets used sparingly and only when
  substantive.
- **Pass when:** headings are specific and the piece is scannable.
- **Fail when:** vague headings, wall-of-text paragraphs, or bullets standing in for undeveloped
  thinking.
- **Evidence required:** quote an offending heading or paragraph.

### C4 — Depth over breadth
- **Check:** each major section answers what/why/so-what and is developed with explanation,
  example, consequence, or practical application — not stated and abandoned.
- **Pass when:** sections are genuinely developed.
- **Fail when:** a section is a single undeveloped claim, or the piece skims too many points
  shallowly instead of developing fewer fully.
- **Evidence required:** name the underdeveloped section.

### C5 — Style discipline
- **Check:** no banned clichés, no repeated sentence-pattern tics, no mixed metaphors, ≤3 em dashes.
- **Pass when:** all hold.
- **Fail when:** any is present — quote it.
- **Evidence required:** the offending phrase/sentence and count (for em dashes).

### C6 — CTA is earned
- **Check:** the CTA concludes the argument the piece made and names a specific next move — not
  generic ("Contact us today," "Ready to get started?").
- **Pass when:** the CTA reads as the natural next step from the argument.
- **Fail when:** generic or disconnected from the piece's actual argument.
- **Evidence required:** quote the CTA.

### C7 — Core Keyword Phrase (CKP)
- **Check:** CKP appears in the first paragraph and links to the corresponding pillar/core page.
- **Pass when:** both present.
- **Fail when:** either is missing.
- **Evidence required:** quote the first paragraph.

### C8 — Subtopic Keyword Phrase (SKP) + meta
- **Check:** SKP used 5–8 times (~0.5–0.8% density), bolded on first use, present in ≥1 H2; meta
  title ≤60 chars includes the SKP; meta description 155–160 chars.
- **Pass when:** all hold.
- **Fail when:** density is off-range, bolding/H2 placement missing, or meta fields miss the
  length/content requirement.
- **Evidence required:** the count, the meta title/description as delivered.

### C9 — Work-ins and link hygiene
- **Check:** every `workIns[]` term used at least once; ≥3 internal links with editorial anchor
  text; 2–3 external links, `.org`/`.gov`/`.edu`, no competitor.
- **Pass when:** all hold.
- **Fail when:** a work-in is missing, internal links are under 3, or an external link is a
  competitor or non-authoritative.
- **Evidence required:** list what's missing.

### C10 — AEO practices
- **Check:** at least 4 of the AEO checklist practices are genuinely present (not just claimed by
  the Writer's self-report) — direct-answer lead, Q&A heading, self-contained sections, data-rich
  formatting, FAQ section, next-step answers, entity consistency, primary-source citations, visible
  expertise, alt-text guidance, markdown-friendly layout.
- **Pass when:** ≥4 are verifiably present in the draft itself.
- **Fail when:** fewer than 4, or a claimed practice isn't actually there on inspection.
- **Evidence required:** name the ≥4 found, and any claimed-but-absent practice.

### C11 — Word count on target
- **Check:** `wordCount` is close to the brief's target (1,200 blog / 2,000 pillar, or the brief's
  explicit override).
- **Pass when:** within a reasonable range of the target, not padded with filler to get there.
- **Fail when:** materially short, materially over, or reaches the count via visible padding.
- **Evidence required:** the delivered word count vs the target.

### C12 — Sourced, not invented
- **Check:** every factual claim traces to the Curator's packet, the Researcher's findings, or
  supplied notes/interviews — nothing invented to fill an `openGaps` hole.
- **Pass when:** all claims trace to a source in the packet.
- **Fail when:** a claim has no traceable source, especially one flagged in `openGaps`.
- **Evidence required:** quote the unsourced claim.

## Verdict

One of **APPROVED** / **NEEDS WORK** / **REJECTED**, consistent with the rows — never APPROVED with
blocking FAILs. FAILs become a `fixList` routed to the Article Writer
for the next draft pass; a voice or sourcing miss too deep to patch (REJECTED) routes back to the
Writer for a full re-draft, not a targeted fix.
