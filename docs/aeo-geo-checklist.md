# AEO/GEO Checklist: Writing to Get Cited by AI Engines

**Status:** Required for every blog and every content brief, effective November 18, 2026. Use it alongside the SEO section of `docs/content-workshop-blog-writer-instructions.md`. Where this file adds a section to the blog structure (Key Points, FAQ), it amends the Blog Outline Template, Blog Brief Template, and Editing Checklist in that file.
**Last updated:** November 18, 2026
**Portable:** Nothing in this file is specific to Content Workshop's brand voice. It can be copied into another project (for example, Chatter) as-is.

**Source:** "Your AI Search Content Checklist," handout from Scott Johnson, Founder, Amplifyed (amplifyed.io). The citation lifts below are the presenter's figures; his sources are in his presentation, and we have not verified them. Use them to set priorities internally. Do not cite them in published copy.

| Element | Presenter's reported lift in AI citations |
| :- | :- |
| Year in the title (where applicable) | 2x+ |
| Updated in the last 12 months | +88% |
| Has a table | +69% |
| First-hand experience | +45% |

---

## 1. Required in every blog

### Key Points (top of the blog)

- **Placement:** directly under the H1 and byline, before the introduction. Use the H2 "Key Points." It is a structural label, so the vague-heading rule doesn't apply to it.
- **Count:** three to five bullets. Default to four for a 1,200-word blog.
- **Format:** a bold one-sentence claim, then the stat or specific fact that backs it, with the source linked.
  - `**[Claim in one sentence.]** [Stat that backs it], according to [linked source].`
- **Each bullet stands alone.** An AI engine may lift one bullet without the others. No "this," "these," or "as above" pointing at another bullet.
- **One claim per bullet,** 35 words maximum.
- **Every stat is real and traceable.** If the claim has no published stat behind it, back it with a concrete fact from first-hand experience (what was done, what happened). Never invent or round a number to make it land.
- **The intro still has to earn attention.** Key Points summarize; they don't replace the hook. The intro should not restate a Key Point sentence.
- **Limits still apply.** Key Points count toward the em dash limit, the "not X, it's Y" limit, and SKP density. Summary bullets are where the contrast construction tends to creep in, so check them first.

### FAQ (bottom of the blog)

- **Placement:** the final section, after the conclusion and CTA. H2: "Frequently Asked Questions About [Topic]." Each question is an H3.
- **Count:** three to five questions for blogs under 1,500 words; five or six for 2,000+ words.
- **Real questions only.** Pull them from Google's People Also Ask, the follow-up questions AI engines suggest for the core keyword, sales and customer calls, or SME input. Phrase each one the way a buyer would type or say it. Record where each question came from in the brief.
- **The first sentence is the answer.** Yes or no, a definition, a number, or a direct recommendation. Then one to three sentences of support. Keep each answer to 40 to 80 words.
- **Each answer stands alone.** No "as we covered above." Someone reading only that answer, or an AI engine quoting it, should get a complete, accurate response.
- **At least one question goes beyond the body.** Cover an adjacent question the body doesn't fully answer, so the FAQ adds coverage instead of only repeating it.
- **Restatement rule:** an FAQ answer may cover ground the body covered, but it must not copy body sentences. Answer from a different angle or compress. Within the FAQ, no two answers make the same point.
- **SKP:** use it in one question where it reads naturally. FAQ uses count toward the 5 to 8 SKP target.
- **Schema:** deliver FAQPage JSON-LD with every draft (template and ownership in section 4). The text in the schema must match the visible question and answer word for word.
  - Note: Google limited FAQ rich results to well-known government and health sites in 2023, so the markup won't produce an FAQ snippet in Google results for most sites. It still makes the question-and-answer structure machine-readable, which is the point for AI engines.

### Word count

Key Points and the FAQ sit **outside** the requested word count unless the request says otherwise. A 1,200-word blog means 1,200 words of body (intro through CTA). The brief lists both the body target and the estimated total (typically +100 to 150 words for Key Points, +250 to 400 for the FAQ).

---

## 2. Required where applicable

### Year in the title
- Use it when the topic is time-bound: trends, benchmarks, predictions, annual guides, tool roundups, regulatory updates.
- Skip it on evergreen point-of-view pieces, where a year would be decoration.
- If the title carries a year, the meta title carries it too, and the piece goes on the annual refresh list.
- Run the title shortening pass (addendum, Rule 5) with the year included.

### Updated in the last 12 months
- The "Last updated" date is displayed by the website (CMS), not written into the blog draft. Writers don't add it.
- Refresh each published piece within 12 months: update stats, Key Points, FAQ (re-check People Also Ask), the year in the title, and broken links. Change the date only when the content actually changes.
- Track refresh dates in the content calendar.

### Table (only when the content is genuinely comparative)
- **Default is no table.** Add one only when the content is truly tabular: several options compared across the same attributes, or decision criteria a reader would scan side by side.
- **Never add a table to satisfy this checklist** or to chase the presenter's citation lift. A table that repackages points the prose already makes is filler.
- If the section already reads cleanly as H3 + paragraph pairs (main guide, Rule 7), leave it that way.
- When a table is warranted, build it as a real HTML table, not an image of one.
- No reason needs to be logged when there's no table. The brief's Table plan row defaults to "None."

### First-hand experience
- Include at least one specific example from our own work, a client (with approval), or an SME: what was done, what happened, and what it taught.
- The brief has to supply it. The writer never invents an experience, a client result, or a quote. If the brief has none, flag it before drafting.

### Date, author, bio
- Every blog publishes with a named author, the publish date, and a two- to three-sentence bio that says why the author is credible on this topic. These are added at publish.
- Author bios are maintained centrally and reused. The brief names the author.

---

## 3. Already covered elsewhere

- **No walls of text:** the main guide's paragraph rule (1 to 3 sentences) and clear H2s cover this.
- **Internal links to related topics:** the SEO checklist (three internal, two external) covers this.
- **Site speed:** a web team task, outside the writer's scope. Check key pages in PageSpeed Insights quarterly.

---

## 4. FAQPage schema template

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "[Question exactly as it appears in the H3]",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "[Answer exactly as it appears on the page]"
      }
    },
    {
      "@type": "Question",
      "name": "[Question 2]",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "[Answer 2]"
      }
    }
  ]
}
</script>
```

**What it is:** FAQPage JSON-LD is structured data (Schema.org vocabulary, JSON format, inside a `<script>` tag) that labels the page's FAQ as questions and answers for search engines and AI crawlers. Readers never see it.

**Ownership:**
- **Writer:** delivers the completed block with the draft, matching the visible FAQ word for word.
- **Publisher:** pastes it into the page through the CMS custom HTML/header field or SEO plugin (e.g., Yoast, Rank Math) and validates it in Google's Rich Results Test or the Schema.org validator before publishing.
- **Anyone editing the FAQ after publish** updates the JSON-LD in the same pass so the two stay identical.

---

## 5. Brief additions

Add these rows to the content brief, after "Proposed Structure":

| Row | What goes in it |
| :- | :- |
| Key Points | Three to five draft bullets: bold claim, backing stat, linked source for each |
| FAQ | Three to six questions, each with where it came from (PAA, AI follow-up, sales call, SME) |
| Table plan | "None" by default. Only if the content is genuinely comparative: what the table compares and which section it sits in |
| First-hand experience | The specific example, story, or SME input, and who supplied it |
| Author and bio | Named author and the bio to use |
| Year in title | Yes or no, and why |
| Refresh date | 12 months from publish |
| Word count | Body target, plus estimated total with Key Points and FAQ |

In the Proposed Structure, list "Key Points" first and "Frequently Asked Questions About [Topic]" last.

---

## 6. Editor pass: AEO/GEO

Run after the Editing Checklist in `docs/content-workshop-blog-writer-instructions.md`.

- [ ] Key Points sit under the H1 and byline, before the intro: three to five bullets, bold claim plus stat, each source linked.
- [ ] Each Key Point stands alone and makes one claim in 35 words or fewer.
- [ ] Every stat in Key Points and the FAQ traces to a real source.
- [ ] The intro doesn't repeat a Key Point sentence.
- [ ] FAQ is the last section: real questions as H3s, the first sentence of each answer answers it, 40 to 80 words each.
- [ ] No FAQ answer copies a body sentence or points back to the body ("as mentioned above").
- [ ] FAQPage JSON-LD is attached and matches the visible text word for word.
- [ ] Year in title, if used, is justified and also appears in the meta title.
- [ ] If there's a table, the content is genuinely comparative and it's built in HTML. No table is the default.
- [ ] At least one first-hand example, sourced from the brief.
- [ ] Author, date, and bio are in place (added at publish; "Last updated" is handled by the CMS).
- [ ] Key Points and FAQ were included in the em dash, contrast-construction, and SKP counts.
