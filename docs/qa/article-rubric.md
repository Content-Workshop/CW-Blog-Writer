---
rubric: article
stage: "Blog / Pillar Page QA"
reviewer: article-karen
version: 2-cw-blog-writer
appliesTo: blog draft
---

# Article rubric: CW-Blog-Writer

The [Article Karen](../../.claude/agents/article-karen.md) agent uses this rubric to review a finished
blog or pillar-page draft. Each criterion gets **PASS / FAIL / ESCALATE / N/A with quoted evidence.
There is no overall score.** Each FAIL becomes an item on the fix list for the writer.

**Where it came from:** adapted from `Content-Workshop/Crius`, `content-engine/docs/rubrics/article-rubric.md`
(v1, commit `7a4ad1f`). Crius criteria C1–C12 are kept in substance. The Crius pipeline inputs
(Scout brief, Curator packet, client CIP) are replaced with this repo's intake and editorial docs. C13–C14 are new.

**Priority of sources.** This rubric summarizes the two editorial docs, and they are the source of truth:
1. `docs/content-workshop-editorial-addendum.md`. It is newer and **wins on any conflict**. Check its date.
2. `docs/content-workshop-blog-writer-instructions.md`.

If either doc has a rule this rubric doesn't list, or the docs and this rubric disagree, apply the doc
and note the gap in the report.

**Rule tiers**
- **House rule:** written in the editorial docs. A miss is a **FAIL**.
- **Brief rule:** a requirement that applies only when the intake or brief supplies it (Crius SEO/AEO
  targets, work-ins, a specific meta-length spec). If the brief supplies it, a miss is a **FAIL**. If not,
  report the measurement as **advisory**: it does not block and is not a FAIL.
- **Watch-list item:** a tell-word or pattern the addendum lists as "flag on use." Report it as **advisory**.

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
- **Pass when:** it reads as Content Workshop (or the supplied client voice), and the persona is
  clearly served.
- **Fail when:** it reads as generic thought-leader copy, is hype-driven, talks down to a technical
  reader, or ignores the stated persona.
- **Evidence:** quote lines against the voice and audience rules.

### C2: Introduction earns attention
- **Check:** the opening uses one of the approved openers: tension, a sharp observation, a contrarian
  angle, a specific problem, a business consequence, a question with real stakes, or a brief scenario.
  None of the banned openers in the *Introductions* section ("In today's digital landscape," "Now more
  than ever," "Let's dive in / delve into / explore," "It's no secret that," etc.).
- **Fail when:** the piece opens with preamble or a banned opener.
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
  - **Section count:** fits the target length (800: 3–4 · 1,200: 4–5 · 1,500: 5–6 · 2,000: 6–8 ·
    2,500+: frameworks, examples, pitfalls, implementation).
- **Fail when:** a heading is vague or audience-blaming, there's a wall-of-text paragraph, or a
  full-sentence bullet list hasn't been converted.
- **Evidence:** quote the offending heading, paragraph or list.

### C4: Depth over breadth
- **Check:** each major section answers three questions: what's the point, why does it matter to
  this reader, and what should they do or reconsider. Each is developed with explanation, example,
  consequence, contrast or application.
  - Any sentence that promises a specific count ("three ways…") is followed by an actual list
    (addendum Rule 3).
  - No restating the previous section as a transition.
- **Fail when:** a section is stated and abandoned, the piece skims too many points, a promised count
  isn't delivered, or a restatement serves as a transition.
- **Evidence:** name the section and quote it.

### C5: Style discipline (required find-pass with counts)
Count each of these and report the numbers. Don't estimate.
- **Negative-setup / positive-insertion construction** ("It's not X, it's Y" / "That's a Y problem,
  not an X problem," in either clause order, including when split across two sentences):
  **0 in title/headings, at most 1 in body.** List every instance found.
- **Em dashes:** **at most 3**, and every one **set closed** (`word—word`). Any spaced dash (`word — word`)
  is a FAIL, even if the count is under 3. A spaced en dash or hyphen used as a dash counts as spaced.
- **Banned clichés:** the *Style Rules* list, including "the distinction matters more than it sounds like
  it should" and close variants. Also look for hedges that announce a point instead of making it.
- **Mixed metaphors:** none.
- **Typos/proofing errors:** none.
- **Advisory:** "silent"/"quiet" used as modifiers (watch list); "predict" where "infer" may fit (watch
  list, not adopted).
- **Fail when:** any blocking count is over its ceiling, any dash is spaced, or any cliché or mixed
  metaphor is present.
- **Evidence:** the counts plus each offending phrase quoted.

### C6: CTA is earned
- **Check:** the CTA concludes the argument the piece made and names a specific next step. No "Contact
  us today," "Reach out to learn more" or "Ready to get started?"
- **Fail when:** the CTA is generic or disconnected from the argument.
- **Evidence:** quote the CTA.

### C7: Core keyword
- **Check (house rules):**
  - The exact-match core keyword appears in the user's **exact word order**, used as an exact match
    **once** (addendum Rule 1).
  - It appears in the first ~100 words of the intro.
  - It appears naturally in the body. Title, an H2 and the conclusion/CTA are "if natural."
  - It never reads as stuffed or forced.
  - The pillar page is linked with natural anchor text (never "click here" or "read this pillar page").
- **Fail when:** the word order differs, the exact match is missing or repeated, it's absent from the
  first ~100 words, it's forced, or the pillar link is missing or has bad anchor text.
- **ESCALATE** if no core keyword or pillar page was supplied.
- **Evidence:** the exact-match count, the first ~100 words, and the pillar anchor.

### C8: Subtopic keyword and meta fields
- **Check (house rules):** the subtopic keyword supports the main topic, appears naturally in the body,
  and appears in a subheading where appropriate.
- **Brief rules (advisory unless the brief requires them):** report the measured values for the Crius
  SEO targets:
  - subtopic keyword used 5–8 times (~0.5–0.8% density), bolded on first use, in at least 1 H2
  - meta title ≤60 characters and includes the subtopic keyword
  - meta description 155–160 characters
- **Fail when:** the subtopic keyword is missing or forced, or a brief-required target is missed.
- **Evidence:** the count, the density, and the meta title/description with character counts (if delivered).

### C9: Link hygiene
- **Check (house rules):**
  - Every internal article supplied at intake is linked.
  - Anchors are editorial and point to the **most specific relevant asset**, not a generic landing page.
  - No end-of-post link dumps unless requested.
- **Brief rules (advisory unless required):** at least 3 internal links; 2–3 external links on
  authoritative domains (`.org`/`.gov`/`.edu`); no competitor domains; every `workIns[]` term used.
  Always report a competitor link as advisory, even if no brief rule applies.
- **Fail when:** a supplied internal link is missing, an anchor is mechanical or generic, or there's a
  link dump.
- **Evidence:** list every link with its anchor, and say what's missing.

### C10: AEO practices (brief rule)
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
- **FAIL** if the brief requires AEO and fewer than 4 are present. Otherwise **advisory**: report the
  count and which practices were found.
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

---

## Verdict

Exactly one verdict, consistent with the rows:
- **APPROVED:** no blocking FAILs. Escalations are only human confirmations (C14 names, missing
  intake) that don't change the copy.
- **NEEDS WORK:** one or more FAILs. Each one goes on the fix list as a targeted change.
- **REJECTED:** the voice (C1) or sourcing (C12) is fundamentally off, and the piece needs a full
  re-draft, not a patch.

Never give APPROVED when any FAIL is blocking. Advisory notes never block.
