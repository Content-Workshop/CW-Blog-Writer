# Content Workshop Editorial Standards — Addendum

**Last updated: September 17, 2026**

**Source:** Patterns extracted from reviewer feedback (JB Clark, David Ebner, Christina Rowell) across four rounds:
- **Round 1** — "AI, GEO, and Trust Are Rewriting 2026 Marketing Playbooks," August 2026
- **Round 2** — "The AI Marketing Course for Marketers Who Don't Have Time for Another AI Course" (AI Marketing Course launch blog), August 26–27, 2026
- **Round 3** — "Why Your AI Marketing Content Needs a Feedback System," August 24–27, 2026
- **Round 4** — "You Don't Need a New Idea. You Need the Missing Circle." (Timely/Painful/Yours content marketing framework blog), September 17, 2026

**How to use this:** These continue the style guidance in the Content Workshop Blog Writer project instructions (`Content_Workshop_Writer_Agent.md`). Each rule cites the specific reviewer feedback it came from, so a future editor — human or AI — can see *why* the rule exists, not just what it says. Rules that hold up across two or more independent pieces get folded into the main instructions file under the relevant section; until then, they live here. **This file is dated at the top on every update** so anyone consulting it — including a new AI assistant with no memory of prior rounds — knows how current the guidance is.

**Caveat:** Round 1 was a single review, one piece — a few of its rules were promoted immediately anyway because they were countable mechanical or factual checks, not taste calls. Rounds 2–4 add three more pieces reviewed by the same core reviewer group (Round 4 drew comments from JB Clark and David Ebner; Christina Rowell did not comment on this piece). **The two-instance bar**: a subjective or stylistic note needs to recur independently in two or more pieces (or two or more rounds) before it hardens into a rule. A factual or mechanical note — spelling, a broken structure, an explicit "hardcode this" instruction from a reviewer — can promote on one instance. Items clear the bar when the same pattern shows up again, independently, in a later round; those promotions are marked below.

---

## Confirmed Rules (Rounds 1–4)

### 1. Match the user's keyword word order exactly, and use the exact-match phrase once.
*(Round 1 — unchanged. See prior version of this addendum for full sourcing.)*

### 2. Verify names against the source — including internal asset and product names, not just external company names.

The original Round 1 rule covered third-party company names. Round 2 surfaces the same underlying failure mode applied internally: a piece referenced the "**Quick Wins Playbook**" as an established asset name, and two reviewers weren't sure that was actually right.

> JB Clark: *"Is this what we're calling it?"* Christina Rowell, same anchor: *"I thought that's what it was called in notion?"* David Ebner extended the thought further, asking whether the Playbook's contents could be mirrored from Notion to the site as a teaser.

Neither reviewer contradicted the name — they questioned whether it matched the canonical source (Notion, in this case) with enough confidence to publish it. **Amended scope:** before a piece ships, verify not just external company/tool names but internal product, program, and asset names against whatever system of record defines them (Notion, the internal wiki, a previous approved piece) — the same discipline Rule 2 already requires for a company like Ahrefs applies to a proprietary asset like a playbook or community name.

### 3. When a sentence promises a specific count, deliver an actual list.
*(Round 1 — unchanged.)*

### 4. Ration — and now strictly police — the negative-setup / positive-insertion construction. [REINFORCED, ROUND 4]

Round 1 named this the "X is not the thing — Y is" antithesis and set a working ceiling of two per piece. Rounds 2 and 3 showed the construction surviving that ceiling by changing shape rather than frequency (splitting across two sentences), which prompted a revised ceiling: **zero in titles/headings, no more than one in body copy per piece.**

**Round 4 shows the revised ceiling is still not holding at the drafting stage.** The Missing Circle piece shipped a draft with three instances of the construction in body copy, not one:

1. *"It's not that you don't have ideas, it's that they seem to be missing something."*
2. *"That's a sourcing problem, not a creativity problem."* — flagged directly: JB Clark: *"Too many of these."*
3. *"Not 'we have a product in this category,' but 'we've seen this pattern enough times to have a real opinion about it.'"*

JB Clark's comment landed on instance #2, but the phrasing — "too many of *these*," plural, not "cut this line" — indicates he was flagging the pattern's density across the draft, not one sentence in isolation. This is the same failure mode Round 3 diagnosed (a rule that measures one surface form gets satisfied while the underlying tic keeps shipping), except this time the ceiling itself was already explicit and specific, and the draft still cleared it three times over.

**Diagnosis:** the ceiling is not the problem. The problem is that nothing forces a check against the ceiling before the draft goes to review. A one-per-piece cap that lives only in this addendum doesn't get enforced unless someone counts.

**Amended rule, effective immediately:** before a draft is finalized, run an explicit find-pass for the construction (any sentence or sentence pair that states what something is not, then what it is, in either order) and cut down to the ceiling — zero in titles/headings, one maximum in body copy — as a required drafting step, not a hoped-for outcome. If more than one instance survives to review, treat it as a process miss, not a style nitpick.

### 5. Titles and headline-length assets get a deliberate shortening pass before they ship.

David Ebner asked for a shorter title in two independent pieces, a full round apart:

> Round 2, on "The AI Marketing Course for Marketers Who Don't Have Time for Another AI Course": *"Maybe: AI Marketing Course for Marketers in a Hurry? We need something a bit shorter, if possible."* Round 3, on the meta title "Why Your AI Marketing Content Needs a Feedback System, Not Just a Style Guide": *"Can we shorten this?"*

Two independent instances, same reviewer, same note, two different pieces — this clears the bar. **Rule:** before finalizing a title, H1, or meta title, do an explicit shortening pass — if the title stacks a main clause plus a qualifying clause (as both flagged examples did), test whether the qualifier can be cut, moved to a subtitle, or dropped entirely without losing the hook.

### 6. Cut the boilerplate hedge "the distinction matters more than it sounds like it should" — and treat it as one instance of a broader throat-clearing pattern to watch for.

This is the single strongest piece of evidence from Round 3: **the identical sentence** — not a paraphrase, the same eleven words — was drafted into both the Round 2 and Round 3 pieces, and cut both times in tracked changes.

> Round 2: *"[[The distinction matters more than it sounds like it should.]] A video can explain the eight-part prompt framework in ten minutes..."* Round 3: *"[[That distinction matters more than it sounds like it should.]] A model that only sees 'before' and 'after' text has no way to generalize..."*

Neither cut carries a reviewer comment explaining it, but the fact that the exact same filler sentence was generated twice and removed twice, without any reviewer needing to ask twice, means it's not incidental. **Rule:** add "the distinction matters more than it sounds like it should" (and close variants — "this matters more than it seems," "that's a bigger deal than it looks like") to the banned-clichés list in the main style guide. More broadly, this is a *transitional hedge that announces a point is about to be made instead of just making it* — the same failure mode as the already-banned "In today's fast-paced world" openers, just relocated mid-paragraph instead of at the top.

### 7. Bulleted lists made of full sentences should become H3 + paragraph pairs, not bullets.

All three reviewers converged on the same fix, independently, in the same comment thread on the Round 3 piece's two large list sections:

> JB Clark: *"Two sections that have big lists with full sentences. We should cut down one of them a little and maybe simplify both?"* David Ebner: *"Agreed. These may be small paragraphs instead of bullets or shortened up. It's great info, though. Maybe an article all on its own!"* Christina Rowell: *"I like the idea of paragraphs. Maybe we do an H3 where the bold is the H3 and the copy under is the paragraph below."*

**Rule:** when a list item requires a full sentence (or more) to land — as opposed to a short noun phrase or fragment — restructure it as an H3 (the bolded lead-in) followed by a paragraph, rather than a bulleted list. Reserve true bullet/numbered lists for items that work as fragments. *(Note: the Round 4 piece's "What Happens When One Circle Is Missing" section already applies this pattern correctly — bolded lead-in phrase plus paragraph, no bullets — with no reviewer correction needed. First clean confirmation that the rule is sticking.)*

### 8. Conceptual frameworks need a name with personality, not just a functional label. [NEW, ROUND 4 — see Watch List; logged here as high-confidence pending a second instance]

On the piece's central framework — three overlapping circles (Timely, Painful, Yours) — JB Clark: *"I like this framing but I want it to be a little more fun, like the circle of truth, interest circle. I don't know."* David Ebner: *"Agreed. I'm down for whatever you settle on."*

Both reviewers liked the underlying mechanic; the note is specifically about the label. This is placed in the Watch List below rather than the numbered rules because it's one instance on one piece — but it's flagged as high-confidence because it's a direct, converged note from both reviewers, not a single stray comment, and it names a real gap: functional labels ("The Three Circles Framework") describe the tool but don't make it memorable or ownable the way a named framework should be. Promotes to a full rule on the next framework-naming instance.

---

## Watch List (first instance this round — need a second before promoting)

**Give named frameworks and models a distinctive, brandable name — not just a descriptive one.**

> JB Clark, on the Timely/Painful/Yours framework: *"I like this framing but I want it to be a little more fun, like the circle of truth, interest circle. I don't know."* David Ebner: *"Agreed. I'm down for whatever you settle on."*

One instance, both active reviewers on the piece. When a blog introduces a proprietary framework, model, or named concept (a three-part test, a matrix, a funnel), draft two or three candidate names — at least one purely descriptive, at least one with a hook or wordplay — and flag both for the writer/reviewer to choose from, rather than defaulting straight to the descriptive option. Watching for whether this recurs on the next framework-driven piece before folding it into the main style guide's structure section.

**Avoid framing a common mistake as something "most teams" or "most marketers" get wrong; describe the failure mode instead of naming the audience as the ones who fail.**

> David Ebner, on the heading "Where Most Teams Get This Wrong": *"Maybe 'Where it's easy to get this wrong.' It removes the finger-pointing aspect in 'most teams.'"*

One instance, but it connects directly to an existing, non-negotiable system instruction: never imply that the audience — sophisticated, time-pressed marketing and cybersecurity professionals — lacks understanding. Watching for whether this recurs in future headline drafts before folding it into the persona/tone section explicitly.

**Prefer "infer" over "predict" when describing how an AI model generates output.**

> David Ebner, on "AI agents don't reason the way a person does. They predict": *"I'd actually say 'infer' here."*

One instance, one reviewer, and genuinely debatable on technical grounds. Logging it rather than adopting it — needs a second instance or an explicit team decision before it becomes a word-choice rule.

**"Silent" and "quiet" are overused enough to flag as tell-words, not full clichés.**

> JB Clark, on "silent rewrite": *"Silent/quiet is another one of those Claude tingle words. It's not bad, I just think it's getting used A LOT."* Christina Rowell, same thread: *"This should be added to the list of words we don't want to do."*

One comment thread, one piece — but Christina's comment is an explicit instruction to add it to the list. High-confidence: the next piece that reaches for "silent" or "quiet" as a modifier should trigger an automatic self-check, and if it recurs, it promotes immediately rather than waiting for a third instance.

**Cut restatements, not just previews.**

> Round 2, cut in tracked changes with no comment attached: *"[[We already ruled out the AI builders above. Here's who's left.]]"* immediately preceding the "Who This Course Is For" section — a sentence that re-states a point the prior section had already made.

One confirmed CW instance (originally sourced from the Chatter addendum as an Imported Candidate). One more independent instance and it promotes to a numbered rule.

---

## Imported Candidates (from the Chatter addendum — status update)

Unchanged this round:

- **Spell out acronyms on first use.** Still zero CW instances.
- **Verify category terminology currency before locking it in.** Still zero CW instances directly.
- **Ground the abstract noun, or cut it.** Still zero CW instances.
- **Ease into self-referential "advantage" sections, or cut them for a CTA instead.** Still zero CW instances.
- **Genericize rather than correct.** Still zero CW instances.
- **Hold point of view steady within a section.** Still zero CW instances.
- **Link anchor text to the most specific relevant asset, not a landing page.** Still zero CW instances.
- **Review-process notes (don't strip comments before every reviewer has pulled a copy, etc.).** Still zero direct CW instances.

---

## Mechanics (standards, not voice — the two-instance bar doesn't apply)

- **Statistic and citation sourcing should be traceable on request.** *(Round 1 — unchanged.)*
- **Proofread after any rewrite pass, not just the first draft.** *(Round 1 — unchanged.)*
- **Em dashes take no spaces, ever — this amends the main guide's existing em-dash rule.** *(Round 3.)* When an em dash is used, it is set closed — no space before or after (`word—word`), never `word — word`.

---

## Process Notes (workflow observations, not copy rules)

- **A reviewer's correction is not automatically right.** *(Round 1 — unchanged, still the clearest standing example is the "AHREFS" case.)*
- **Non-preference edits need a stated reason.** *(Round 2 — unchanged.)* A tracked-change edit that reflects a rule should carry a comment explaining why; a pure wording preference doesn't need justification, but the reviewer should be able to tell which kind of edit it is at a glance.
- **Terminology decisions need to be resolved once, then applied everywhere the term appears — not just at the flagged spot.** *(Round 3 — unchanged.)*
- **A confirmed rule with a numeric ceiling needs a drafting-time check, not just a written ceiling. [NEW, ROUND 4]** Rule 4's ceiling was tightened in Round 3 specifically because the construction kept resurfacing in new forms. Round 4 shows the tightened version still isn't being checked against during drafting — the piece shipped three instances against a stated cap of one. The pattern across Rounds 3 and 4 is the same: a rule gets written correctly, and still doesn't hold, because nothing in the drafting process actually counts against it before the piece reaches a reviewer. **Standing instruction:** for any rule with a numeric ceiling (Rule 4's construction cap, the three-em-dash cap), do a dedicated pass counting instances against the stated limit before considering a draft finished — the same way word count gets checked against a target.
- **This addendum states its own update date for a reason.** *(Round 3 — unchanged.)* Every future update should keep the "Last updated" line current.
- **This addendum, not the main instructions file, is where new-round patterns land first.** *(Round 1 principle — unchanged.)* Rules 1–7 are stable enough to move into `Content_Workshop_Writer_Agent.md` now; Rule 4 in particular should **replace** the existing "Avoid repeated sentence structures" language rather than sit alongside it. Rule 8 (framework naming) stays here until it clears the two-instance bar.

---

## Base Rule Confirmations

- **Repeated sentence structure rule (Rule 4) — confirmed rule is correct, drafting discipline is the remaining gap.** Round 4 shows the function-based definition catches the construction correctly (all three flagged instances were the same underlying pattern in different clause orders), but writing the rule down didn't stop it from shipping three-over-cap in the next piece. The fix is process, not wording — see the new Process Note above.
- **Em dash count rule (≤3 per blog, closed spacing) — holding.** No violations flagged in the Round 4 piece.
- **Persona/tone rule (never imply the audience lacks understanding) — holding, no new surfaces this round.**
- **H3 + paragraph structure for sentence-length list items (Rule 7) — first clean confirmation.** The Round 4 piece applied this correctly without a reviewer needing to flag it. Worth watching whether this holds without prompting on Round 5.
