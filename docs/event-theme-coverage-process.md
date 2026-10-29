# Event Theme Coverage: Process Brief

**Purpose:** Find which big problems an upcoming event will put on the table, check whether our blog already has a clear point of view on each one, and propose the few new posts that would close the real gaps.

**Origin:** Built and refined on the Content Workshop / CyberCon run (October 2026). The lessons from that run are written into the rules below, so a new chat doesn't need to repeat the false starts.

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
| Event name | `[event]` |
| Event session list | `[paste titles + one-line descriptions]` |
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

### Step 2: Group the sessions into 5–7 problems
- Each problem is a question attendees will be asking, phrased in plain language (e.g., "Everyone sounds the same"), not a session category.
- Put each session in one problem. Event-format sessions (game shows, performances, open roundtables, community business) don't need a home. Note them once and move on.
- Note any theme that runs across several problems (e.g., AI), but don't make it its own problem unless it's also a hands-on topic in its own right.

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

## Reference: the CyberCon outcome (for calibration)

87 sessions → 6 problems. 2 covered, 3 partly covered, 1 not ours → 3 new posts plus 1 optional, and no updates. That scale is the target: a short list someone can act on.
