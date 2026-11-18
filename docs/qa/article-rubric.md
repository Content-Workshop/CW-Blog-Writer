---
rubric: article
stage: "Blog / Pillar Page QA"
reviewer: article-karen
version: 6-cw-blog-writer
appliesTo: blog draft
---

# Article rubric: CW-Blog-Writer

The [Article Karen](../../.claude/agents/article-karen.md) agent uses this rubric to review a finished
blog or pillar-page draft. Each criterion gets **PASS / FAIL / ESCALATE / N/A with quoted evidence.
There is no overall score.** Each FAIL becomes an item on the fix list for the writer.

**Where it came from:** adapted from `Content-Workshop/Crius`, `content-engine/docs/rubrics/article-rubric.md`
(v1, commit `7a4ad1f`). Crius criteria C1–C12 are kept in substance. The Crius pipeline inputs
(Scout brief, Curator packet, client CIP) are replaced with this repo's intake and editorial docs. C13–C14 are new;
C15–C16 were added in v5 for the addendum's Round 5–6 rules (Nov 12, 2026 update).

**Priority of sources.** This rubric summarizes the two editorial docs, and they are the source of truth:
1. `docs/content-workshop-editorial-addendum.md`. It is newer and **wins on any conflict**. Check its date.
2. `docs/content-workshop-blog-writer-instructions.md`.

If either doc has a rule this rubric doesn't list, or the docs and this rubric disagree, apply the doc
and note the gap in the report.

**Rule tiers**
- **House rule:** written in the editorial docs. A miss is a **FAIL**.
- **Brief rule:** a requirement that applies only when the intake or brief supplies it (work-ins,
  subtopic-keyword bolding/H2 placement, subtopic keyword in the meta title). If the brief supplies it,
  a miss is a **FAIL**. If not, report the measurement as **advisory**: it does not block and is not a FAIL.

The SEO/AEO numbers in C8–C10 (subtopic keyword 5–8 uses, meta lengths, link counts, ≥4 AEO practices)
are **house rules** (since v3; v4 makes the external-link domain a preference): they are written in the instructions' *SEO* section and always block.
- **Editor Checklist item:** anything in the addendum's *Editor Checklist* (Passes 1–6) is a **house rule**,
  including the high-confidence Watch List items it lists ("earn" limit, mirrored pairs, ship/ceiling/argument,
  silent/quiet, exceptions H2, short intro paragraphs). A miss is a **FAIL**.
- **Watch-list item not in the Editor Checklist** (e.g. predict→infer, framework naming, fragment series as a
  list): report it as **advisory**.

**Judgment checks: clear-cut only (C4 restatements, C16 one-liners).** These two checks can't be counted,
so a fresh reviewer will always find new borderline candidates. A **FAIL** needs a clear-cut case:
- a sentence that repeats its own heading, or a point already made earlier, in close to the same words;
- a slogan or aphorism with no actor (nobody does anything in it);
- a standalone throat-clearing sentence that only announces a point.

Everything else (partial overlaps, lines that could be tighter, defensible stylistic choices) goes under
**ADVISORY** as a suggestion and does not block. When in doubt, it's advisory. **The countable checks are
unchanged and still block:** negative-setup, mirrored pairs, "earn," banned words, em dashes, keyword and
link counts, intro paragraph length.

**Verdict values**
- `ESCALATE`: use when the writer flagged a deliberate deviation with a reason, or when you can't
  judge without a missing input (for example, no pillar page was supplied). Never use it for an
  unflagged miss. That is a FAIL.
- `N/A`: use only when the criterion doesn't apply to this piece (for example, no framework is named).

---

## Criteria

### C1: Content Workshop voice and persona fit
- **Check:** the voice described in the instructions' *Voice*, *Content Philosophy*, *Audience Rules* and
  *Cybersecurity Rules* sections: confident, strategic, clear, direct, with a real point of view. It is
  written for the stated target persona, not generic "businesses."
  - If a client voice guide was supplied, judge against that instead.
  - In cybersecurity, the draft must never imply that CISOs, CTOs or engineers lack technical
    understanding.
  - **Point of view holds:** "you" stays "you" inside a section. Content Workshop never speaks as if it
    works inside the reader's company ("our managers"). If the piece uses CW's own team as an example,
    each section makes clear whose team is meant.
  - **No internal shop vocabulary** in reader-facing copy (addendum Rule 12): "reviewer" → "editor";
    no "ship," "ceiling," "argument," "find-pass," "two-instance bar," "promote," "Watch List."
- **Pass when:** it reads as Content Workshop (or the supplied client voice), and the persona is
  clearly served.
- **Fail when:** it reads as generic thought-leader copy, is hype-driven, talks down to a technical
  reader, ignores the stated persona, shifts point of view, or uses internal shop vocabulary.
- **Evidence:** quote lines against the voice and audience rules.

### C2: Introduction earns attention
- **Check:** the opening uses one of the approved openers: tension, a sharp observation, a contrarian
  angle, a specific problem, a business consequence, a question with real stakes, or a brief scenario.
  None of the banned openers in the *Introductions* section ("In today's digital landscape," "Now more
  than ever," "Let's dive in / delve into / explore," "It's no secret that," etc.).
  - **Intro paragraphs are one or two sentences each**, and an imperative opener gives each instruction
    its own sentence (Editor Checklist Pass 5).
- **Fail when:** the piece opens with preamble or a banned opener, or an intro paragraph runs past two
  sentences.
- **Evidence:** quote the opening lines.

### C3: Structure and headings
- **Check:**
  - **Headings:** H2/H3s are specific and useful to the reader. Never "Why It Matters," "Key
    Benefits," "Final Thoughts" or "Conclusion."
  - **No audience-blaming headings:** "Where Most Teams Get This Wrong" should be "Where It's Easy to
    Get This Wrong."
  - **Paragraphs:** mostly 1–3 sentences.
  - **Bullets:** used sparingly. **Any bulleted list of full sentences must be H3 + paragraph pairs
    instead.**
  - **No H2 devoted to exceptions or counterarguments.** A boundary condition gets one or two sentences
    inside the relevant section (Editor Checklist Pass 5).
  - **Advisory:** three or more parallel fragments strung inline may read better as a short list (watch list).
  - **Section count:** fits the target length (800: 3–4 · 1,200: 4–5 · 1,500: 5–6 · 2,000: 6–8 ·
    2,500+: frameworks, examples, pitfalls, implementation).
- **Fail when:** a heading is vague or audience-blaming, there's a wall-of-text paragraph, a
  full-sentence bullet list hasn't been converted, or an H2 is devoted to exceptions.
- **Evidence:** quote the offending heading, paragraph or list.

### C4: Depth over breadth
- **Check:** each major section answers three questions: what's the point, why does it matter to
  this reader, and what should they do or reconsider. Each is developed with explanation, example,
  consequence, contrast or application.
  - Any sentence that promises a specific count ("three ways…") is followed by an actual list
    (addendum Rule 3).
  - **Restatement pass (addendum Rule 9):** name each section's one point, then flag any sentence that
    repeats a point already made in that section or an earlier one, **including a sentence that restates
    its own heading**, and slogan-style summary lines. A thesis may be restated once, on purpose, in the
    conclusion. Look hardest at the middle third.
- **Fail when:** a section is stated and abandoned, the piece skims too many points, a promised count
  isn't delivered, or a **clear-cut** restatement survives (see *Judgment checks*). Partial overlaps go
  under ADVISORY.
- **Evidence:** name the section and quote it.

### C5: Style discipline (required find-pass with counts)
Count each of these and report the numbers. Don't estimate.
- **Negative-setup / positive-insertion construction** ("It's not X, it's Y" / "That's a Y problem,
  not an X problem," in either clause order, including when split across two sentences, **and "instead
  of X, Y" / "rather than X, Y" when they set up a contrast**): **0 in title/headings, at most 1 in body.**
  A quoted example used to illustrate the tell doesn't count. List every instance found.
- **Mirrored role pairs** ("X earns A. Y earns B." — back-to-back sentences that mirror each other's
  syntax to assign roles): **0**. Swapping the verb doesn't fix it; the mirroring is the tell.
- **"Earn" in any form:** **at most 1** per piece.
- **"Isn't just" / "doesn't just":** **at most 1**.
- **Em dashes:** **at most 3**, and every one **set closed** (`word—word`). Any spaced dash (`word — word`)
  is a FAIL, even if the count is under 3. A spaced en dash or hyphen used as a dash counts as spaced.
- **Banned clichés:** the *Style Rules* list, including "the distinction matters more than it sounds like
  it should" and close variants. Also look for hedges that announce a point instead of making it.
- **Mixed metaphors:** none.
- **Typos/proofing errors:** none.
- **A number needs its noun:** a numeral standing in for a noun names it ("three sites," not "three").
- **Find-and-replace words (Editor Checklist Pass 3), 0 each in reader-facing copy:** "reviewer"
  (→ editor), "ship/ships/shipped" (→ publish), "ceiling" (→ limit), "argument" (→ message, point, the
  piece), "silent"/"quiet" as modifiers, "most teams / most marketers get this wrong."
- **Advisory:** "predict" where "infer" may fit (watch list, not adopted).
- **Fail when:** any blocking count is over its limit, any dash is spaced, any find-and-replace word
  survives, a number lacks its noun, or any cliché or mixed metaphor is present.
- **Evidence:** the counts plus each offending phrase quoted.

### C6: CTA is earned
- **Check:** the CTA concludes the argument the piece made and names a specific next step. No "Contact
  us today," "Reach out to learn more" or "Ready to get started?"
- **Fail when:** the CTA is generic or disconnected from the argument.
- **Evidence:** quote the CTA.

### C7: Core keyword
- **Check (house rules):**
  - The exact-match core keyword appears in the user's **exact word order**, used as an exact match
    **once in body copy** (addendum Rule 1). **The title, H1 and meta title don't count toward the once
    rule.** Report title/H1/meta uses separately.
  - It appears in the first ~100 words of the intro.
  - It appears naturally in the body. Title, an H2 and the conclusion/CTA are "if natural."
  - It never reads as stuffed or forced.
  - The pillar page is linked with natural anchor text (never "click here" or "read this pillar page").
- **Fail when:** the word order differs, the exact match is missing or repeated in body copy, it's absent from the
  first ~100 words, it's forced, or the pillar link is missing or has bad anchor text.
- **ESCALATE** if no core keyword or pillar page was supplied.
- **Evidence:** the body exact-match count (title/H1/meta uses listed separately), the first ~100 words,
  and the pillar anchor.

### C8: Subtopic keyword and meta fields
- **Check (house rules):**
  - The subtopic keyword supports the main topic, appears naturally in the body, and appears in a
    subheading where appropriate.
  - It is used **5–8 times** in body copy and subheadings (~0.5–0.8% density at typical lengths), without
    sounding stuffed. **The title/H1, meta title and meta description don't count**; report them separately.
  - **Meta title ≤60 characters. Meta description 155–160 characters.** Count characters; don't estimate.
    If either is missing from the deliverable, that's a FAIL.
- **Brief rules (advisory unless the brief requires them):** subtopic keyword bolded on first use, in at
  least 1 H2, and included in the meta title.
- **Fail when:** the subtopic keyword is missing or forced, it's used fewer than 5 or more than 8 times,
  a meta field is missing or out of range, or a brief-required target is missed.
- **Evidence:** the count, the density, and the meta title/description with character counts (if delivered).

### C9: Link hygiene
- **Check (house rules):**
  - Every internal article supplied at intake is linked.
  - Anchors are editorial and point to the **most specific relevant asset**, not a generic landing page.
  - No end-of-post link dumps unless requested.
  - **At least 3 internal links.** The pillar-page link counts as one.
  - **2–3 external links** to reputable sources. No competitor domains. HubSpot is **not** a competitor.
- **Preference (advisory):** `.org`/`.gov`/`.edu` sources where a strong one exists. Other reputable
  domains (industry publications, vendor research) are acceptable. Note any that look sponsored.
- **Brief rules (advisory unless required):** every `workIns[]` term used.
- **Fail when:** a supplied internal link is missing, there are fewer than 3 internal links, an anchor is
  mechanical or generic, there's a link dump, the external links number fewer than 2 or more than 3,
  or an external link is non-reputable or goes to a competitor.
- **Evidence:** list every link with its anchor, and say what's missing.

### C10: AEO practices (house rule)
- **Check:** how many of these practices are actually present in the draft:
  - direct-answer lead
  - Q&A heading
  - self-contained sections
  - data-rich formatting
  - FAQ section
  - next-step answers
  - entity consistency
  - primary-source citations
  - visible expertise
  - alt-text guidance
  - markdown-friendly layout
- **Pass when:** at least 4 are verifiably present in the draft itself.
- **Fail when:** fewer than 4 are present, or a practice the writer claimed isn't actually there.
- **Evidence:** name each practice found. If the writer claimed a practice, say whether it's actually
  there.

### C11: Word count on target
- **Check:** the measured word count is close to the requested length. It isn't reached by padding,
  and it isn't short by hundreds of words.
- **Fail when:** the draft is materially short or over (as a working line, more than ~10%), or the
  count was reached with visible filler.
- **ESCALATE** if no length was supplied (and say what the default would be).
- **Evidence:** the measured count (state the method) against the target.

### C12: Sourced, not invented
- **Check:** every statistic, named study, quote or specific factual claim can be traced. Either it is
  cited in the draft, or it is backed by notes, interviews or sources the writer supplied. Nothing is
  invented to fill a gap.
- **Fail when:** a stat or specific claim has no traceable source in the draft or the supplied
  material. Quote it.
- **Evidence:** list every untraced claim. If none were found, say how you checked.

### C13: Titles (new)
- **Check:**
  - The title, H1 and meta title have had the **shortening pass**. A main clause stacked with a
    qualifying clause should be trimmed, moved to a subtitle, or have the qualifier dropped
    (addendum Rule 5).
  - The title isn't vague ("The Future of AI Content").
  - No negative-setup construction (see C5).
  - **Advisory:** if the piece introduces a named framework or model, 2–3 candidate names are offered,
    at least one descriptive and at least one with a hook (watch list).
- **Fail when:** a stacked-clause title hasn't been shortened, or the title is vague.
- **Evidence:** quote the title, H1 and meta title. Give a shorter option as the fix.

### C14: Name verification (new)
- **Check:** every company, tool, product, program or internal asset name (playbooks, courses,
  communities) is spelled and named as its source of record has it.
- **Fail** if a name is demonstrably wrong.
- **ESCALATE** every internal asset name you can't verify from the repo or the supplied material, so
  a human can confirm it against Notion, the wiki or an approved piece. Never assume a name is right.
- **Evidence:** list each name and its verification status.

### C15: Personality (new, addendum Rule 10)
- **Check:** at least one moment of humor, irreverence, or a recognizable everyday or pop-culture
  reference, usually in the first H2 where the problem is set up. Guardrails:
  - The joke makes the same point as the paragraph it sits in.
  - It doesn't interrupt a cause-and-effect sequence.
  - It uses a current reference, not a dated one.
  - One analogy per idea.
  - It never comes at the reader's expense, and it doesn't shift point of view (see C1).
- **Fail when:** the piece has no such moment, or one breaks a guardrail.
- **Evidence:** quote the moment and where it sits.

### C16: Aphoristic one-liners (new, addendum Rule 11)
- **Check:** read every short sentence that closes a paragraph or follows a heading. For each one:
  1. If it restates the paragraph or heading, it should be cut (see C4).
  2. If it makes the point through an abstraction or an image the reader has to decode, it should be
     rewritten as a plain statement of who does what, naming the people and the action.
  3. If nothing concrete sits underneath, it should be cut.
  - **At most 1 deliberate punchline per piece**, and only where it carries a real claim.
  - Also cut throat-clearing: sentences that announce a point is coming instead of making it.
- **Fail when:** more than one punchline survives, or a **clear-cut** case survives: a slogan with no
  actor, a line that repeats its heading or an earlier point in close to the same words, or a standalone
  throat-clearing sentence (see *Judgment checks*). Lines that are merely tightenable go under ADVISORY.
- **Evidence:** list each candidate with your call (keep / rewrite / cut). Give a plain rewrite for each
  one to change.

---

## Verdict

Exactly one verdict, consistent with the rows:
- **APPROVED:** no blocking FAILs. Escalations are only human confirmations (C14 names, missing
  intake) that don't change the copy.
- **NEEDS WORK:** one or more FAILs. Each one goes on the fix list as a targeted change.
- **REJECTED:** the voice (C1) or sourcing (C12) is fundamentally off, and the piece needs a full
  re-draft, not a patch.

Never give APPROVED when any FAIL is blocking. Advisory notes never block.
